---
marp: true
theme: custom-default
footer: 'Refactoring your Developer Identity'
transition: reveal
---

![bg right alt: Illustration representing a code refactor concept (decorative)](./img/refactor.png)
# Refactoring Your Developer Identity
## Moving Beyond Your Favorite Stack
<!-- Speaker Notes: Story: senior engineer declines greenfield service (Go + event-driven) because they're a "Java person"; opportunity + visibility shifts to someone who learns. Ask: Where does your real leverage come from? -->

---


![bg left:40% alt: Speaker portrait of Chris Ayers](./img/portrait.png)

## Chris Ayers

_Senior Site Reliability Engineer_  
_Azure CXP AzRel_  
_Microsoft_

<i class="fa-brands fa-bluesky"></i> BlueSky: [@chris-ayers.com](https://bsky.app/profile/chris-ayers.com)
<i class="fa-brands fa-linkedin"></i> LinkedIn: [chris\-l\-ayers](https://linkedin.com/in/chris-l-ayers/)
<i class="fa fa-window-maximize"></i> Blog: [https://chris-ayers\.com/](https://chris-ayers.com/)
<i class="fa-brands fa-github"></i> GitHub: [Codebytes](https://github.com/codebytes)
<i class="fa-brands fa-mastodon"></i> Mastodon: [@Chrisayers@hachyderm.io](https://hachyderm.io/@Chrisayers)
<i class="fa-brands fa-twitter"></i> Twitter (legacy / less active): @Chris_L_Ayers

---

## Agenda
- Problem & identity loop
- Smells & quick self‑assessment
- Costs: risk, opportunity, energy
- AI shift & resilience
- Patterns: triggers & anti‑patterns
- Durable skills & deep dives
- Operating habits (30/60/90)
- Pitfalls, resources, Q&A
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


## Cost & Risk Landscape

<!-- Speaker Notes: Frame core thesis fast: identity over-fitted to stack shrinks leverage surface and erodes future optionality. Set urgency without shame. -->

---

## Stack-Lock: Immediate Friction

- Pigeonholed into repetitive maintenance work
- Late paradigm fit → rework & credibility drag
- Comfort tasks crowd out deliberate practice reps
- AI narrows raw speed gap in your “home” stack
<!-- Speaker Notes: Four fast costs: (1) Task funnel shrink. (2) Design pivots arrive late. (3) Practice displaced. (4) Automation erodes speed-as-identity. Transition: hidden compounding losses. -->

---

## Compounding Opportunity Loss

- Avoiding paradigms erodes future intuition
- Fewer option/trade-off reps → slower trust for scope
- Thin negotiation narrative (tool-centric vs outcome-focused)
- Weak decision record trail limits portable evidence
<!-- Speaker Notes: Emphasize compounding: intuition & trust curves start earlier for those sampling paradigms now. Encourage audience to note which bullet stings most. -->

---

## Career & Resilience Risk Surface

 - Platform / ecosystem shifts → slower safe redeploy
 - Cross-layer blind spots create collaboration friction
 - Missing decision records blocks early architecture ownership
 - Narrow pattern map = fragile during org reshuffle
<!-- Speaker Notes: Tie to resilience: adaptability becomes core value as automation rises; artifacts + breadth = insurance. -->

---

## Energy & Motivation Risks

- Maintaining an “expert only” posture burns cognitive budget
- Monotony lowers curiosity & intrinsic reward loops
- Missing visible progress signals stalls momentum
- Burnout risk rises without healthy context switching variety
<!-- Speaker Notes: Human side: sustained motivation requires novelty + progress signals. Link to preventative maintenance for career energy. -->

---

## AI Replacement Risk
**What AI Does vs What You Should Do**

- Recognize AI acceleration on routine popular‑stack code
- Stop relying on raw single‑stack speed as a moat
- Define the real problem before typing any code
- Surface constraints & risks early (latency, cost, ops, security)
- Say “no / not yet” to extra services, libraries, abstractions
- Record decisions (problem, options, criteria, choice, rejected alternatives)
- Sample new paradigms early to judge fit quickly
<!-- Speaker Notes: Keep it plain: AI accelerates average implementation. Differentiation shifts to upstream problem clarity, early constraint/risk detection, and disciplined non-adoption. Emphasize: senior judgment = deciding *not* to add tech. Prompt: This week, replace one auto-build impulse with a short decision record capturing a clear “not now.” -->

---

## Behavioral Patterns & Triggers
### Recognizing the Reflexes Before Changing Them
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

* Force-Fitting Legacy Framework – raises coupling & latency; hides paradigm mismatch
* Premature Comfort Ergonomics – adds migration & cognitive debt before value
* Missing Calibrated First Slice – drift (endless spikes) or gold-plating waste
* Tool-First RFC – debate devolves to preferences; problem clarity lost
* Anecdote-Weighted Risk – single scare blocks simpler data-supported option
* Deferring Non-Functionals – retrofitting cost/latency/operability later is expensive
* Silo Reinforcement – defensive reviews slow diffusion; team resilience drops
* Rewrite-Later Myth – placeholder hardens; rewrite budget never arrives
<!-- Speaker Notes: Each bullet = Name: primary consequence. Use to map directly to counter-pattern slide. Prompt: Star TWO you personally slip into; those become your habit replacement targets. -->

---

## Mini Story: Comfort Lock (.NET → AI Gap)
- Reliable .NET engineer defers tiny Python reps (“stay efficient” rationale)
- Early AI prototypes (scripts, embeddings) ship without their input
- Activation energy rises; avoidance loop strengthens
- Perception shifts: peers seen expanding scope; they appear static
<!-- Speaker Notes: Normalize subtle pattern: avoidance disguised as efficiency. Emphasize quiet opportunity erosion rather than dramatic failure. Prompt: Ask for a quick show of hands: who has deferred a <30 line script because it felt outside lane? -->

---

<!-- Section Divider -->
## Skills Beyond the Stack
## Transferable Skills Beyond Syntax & Frameworks
<!-- Speaker Notes: Transition into the assets that transcend stacks; reframe identity around durable, compounding skills. Prompt audience to inventory their own. -->

---

## Transferable Skills (Exercise)

- List 3 non-stack skills you used this week
- Star the one that most amplified team impact
- Pick 1 that needs deliberate reps next month
- Note where you currently practice (or don't)
- Jot how you'd evidence it in a review
<!-- Speaker Notes: 60–75s silent exercise. Reinforce: We surface THEIR inventory first (avoid anchoring). Prompt: "Non-stack = would still matter if the language changed tomorrow." After time, quick show of hands: who picked a skill outside pure coding? Transition: now reveal example inventory to calibrate & fill gaps. -->

---

# Transferable Skill Inventory 

- Systems thinking / decomposition (clarify boundaries early)
- Risk / cost / constraint awareness (design within realities)
- Trade-off articulation (expose cost vs benefit explicitly)
- Structured problem solving (options & criteria discipline)
- Debugging methodology (structured hypothesis & tooling fluency)
- Communication & facilitation (alignment + reduced thrash)
- Cross-cutting concerns (DevOps, security, identity, observability)
- Mentorship & knowledge sharing
<!-- Speaker Notes: Ordered from foundation → analysis → comparison → structured decision → diagnostic loop → alignment → horizontal quality → scaling via diffusion. Encourage audience to star their weakest two. -->

---

## Systems Thinking

- Define system boundary + external actors first
- Surface invariant constraints (latency SLO, throughput, compliance)
- Map critical flows
- Identify coupling types (temporal, data, deploy)
- Make feedback loops explicit (metrics → alert → response)
- Write failure narrative: "It’s 2am, what broke?" adjust design
<!-- Speaker Notes: Boundary + invariants anchor later constraints; coupling + failure narrative expose hidden risk early. -->

---

## Risk / Cost / Constraint Awareness

- Surface non-negotiables first (SLOs, budget, compliance, headcount)
- Quantify impact (latency +X ms, error %, spend delta) before solutioning
- Distinguish one-time vs run-rate cost (people & ops included)
- Label uncertainty zones; target with thin experiments
- Map hidden constraints (org policy, data residency, release cadence)
<!-- Speaker Notes: Constraints early prevent rework & credibility loss. Sets stage for explicit trade-offs. -->

---

## Trade-Off Articulation

- Make costs, benefits, risks explicit (write them, don’t imply)
- Compare distinct shapes; avoid pseudo-choices (3 variants of same)
- Use shared criteria (cost, complexity, risk, time-to-value, operability)
- Call irreversibility & exit cost out early
- Record decision + review date (prevents revisionist history)
<!-- Speaker Notes: Trade-off clarity signals seniority; written review date creates revisit trigger when context shifts. -->

---

## Reversibility (One-Way vs Two-Way Doors)

- Two-Way Door: low exit / rollback cost → bias toward fast, thin experiment
- One-Way Door: high exit or irreversibility → deepen option set & criteria before commit
- Engineer reversibility: feature flags, abstraction seams, temporary adapters, staged data migrations
- Delay one-way commits until forcing constraint / trigger; keep optionality alive
- Record door type + revisit trigger in each decision record (prevents silent hardening)
<!-- Speaker Notes: Borrowed from Bezos framing. Goal: accelerate safe, reversible bets while slowing & formalizing irreversible ones. Prompt: Identify one pending decision you can re-shape into a two-way door this week. -->

---

## Structured Problem Solving

- Restate problem w/ measurable impact (latency +X ms, error rate 3%)
- Separate symptom vs root signal (timeline + first deviation)
- Enumerate constraints (SLO, budget, headcount, deadline) before options
- Generate 3 distinct option shapes (simplest / resilient / scalable)
- Compare via 3–5 shared criteria (cost, complexity, risk, time-to-value)
- Capture decision rationale
<!-- Speaker Notes: Forces disciplined option diversity & reusable criteria; decision record prevents re-litigation. -->

---

## Debugging Methodology (Structured Loop)

- Frame failure: what / where / when / impact (baseline state)
- Rank hypotheses (prob × impact) → pick next test by info gain
- Close visibility gap (add only needed observation before guessing)
- Run smallest disproof & isolate variables (env, config, data, version)
- Lock in learning: concise cause + guardrail + diffusion decision record
<!-- Speaker Notes: Tech-agnostic loop: frame → rank → observe → disprove → institutionalize. Emphasize INFORMATION GAIN and making learning portable (artifact + guardrail). Prompt: Which link do you skip? -->

---

## Debugging Loop Mnemonic (FRAME → RANK → OBSERVE → DISPROVE → RECORD)

1. FRAME: Define what changed, where it manifests, when it started, impact delta.
2. RANK: Order hypotheses by (probability × impact × test effort) for maximum information gain.
3. OBSERVE: Add only the missing visibility (targeted log, metric, trace span) before acting.
4. DISPROVE: Run the smallest isolating experiment; change one variable at a time.
5. RECORD: Capture root cause, guardrail added, diffusion snippet (turn fix into shared capability).

**Reminder**: Stop when remaining hypotheses have low expected information gain relative to effort.
<!-- Speaker Notes: Reinforces disciplined loop; turns ad-hoc debugging into repeatable method. -->

---

## Communication & Facilitation

- Start with problem + impact before solution detail
- Surface 3 assumptions explicitly; invite challenge early
- Time-box divergence → convergence (agenda w/ decision point)
- Summarize decisions + owners live (shared doc / chat)
- Translate across domains (latency vs UX vs cost) neutrally
- Close loop: publish outcome + rationale asynchronously
<!-- Speaker Notes: Alignment multiplier; explicit assumptions + live capture slash thrash & meeting recursion. -->

---

## Cross-Cutting Concerns (DevOps · Security · Identity · Observability)

- DevOps: automate build/test/deploy; track DORA (deploy freq, lead time, MTTR, CFR)
- Security: shift-left reviews, least privilege, abuse cases, secret hygiene
- Identity & Access: central authn, least-privilege RBAC, audit trails, zero trust posture
- Observability: metrics (RED/USE), structured logs, traces, SLO + error budget loop
- Governance: lightweight policies codified (lint, IaC guardrails) to scale consistency
<!-- Speaker Notes: Treat as dimensions on every design: ask explicitly how choices impact deployability, threat surface, identity scope, observability. -->

---

## Mentorship & Knowledge Sharing

- Pair outside comfort weekly → bi-directional pattern transfer
- Convert solved incident / decision into 5‑bullet internal post
- Run micro-teach (10 min) within 24h of learning slice
- Encourage question framing: context → goal → constraint → ask
- Seed successors: shadow → co-own → autonomous handoff
<!-- Speaker Notes: Diffusion compounds organizational leverage; lightweight artifacts + rapid teach-backs convert personal learning into team capability. -->

---


## Adapting to Change and a Growth Mindset

---

## 30-Day Focus (Mindset Foundations)
- Notice default reactions: log brief notes when you reach for the familiar before reframing the problem
- Practice deliberate problem framing: write a short context → impact → constraints → open questions outline before starting significant work
- Cultivate curiosity: explore one unfamiliar pattern or technique and summarize its essence in plain language (when it helps / when it hurts)
- Shift from output to clarity: create concise decision records that emphasize why not just what
- Reframe conversations: translate at least one technical ask into business or user impact language and reflect on the shift
- Begin reflective practice: end each week with three prompts (What assumption did I surface? What bias did I interrupt? What skill felt stretched?)
- Adopt a learning posture in feedback: offer one strengths-first, growth-oriented critique to a peer
<!-- Speaker Notes: Month 1 centers on awareness, reframing, and reflective loops—lightweight artifacts over volume. -->

---

## 60-Day Focus (Habit Deepening & Diffusion)
- Internalize framing reflex: pause autopilot starts; ensure every meaningful task begins with a written problem frame
- Normalize experimentation: run small, time-boxed trials framed as questions (“If we try X, do we reduce Y friction?”) and capture adopt / defer reasoning
- Embrace reversibility: revisit an earlier decision; document what changed and why adjustment was low-cost
- Mentor through questions: guide a peer by asking clarifying, constraint, and risk questions instead of prescribing tools
- Facilitate alignment: host a concise session that moves a group from divergent options to shared criteria-based choice; reflect on what unlocked convergence
- Strengthen reflection: evolve weekly journal with a fourth prompt (Which judgment improved and how do I know?)
- Model psychological safety: surface one of your own mistaken assumptions publicly and reframe it as learning fuel
<!-- Speaker Notes: Month 2 reinforces identity shift via habitual framing, safe micro-experiments, and diffusion by inquiry not authority. -->

---

## 90-Day Focus (Identity Shift & Sustainable Leverage)
- Operate from principles: articulate concise personal heuristics (e.g., “Frame before solution”, “Prefer reversible steps first”, “Surface trade-offs explicitly”)
- Demonstrate adaptive judgment: compile short judgment stories emphasizing context shifts and calibrated pivots, not raw output
- Institutionalize clarity: create or refine a lightweight shared template (problem frame → options → criteria → decision → revisit trigger) adopted by others
- Foster autonomy: enable peers to frame and decide without you by sharing heuristics and reflective prompts
- Sustain reflective loop: continue weekly practice; synthesize quarter themes (biases diminished, new default behaviors installed)
- Anchor growth narrative: write a one-page self-story focusing on mindset evolution (from tool identity → systems & judgment identity)
<!-- Speaker Notes: Month 3 consolidates identity evolution; focus on codified principles, distributed clarity, and sustainable reflective practice. -->

---

## Common Pitfalls During Shift
- Passive Consumption Over Creation – defaulting to reading/watching instead of producing thin slices or decision records
- Mastery Gatekeeping – waiting for 100% fluency before shipping a reversible slice
- Error Concealment – hiding learning mistakes vs surfacing them as judgment stories / guardrails
- Shiny Object Whiplash – chasing each new tool without a framed problem & exit criterion
- Shallow Sampling – breadth without scheduled depth reps (no deliberate repetition)
<!-- Speaker Notes: Pair each pitfall with its antidote: Ship thin slices; treat mistakes as artifacts; frame before adopting; schedule depth reps. Prompt audience to pick ONE to actively counter next week. -->

---

## Resources & Further Reading
- Architecture Decision Record Patterns (templates, review cadences)
- Post-Mortem & Incident Facilitation Guides (blameless synthesis, diffusion)
- Systems Thinking & Design Primers (boundaries, flows, feedback loops)
- Cognitive Bias & Judgment References (bias interruption checklists)
- Deliberate Practice & Learning Loop Sources (experiment design, reflection prompts)
<!-- Speaker Notes: Replace with repo links / handout. Encourage choosing ONE resource to operationalize (e.g., adopt ADR template) rather than bookmarking all. -->

---

## Q&A / Discussion
- Where is your identity over‑attached to a tool or pattern?
- Which transferable skill will you deliberately surface next month?
- What is your first small reversible experiment and its success criterion?
<!-- Speaker Notes: Capture public commitments (skill + experiment + success signal). Encourage writing experiment hypothesis format: “If we do X, we expect Y signal within Z timeframe.” -->

---

# Thank You

<div class="columns">
<div>

## Refactor Your Identity *Continuously*
### Not Reactively

</div>
<div>

## Follow Chris Ayers

<i class="fa-brands fa-bluesky"></i> BlueSky: [@chris-ayers.com](https://bsky.app/profile/chris-ayers.com)
<i class="fa-brands fa-linkedin"></i> LinkedIn: [chris\-l\-ayers](https://linkedin.com/in/chris-l-ayers/)
<i class="fa fa-window-maximize"></i> Blog: [https://chris-ayers\.com/](https://chris-ayers.com/)
<i class="fa-brands fa-github"></i> GitHub: [Codebytes](https://github.com/codebytes)
<i class="fa-brands fa-mastodon"></i> Mastodon: [@Chrisayers@hachyderm.io](https://hachyderm.io/@Chrisayers)
~~<i class="fa-brands fa-twitter"></i> Twitter: @Chris_L_Ayers~~

</div>
</div>
<script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>