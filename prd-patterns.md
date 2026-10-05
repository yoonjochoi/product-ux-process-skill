# PRD success patterns

Rubric distilled from a gold-standard Assisted Onboarding strategy + experiment PRD. Patterns are generalized — encode structure, not confidential metrics.

**Language:** Designer-friendly name first; product/strategy term in parentheses.

**Sequencing:** Early framing locks mission + north star. **Where it shows up in product (surfaces)** is often provisional at first and confirmed in the team workshop after research, decision funnel, Fogg, and analogs.

---

## 1. Frame the mission and the number (Charter + quantified north star)

What we’re doing, why one success matters to the business, and the from → to metric. Surfaces may be a rough hypothesis only.

**Must include**
- Mission (one clear job)
- Value of one win (why an incremental success matters)
- North star: baseline → target
- Constraints / in-scope intent
- Optional: candidate surfaces (not locked)

**Example**
Mission = help new customers onboard via AI + human experts. Value of one win = ~$X per incremental successful setup. North star = assisted onboarding rate from under ~15% → ~35%. Candidate surfaces: Setup Hub, GTKM, Contact Experts — not locked yet.

**Fail if**
- Only a feature list
- No baseline/target
- Surfaces treated as final before workshop

---

## 2. Ground the problem in research (Research-based problem)

The problem must be backed by primary/secondary research, not stakeholder opinion alone.

**Must include**
- Qual: interviews, quotes, JTBD language from real customers
- Quant: funnel, abandonment, outcome correlations
- Synthesis: prior study takeaways + what worked / didn’t
- A problem you can defend with citations/evidence

**Example**
Customer quote on time scarcity + finding that assisted-onboarding completers are far more likely to finish core actions + research on why customers avoid expert calls → evidence-backed problem before any solution workshop.

**Fail if**
- Problem is a rephrased feature request
- No customer voice or data

---

## 3. Prove the problem before designing (Problem stack before solutions)

Stack evidence into a decision-ready narrative.

**Stack order**
1. Overarching problem
2. Mad-libs problem statement: `I am / I am trying to / But / Because / Which makes me feel`
3. Why current path fails
4. Funnel diagnosis
5. What worked / didn’t
6. Primary hypothesis

**Example**
Overarching = admin “slog” for small business owners. Mad-libs = trying to run invoicing/payroll in one place, stuck on foundational setup. Funnel drops before expert contact. Primary hypothesis names the main barrier to test.

**Fail if**
- Jumps from anecdote to solution
- No primary hypothesis

---

## 4. Map the path to the action (Decision funnel)

Before inventing solutions, map stages to the target behavior and mark drop-offs. This chooses **which stage to attack**.

**Typical stages**
Awareness → Interest → Decision → Action (adapt labels to the behavior)

**Must include**
- Named stages
- Evidence of where drop-off is worst
- Primary stage to attack

**Example**
Setup Call funnel: Awareness (eligibility) → Interest (value + psychological safety) → Decision (prioritize & schedule) → Action (attend & engage). Worst drop-off at Interest/Decision → don’t workshop Awareness-only ideas.

**Fail if**
- Solutions exist with no journey-stage diagnosis
- Funnel only appears as a late appendix after designs

---

## 5. Name the human behavior mechanics (Behavioral grounding / Fogg)

Strategy isn’t “make a better UI” — it’s “change a specific behavior.” Default model: **Fogg Behavior Model (B = MAP)**. Apply MAP **at the funnel stage(s)** with worst drop-off.

### Fogg primer (B = MAP)

A target behavior happens only when three things converge at the same moment:

| Lever | Question | If broken, design toward… |
|-------|----------|---------------------------|
| **Motivation** | Do they *want* the outcome right now? | Sharper value, less fear/uncertainty, vivid outcome |
| **Ability** | Can they do it *easily enough*? | Shorter path, lower commitment, less cognitive/logistics friction, lighter channels |
| **Prompt** | Is there a cue *at that moment*? | In-context ask at the stuck moment, not a generic tile |

**Must include**
- Named target behavior
- Funnel stage in focus
- MAP diagnosis (which lever(s) are primary blockers)
- Bets that map to those levers

**Example**
Target = book/attend/engage with expert help. Stage = Interest/Decision. Motivation often present; Ability blocked by high-commitment scheduled call; Prompt mistimed vs moments of stuckness → bets raise Ability + improve Prompts.

**Assessment rule**
Require funnel stage + Fogg (or equivalent) diagnosis before accepting feature ideas. Flag bets that don’t map to M, A, or P.

**Fail if**
- Features with no behavior model
- Only “market it harder” when Ability/Prompt are the blockers

---

## 6. Steal clarity from analogs (Analog research)

After funnel stage + MAP levers are known, study products *outside* the domain that solved a similar **human** problem. Borrow the experience pattern, not UI chrome.

**Why after Fogg**
Analogs are sharper when filtered by “we need Ability + Prompt at Decision,” not a generic mood board.

**Extract per analog**
- Target behavior
- How they handle M / A / P
- Tech-only, human-led, or hybrid — for whom?
- Which journey moment the magic interaction hits
- What “good” would feel like adapted to our surfaces
- Explicit **steal** vs **reject**

**When**
- Prep into strategy workshop (2–4 analogs)
- Reuse in design go-wide
- Not appendix-only after designs are done

