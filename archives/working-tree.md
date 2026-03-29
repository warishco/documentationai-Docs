# Waricha Writing Manual — Working Tree (Diagram)

**Purpose:** Use this diagram to understand the structure of the repository and
plan the high-level structure of my writing manual. Once ready, move to the
[Information Architecture](information-architecture.md) document to create the
content structure.

---

Legend:

- `[NAV]` Listed in `documentation.json` navigation
- `[DOC]` Deployed documentation page (exists as `.mdx` at the repo root or in a
  folder)
- `[SAMPLE]` Placeholder/sample content you may later replace or remove
- `[PRIVATE]` Private workspace content (not deployed)
- `[CONFIG]` Site configuration / source-of-truth

---

## Working tree (repo-level)

```text
Waricha Writing Manual (repo)
├── documentation.json                     [CONFIG] sidebar + nav structure
├── openapi.yaml                           [CONFIG] API reference source
├── README.md                              [DOC] (repo) quick orientation
├── introduction.mdx                       [DOC][NAV]
├── now.mdx                                [DOC][NAV]
├── process/
│   └── overview.mdx                       [DOC][NAV]
├── ways-of-working/
│   └── tools-and-stack.mdx                [DOC][NAV]
├── frameworks/
│   └── framework-card-template.mdx        [DOC][NAV]
├── components/
│   ├── callouts.mdx                       [DOC] component docs
│   ├── cards.mdx                          [DOC] component docs
│   ├── code.mdx                           [DOC] component docs
│   ├── images.mdx                         [DOC] component docs
│   ├── steps.mdx                          [DOC] component docs
│   └── tabs.mdx                           [DOC] component docs
├── help-center.mdx                        [DOC][SAMPLE]
├── help-center/
│   ├── faq/
│   │   └── getting-started.mdx            [DOC][SAMPLE]
│   ├── guides/
│   │   └── setup-project.mdx              [DOC][SAMPLE]
│   └── troubleshooting/
│       └── install-error.mdx              [DOC][SAMPLE]
├── authentication.mdx                     [DOC][SAMPLE]
├── changelog.mdx                          [DOC][SAMPLE]
├── concepts.mdx                           [DOC][SAMPLE]
├── components.mdx                         [DOC][SAMPLE]
├── notice.mdx                             [DOC][SAMPLE]
├── quickstart.mdx                         [DOC][SAMPLE]
└── resources/
    ├── README.md                          [PRIVATE] rules for resources/
    ├── Checklists/
    │   └── Content Checklist (v1.1.0)/
    │       └── Content Checklist (v1.1.0).md  [PRIVATE] checklist freebie
    ├── information-architecture.md        [PRIVATE] IA outline (H2–H4 per page)
    ├── working-tree.md                    [PRIVATE] this diagram
    ├── style-guide-inspiration.md         [PRIVATE] reference material
    └── writing-manual-devlog.md           [PRIVATE] build log / decisions
```

---

## Navigation tree (from `documentation.json`)

This is the current _published_ sidebar.

```text
Manual
├── Start Here
│   ├── Introduction                       /introduction
│   └── Now                                /now
├── Process
│   └── Writing process overview           /process/overview
├── Ways of Working
│   └── Tools and stack (docs-as-code)     /ways-of-working/tools-and-stack
└── Frameworks
    └── Framework card template            /frameworks/framework-card-template
```

---

## Proposed future tree (based on your IA outline)

These are the likely additions implied by the end-to-end process you’re
documenting.

```text
process/
├── intake-and-scope.mdx
├── discovery-and-research.mdx
├── outlining.mdx
├── drafting.mdx
├── review-and-revision.mdx
├── publishing.mdx
└── maintenance.mdx

templates/
├── discovery-brief.mdx
└── outline-template.mdx

checklists/
└── pre-publish.mdx
```
