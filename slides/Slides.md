---
marp: true
theme: custom-default
footer: 'Refactoring your Developer Identity'
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
- How identity forms & calcifies
- Costs of stack-locked posture
- Transferable skill inventory
- Adoption & learning loops
- Decision & evaluation frameworks
- Career risk & future-proofing (incl. AI)
- Action plans (30 / 60–90 days)
- Q&A / Discussion
<!-- Speaker Notes: Set expectations; reassure: no shaming-this is an upgrade path. -->

---

## Why This Talk (Problem Frame)

<div class="columns">
<div>

## Problem

* Identity tied closely to tools or stacks
* New tech feels uncomfortable or risky
* Familiar solutions stretched too far

</div>
<div>

## Opportunity (what we'll explore)

* Skills transfer across domains
* Strong architecture & judgment multiply your impact
* Adaptability makes you durable

</div>
</div>

<!-- Speaker Notes: 
- "These are normal patterns - most of us have felt them."
- "But if we shift perspective, the very same moments of discomfort become opportunities."
- "That's the journey of this talk: moving from left to right."

Architecture
- Architecture decisions shape everything downstream (cost, reliability, maintainability).
- A good design choice early saves dozens of developer-hours later.
- Example: choosing event-driven vs. monolith - one decision influences scalability, fault tolerance, and team velocity.

Judgment
- Tools and frameworks change, but judgment about trade-offs doesn't.
- Knowing when "simple and fast" is right vs. when to invest in "robust and scalable" is more valuable than syntax knowledge.
- Example: deciding to reuse a service vs. rebuilding from scratch - good judgment avoids waste.

Leverage
- These skills amplify impact. One engineer with strong architectural thinking and sound judgment multiplies the effectiveness of a whole team.
- Unlike syntax, these are transferable across stacks, domains, and roles.
-->

---

## How Technical Identity Forms

<div class="mermaid">
flowchart LR
    A[Comfort] --> B[Praise]
    B --> C[Label]
    C --> D[Cost]
    D --> E[Fear]
    E --> A
</div>  

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

## Cost of Stack-Locked Identity (Org)
- Slower option exploration
- Architecture skewed to existing tooling
- Hidden bus factor increases
- Talent mobility bottlenecks
- Innovation surface narrows
<!-- Speaker Notes: Exec-level framing: this is an organizational risk vector. -->

---

## Cost of Stack-Locked Identity (You)
- Plateau in responsibility scope
- Reduced negotiating leverage
- Vulnerability to platform shifts
- Harder transition into strategic roles
- Higher burnout defending old patterns
<!-- Speaker Notes: Personal risk management framing. -->

---

## Comfort Zone Triggers
- New language / runtime model
- Different architectural style (event-driven, functional)
- Managed cloud service vs self-hosted
- Product / business centric conversation
- Elevated ambiguity or incomplete specs
<!-- Speaker Notes: Label triggers to reduce automatic avoidance. -->

---

## Common Anti-Patterns (1/2)
- Force-fit to familiar framework
- Recreating old stack ergonomics prematurely
- Gold-plating early prototypes
- Tool-first RFCs
- Overweighting anecdotal past incidents
<!-- Speaker Notes: Quick example for first item. -->

---

## Common Anti-Patterns (2/2)
- Endless spikes without convergence
- Ignoring non-functionals (cost, latency, ops)
- Refusal to pair outside specialty
- Defensive code review posture
- "Rewrite later" myth (never happens)
<!-- Speaker Notes: Emphasize convergence criteria. -->

---

## Transferable Skill Inventory
- Systems thinking / decomposition
- Trade-off articulation
- Debugging methodology & tooling mindset
- Communication & facilitation
- Risk, cost, and constraint awareness
- Mentorship & knowledge diffusion
<!-- Speaker Notes: THIS is your fungible capital; highlight portability. -->

---

## Skill Mapping Exercise
- Pick 1 new tech: map 5 core concepts to known ones
- Identify gaps (verbs) not nouns (names)
- Draft a 1-sentence mental model per concept
- Validate with someone using the tech daily
- Refine & store in personal notebook
<!-- Speaker Notes: Demonstrate with quick example if time. -->

---

## Case Study: Forced Paradigm
- Team insisted on using monolith patterns in event system
- Result: brittle integration layer, high coupling
- Lost 6 weeks + on-call pain
- Alternative: start with native event choreography primitives
<!-- Speaker Notes: Highlight cost of identity inertia. -->

---

## Case Study: Adaptive Shift
- Engineer joined unfamiliar data pipeline project
- Built concept map + small slice in 3 days
- Authored concise decision log & teach-back
- Became go-to bridge between teams
<!-- Speaker Notes: Show fast ramp formula works. -->

---

## Shift: Developer -> Problem Solver
- Begin at outcome & constraints
- Ask: what's the simplest viable path?
- Let domain shape tool selection
- Optimize for team maintainability horizon
- Seek clarity, not cleverness
<!-- Speaker Notes: Re-anchor identity to outcomes. -->

---

