# Product/UX Process Skill

A personal Product/UX playbook distilled from a gold-standard strategy + experiment PRD pattern. Use it to assess briefs, find gaps, recommend next steps, and draft missing PRD sections.

**Language:** Designer-friendly name first; product/strategy term in parentheses  
Example: *Frame the mission and the number (Charter + quantified north star)*

## What’s inside

| File | Purpose |
|------|---------|
| `SKILL.md` | Cursor skill entrypoint — when to use, workflow, assessment output format |
| `prd-patterns.md` | 13 success patterns + Fogg (B = MAP) primer |
| `process.md` | 12-stage Product/UX lifecycle with exit criteria |
| `templates.md` | Strategy PRD + Experiment PRD skeletons |
| `examples.md` | Strong vs weak contrasts per pattern |

## Use in Cursor

### Personal (all your projects)

```bash
cp -R product-ux-process ~/.cursor/skills/
```

Or clone this folder to:

```text
~/.cursor/skills/product-ux-process/
```

### Project (share with a repo’s collaborators)

```bash
mkdir -p .cursor/skills
cp -R product-ux-process .cursor/skills/
```

Commit `.cursor/skills/product-ux-process/` so teammates get it when they open the repo in Cursor.

### Invoking it

In any Cursor chat:

- “Assess this brief against my Product/UX process”
- “What stage am I in and what’s missing?”
- “Draft the experiment PRD sections I’m missing”
- “Gap analysis before our workshop”

Cursor loads `SKILL.md` from the skill description; the agent then reads the supporting files as needed.

## Use on any AI platform

The process knowledge is plain markdown. Cursor packaging (`SKILL.md` frontmatter, skill folders) is optional.

### Option A — Attach / upload as context

Upload or attach:

1. `process.md` (stages)
2. `prd-patterns.md` (rubric)
3. Optionally `templates.md` and `examples.md`

Then ask the same assessment questions.

### Option B — Paste a system / project instruction

Use this as a custom GPT, Claude Project, or system prompt (short version):

```text
You are my Product/UX process coach. Follow the dual-language pattern names
(designer-friendly first, product term in parentheses).

When I share a brief, PRD, or project notes:
1. Diagnose the current process stage (1–12).
2. Score against the 13 success patterns.
3. Output: Stage diagnosis, Strengths, Gaps (Critical / Important / Nice-to-have),
   Ideal next steps (3–7 with artifacts), and a PRD scorecard if assessing a doc.

Rules:
- Require research-backed problems before features.
- Require decision-funnel stage + Fogg (Motivation / Ability / Prompt) before bets.
- Surfaces lock after the strategy workshop, not in the initial charter.
- Design is a loop: personas → go wide → narrow → prototype → usability → repeat.
- Keep examples generalized; no confidential metrics.

I will paste or attach process.md and prd-patterns.md as the source of truth.
```

Then paste or pin `process.md` + `prd-patterns.md` in that workspace.

### Option C — Notion / docs hub

Copy the markdown files into a Notion database or docs folder and @-mention them when starting a new initiative review.

## Assessment output (standard)

Every assessment should use:

1. **Stage diagnosis** — where the work sits
2. **Strengths** — what already meets the bar
3. **Gaps** — Critical / Important / Nice-to-have
4. **Ideal next steps** — ordered actions + artifacts
5. **PRD scorecard** — if assessing a document

## Process at a glance

```text
Charter → Research → Diagnose → Decision funnel → Fogg → Analogs
→ Workshop (confirm surfaces) → Vision / Big Bets → Experiment PRDs
→ Design loop → Validate → Ship / measure / revise
```

## Notes

- No confidential company metrics belong in these files; examples stay generalized.
- Keep a personal copy in `~/.cursor/skills/` for yourself; share via project `.cursor/skills/` or this folder/repo for others.
