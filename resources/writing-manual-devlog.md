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

- What I changed: Added [working-tree.md](working-tree.md) and
  [information-architecture.md](information-architecture.md).
- Why: To outline the structure of the repository and plan the high-level
  structure of my writing manual.
- Next: Test if this approach works for me.
- Question: What if the outline (information architecture) is too long? Should I
  break it into multiple pages?
