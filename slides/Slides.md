---
marp: true
theme: custom-default
footer: 'Refactoring your Developer Identity'
transition: reveal
---

![bg right](./img/refactor.png)
# Refactoring Your Developer Identity
## Moving Beyond Your Favorite Stack
<!-- Speaker Notes: Story: senior engineer declines greenfield service (Go + event-driven) because they're a "Java person"; opportunity + visibility shifts to someone who learns. Ask: Where does your real leverage come from? -->

---


![bg left:40%](./img/portrait.png)

## Chris Ayers

_Senior Site Reliability Engineer_  
_Azure CXP AzRel_  
_Microsoft_

<i class="fa-brands fa-bluesky"></i> BlueSky: [@chris-ayers.com](https://bsky.app/profile/chris-ayers.com)
<i class="fa-brands fa-linkedin"></i> LinkedIn: - [chris\-l\-ayers](https://linkedin.com/in/chris-l-ayers/)
<i class="fa fa-window-maximize"></i> Blog: [https://chris-ayers\.com/](https://chris-ayers.com/)
<i class="fa-brands fa-github"></i> GitHub: [Codebytes](https://github.com/codebytes)
<i class="fa-brands fa-mastodon"></i> Mastodon: [@Chrisayers@hachyderm.io](https://hachyderm.io/@Chrisayers)
~~<i class="fa-brands fa-twitter"></i> Twitter: @Chris_L_Ayers~~

---

## Agenda
- Problem & framing
- Identity formation & lock‑in mechanics
- Cost, risk & opportunity landscape
- Patterns, triggers & anti‑patterns
- Transferable skills beyond the stack
- Adaptive mindset & operating loop
- Decision matrix, learning debt & lightweight artifacts
- Career resilience & future‑proofing (AI & automation)
- Action plans (30 | 60–90 day)
- Q&A / Discussion
<!-- Speaker Notes: Updated to reflect consolidated adaptive section (loops + decisions + learning debt) and clearer progression: awareness → diagnosis → durable skills → operating system → artifacts → resilience → action. Reassure: no shaming—this is an upgrade path. -->

---

## Why This Talk

<div class="columns">
<div>

## Problem

* Identity tied closely to tools or stacks
* New tech feels uncomfortable or risky
* Familiar solutions stretched too far

</div>
<div>

## Opportunity

* Skills transfer across domains
* Strong architecture & judgment multiply your impact
* Adaptability makes you durable

</div>
</div>

<!-- Speaker Notes:
Frame: Normal to anchor identity to tools. Cost appears when growth = avoiding discomfort.
Bridge: Recast discomfort as the leading indicator of future leverage.
Anchor themes (3): Architecture (upstream leverage), Judgment (trade-off clarity), Leverage (multiplying effect across domains). -->
<!-- Transition Cue: Next we unpack how that identity hardens. -->

---

## How Technical Identity Forms

**Loop**
1. Early win → speed & praise
2. Requests funnel back to “the expert”
3. Repetition deepens comfort & narrows lens
4. Discomfort risk feels higher → avoidance

<!-- Speaker Notes: 
- Early wins in one stack = comfort and speed
- Positive feedback reinforces the pattern
- Labeled as "the X expert" by teams or orgs
* Hard to walk away from years of investment
* Feels risky to be a beginner again

- "This isn't a flaw-it's human psychology. We all like to stick with what we're praised for."
- "Teams and orgs reinforce it too-once you're branded the X expert, people keep pulling you back there."
- "That's how identity calcifies. Not because of weakness, but because of perfectly normal incentives."
-->

---

## Identity Smells
  

- Introducing yourself by stack
- Preferring the familiar before exploring alternatives
- Refactoring early toward patterns you know well
- Hesitant to review outside your specialty
- Equating speed in one stack with seniority

<!-- Speaker Notes: 
- "Think of these like code smells - they're not disasters, just signals worth paying attention to."
- Introducing yourself by stack: "Back in the day it was normal to say ‘I'm a Java developer' or ‘.NET developer.' But now systems span languages, platforms, and services. Defining yourself too narrowly can box you in."
- Preferring the familiar: "We used to roll our own authentication flows. Today, with OAuth and managed identity, doing it yourself is often a security risk."
- Refactoring early toward known patterns: "Forcing everything into MVC worked when web apps were simpler, but microservices and event-driven designs pushed us toward new patterns."
- Hesitant to review outside your specialty: "Infra-as-code used to feel like ‘not my job.' Now, reliability and performance are defined as much by infra as by code."
- Equating speed with seniority: "In the past, being the fastest at writing raw SQL was impressive. Today, ORMs, caching, and distributed databases have shifted what ‘senior' really means."

- "Now, those patterns we just walked through? They're not abstract. Most of us can probably think of times we've done at least one of them. Let's take a moment to reflect privately."
- "This isn't about guilt or sharing - just noticing where identity shows up in your own work."
-->

---


## Self-Assessment (Silent Exercise)

* List 3 tech areas you reflexively avoid

* Note the last time you shipped in an unfamiliar stack

* Identify a decision you biased toward comfort

* What fear drove it? (status / time / exposure)

* Circle one to interrogate later

<!-- Speaker Notes: 
- "We're going to pause for 90 seconds. No sharing, no judgment - this is just for you."
- List 3 tech areas you reflexively avoid:  
    "For example, some of us shy away from front-end frameworks, or from infra-as-code, or maybe even machine learning. Write down yours."
- Last time you shipped in an unfamiliar stack:  
    "Think of the last time you had to work outside your comfort zone. How did that feel? What did you learn?"
- Decision biased toward comfort:  
    "Maybe you picked the database you always use, even if another one might have been better."
- What fear drove it:  
    "Was it fear of slowing down, of looking junior again, of losing credibility? Totally normal."
- Circle one to interrogate later:  
    "You don't have to solve it now. Just pick one that feels worth revisiting after this talk."

- "Okay, let's bring it back. You don't have to share what you wrote - this is just for you. But keep that note nearby, because we'll circle back later when we talk about action plans."
- "The point isn't to feel bad about the past - it's to notice the patterns so you can choose differently in the future."
-->

---


# <!-- fit -->Cost & Risk Landscape

## What rigidity costs you over time
<!-- Speaker Notes: Transition: We've surfaced personal patterns; now translate identity lock into concrete organizational and personal risk dimensions before prescribing change. Anchor audience attention on why change is economically & operationally rational. -->

---

<!-- Brief pivot: We'll narrow straight to how identity rigidity constrains YOUR leverage and what shifts when you refactor it. -->

# Risk Surface

- Narrow tool identity → funnel of repetitive maintenance work
- Miss paradigm fit early → rework & credibility drag
- AI automates rote stack speed faster than you up-skill
<!-- Speaker Notes: Make risk concrete: (1) Narrow framing means others route you low-variance tasks; reduces exposure to architecture decisions. (2) Staying in familiar paradigm causes late design pivots that appear as indecision. (3) AI closes gap on raw throughput; leverage must shift to judgment, architecture, integration, trade-offs. Transition: now quantify opportunity lost. -->

---

# Opportunity Cost

- Each avoided paradigm = delayed compounding mental model
- Comfort tasks displace deliberate practice reps
- Missed early reps defer staff-level readiness timeline
<!-- Speaker Notes: Emphasize compounding: early exposure to streaming, idempotency, back-pressure yields years of intuition; skipping now pushes out senior signals (cross-domain design, trade-off fluency). Encourage audience to think of paradigms as interest-bearing assets. -->

---

# Negotiation & Mobility

- Broader pattern vocabulary = more roles you can credibly step into
- Outcome-first narratives shift interviews from quiz to co-design
- Lightweight decision records externalize your leverage (portable evidence)
- Clear trade-off language increases perceived seniority & comp ceiling
<!-- Speaker Notes: Differentiators: (1) Pattern vocabulary (events, CQRS, back-pressure, caching strategies) expands credible role scope (platform, data, reliability). (2) Outcome narratives: Framing past work as problem -> constraints -> options -> decision turns interviews into peer discussions, reducing algorithm trivia focus. (3) Decision records: Small artifacts (context, options, rationale) become portable proof of judgment across teams/companies. (4) Trade-off language (latency vs durability, consistency vs throughput) signals seniority; strengthens negotiation BATNA by evidencing repeatable thinking, not just stack familiarity. Prompt: Circle which of these is weakest for you today. -->

---

# Resilience & Advancement

- Paradigm fluency (events, streaming, functional, batch) = faster safe redeploy when platforms shift
- Cross-layer empathy (frontend ↔ backend ↔ infra ↔ data) dissolves friction → you become default design facilitator
- Pattern breadth + decision artifacts → earlier trust for owning architecture scope

<!-- Speaker Notes: (1) Paradigm fluency: naming + selecting patterns (event sourcing vs CRUD, stream processing vs batch) lets you pivot when a language/runtime or framework is disrupted (including AI-generated boilerplate). (2) Cross-layer empathy: Understanding concerns of UX performance, API latency, infra cost, data modeling enables you to translate between specialties—this accelerates consensus and reduces meeting cycles. (3) Breadth + artifacts: A track record of diverse pattern application + decision documents builds executive and peer trust to hand you architectural stewardship earlier.
 -->

---

# Energy & Motivation Return

- Dropping defensive “expert” posture frees attention for exploration
- Novel paradigms supply fresh puzzles → sustainable curiosity (not boredom)
- Small visible skill increments produce micro‑dopamine → momentum flywheel
- Variety reduces burnout: switching modes (event, data, infra) resets mental cache
<!-- Speaker Notes: Joy + clarity: (1) Defensiveness consumes cycles (“prove I’m still the expert”); releasing it reallocates energy to learning. (2) Novel paradigms act like new game mechanics—brain treats them as engaging puzzles, combating stagnation. (3) Frequent, bite-sized wins (one new mental model clarified, a decision record written) create intrinsic reward loops; motivation becomes self-fueling. (4) Intentional variety is preventative maintenance against burnout—context shifts refresh cognitive resources instead of grinding a single narrow loop. Prompt: Note which of these you’re currently missing. -->

---

# Leverage Shift Summary

- You keep depth; you gain a richer map to apply it creatively
- Breadth unlocks better roles, safer pivots, and wider influence surface
- Early discomfort is an investment that returns calmer ops & stronger trust
- Variety + continuous micro-learning = sustained joy instead of stagnation
<!-- Speaker Notes: Synthesis framed with joy: (1) Depth not discarded—now a versatile toolset applied across more contexts (creative satisfaction). (2) Breadth multiplies optionality: roles, domains, influence channels (design reviews, architecture forums). (3) Discomfort reframed as front-loaded capital expenditure yielding downstream operational serenity and reputational trust. (4) Variety + micro-learning loops prevent plateau; career feels like a sequence of engaging levels, not one long maintenance grind. CTA: Choose one intentional discomfort experiment for the next sprint and write it down now. Transition to behavioral patterns to operationalize change. -->

---

# <!-- fit --> Behavioral Patterns & Triggers
### Recognizing the reflexes before changing them
<!-- Speaker Notes: Pivot from cost awareness to diagnostic mode: name the triggers and anti-patterns so they become observable and interruptible. Encourage note-taking of personal matches. -->

---

## Comfort Zone Triggers

* New language / runtime → fluency drops; instinct: retreat to old stack
* Paradigm shift (events, functional, streaming) → mental remap tax feels costly
* Managed service option → perceived loss of control vs custom build comfort
* Outcome-first conversation → no tool anchor yet; anxiety to reassert expertise
* Ambiguous / shifting spec → fear of visible misstep; default to familiar template
<!-- Speaker Notes: Standardize pattern: Trigger → internal effect → reflex. Goal: label early so you can pause instead of auto-selecting the familiar path. Prompt: Star the two that fire most for you; those become interruption targets. -->

---

## Common Anti-Patterns

* Force-fit legacy framework: raises coupling & latency; hides paradigm mismatch
* Premature comfort ergonomics: adds migration & cognitive debt before value
* Missing calibrated first slice: drift (endless spikes) or gold-plating waste
* Tool-first RFC: debate devolves to preferences; problem clarity lost
* Anecdote-weighted risk: single scare blocks simpler, data-supported option
* Deferring non-functionals: retrofitting cost/latency/operability later is expensive
* Silo reinforcement: defensive reviews slow diffusion; team resilience drops
* "Rewrite later" myth: placeholder hardens; rewrite budget never arrives
<!-- Speaker Notes: Each bullet = Name: primary consequence. Use to map directly to counter-pattern slide. Prompt: Star TWO you personally slip into; those become your habit replacement targets. -->

---

## Mini Story: Comfort Lock (.NET → AI Gap)
- Reliable .NET engineer defers tiny Python reps (“stay efficient” rationale)
- Early AI prototypes (scripts, embeddings) ship without their input
- Activation energy rises; avoidance loop strengthens
- Perception shifts: peers seen expanding scope; they appear static
<!-- Speaker Notes: Normalize subtle pattern: avoidance disguised as efficiency. Emphasize quiet opportunity erosion rather than dramatic failure. Prompt: Ask for a quick show of hands: who has deferred a <30 line script because it felt outside lane? -->

---

## Flip Pattern → Leverage
- Micro-rep plan: 25‑min daily slice (run sample API, parse JSON, embed text)
- Fast visible win (internal assistant / log summarizer) reframes identity
- Translator role emerges: C# services ↔ Python AI tooling
- Result: Earlier seat in AI augmentation decisions vs reactive consumption
<!-- Speaker Notes: Contrast minimal investment vs compounded leverage. Invite audience to jot one micro-slice they could attempt this week. Transition directly to Counter-Patterns / later action plan. -->

---

<!-- Section Divider -->
# <!-- fit -->Skills beyond the Stack
## Transferable Skills beyond syntax & frameworks
<!-- Speaker Notes: Transition into the assets that transcend stacks; reframe identity around durable, compounding skills. Prompt audience to inventory their own. -->

---

# Transferable Skills (Exercise)

- List 3 non-stack skills you used this week
- Star the one that most amplified team impact
- Pick 1 that needs deliberate reps next month
- Note where you currently practice (or don't)
- Jot how you'd evidence it in a review
<!-- Speaker Notes: 60–75s silent exercise. Reinforce: We surface THEIR inventory first (avoid anchoring). Prompt: "Non-stack = would still matter if the language changed tomorrow." After time, quick show of hands: who picked a skill outside pure coding? Transition: now reveal example inventory to calibrate & fill gaps. -->

---

# Transferable Skill Inventory 

- Systems thinking / decomposition (clarify boundaries early)
- Trade-off articulation (expose cost vs benefit explicitly)
- Debugging methodology (structured hypothesis & tooling fluency)
- Communication & facilitation (alignment + reduced thrash)
- Risk / cost / constraint awareness (design within realities)
- Mentorship & knowledge diffusion (multiplying effect)
<!-- Speaker Notes: Briefly define each; tie to portability: survives framework shifts, compounds over time, accelerates org learning. Encourage audience to compare with their list—add any missing that resonate. Emphasize: maintain a living doc of these; review quarterly. -->

---

# Systems Thinking 

- Define system boundary + external actors first
- Surface invariant constraints (latency SLO, throughput, compliance)
- Map critical flows
- Identify coupling types (temporal, data, deploy)
- Make feedback loops explicit (metrics -> alert -> response)
- Write failure narrative: "It’s 2am, what broke?" adjust design
<!-- Speaker Notes:
Purpose: Shift identity from feature implementer to systems steward. 
Boundary: Force explicit scope; prevents accidental creep into adjacent systems.
Invariants: Latency SLO, durability requirement, regulatory constraints anchor trade-offs.
Flows: Draw minimal sequence / data flow; include at least one degradation scenario to expose hidden dependencies.
Coupling: Ask: Are components forced to wait (temporal), share schema (data), or deploy together (deploy)? Pick ONE to decouple this iteration.
Feedback Loops: No loop = silent failure. Define metric → threshold → alert owner.
Failure Narrative: Pre-mortem story reveals observability & resilience gaps early.
Facilitator Prompt: Ask audience which coupling type bites them most today.
-->

---

# Structured Problem Solving

- Restate problem w/ measurable impact (latency +X ms, error rate 3%)
- Separate symptom vs root signal (timeline + first deviation)
- Enumerate constraints (SLO, budget, headcount, deadline) before options
- Generate 3 distinct option shapes (simplest / resilient / scalable)
- Compare via 3–5 shared criteria (cost, complexity, risk, time-to-value)
- Capture decision rationale
<!-- Speaker Notes:
Restate: Convert vague pain into metrics; aligns team & defines success exit.
Symptom vs Root: Build a short event timeline; highlight first anomaly. Prevents cargo-cult fixes.
Constraints First: Avoids unconstrained ideation that later collapses when reality appears.
Options: Force structural diversity (don’t pick 3 variants of the same approach).
Criteria: Reusable rubric accelerates future similar decisions; reduces opinion heat.
Decision Record: Locks clarity; shields from re-litigating mid-implementation.
Facilitator: Ask for a recent example where constraints appeared too late.
-->

---

# Troubleshooting & Debugging Loop
- Define failure signature (symptoms + scope + severity)
- Form ranked hypotheses (probability × impact)
- Instrument / log gap?
- Run smallest falsification test per hypothesis
- Update mental model & prune disproved paths
- Capture root cause narrative + prevention action
<!-- Speaker Notes:
Signature: Precise scope prevents rabbit holes (which users / endpoints / regions?).
Hypotheses: Weighted list avoids random walk debugging.
Instrumentation Gap: If blind, invest first in visibility (log field, metric, trace span) before deeper guesswork.
Falsification: Choose step that eliminates most possibilities fastest (binary narrowing).
Model Update: Write quick note on actual system behavior vs prior belief; accelerates future incidents.
Root Cause Narrative: Include trigger, contributing factors, detection latency, remediation, prevention.
Facilitator: Quick poll—who still debugs without a written hypothesis list? Highlight efficiency gains.
-->

---

# Communication & Facilitation

- Start with problem + impact before solution detail
- Surface 3 assumptions explicitly; invite challenge early
- Time-box divergence → convergence (agenda w/ decision point)
- Summarize decisions + owners live (shared doc / chat)
- Translate across domains (latency vs UX vs cost) neutrally
- Close loop: publish outcome + rationale asynchronously
<!-- Speaker Notes:
Problem First: Prevents stakeholders anchoring on premature tool choice.
Assumptions: Making them explicit accelerates risk discovery & psychological safety to challenge.
Divergence/Convergence: Avoid endless ideation—signal when exploring ends & selection starts.
Live Summaries: Real-time capture reduces post-meeting ambiguity and rework.
Translation: Reframe concerns in counterpart’s vocabulary (e.g., “This adds 40ms p95 but halves on-call pages”).
Close Loop: Document outcome & reasoning; builds institutional memory & reduces repeat debates.
Facilitator Prompt: Ask who currently writes live decision notes; encourage trial next week.
-->

---

# Mentorship & Knowledge Sharing

- Pair outside comfort weekly → bi-directional pattern transfer
- Convert solved incident / decision into 5‑bullet internal post
- Run micro-teach (10 min) within 24h of learning slice
- Encourage question framing: context → goal → constraint → ask
- Seed successors: shadow → co-own → autonomous handoff
<!-- Speaker Notes:
Goal: Shift from individual learning to organizational compounding.
Pairing: Cross-domain pairing dissolves silos; treat as deliberate curriculum, not ad hoc rescue.
Post Conversion: Capture outcome, context, options, decision, lesson—keeps artifacts lightweight & searchable.
Micro-Teach: Teaching within 24h solidifies retention; 10 min lightning avoids scheduling friction.
Framed Questions: Improves signal quality & reduces back-and-forth latency; model publicly.
Diffusion Metric: Simple count—artifacts produced & distinct consumers (views, comments). Use to detect stagnation.
Successor Seeding: Intentional ownership transition prevents gatekeeping; increases resilience.
Facilitator Prompt: Ask who currently measures diffusion; propose adopting a simple monthly metric.
-->

---

# Security Thinking

- Threat sketch first: actors, asset, entry, impact
- Default deny: only grant minimal runtime / network / data scope
- Validate + sanitize all external input
- Add abuse case to each feature (misuse path & mitigation)
<!-- Speaker Notes:
Threat Sketch: 90-second whiteboard; clarifies what you are *actually* protecting.
Least Privilege: Narrow IAM roles, container perms, network egress; reduces blast radius.
Input Validation: Early reject invalid shape; prevents injection & resource abuse.
Secrets: Central rotation + audit; environment sprawl increases leak risk.
Logging: Enough to investigate (user id hash, action, timestamp) without secrets/tokens.
Abuse Case: Ask “How would someone exploit or degrade this?” prompts preemptive guardrails.
Facilitator Prompt: Quick show—who writes abuse cases today? Encourage adding one next PR.
-->

---

# Adaptive Operating System
### Making Change Cheap & Repeatable
- Core loop turns signals into shared learning
- Artifacts: decision snippets, thin experiments, learning debt log
- Metrics: loop cycle time, closure rate, diffusion reach
<!-- Speaker Notes: Position this as an operating system: rapid sense → experiment → integrate → teach. Emphasize low friction + compounding artifacts. -->

---
# Mindset Pyramid → Loop
**Pyramid (enable upward):**
1. Clarity (outcome & constraints)
2. Option diversity (≥3 distinct)
3. Thin experiment (small vertical risk slice)
4. Reflection (expected vs actual)
5. Diffusion (artifact / teach-back)
**Operating Loop:** Observe → Map → Slice → Measure → Reflect → Diffuse → (repeat)
<!-- Speaker Notes: Show dependency: without clarity, diversity degrades; without thin experiment, reflection is conjecture; without diffusion, benefits localize. -->

---
# Decisions & Experiments
- Thin Experiment: validate biggest uncertainty fast (days, not weeks)
- Decision Matrix: Build | Buy | Learn Prototype | Delegate/Pair | Defer
- Prompts: Differentiation? Operational drag? Uncertainty? Blast radius? Exit cost?
**6-Line Decision Artifact**
1. Context 2. Options 3. Decision 4. Trade-offs 5. Risk+Mitigation 6. Review date
<!-- Speaker Notes: Keep decision friction ultra-low to sustain habit; explicit trade-offs prevent revisionist history. -->

---
# Learning Debt & Adoption
**Learning Debt Item:** unknown / hypothesis / next probe / date
- Weekly triage: impact × recurrence risk
- Close states: validated, disproved, superseded
- Purge stale (>45d) or escalate
**Adoption Loop:** Map → Slice → Log Unknowns → Pressure Test (real data) → Teach Back → (repeat)
Metrics: closure %, median time-to-closure
<!-- Speaker Notes: Treat knowledge gaps as backlog; closure (even disproved) frees cognition; adoption loop targets 2–5 day cadence. -->

---
# Build / Buy / Delegate Heuristics
- Build: differentiates & offers learning yield with manageable ops
- Buy/Service: commodity, high reliability/compliance need
- Prototype (Learn): high uncertainty; cheap risk probe first
- Delegate/Pair: high risk + low internal context
- Defer/Simplify: low impact + high churn
**Tool Checklist:** problem crisp? success metrics? total cost? ecosystem maturity? rollback story?
<!-- Speaker Notes: Avoid reflexive building; emphasize explicit cost of ownership and migration. -->

---
# Career Resilience Signals
Risk Vectors: platform obsolescence, AI commoditizing rote, identity over-fitting, business isolation
Shifts:
- Value migrates to judgment, constraint modeling, system design
- Artifact trail = portable capital (decisions, slices, closures)
- Option density expands future role surface
Narrative: "I run an engine that de-risks change & scales others."
<!-- Speaker Notes: Link operational loop metrics to promotable narrative; resilience via transferable system not static tool expertise. -->

---
# Habits & Leverage
Breadth Habits: 1 micro-experiment / sprint; rotate review domains; shadow adjacent design; weekly post-mortem read; teach-back cadence
Mentorship: model inquiry, enforce question framing, celebrate learning velocity
Influence: frame proposals in outcomes, surface trade-offs early, invite dissent, close loops
Mindset Refactor: tool preference ≠ identity; living skill inventory; quarterly structured discomfort
<!-- Speaker Notes: Small, rhythmic habits > sporadic intensity. Mentorship and artifacts multiply impact & credibility. -->

---

## 30-Day Focus (Foundations)
- Select 2 personal anti-patterns → map explicit counter-pattern replacements
- Ship 1 thin slice in unfamiliar stack (record baseline cycle time)
- Log 8 learning debt items; close ≥4 (track closure median)
- Publish 2 lightweight decision artifacts (≤6 lines each)
- Pair / review outside comfort area weekly (4 reps)
- Track 3 leading metrics: slice cycle time, artifacts count, diffusion (views / attendees)
<!-- Speaker Notes: Emphasis = habit installation & measurement baselines. Keep scope small; success = consistent cadence not volume. -->

---

## 60-Day Focus (Depth & Diffusion)
- Lead a small improvement / feature in new stack (2nd/3rd slice faster than baseline)
- Facilitate 1 cross-team design or post-mortem (practice translation skill)
- Expand artifact library: total ≥5 decision records + 1 internal primer
- Mentor a peer through full adaptive loop (observe→diffuse)
- Reduce learning debt median closure time by 20% vs baseline
<!-- Speaker Notes: Move from personal loop to facilitating others; introduce comparative improvement metric to show compounding. -->

---

## 90-Day Focus (Leverage & Evidence)
- Demonstrate sustained slice cycle time reduction (≥30% vs day-0)
- Achieve ≥10 distinct consumers of artifacts (comments, views, attendees)
- Maintain learning debt closure median < 14 days (no zombie items)
- Be requested for ≥2 architecture / decision reviews outside team
- Curate 3 judgment stories (context → options → decision → outcome) for performance review / promo packet
<!-- Speaker Notes: Translate operating system outputs into promotable evidence & resilience indicators; focus on portability & external trust signals. -->

---

## Personal Roadmap Prompts
- What skill is under-leveraged?
- Which risk vector most relevant now?
- What experiment has asymmetric upside?
- Who can hold you accountable?
- What will you sunset saying about yourself?
<!-- Speaker Notes: Encourage writing answers tonight. -->

---

## Accountability Mechanisms
- Peer learning circle
- Monthly retro with manager
- Public decision log channel
- Scheduled discomfort block
- Quarterly identity audit
<!-- Speaker Notes: Systems > willpower. -->

---

## Common Pitfalls During Shift
- Over-consuming passive content
- Waiting for full mastery before shipping
- Hiding learning mistakes
- Overcorrecting: chasing every shiny tool
- Neglecting depth entirely
<!-- Speaker Notes: Balance breadth & depth deliberately. -->

---

## Resources & Further Reading
- Architecture decision record patterns
- Post-mortem facilitation guides
- System design primers
- Cognitive bias cheat sheets
- Learning loop / deliberate practice sources
<!-- Speaker Notes: Provide actual links in repo / handout. -->

---

## Q&A / Discussion
- Where are you over-attached?
- What skill will you surface next month?
- What's your first experiment?
<!-- Speaker Notes: Facilitate share & commitments. -->

---

# Thank You

<div class="columns">
<div>

# Refactor your identity ***continuously***
## *not reactively*

</div>
<div>

## Follow Chris Ayers

<i class="fa-brands fa-bluesky"></i> BlueSky: [@chris-ayers.com](https://bsky.app/profile/chris-ayers.com)
<i class="fa-brands fa-linkedin"></i> LinkedIn: - [chris\-l\-ayers](https://linkedin.com/in/chris-l-ayers/)
<i class="fa fa-window-maximize"></i> Blog: [https://chris-ayers\.com/](https://chris-ayers.com/)
<i class="fa-brands fa-github"></i> GitHub: [Codebytes](https://github.com/codebytes)
<i class="fa-brands fa-mastodon"></i> Mastodon: [@Chrisayers@hachyderm.io](https://hachyderm.io/@Chrisayers)
~~<i class="fa-brands fa-twitter"></i> Twitter: @Chris_L_Ayers~~

</div>
</div>