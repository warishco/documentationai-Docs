# Waricha Writing Manual — AI Agent Handoff Brief

## Project at a Glance

| Attribute | Value |
|-----------|-------|
| **Name** | Waricha Writing Manual |
| **Type** | Personal technical writing playbook (docs-as-code) |
| **Platform** | Mintlify documentation site |
| **Purpose** | Document my end-to-end writing process so it's visible, repeatable, and maintainable |
| **Default Audience** | Me; secondary: content managers, founders, technical writers |

---

## What This Manual Covers

- **Process:** End-to-end workflow (intake → discovery → outline → draft → review → publish → maintenance)
- **Tools & Stack:** Docs-as-code workflow (GitHub, Markdown/MDX, documentation.ai)
- **Frameworks:** Reusable writing frameworks and patterns
- **Ways of Working:** Collaboration, feedback, and maintenance mindset
- **Templates & Checklists:** Executable assets readers can adapt (future "freebies" section)

**Out of scope:** Marketing copywriting, long-form essays

---

## Repository Structure

```
documentationai-Docs/
├── README.md                          # Foundational info + build workflow
├── documentation.json                 # Published navigation
├── archives/                          # Early planning docs (preserved)
│   ├── information-architecture.md   # Original consolidated IA (messy)
│   └── working-tree.md               # Original repo tree
├── materials/                         # Private workspace (formerly resources/)
│   ├── README.md                     # Rules for materials/
│   ├── writing-manual-devlog.md      # Build log + decisions
│   ├── style-guide-inspiration.md    # Reference material
│   ├── outlines/                     # Per-topic outlines (empty, for future)
│   └── Checklists/
│       └── Content Checklist (v1.1.0)/
│           └── Content Checklist (v1.1.0).md  # My working checklist
├── introduction.mdx                 # [PUBLISHED] Welcome + where to start
├── now.mdx                          # [PUBLISHED] Current focus
├── process/
│   └── overview.mdx                 # [PUBLISHED] Writing process overview
├── ways-of-working/
│   └── tools-and-stack.mdx          # [PUBLISHED] Tools and workflow
└── frameworks/
    └── framework-card-template.mdx  # [PUBLISHED] Framework template
```

**Key convention:** `materials/` = private workspace (`.md` files, not in `documentation.json`); root folders = published manual (`.mdx` files, listed in `documentation.json`)

---

## My Build Workflow

1. **Define foundational info** in root `README.md` (scope, audience, what's in/out)
2. **Plan content organization** using a diagram (I do this outside Windsurf)
3. **Create per-topic outlines** in `materials/outlines/` (one per topic, not consolidated)
4. **Recreate working tree** once structure is solid
5. **Write manual pages** as `.mdx`, add to `documentation.json`
6. **Log decisions** in `materials/writing-manual-devlog.md`

---

## Key Decisions & Why

| Decision | Rationale |
|----------|-----------|
| Moved early planning docs to `archives/` | Preserved history without cluttering active workspace |
| Created `materials/outlines/` for per-topic outlines | Avoided consolidating everything into one messy IA document |
| Renamed `resources/` → `materials/` | "Resources" implied visitor-facing section; "materials" signals private source material |
| Root README now holds foundational info | Originally put this in `introduction.mdx`; README is the proper first step |
| Content Checklist phases are stable | Warm-up, Stage 1-3, Phase 4 structure is fixed; details inside each phase can vary by project |

---

## Content Checklist (My Operating System)

**Location:** `materials/Checklists/Content Checklist (v1.1.0)/Content Checklist (v1.1.0).md`

| Phase | Purpose |
|-------|---------|
| **Warm-Up** | Workspace setup, gather brief and materials |
| **Stage 1: Pre-Writing** | Plan, research, outline, revise outline |
| **Stage 2: Writing** | TUFD (draft from structure), draft, visuals |
| **Stage 3: Post-Writing** | Copy editing, proofreading, submission, revisions |
| **Stage 4: Maintenance** | Triggers, what decays, workflow, ownership |

---

## Current State

### ✅ Done
- Repository initialized with Mintlify structure
- Core published pages: Introduction, Now, Process Overview, Tools & Stack, Frameworks
- Private workspace: materials/ with devlog, checklists, outlines scaffolding
- Archives folder preserving early planning docs
- Root README with foundational info and build workflow

### 📋 In Progress / Next (My Action)
- Create content organization diagram (outside Windsurf)
- Create per-topic outlines in `materials/outlines/`
- Recreate clean working tree document
- Build remaining process pages based on Content Checklist phases

### 🎯 Target Navigation (Future)
```
Manual
├── Start Here
│   ├── Introduction
│   └── Now
├── Process
│   ├── Writing process overview (existing)
│   ├── Warm-up
│   ├── Stage 1: Pre-Writing
│   ├── Stage 2: Writing
│   ├── Stage 3: Post-Writing
│   └── Phase 4: Maintenance
├── Ways of Working
│   └── Tools and stack (docs-as-code)
├── Frameworks
│   └── Framework card template
└── Templates & Checklists (freebies)
    └── Content checklist (v1.1.0)
```

---

## Working Rules

**For `materials/` (private):**
- Keep as `.md` (not `.mdx`)
- Do not add to `documentation.json`
- Use HTML comments for inline notes: `<!-- Question: ... -->`
- Move bigger thinking to devlog

**For published pages:**
- Use `.mdx` for Mintlify components
- Add to `documentation.json` for navigation
- Follow framework card template structure

---

## Questions for Next AI Agent

1. Should "Templates & Checklists" be integrated into main navigation or kept as a separate "freebies" area?
2. For per-topic outlines in `materials/outlines/`, create one per process phase or one per page?
3. When recreating the working tree, reflect target state or current state?

---

## Contact & Context

**I am currently:** Planning content structure via diagram (outside this chat)  
**Likely next interaction:** Reviewing outlines or drafting specific manual pages  
**Key constraint:** Phase names (Warm-up, Stage 1-3, Phase 4) are stable; internal details flexible  
**Ultimate goal:** Executable manual that showcases my thinking for potential clients

**For reference:** See `materials/project-brief-for-ai.md` for an earlier, more narrative version of this brief.