## Business Context: Core Questions
- What metric (lagging) are we moving?
- Leading indicator proxy?
- Cost of delay vs cost of build?
- Critical failure modes & blast radius?
- Scale trajectory & volatility?
- Regulatory / compliance boundaries?
<!-- Speaker Notes: Encourage capturing answers up front. -->

---

## Business Model Cheat Sheet
- Revenue driver or cost center?
- Direct customer impact or internal leverage?
- Differentiator vs commodity capability?
- SLA / SLO expectations?
- Budget & lifecycle horizon?
<!-- Speaker Notes: Use to justify tech choices in exec language. -->

---

## New Stack Adoption Loop
- Map concepts to known primitives
- Build smallest vertical slice
- Log unknowns explicitly
- Pressure-test with real data
- Teach back to cement learning
<!-- Speaker Notes: Show cycle time target: 2–5 days per loop. -->

---

## Adoption Loop (Visual)
<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@11/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>
<div class="mermaid">
flowchart LR
  A(Map) --> B(Slice)
  B --> C(Log Unknowns)
  C --> D(Pressure Test)
  D --> E(Teach Back)
  E --> A
</div>
<!-- Speaker Notes: Reinforce iterative nature; stop after value, not after mastery. -->

---

## Learning Debt Log (Example Fields)
- Date / Topic
- Unknown / Question
- Current hypothesis
- Source to validate
- Status (open / closed)
- Next action trigger
<!-- Speaker Notes: Model after technical debt-make visible. -->

---

## Decision Framework (Build / Learn / Delegate)
- Differentiator? -> Build core
- Commodity? -> Buy / service
- Enables compounding learning? -> Invest
- High risk + low context? -> Pair / consult
- Low impact + high churn? -> Defer / simplify
<!-- Speaker Notes: Prevent reflex build-everything. -->

---

## Mini Decision Record (Template)
- Context
- Option(s) considered
- Decision & rationale
- Trade-offs accepted
- Risks & mitigation
- Review date (sunset / revisit)
<!-- Speaker Notes: Keep under 6 bullets; frictionless or it dies. -->

---

## Build vs Buy Heuristics
- Frequency of change (domain > infrastructure?)
- Strategic differentiation potential
- Operational burden tolerance
- Integration surface complexity
- Exit / migration cost
<!-- Speaker Notes: Add weighted scoring if needed; start simple. -->

---

## Tool Evaluation Checklist
- Problem statement crisp?
- Success metrics defined?
- Total cost (licensing + people + ops)?
- Ecosystem maturity & docs?
- Failure & rollback story?
<!-- Speaker Notes: Avoid shiny-object churn. -->

---

## Career Risk Vectors
- Platform obsolescence
- AI automating rote layer
- Over-fitting identity to temporary hype
- Isolation from business dialogue
- Defensiveness blocking growth
<!-- Speaker Notes: Risks framed as manageable with strategy. -->

---

## Automation & AI Impact
- Routine code generation commoditized
- Differentiation shifts to system design
- Prompt literacy ≠ strategic leverage
- Human value: model constraints & trade-offs
- Identity anchored in judgment & ethics
<!-- Speaker Notes: Align identity with irreducible human tasks. -->

---

## Mindset Refactor Checklist
- Tool preference ≠ identity core
- Maintain living skill inventory
- Track & review key decisions
- Seek structured discomfort quarterly
- Explain choices via first principles
<!-- Speaker Notes: Suggest recurring calendar block. -->

---

## Maintaining Breadth Habits
- 1 small experiment / sprint
- Rotate code review domains
- Shadow design discussions outside comfort
- Read 1 architecture post-mortem / week
- Teach-back sessions internally
<!-- Speaker Notes: Compound minor habits > occasional big pushes. -->

---

## Mentorship as Leverage
- Teach adaptable thinking, not syntax
- Pair in unfamiliar territory intentionally
- Encourage question framing discipline
- Model humble inquiry
- Celebrate learning velocity
<!-- Speaker Notes: Mentoring reinforces your own generalization. -->

---

## Influence Without Authority
- Frame proposals in business outcomes
- Use lightweight ADRs to build trust
- Surface trade-offs transparently
- Invite dissent early
- Close the loop on decisions
<!-- Speaker Notes: Identity shifts when influence style matures. -->

---

## 30-Day Action Plan
- Audit last 5 technical decisions (bias?)
- Pair on feature in unfamiliar layer
- Log & close 10 learning debt items
- Publish 2 mini decision records
- Replace 1 tool-first pitch with outcome brief
<!-- Speaker Notes: Public commitment increases follow-through. -->

---

## 60–90 Day Extension
- Lead small initiative in new stack
- Facilitate cross-team architecture review
- Create internal primer for new tech
- Mentor peer through adoption loop
- Present outcomes to leadership
<!-- Speaker Notes: Moves identity externally. -->

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

## Measuring Progress (Leading Indicators)
- Time-to-first-vertical-slice in new stack
- Diversity of code review contributions
- Number of decision records authored
- Instances of framing outcome before tool
- Cross-team asks for architectural input
<!-- Speaker Notes: Track like product metrics. -->

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

## Thank You
### Refactor identity continuously - not reactively
<!-- Speaker Notes: Closing slide relocated & abstract removed as requested. -->
