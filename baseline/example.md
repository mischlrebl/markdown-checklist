> 3/41 · 7% · 2 N/A

# Feature Checklist

## Introduction

This is plain text — no checkbox, renders as-is. Emojis work too 😊
Since there are no checkboxes in this section, no progress bar appears in the header. The text is long enough to show a soft line break.

## Checkbox styles

- [ ] Unchecked task
- [x] Pre-checked task
- [-] Not applicable (N/A) — excluded from progress total but shown with its own indicator on the section header. The [-] state is app-specific, not standard markdown ⚠️
- [ ] A plain bullet becomes a checkbox automatically
- [ ] Asterisk bullet also works
- [ ] Plus bullet as well
• Unrecognised bullet — no checkbox is created
It is good practice not to mix bullet styles in the same list.

### Numbered & lettered lists, Nesting

- [ ] 1. First numbered item — the number is shown in the label
- [ ] 2. Second numbered item
- [ ] 3. Third item
  - [ ] a. Letter sub-point — indented one level below numbers
  - [ ] b. Another letter sub-point
  - [ ] C. Uppercase letter also works
    - [ ] 1. an additional level deeper
- [ ] 4. Back to top level

#### Import with unindented lines

Paste any list — from a document, spreadsheet, or plain text, not just markdown. Auto-nested correctly in the checklist. Use `Format → Fix list indentation` to make the structure explicit in the source.
- [ ] 1. Build
- [ ] 2. Test
  - [ ] a. Unit
  - [ ] b. Integration
    - [ ] 1. Deploy

## Fully completed section

- [x] first
- [x] second
- [-] none

## Inline formatting

- [ ] **Bold** with double asterisks
- [ ] *Italic* with single asterisks
- [ ] `inline code` with backticks
to copy an `example command` place it outside a task (no checkbox, no interaction)
- [ ] ~~Strikethrough~~ with double tildes
- [ ] ==Highlighted== with double equals signs
- [ ] [Markdown cheat sheet](https://www.markdownguide.org/cheat-sheet/) — click to open in a new tab; URL shown on hover
- [ ] Combined: **bold and *italic* text** in one item

> Blockquotes are useful for notes or context
> Consecutive lines merge into one visual block
---
- [ ] Item after a horizontal divider
  - [ ] sub-item
> sub blockquote

## Non-standard line break behavior ⚠️

Each line in the editor creates a new element — no blank line needed (unlike standard markdown).
This is the second line, separated by a single newline.

Blank lines add visual spacing between items:

- [ ] Item before the gap
- [ ] Another item before the gap

- [ ] Item after the gap

## Edge cases

#### Parenthesis delimiter — normalised to dot in output

- [ ] 1. First item with parenthesis
- [ ] 2. Second item
  - [ ] a. Letter sub-item with parenthesis
  - [ ] b. Another one

#### Letters at top level with numbered sub-items

  - [ ] a. First letter item
    - [ ] 1. First numbered sub-item
    - [ ] 2. Second numbered sub-item
  - [ ] b. Second letter item
    - [ ] 1. Another numbered sub-item

## Font ligatures

If **Fira Code** is installed on your system, character pairs render as single ligature glyphs wherever the font is active:

->  -->  =>  ==>  <-  <--  <->  <=>

Ligatures are purely visual — the underlying characters are unchanged. No ligatures appear if Fira Code is not installed; the fallback fonts do not support them.