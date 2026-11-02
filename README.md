# dstwiki

A Don't Starve Together knowledge graph, in brain v2 format: one Markdown file
per entity with YAML frontmatter, and an OWL-flavoured T-box in
`db/schema.yaml`.

```sh
brain --db . reindex
brain --db . 'what do beefalo eat?'
brain --db . web
```

## Where this came from

Converted from the es6 database at `/workspace/cli/dstwiki` (a `schema.mjs` +
`data.mjs` pair), with:

```sh
brain convert /workspace/cli/dstwiki --out ./db --ontology dstwiki
```

That source keeps growing as the wiki is crawled, so **this is a snapshot, not
a fork** — re-run the conversion to pick up new entities. Two things the
converter changed and reported rather than doing silently:

- **23 ids were renamed.** A slug is a filename here, and `id` is deliberately
  narrow (`[A-Za-z0-9][A-Za-z0-9._-]*`), so `Item/Abigail's_Flower` became
  `Item/Abigails_Flower`. Every edge pointing at one was renamed with it, and
  the display name is untouched — it comes from `identity.title`, which is
  where an apostrophe belongs.
- **`SPAWNS` and `YIELDS` were widened from `nto` to `mtm`.** The es6 schema
  declares them single-valued and 27 structures have several targets each — a
  Grave really does yield more than one thing. A cardinality the data
  contradicts is a stale declaration, not a constraint.

`brain --db . validate` is clean: 0 errors, 0 warnings.

## The question suite

`tests/test-cases.json` holds seven questions `brain bench suite` runs against
`crawl`, each with the answer it must produce and a note on what makes it hard.
They are the dstwiki half of the crawl's regression set.

```sh
brain --db . bench suite
```
