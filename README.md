# Markdown Checklist

A single-file interactive checklist tool. Paste or open any markdown list — get live, persistent, three-state checkboxes with progress tracking per section and in total. No install, no account, no server.

**[Open the app →](https://mischlrebl.github.io/markdown-checklist/)**

---

## What it does

Write or paste a markdown list in the editor on the left — the checklist **renders live** on the right. Check items off, mark steps as N/A, collapse sections, track progress. Everything is **saved automatically** in the browser and survives page reloads and restarts.

The live preview makes the editor equally useful for **authoring and refining** checklists. Add a missing step mid-process, reorganize sections, or build a template from scratch — the structure and formatting are visible instantly as you type, without switching tools.

---

## Use cases

- **Deployment runbooks** — paste a 20-step procedure, tick each step, mark environment-specific steps as N/A
- **Code review** — structured criteria with collapsible sections per concern area
- **Daily to-do list** — jot down tasks as they come up, nest sub-tasks as they grow, and check them off through the day
- **Incident response** — follow a runbook step-by-step under pressure

---

## Template and Run

A checklist has two lives:

> **Template** — the blank, reusable structure you keep in version control. Open it with **Open**, edit it in the editor, save it back with **Save** or `Ctrl+S`.
>
> **Run** — the filled-out result after completing a process. Capture it with **Export**, which writes all checkbox states to a new markdown file. Commit that file to version control as a traceable, diffable record of what was done and what was skipped.

Keep them separate: the template stays clean for the next run; the exported result documents what happened.

---

## Checkbox states

- [ ] Unchecked
- [x] Checked
- [-] N/A / skip — excluded from the progress total, shown with its own indicator

Click any checkbox to cycle through all three states. The `- [-]` syntax is app-specific and not standard markdown. Plain bullets (`-`, `*`, `+`) and numbered or lettered lists (`1.`, `a.`) become checkboxes automatically.

---

## Features

- Three-state checkboxes: unchecked → checked → N/A
- Per-section and total progress tracking
- Collapsible sections
- Inline formatting: bold, italic, inline code, strikethrough, highlight, links, blockquotes
- Open and save markdown files directly (Chromium) or via upload / download fallback
- Export filled checklist as markdown — paste back to restore the exact state
- Focus mode — hides the toolbar and editor, leaving only the checklist and a slim progress bar
- Undo toast for destructive actions (Clear, Load demo, Check all)
- All state persisted in `localStorage`

---

## No install

One HTML file. Open it in a browser, or use the [hosted version](https://mischlrebl.github.io/markdown-checklist/).

---

## License

[GPL-3.0](LICENSE)

---

*The app and this README were built with [Claude AI](https://claude.ai) by Anthropic, guided and shaped throughout by a human.*
