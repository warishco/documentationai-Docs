# Waricha Writing Manual - Project Brief for AI Agent

## Project Overview

**Name:** Waricha Writing Manual (MyWM)  
**Type:** Personal technical writing playbook  
**Repository:** GitHub repository  
**Primary Purpose:** Document my end-to-end writing process so it's visible,
repeatable, and maintainable

---

## What This Manual Covers

The manual documents how I plan, write, review, publish, and maintain technical
content. It includes:

- **Process:** End-to-end workflow from intake to maintenance
- **Tools & Stack:** Docs-as-code tooling and workflow
- **Frameworks:** Reusable writing frameworks and patterns
- **Ways of Working:** How I collaborate with stakeholders
- **Resources:** Executable assets readers can adapt

**Explicitly out of scope:** Marketing copywriting, long-form essays

---

## Current Repository Structure

```
documentationai-Docs/
├── README.md                          # Foundational info + build workflow
├── documentation.json                 # Site navigation configuration
├── archives/                          # Archived early planning docs
│   ├── information-architecture.md   # Original consolidated IA (messy)
│   └── working-tree.md               # Original repo tree diagram
├── materials/                         # Private workbench (formerly resources/)
│   ├── README.md                     # Rules for materials/ folder
│   ├── writing-manual-devlog.md      # Build log + decisions
│   ├── style-guide-inspiration.md    # Reference material
│   ├── outlines/                     # Per-topic outlines (new)
│   └── Checklists/
│       └── Content Checklist (v1.1.0)/
│           └── Content Checklist (v1.1.0).md
├── introduction.mdx                 # Published: Welcome + what to read first
├── now.mdx                          # Published: Current focus
├── process/
│   └── overview.mdx                 # Published: Writing process overview
├── ways-of-working/
│   └── tools-and-stack.mdx        # Published: Tools and docs-as-code workflow
└── frameworks/
    └── framework-card-template.mdx # Published: Framework template
```

**Legend:**

- `[PUBLISHED]` = Listed in documentation.json, deployed
- `[PRIVATE]` = Materials folder (not deployed, for building the manual)
- `[ARCHIVED]` = Early planning docs preserved but not current

---

## Build Workflow (How I Work on This Manual)

1. **Foundational info in README.md** - Start here, define scope/audience
2. **Plan content organization using a diagram** - Outside Windsurf (I'll do
   this)
3. **Create per-topic outlines** in `materials/outlines/` - One outline per
   topic
4. **Recreate working tree** after structure is solid
5. **Write actual manual pages** as `.mdx`, add to `documentation.json`
6. **Document decisions** in `materials/writing-manual-devlog.md`

---

## Key Decisions & Evolution

### March 2, 2026 - Workspace Restructuring

**Mistakes identified:**

- Didn't define foundational info upfront in README (put it in introduction
  instead)
- Created working tree before finalizing content structure
- Built IA as one messy consolidated document
- No diagram before file creation

**Actions taken:**

- Created `archives/` folder for old planning docs
- Created `materials/outlines/` for per-topic outlines
- Renamed `resources/` → `materials/` to avoid confusion with "resources
  section"
- Updated README with proper foundational info

### March 17, 2026 - Folder Rename

Renamed `resources/` to `materials/` because:

- "Resources" implied visitor-facing section
- "Materials" better signals "source material for content creation"
- Avoids confusion in IA/navigation design

---

## Content Checklist (Key Working Asset)

**Location:**
`materials/Checklists/Content Checklist (v1.1.0)/Content Checklist (v1.1.0).md`

**Structure:**

1. **Warm-Up** - Workspace setup, gather materials
2. **Stage 1: Pre-Writing** - Plan, research, outline, outline revision
3. **Stage 2: Writing** - TUFD (draft from structure), draft, visuals
4. **Stage 3: Post-Writing** - Copy editing, proofreading, submission, revisions
5. **Stage 4: Maintenance** - Triggers, what to maintain, workflow, ownership

**Note:** Phase structure is stable; details inside each phase can vary by
project.

---

## Current State & Next Steps

### ✅ Completed

- Repository initialized with Mintlify structure
- Core published pages: Introduction, Now, Process Overview, Tools & Stack,
  Frameworks
- Private workspace: materials/ folder with devlog, checklists, outlines
  scaffolding
- Archives folder preserving early (messy) planning docs
- Root README with foundational info and build workflow

### 📋 Next (Pending My Action)

- Create diagram for content organization (outside Windsurf)
- Create per-topic outlines in `materials/outlines/`
- Recreate clean working tree document
- Build out remaining process pages based on Content Checklist phases

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
└── Templates & Checklists (freebies section)
    └── Content checklist (v1.1.0)
```

---

## Rules & Conventions

**For materials/ folder:**

- Keep files as `.md` (not `.mdx`)
- Do not add to `documentation.json` (private workspace)
- Use HTML comments for inline notes: `<!-- Question: ... -->`
- Move bigger thinking to devlog

**For published pages:**

- Use `.mdx` for Mintlify components
- Add to `documentation.json` for navigation
- Follow framework card template structure

---

## Communication Context

**I'm currently:** Planning the content structure via diagram (outside this
chat)  
**Next AI interaction likely:** Reviewing outlines or helping draft specific
manual pages  
**Key constraint:** I prefer stable phase names (Warm-up, Stage 1-3, Phase 4)
but flexible details within each phase  
**Goal:** Executable manual that's also a showcase of my thinking for potential
clients

---

## Questions for Next AI Agent

1. Should I consolidate the "Templates & Checklists" section into the main
   navigation, or keep it as a separate "freebies" area?
2. For per-topic outlines in `materials/outlines/`, should I create one outline
   per process phase, or one per page?
3. When I recreate the working tree, should it reflect the target state or
   current state?
