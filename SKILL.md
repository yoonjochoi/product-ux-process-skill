---
name: product-ux-process
description: >-
  Assesses product and UX work against a gold-standard PRD and full Product/UX
  process (charter, research-based problem, decision funnel, Fogg, analogs,
  workshop, Big Bets, experiment PRDs, personas, iterative design, validate,
  ship). Use when the user asks to assess a project or brief, find gaps in a
  PRD, decide ideal next steps, draft missing PRD sections, or invoke their
  Product/UX process skill.
---

# Product/UX Process

Personal playbook for assessing initiatives against a successful Product/UX process and PRD pattern language.

**Language:** Designer-friendly name first; product/strategy term in parentheses. Example: Frame the mission and the number (Charter + quantified north star).

## When to use

- Assess this brief / project / PRD against my Product/UX process
- What stage am I in and what’s missing?
- What are the ideal next steps?
- Draft the experiment PRD / strategy sections I’m missing
- Gap analysis before a workshop, design cycle, or experiment

## Workflow

1. **Read supporting files as needed**
   - Stages + exit criteria: [process.md](process.md)
   - Pattern rubric + Fogg primer: [prd-patterns.md](prd-patterns.md)
   - Doc skeletons: [templates.md](templates.md)
   - Strong vs weak contrasts: [examples.md](examples.md)

2. **Intake** — Gather whatever the user shares (brief, PRD, notes, case study, verbal summary). Do not require a Google Doc fetch.

3. **Diagnose stage** — Map the work to the current stage in [process.md](process.md) (1–12). Surfaces may still be provisional before the strategy workshop.

4. **Score against patterns** — Check patterns in [prd-patterns.md](prd-patterns.md). Flag missing or weak items.

5. **Output assessment** — Always use the format below.

6. **Optional drafting** — If asked, draft missing sections using [templates.md](templates.md). Keep examples generalized; no confidential company metrics.

## Assessment output (required every time)

```markdown
## Stage diagnosis
[Current stage number + name. One sentence on why.]

## Strengths
- [What already meets the gold bar]

## Gaps
### Critical
- [Gap] → maps to [pattern/stage]
### Important
- [Gap] → maps to [pattern/stage]
### Nice-to-have
- [Gap] → maps to [pattern/stage]

## Ideal next steps
1. [Action] → artifact: [what to produce]
2. …
(3–7 steps, ordered)

## PRD scorecard
(Only if assessing a doc. Score each pattern: Strong / Partial / Missing)
| Pattern | Score | Note |
|---------|-------|------|
| … | … | … |
```

## Rules

- Prefer dual language in headings when naming patterns or stages.
- Require evidence-backed problems before accepting feature ideas.
- Require decision-funnel stage + Fogg (MAP) diagnosis before accepting solution bets.
- Surfaces (“where it shows up in product”) lock after the strategy workshop, not in the initial charter.
- Design is a loop: personas → go wide → narrow → quick prototype → usability → repeat.
- Formative usability = design stage; summative experiment validation = validate stage.
- Generalize examples; do not invent or paste confidential metrics.
