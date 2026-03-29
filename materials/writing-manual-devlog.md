# Writing Manual Devlog (private)

This is where I document how I’m building the manual.

It’s intentionally messy: ideas, questions, tradeoffs, and decisions.

Nothing here is meant to be published.

## Conventions

### Inline private notes inside published pages

When I want to leave myself a note inside a published `.mdx` page without
rendering it, I use an HTML comment:

```html
<!-- Question: is this step too detailed for the reader? -->
```

Notes:

- HTML comments won’t show in the rendered page.
- I use this for small reminders, questions, and TODOs.

### Bigger thinking belongs here

If the note is more than a few lines, I move it into this devlog and link to the
relevant page path.

---

## Log

### 1-03-2026

- What I changed: Added [working-tree.md](../archives/working-tree.md) and
  [information-architecture.md](../archives/information-architecture.md).
- Why: To outline the structure of the repository and plan the high-level
  structure of my writing manual.
- Next: Test if this approach works for me.
- Question: What if the outline (information architecture) is too long? Should I
  break it into multiple pages?

### 2-03-2026

- What I changed: Reorganized the workspace to reflect a revised approach.
  - Created `archives/` at repo root.
  - Created `materials/outlines/` for per-topic outlines.
  - Moved the early planning docs to `archives/`:
    - `archives/working-tree.md`
    - `archives/information-architecture.md`
- Why: I noticed issues with my initial approach:
  - I didn’t define foundational info upfront in the repo `README.md`.
  - I created a working tree before finalizing content structure.
  - I tried to outline too much in one IA document and it became messy.
  - I didn’t create a big-picture diagram before creating files.
- Next:
  - Write a README that contains the foundational information before proceeding.
  - Plan content organization using a diagram (outside Windsurf).
  - Recreate the working tree after the content structure is solid.
  - Outline content per topic (avoid consolidating everything into one
    document).
