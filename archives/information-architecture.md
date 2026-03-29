# Waricha Writing Manual — Information Architecture (Outline)

This document is a working outline of the Writing Manual.

Each page below includes a suggested structure (H2–H4) and the key points to
include.

---

## 1) Introduction (`/introduction`)

### H2: Welcome to my writing manual <!-- NOTE: This section is to answer "What" -->

<!-- IDEA: Refer to Splunk docs for an example of a "Welcome to our docs" page -->

#### H3: Who I am (context)

- Introduce myself and my role (technical writer).
  - Link to [my about me page](https://warish.co/about-me/).
- What this manual is about (a personal writing manual).
- Where I use this manual (for writing
  [my own tech blog](https://h1tags.hashnode.dev/) and for my clients).
- Who it is for (me, content managers/leads, founders, technical writers).

#### H3: What this manual covers (scope)

- Writing process
- Tools and stack
- Frameworks (e.g., writing frameworks)
- Ways of working with me (e.g., collaboration, feedback)
- What is explicitly out of scope (e.g., marketing copywriting, long-form
  essays).

### H2: Why I created this manual <!-- NOTE: This section is to answer "Why" -->

- **To make my process visible and repeatable.**
  <!-- NOTE: This is for my own use. --> I turn my scattered thoughts, lessons learned, and best practices into a structured system.
- **To showcase my thinking and writing process when I work with clients.**
  <!-- NOTE: This is to attract potential clients; refine this sentence. --> I answer questions like "What does your writing process look like?" and "How do you work with clients?"
- **To share guidance for other technical writers.**
  <!-- NOTE: This is to help other technical writers. They can use my manual as a template or reference and adapt it to their own needs. --> I create my manual so they can learn from my experience.

### H2: How I create this manual <!-- NOTE: This section is to answer "How" -->

- I use GitHub to host this manual and manage the content and tasks.
- This is a living document. I will update it as I learn and refine the system.

### H2: What you should read first <!-- This section is to answer "Where" -->

#### H3: Reading paths by intent

- “I want the full system” path. Go to `/process/overview`.
  <!-- NOTE: Link to Process overview and Tools/stack. -->
- “I want to understand how you work” path. Go to
  `/ways-of-working/tools-and-stack`.
  <!-- NOTE: Link to Ways of working. -->
- “I need a template/checklist now” path. Go to
  `/frameworks/framework-card-template`.
  <!-- NOTE: Link to Frameworks. -->

---

## 2) Now (`/now`)

### H2: Current focus

#### H3: What you’re changing and why

- What you’re improving in the system.
- The underlying driver (pain point / pattern / recurring issue).

### H2: Next revisions

#### H3: What’s coming next

- Near-term pages to add.
- Examples and artifacts you plan to publish.

#### H3: Definition of “shippable” for the next batch

- Minimum completeness bar.
- What can remain rough.

---

## 3) Writing process overview (`/process/overview`)

### H2: The workflow (high level)

#### H3: The 7 stages

- Intake and scope
- Discovery and research
- Outline
- Draft
- Review and revision
- Publish
- Maintenance

#### H3: When to loop back

- Signals that you should return to an earlier stage.
- What gets updated when you loop (brief, outline, examples, etc.).

### H2: What I optimize for

#### H3: Reader outcomes

- Time-to-first-success.
- Reduced confusion / fewer support questions.

#### H3: Writer outcomes

- Lower rework.
- Faster iteration.

### H2: Quality gates

#### H3: Gate: before outlining

- Criteria for “scope is clear enough to write”.

#### H3: Gate: before drafting

- Criteria for “outline answers the right questions in the right order”.

#### H3: Gate: before publishing

- Link checks, example consistency, terminology stability.

### H2: Key artifacts

#### H3: What each artifact contains

- Discovery brief
- Outline
- Draft
- Review notes + resolution log
- Maintenance notes

#### H3: Storage/format conventions

- Where artifacts live in the repo.
- How you name them.

### H2: What changes as I learn

#### H3: Update triggers

- Rework patterns.
- Stakeholder friction.
- Reader questions.

---

## 4) Tools and stack (docs-as-code) (`/ways-of-working/tools-and-stack`)

### H2: Core tools

#### H3: What you use

- IDE, Git/GitHub, Markdown/MDX, documentation.ai.

#### H3: Why these tools

- What each tool enables (reviewability, repeatability, maintenance).

### H2: My default workflow

#### H3: Branching model

- One branch per coherent change.

#### H3: Publish flow

- Draft → self-review → PR → merge.

### H2: What I look for in review

#### H3: Review checklist (high-level)

- Intent clarity.
- Terms consistency.
- Reasons for steps.
- Minimal, accurate examples.

### H2: Maintenance mindset

#### H3: Rot prevention

- What changes in 30–90 days.
- What goes stale first.
- Who should notice when it breaks.

---

## 5) Framework card template (`/frameworks/framework-card-template`)

### H2: What it is

#### H3: Definition

- One-paragraph explanation of the framework.

#### H3: Why it exists

- What problem it solves in your writing work.

### H2: When I use it

#### H3: Triggers

- Situations or doc types where it’s a fit.

#### H3: When not to use it

- Anti-patterns.

### H2: Inputs

#### H3: Required inputs (for this framework)

- Information you must have before starting.

#### H3: Optional inputs (nice-to-have)

- What improves quality but isn’t mandatory.

### H2: Steps

#### H3: Step-by-step procedure

- Clear sequence.
- Decision points.

#### H3: Variations

- Common variants for different audiences.

### H2: Output

#### H3: What “done” looks like

- Concrete artifacts produced.

### H2: Common failure modes

#### H3: Symptoms and fixes

- What goes wrong.
- How to recover.

### H2: Example

#### H3: Real example

- A filled-in sample.

---

## Proposed next pages (recommended additions)

These pages are implied by the end-to-end process but are not yet present as
dedicated pages.

## A) Intake and scope (`/process/intake-and-scope`)

### H2 (A): Goal of this stage

#### H3: What you’re trying to decide

- What problem you’re solving.
- Whether this is worth documenting now.

### H2 (A): Inputs

#### H3: Required inputs

- Product reality, audience, constraints.

#### H3: Source-of-truth hierarchy

- What you treat as authoritative (code, PM, support tickets, SME interviews).

### H2 (A): Scope definition

#### H3: In-scope / out-of-scope

- Crisp boundaries.

#### H3: Success criteria

- What “done” means.

### H2 (A): Risks and assumptions

#### H3: What could invalidate the doc

- Known unknowns.

### H2 (A): Output

- A short brief you can hand to a reviewer.

## B) Discovery and research (`/process/discovery-and-research`)

### H2 (B): What you’re learning

#### H3: Reader questions

- What the reader is really trying to do.

#### H3: Product behavior

- Confirming reality (not only intended behavior).

### H2 (B): Research methods

#### H3: What you check

- Code, UI, logs, support tickets, SME interviews.

### H2 (B): Synthesis

#### H3: Key findings

- Constraints.
- Gotchas.
- Concept prerequisites.

### H2 (B): Output

- Updated brief and a prioritized question list.

## C) Outlining (`/process/outlining`)

### H2 (C): Why outline first

#### H3: What an outline prevents

- Wrong order.
- Missing prerequisites.
- Unbounded scope.

### H2 (C): Outline structure

#### H3: Recommended patterns

- Task-first.
- Concept-first.
- Troubleshooting-first.

#### H3: Ordering rules

- Prerequisites before steps.
- Definitions before references.

### H2 (C): Outline review gate

#### H3: Questions the outline must answer

- What will the reader achieve?
- What do they need to know first?
- What are the failure modes?

### H2 (C): Output

- A shareable outline with headings and planned examples.

## D) Drafting (`/process/drafting`)

### H2 (D): Drafting principles

#### H3: Make intent visible

- Explain reasons.

#### H3: Prefer specifics over advice

- Concrete steps and constraints.

### H2 (D): Writing mechanics

#### H3: Headings and scanning

- First-screen clarity.

#### H3: Examples

- Minimal, accurate, copy-pasteable.

### H2 (D): Handling edge cases

#### H3: When to branch into another page

- Avoid overloading a single page.

### H2 (D): Output

- A complete draft aligned to the outline.

## E) Review and revision (`/process/review-and-revision`)

### H2 (E): Review types

#### H3: Technical accuracy review

- SMEs, engineers.

#### H3: UX/readability review

- Can a reader succeed?

### H2 (E): Review checklist

#### H3: Consistency

- Terms, style, structure.

#### H3: Completeness

- Prereqs, steps, troubleshooting.

### H2 (E): Resolving feedback

#### H3: Decision log

- What you changed and why.

#### H3: Tradeoffs

- Explicitly accepted issues.

### H2 (E): Output

- A revised draft + resolution notes.

## F) Publishing (`/process/publishing`)

### H2 (F): Pre-publish checks

#### H3: Links and navigation

- Correct paths.

#### H3: Examples sanity check

- Still accurate.

### H2 (F): Release notes mindset

#### H3: What changed

- Record meaningful changes.

### H2 (F): Output

- Published page + a traceable record of the change (PR).

## G) Maintenance (`/process/maintenance`)

### H2 (G): Maintenance triggers

#### H3: Signals

- Product changes.
- Reader questions.
- Support patterns.

### H2 (G): What you maintain

#### H3: What decays fastest

- Screenshots, UI steps, API params.

### H2 (G): Maintenance workflow

#### H3: Cadence

- 30/60/90-day checks where appropriate.

#### H3: Ownership

- Who should notice breakage.

### H2 (G): Output

- Updated doc + maintenance notes.

---

## Optional: Templates & checklists section (if you want the manual to be executable) <!-- NOTE: Agree to include this section as resources for other technical writers or those who want to implement the manual -->

### H2: How to use this section

- Treat these as free resources so readers can copy and adapt.
- Keep each checklist versioned (so changes are trackable).
- Prefer linking to the canonical file in `resources/`.

## C1) Content checklist (`resources/Checklists/Content Checklist (v1.1.0)/Content Checklist (v1.1.0).md`)

### H2 (C1): What it is

- A working checklist for writing a content piece.

### H2 (C1): Structure

- Warm-Up
- Stage 1: Pre-Writing
- Stage 2: Writing
- Stage 3: Post-Writing
- Stage 4: Maintenance

### H2 (C1): Future checklists

- Add new checklists under `resources/Checklists/<Name (vX.Y.Z)>/`.
- Keep one “canonical” checklist per folder.

## T1) Discovery brief template (`/templates/discovery-brief`)

### H2 (T1): Template fields

#### H3: Audience and use case

- Primary user.
- Job-to-be-done.

#### H3: Scope

- In/out.

#### H3: Assumptions and risks

- What might change.

#### H3: Success criteria

- What counts as success.

### H2 (T1): Example (filled)

- One real example.

## T2) Outline template (`/templates/outline-template`)

### H2 (T2): Required sections

#### H3: Goal + prerequisites

- What the reader will achieve.

#### H3: Steps + verification

- How the reader confirms success.

#### H3: Troubleshooting

- Common failures.

### H2 (T2): Example (filled)

- One real example.

## T3) Pre-publish checklist (`/checklists/pre-publish`)

### H2 (T3): Accuracy

#### H3: Product reality

- Verified behaviors.

### H2 (T3): Usability

#### H3: First-screen clarity

- Reader knows what to do.

### H2 (T3): Consistency

#### H3: Terms and examples

- Stable terminology.

### H2 (T3): Maintenance readiness

#### H3: What will change

- Notes on decay points.
