# AGENTS.md

Conventions for adding or editing entries in this repo.

## What this repo is

Personal notes on the tools and practices in my daily dev stack. Plain Markdown,
readable on GitHub. A website may be generated from these files later, so keep
the structure and frontmatter consistent.

## Layout

- Tools live in category folders: `<category>/<tool-slug>/README.md`
  (e.g. `ai/understand-anything/README.md`). Slugs are kebab-case.
- Screenshots for an entry go in `<category>/<tool-slug>/img/` — PNG or WebP,
  under ~500 KB each, referenced with relative paths.
- Workflows that span several tools live in `practices/<slug>.md` and link to
  the tool entries they use.
- Each folder has a `README.md` listing its entries. Create a new category
  folder (with its `README.md`) only when the first entry for it arrives.

## Entries

- Start from [`_template.md`](_template.md): keep its frontmatter fields and
  section order. Drop a section only if it would be empty.
- `status` is one of `daily`, `trying`, `dropped`. Set `last_reviewed` to the
  date of the edit.
- Write in English, first person, short. Describe my actual usage — never
  invent experience, commands I haven't run, or opinions I haven't stated.
  When unsure, ask or keep the section minimal.
- No hype or marketing language. Gotchas matter as much as features.
- Don't add placeholder images or TODO markers.

## When adding or changing an entry

1. Add or update the row in the root `README.md` index table
   (name linked to the entry · category · one-liner · status).
2. Add or update the entry in its category folder's `README.md`.
