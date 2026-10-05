# Product/UX process stages

Full lifecycle derived from a gold-standard strategy/experiment PRD, extended into design and learning. Designer-friendly name first; product term in parentheses.

**Sequencing rules**
- Surfaces (“where it shows up in product”) are provisional in stage 1; confirmed in stage 7 workshop; locked in stage 8.
- Strategy ideation workshop (stage 7) ≠ design go-wide workshops (stage 10b).
- Formative usability = stage 10. Summative experiment validation = stage 11.

```text
1 Charter → 2 Research → 3 Diagnose → 4 Decision funnel
→ 5 Fogg → 6 Analogs → 7 Workshop → surfaces
→ 8 Vision/Big Bets → 9 Experiment PRDs
→ 10 Design loop (personas → wide → narrow → proto → usability → repeat)
→ 11 Validate → 12 Ship/measure/revise
```

---

## 1. Frame the mission and the number (Charter)

**Job:** Define mission, north star, value of one win, constraints. Surfaces optional/provisional.

**Designer activities**
- Align on the human outcome and business stake
- List candidate surfaces without locking them

**Exit criteria**
- Written charter
- Baseline → target for the north star
- Value of one win stated (even if approximate)

**Done-enough example**
“Raise assisted onboarding from under ~15% → ~35%; each incremental setup worth ~$X.” Candidate surfaces noted, not locked.

---

## 2. Ground the problem in research (Research)

**Job:** Gather/synthesize qual + quant + prior studies into a research-based problem.

**Designer activities**
- Mine or run interviews; pull quotes and JTBD language
- Partner with analytics on funnel/outcomes
- Synthesize prior research and experiment learnings

**Exit criteria**
- Cited problem evidence pack (quotes, data, takeaways)
- Problem defensible without jumping to a feature

**Done-enough example**
Customer quotes + funnel drop-offs + prior research on expert avoidance in a shareable research brief.

---

## 3. Prove the problem (Diagnose)

**Job:** Build the full problem stack + primary hypothesis.

**Designer activities**
- Write mad-libs problem statement
- Document what worked / didn’t
- Draft primary hypothesis the team can debate

**Exit criteria**
- Mad-libs problem + primary hypothesis
- Problem stack reviewed with partners

**Done-enough example**
Mad-libs problem + hypothesis: “prompts mistimed + call too high-commitment.”

---

## 4. Map the path to the action (Decision funnel)

**Job:** Name stages to the target behavior; mark worst drop-off; pick stage to attack.

**Designer activities**
- Map awareness → interest → decision → action (or adapted stages)
- Overlay data/qual on each stage
- Choose primary stage for intervening

**Exit criteria**
- Named funnel stages
- Primary stage to attack with rationale

**Done-enough example**
Awareness → Interest → Decision → Action; worst drop-off at Interest/Decision (value + scheduling commitment).

---

## 5. Name the behavior mechanics (Fogg / behavioral grounding)

**Job:** Diagnose Motivation / Ability / Prompt **at the chosen funnel stage**.

**Designer activities**
- Name target behavior
- Score M / A / P at the drop-off stage
- State which lever(s) bets should move

**Exit criteria**
- MAP diagnosis with primary blocker lever(s)
- Link to funnel stage

**Done-enough example**
At Decision stage, Ability + Prompt are primary blockers; Motivation mostly present.

See Fogg primer in [prd-patterns.md](prd-patterns.md).

---

## 6. Steal clarity from analogs (Analog research)

**Job:** Gather outside-product patterns that move the same MAP levers / funnel stage.

**Designer activities**
- Select 2–4 analogs (not only competitors)
- Extract M/A/P and journey-moment patterns
- Write steal vs reject notes; pair to pathways if known

**Exit criteria**
- Analog pack ready for workshop
- Steal/reject explicit

**Done-enough example**
Canva/Duolingo for tech-only Ability+Prompt; Superhuman/HubSpot for human-led Motivation+Ability.

---

## 7. Workshop ideas as a team (Ideation workshop)

**Job:** Cross-functional brainstorm mapped to funnel stage + MAP + analogs; identify where it shows up in product.

**Designer activities**
- Facilitate or co-facilitate
- Cluster ideas by bet theme / stage / lever
- Drive to candidate surfaces + shortlist

**Exit criteria**
- Clustered idea landscape
- Candidate surfaces
- Shortlist for Big Bets / experiments

