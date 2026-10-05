# .gitback

This directory is written by Gitback, the feedback board built for this repository,
and it belongs to you. Everything in it is plain markdown and YAML that a person can
read and edit without any tool of ours: if you stop using Gitback, delete nothing —
it all keeps working as documentation.

## What is here

- `config.yml` — which discussion category feeds which part of the board, how
  roadmap labels map to lanes, and the Support settings.
- `faq/` — one markdown file per question. The filename is the question's slug; the
  frontmatter at the top holds the question text, its order, tags, the date it was last
  updated and the discussion it was promoted from. The body is the answer.
- `help/` — one markdown file per help article, named by its slug, with its title and
  tags in the frontmatter. `help/collections.yml`, when present, lists the curated
  collections and the articles in each, in order.
- `support/replies/` — one markdown file per canned Support reply. A title line in
  the frontmatter names it; otherwise the filename does. The body is the reply.
- `README.md` — this file.

## Editing by hand

Edit or add any file directly and commit it. To add a question, create a new file in
`faq/` with a frontmatter block that has at least a question line; to remove one,
delete its file. The board reads the directory itself, so a change takes effect as
soon as it is on the default branch.

The index below is a convenience, never a source of truth. Gitback regenerates it in
the same commit as any change it makes, but a file you add by hand works before the
index catches up, and an index entry with no file behind it means nothing.

## Index

- [`config.yml`](config.yml) — board configuration