**Example**
Nellie (tech-only): Canva, Duolingo — progressive self-serve, low commitment. Marvin (human-led): Superhuman, HubSpot — structured expert onboarding. Insight: different pathways, not one average experience.

**Fail if**
- Jump to UI with no outside references
- Only direct competitors cited
- No steal/reject notes

---

## 7. Workshop ideas as a team (Collaborative ideation)

After research + funnel + Fogg + analogs, run a cross-functional workshop. Surfaces often get confirmed here.

**Inputs**
Charter, research-based problem, problem stack, decision funnel, Fogg diagnosis, analogs, personas if ready

**Outputs**
- Ideas clustered by bet theme / funnel stage / MAP lever
- Candidate surfaces (where it shows up in product)
- Shortlist for Big Bets / experiments

**Example**
Workshop favors in-context prompt at abandonment and durable expert access in agentic onboarding over homepage banners; surfaces finalize to Setup Hub / GTKM / Contact Experts.

**Fail if**
- Ideation before evidence + MAP
- Surfaces invented by one person with no team pass
- Feature laundry list with no clustering

---

## 8. Paint the destination, then pick a few bets (Vision + Big Bets)

Converge workshop output into a vision + 3–5 strategic pillars. Lock surfaces here (or refine workshop list).

**Must include**
- Vision statement
- 3–5 Big Bets (pillars, not a backlog dump)
- Locked surfaces

**Example**
Vision = expert-led platform onboarding. Bets = default next-best-action for expert help; surface value in context; expand eligibility; zero-friction multi-channel service.

**Fail if**
- 15 “bets” that are really tickets
- Vision with no pillars
- Surfaces still vague after strategy

---

## 9. Ask what each metric will teach us (Metrics as questions)

Success and learning metrics framed as “Question to Answer.”

**Must include**
- Key success metrics → decision each answers
- Learning metrics → decision each answers

**Example**
Success: “Does multi-call drive incremental revenue per customer?” Learning: “Are treatment customers reaching out more?” / “Is experience quality maintained?”

**Fail if**
- Vanity metrics with no decision link
- Success metrics only, no learning metrics

---

## 10. Break strategy into testable bets (Nested experiment PRDs)

Under the strategy, nest shovel-ready experiment PRDs.

**Each experiment PRD should include**
- Provocation in ~2 sentences
- Problem (brief)
- LOFA (leap of faith assumption)
- Hypothesis
- Success + learning metrics (as questions)
- Functional requirements
- Risks, open questions
- Strategic alignment to a Big Bet

**Example**
Nested PRDs for durable expert access in agentic onboarding, dynamic contact experts at moments of need, multiple onboarding calls.

**Fail if**
- Strategy with no testable slice
- Experiment with no LOFA / hypothesis / requirements

---

## 11. Define when we graduate (Graduation criteria)

Pilot → experiment → scale. Clear bars to expand or kill.

**Must include**
- Stage definitions (pilot / experiment / scale)
- Thresholds or decision rules
- What happens if bars aren’t met

**Example**
Small multi-call pilot with ring-fenced experts must clear contact/quality/learning bars before a fuller A/B or broader eligibility.

**Fail if**
- “We’ll know it when we see it”
- Scale planned with no pilot learning plan

---

## 12. Design for different people differently (Personas as pathways)

Before (and throughout) the design loop, define who you’re designing for and which solution *mode* fits each. Personas are an **input** to go-wide, not an afterthought. May start in research; must be explicit before design go-wide.

**Must include**
- Named personas / segments
- Pathway/mode per persona (e.g. tech-only vs human-led)
- Tie to same north star

**Example**
Nellie (new to product) → guided self-serve/AI. Marvin (migrator) → human-led onboarding. Same north star, different paths.

**Fail if**
- One average user
- Personas as decoration with no design implications

---

## 13. Go wide, then narrow — repeatedly (Iterative design process)

Design is a loop until the experience reflects product needs and user needs.

**Loop**
1. **Go wide** — multiple directions across persona pathways; design workshops as needed (≠ strategy workshop); reuse analogs
2. **Narrow** — critique vs problem, Fogg, funnel stage, personas, constraints, metrics-as-questions
3. **Quick prototype** — lowest fidelity that answers the current question
4. **Usability research** — formative; test relevant segments
5. **Repeat** until decision-ready for build/experiment

**Guides while looping**
Personas/pathways; decision-funnel stage; MAP lever being moved

**Example**
Wide set of expert-handoff patterns → narrow to inline + durable access → prototype → usability shows unclear AI vs expert boundary → another cycle on handoff framing.

**Note**
Formative usability = this pattern. Summative experiment validation / graduation = later process stage.

**Fail if**
- Single mock shipped as “the design”
- No usability before build
- Go-wide skipped (jumped to first idea)

---

## Quick scorecard checklist

When assessing a PRD or brief, score each pattern: **Strong / Partial / Missing**

1. Mission and number (Charter)
2. Research-based problem
3. Problem stack + hypothesis
4. Decision funnel
5. Fogg MAP at drop-off stage
6. Analogs (steal/reject)
7. Team workshop + surfaces
8. Vision + Big Bets
9. Metrics as questions
10. Nested experiment PRDs
11. Graduation criteria
12. Personas as pathways
13. Iterative design loop evidence