**Done-enough example**
Shortlist includes dynamic prompt at abandonment, durable expert step in agentic onboarding, async leave-a-message; surfaces around Setup Hub / GTKM / Contact Experts.

---

## 8. Set the direction (Strategy)

**Job:** Vision, Big Bets, locked surfaces, success/learning metrics.

**Designer activities**
- Help articulate vision and pillar bets from workshop shortlist
- Lock surfaces with PM/eng
- Frame metrics as questions (with PM/analytics)

**Exit criteria**
- Strategy PRD draft that passes [prd-patterns.md](prd-patterns.md) for patterns 1–9 (as applicable)
- Surfaces locked

**Done-enough example**
Expert-led onboarding vision + 4 Big Bets; metrics as questions the half will answer.

Use Strategy template in [templates.md](templates.md).

---

## 9. Break it into tests (Slice)

**Job:** Turn bets into experiment / LOFA PRDs.

**Designer activities**
- Co-write provocation, problem-in-brief, requirements implications
- Ensure each experiment maps to a Big Bet + MAP lever + funnel stage

**Exit criteria**
- At least one shovel-ready experiment PRD

**Done-enough example**
“Dynamic help at setup abandonment” has provocation, LOFA, requirements, and test plan.

Use Experiment template in [templates.md](templates.md).

---

## 10. Design the experience (Iterative design)

**Job:** Repeatable design loop. Personas/pathways **before** going wide.

**Exit criteria**
Decision-ready design that reflects:
- Product needs (hypothesis, bet, surfaces, metrics)
- User needs (research + usability evidence)

### 10a. Personas as pathways
Who we’re designing for; which solution modes fit which people. May start in research; must be explicit before go-wide.

### 10b. Go wide
Multiple design directions across pathways; design brainstorms/workshops as needed; reuse analogs. Separate from stage 7 strategy workshop.

### 10c. Narrow
Critique against problem, funnel stage, Fogg levers, personas, constraints, metrics-as-questions. Select 1–2 directions to pressure-test.

### 10d. Quick prototype
Fidelity only as high as needed to learn the next thing (flows, clickable, script, voice, etc.).

### 10e. Usability research (formative)
Test with relevant persona segments; capture failures in comprehension, trust, ability, prompt timing.

**Repeat 10b–10e** until ready to build / experiment.

**Done-enough example**
Nellie vs Marvin pathways → wide expert-handoff patterns → narrow to inline + durable access → prototype → usability shows unclear AI vs expert boundary → another cycle → designs match bet and mental models.

---

## 11. Learn before you scale (Validate)

**Job:** Qual + quant learning plan for the experiment; graduation criteria.

**Designer activities**
- Partner on learning questions and success thresholds
- Separate formative usability (done in 10) from experiment readouts

**Exit criteria**
- Graduation criteria defined (pilot → experiment → scale)
- Instrumentation / readout plan clear

**Done-enough example**
Pilot with ring-fenced experts; graduate if contact rate and quality clear thresholds without transfer-rate blowups.

---

## 12. Ship, measure, revise (Ship and learn)

**Job:** Instrument, read results, revise bets. Decide iterate / expand / kill.

**Designer activities**
- Support readout interpretation against MAP + funnel stage
- Propose design revisions or new experiment slices

**Exit criteria**
- Explicit decision: iterate / expand / kill
- Learnings fed back into strategy or next experiment

**Done-enough example**
Multi-call pilot lifts reengagement but burns expert time → revise toward async instead of expanding live calls.

---

## Stage diagnosis cheat sheet

| If you mostly have… | You’re probably in… |
|---------------------|---------------------|
| Ambiguous goal, no metric | 1 Charter |
| Opinions, thin evidence | 2 Research |
| Research but no mad-libs/hypothesis | 3 Diagnose |
| Problem but no journey drop-off pick | 4 Decision funnel |
| Journey pick but no M/A/P | 5 Fogg |
| MAP clear but no outside patterns | 6 Analogs |
| Diagnosis ready, no team ideation / surfaces | 7 Workshop |
| Ideas, no vision/pillars/locked surfaces | 8 Strategy |
| Strategy, no shovel-ready experiment | 9 Slice |
| Experiment brief, thin design loop | 10 Design |
| Design ready, no graduation bars | 11 Validate |
| Live in market, no revise decision | 12 Ship/learn |
