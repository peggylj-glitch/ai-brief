# The AI Brief

A daily digest of **frontier AI** (new models, lab announcements, benchmarks)
and **AI in enterprise finance functions** (FP&A, close, treasury, tax, audit,
procurement) — compiled every morning and published here.

## Structure

- `index.html` — the public archive site (served via GitHub Pages)
- `briefs/` — one markdown file per edition, plus `index.json`, the
  machine-readable feed the site renders

## How it updates

Each morning the brief is compiled, the new edition is appended to
`briefs/index.json`, and the result is committed. The site picks it up
automatically — no rebuild step.
