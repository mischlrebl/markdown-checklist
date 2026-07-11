# Baseline

Reference exports of the app's built-in example — the one loaded via **Syntax → Load example**, which covers every syntax case (headings, checkbox states, bullets, numbered/lettered/roman-numeral nesting, inline formatting, etc.).

- `example.md` — from **Export**
- `example.html` — from **Save as HTML**

## Purpose

These are known-good snapshots to diff future exports against, to confirm a change to the renderer, parser, or export logic hasn't altered the output unexpectedly.

## Regenerating

1. Click **Syntax → Load example**.
2. Click **Export**, overwrite `example.md` with the download.
3. Click **Export → Save as HTML**, overwrite `example.html` with the download.
4. Diff both against the previous versions before committing — a diff is expected after an intentional change; an unexpected diff is a regression.
