# Curriculum Architecture

## Status

**Personalized architecture established — detailed curriculum pending**

The initial high-level curriculum architecture was established before the
diagnostic.

The practical diagnostic is now complete.

The curriculum should therefore be personalized around demonstrated strengths,
gaps, career direction, and real-world engineering context.

The detailed module structure, references, workload, exercises, and assessment
criteria are **not yet fully locked**.

## Educational Target

The program should approximate the intellectual breadth and depth of a strong
master's-level software engineering education while allowing a project-driven,
self-directed structure.

The academic reference point includes:

* ACM/IEEE-CS Graduate Software Engineering 2009 (GSwE2009);
* ACM/IEEE-CS/AAAI Computer Science Curricula 2023 (CS2023);
* relevant Software Engineering Institute material;
* established textbooks;
* peer-reviewed research;
* standards;
* authoritative technical documentation.

The curriculum should integrate theory and practice rather than functioning as
a collection of disconnected technical tutorials.

## Core Design Principle

The curriculum should optimize for:

> **demonstrated capability rather than completed topics.**

A topic is valuable when the learner can use it to:

* reason;
* build;
* analyze;
* evaluate;
* investigate;
* make better engineering decisions.

The curriculum should therefore combine:

* foundational knowledge;
* advanced engineering practice;
* project work;
* evidence-based evaluation;
* research literacy;
* independent investigation.

## Diagnostic-Based Personalization

The diagnostic produced an important overall finding:

> The learner's practical engineering instincts are generally stronger than
> their formal systems knowledge.

Therefore the curriculum should:

1. Teach theory underneath existing practical intuition.
2. Avoid unnecessary repetition of basic software-development skills.
3. Use realistic engineering scenarios.
4. Connect CS foundations directly to production/system problems.
5. Emphasize reasoning, trade-offs, measurement, and evidence.
6. Use projects to integrate multiple competencies.

## Competency Spine

### 1. Software Engineering & Architecture

Competencies:

* requirements engineering;
* software design;
* architecture;
* domain modeling;
* state machines;
* architectural decomposition;
* modularity;
* coupling/cohesion;
* interfaces and contracts;
* architecture evaluation;
* architectural trade-offs;
* scalability;
* resilience;
* observability;
* technical debt;
* software evolution;
* engineering decision-making.

### 2. Data, Transactions & Concurrency

This is the highest immediate foundation priority.

Competencies:

* relational model;
* SQL;
* data modeling;
* PostgreSQL;
* indexes;
* query planning;
* constraints;
* transactions;
* ACID;
* isolation;
* locking;
* row-level locking;
* optimistic concurrency;
* pessimistic concurrency;
* race conditions;
* consistency;
* invariants;
* state transitions;
* idempotency.

### 3. Distributed Systems

Competencies:

* networking fundamentals;
* service boundaries;
* synchronous/asynchronous communication;
* timeouts;
* retries;
* duplicate messages;
* queues;
* distributed state;
* consistency;
* failure modes;
* reconciliation;
* distributed tracing;
* observability;
* resilience;
* recovery.

### 4. Quality Engineering & Reliability

The learner already has significant practical testing experience.

The curriculum should therefore emphasize the theory and reasoning needed to
move beyond test-layer selection.

Competencies:

* software quality models;
* testing theory;
* risk-based testing;
* test design;
* state-transition testing;
* unit/integration/system testing;
* property-based testing;
* mutation testing;
* exploratory testing;
* test automation;
* test adequacy;
* coverage limitations;
* concurrency testing;
* failure/recovery testing;
* reliability;
* performance;
* security testing;
* quality measurement;
* production quality;
* observability;
* incident response.

### 5. AI Engineering

The learner has substantial practical AI usage but limited formal AI/ML
knowledge.

Competencies:

* probability/statistics foundations;
* machine learning foundations;
* neural networks;
* deep learning;
* transformers;
* language models;
* embeddings;
* retrieval;
* RAG;
* tool use;
* agents;
* AI-system architecture;
* evaluation;
* reliability;
* safety/security;
* cost/latency trade-offs;
* model/system lifecycle.

### 6. AI + Software Quality

This is a potentially important interdisciplinary specialization.

Competencies:

* AI-assisted test generation;
* evaluation methodology;
* benchmark design;
* test-set construction;
* LLM evaluation;
* agent evaluation;
* regression evaluation;
* robustness;
* hallucination/failure analysis;
* grounding;
* human-in-the-loop systems;
* AI observability;
* quality measurement.

### 7. Research & Engineering Method

Competencies:

* literature search;
* literature review;
* research questions;
* hypotheses;
* experimental design;
* qualitative methods;
* quantitative methods;
* measurement;
* validity;
* threats to validity;
* reproducibility;
* statistical reasoning;
* technical writing;
* peer-review literacy.

### 8. Professional / Technical Leadership

The learner's intended career direction is approximately 70% expert/IC and
30% managerial/technical leadership.

Leadership should therefore be embedded into technical work rather than taught
as a separate management curriculum.

Competencies:

* estimation;
* prioritization;
* technical communication;
* decision-making under uncertainty;
* risk management;
* stakeholder communication;
* planning;
* delegation;
* influence;
* engineering execution;
* time management;
* mentoring;
* technical strategy.

## Foundations Track

The engineering spine is supported by a selective CS foundations track.

Primary areas:

* Algorithms and data structures
* Databases
* Networking
* Operating systems
* Concurrency
* Distributed systems
* Probability and statistics
* Discrete mathematics

These are not intended to become a complete repeat of undergraduate CS.

Instead:

> Learn or refresh foundations when they become necessary for higher-level
> competence.

## Foundation Priority

Based on the diagnostic:

### High Priority

* Databases
* SQL
* Transactions
* Concurrency
* Probability/statistics

### Medium Priority

* Networking
* Distributed systems
* Algorithms/data structures
* Operating systems

### Just-in-Time / Supporting

* Discrete mathematics
* computer architecture;
* additional mathematics required by later topics.

This priority remains adjustable.

## Personalized Learning Sequence

The original generic sequence is replaced by the following personalized
conceptual progression:

```text
Data & Concurrency
        ↓
Architecture & Distributed Systems
        ↓
Quality & Reliability
        ↓
AI Engineering
        ↓
AI + Software Quality
        ↓
Integrated Intelligent Systems
        ↓
Research Method
        ↓
Independent Research / Capstone
```

This is **not a fixed semester schedule**.

Projects may cause the learner to move between areas.

## First Learning Block

### Data & Concurrency

The first substantive learning block should connect database foundations
directly to the learner's existing engineering context.

Proposed sequence:

```text
SQL
→ relational modeling
→ PostgreSQL
→ indexes
→ query planning
→ transactions
→ isolation
→ locking
→ concurrency
→ state machines
→ invariants
→ idempotency
```

### Intended Outcomes

By the end of this block, the learner should be able to:

* write correct non-trivial SQL;
* explain relational modeling decisions;
* design useful PostgreSQL indexes;
* reason about query execution at an appropriate level;
* explain transaction boundaries;
* explain ACID properties;
* reason about isolation;
* use row-level locking appropriately;
* identify race conditions;
* distinguish optimistic and pessimistic concurrency;
* model valid state transitions;
* define and protect important invariants;
* design idempotent operations;
* analyze concurrent operations in a financial workflow.

### Proposed Applied Exercise

Use the escrow transaction scenario as the running case.

The learner should eventually design:

* transaction schema;
* relationships;
* state machine;
* constraints;
* indexes;
* important SQL queries;
* transaction boundaries;
* PAY/CANCEL concurrency behavior;
* idempotency strategy;
* failure/recovery behavior.

The goal is not merely to produce code.

The learner must be able to explain and defend the design.

## Quality Integration

The Data & Concurrency block should eventually connect to Quality Engineering.

Examples:

* test legal and illegal state transitions;
* test duplicate payment;
* test concurrent payment/cancellation;
* test transaction rollback;
* test idempotency;
* test invariant preservation;
* test recovery after failure.

This makes the learning project simultaneously useful for:

* databases;
* backend engineering;
* concurrency;
* software design;
* quality engineering.

## AI Integration

AI should not be introduced into the first learning block merely for
novelty.

Later AI work should build on the established engineering foundation.

For example, an AI QA system should eventually be required to understand:

* requirements;
* state machines;
* business invariants;
* valid/invalid transitions;
* test adequacy;
* evaluation metrics.

This prevents the AI layer from becoming a system that simply generates
plausible-looking tests.

## Potential Flagship Direction

A potential flagship project is:

> A system that automates or assists QA processes in environments with limited
> dedicated QA capacity.

This remains a **candidate**, not a commitment.

The project must first pass:

> problem → evidence → requirements → design → implementation → measurement

The technology and use of AI should follow the problem rather than determine
it.

## Project Integration

Projects are not separate from the curriculum.

A project should serve as a context in which multiple competencies are
demonstrated.

A serious project should ideally require:

* requirements analysis;
* architectural decisions;
* implementation;
* testing;
* quality strategy;
* measurement;
* documentation;
* operational reasoning;
* trade-off analysis;
* retrospective evaluation.

More advanced projects should additionally require:

* literature grounding;
* explicit research questions where appropriate;
* experimental design;
* quantitative evaluation;
* comparison against alternatives;
* analysis of limitations.

## Mastery Levels

The program uses an evidence-based mastery model.

### Level 1 — Understand

Can explain core ideas and terminology accurately.

### Level 2 — Apply

Can apply concepts to well-defined engineering problems.

### Level 3 — Analyze

Can diagnose unfamiliar problems, handle ambiguity, and reason about causes.

### Level 4 — Evaluate

Can compare alternatives, evaluate evidence, reason about trade-offs, and
defend decisions.

### Level 5 — Synthesize

Can integrate multiple areas of knowledge to solve complex or open-ended
engineering problems.

### Level 6 — Investigate

Can independently formulate and investigate a meaningful question using
appropriate evidence and methodology.

The target for master's-level competence is primarily Levels 5–6 in the
learner's major competency areas, supported by strong Levels 3–4 across the
broader engineering foundation.

## Evidence Model

Competence must be demonstrated through evidence.

Possible evidence includes:

* technical explanation;
* oral defense;
* written analysis;
* system design;
* implementation;
* code;
* test strategy;
* debugging investigation;
* experiment;
* benchmark;
* production-style artifact;
* literature synthesis;
* research report;
* project retrospective;
* independent investigation.

A topic is not considered mastered merely because it was:

* read;
* watched;
* discussed;
* explained by ChatGPT;
* included in a project without evidence of understanding.

## Curriculum Flexibility

Not every topic deserves equal time.

For each topic ask:

1. Is it foundational?
2. Is it important to the target competence?
3. Is it needed to understand later material?
4. Is it current/relevant?
5. Can the learner already demonstrate competence?
6. Can it be learned efficiently when needed?
7. Does it contribute meaningfully to a current project or research question?

Topics may be classified as:

* **Core** — essential to the target capability.
* **Supporting** — important but not a primary focus.
* **Elective** — valuable but not necessary.
* **Just-in-time** — learned when required by a problem.
* **Skip/defer** — intentionally postponed because current value is low.

## Academic Evidence Policy

Use substantial real academic and authoritative material.

For academic, scientific, technical, or current claims:

* Prefer primary sources.
* Prefer peer-reviewed research where appropriate.
* Use established textbooks for foundational material.
* Use standards and official documentation for technical standards/practices.
* Use current sources for rapidly changing areas such as AI.
* Verify citations.
* Never invent papers, books, authors, results, quotations, or DOIs.
* Clearly distinguish evidence, interpretation, uncertainty, and opinion.

The academic backbone includes:

* ACM/IEEE-CS Graduate Software Engineering 2009 (GSwE2009);
* ACM/IEEE-CS/AAAI Computer Science Curricula 2023 (CS2023);
* relevant Software Engineering Institute material;
* established textbooks;
* peer-reviewed papers;
* standards;
* authoritative technical documentation.

## Research / Capstone Direction

The long-term program should culminate in an independent master's-level
project or thesis-like investigation.

A capstone should involve:

* a meaningful problem;
* explicit motivation;
* relevant literature;
* a clear research or engineering question;
* appropriate methodology;
* implementation or investigation where appropriate;
* evidence;
* evaluation;
* limitations;
* defensible conclusions;
* professional technical communication.

A project can become a research project if its question, methodology,
evidence, and evaluation justify that transition.

## Current State

The practical diagnostic is complete.

The personalized competency architecture is established.

The detailed curriculum has **not yet been finalized**.

## Next Step

Continue in **PLAN mode**.

The next session should define the detailed curriculum for the first learning
block:

> **Data & Concurrency: SQL → PostgreSQL → Transactions → Concurrency**

The detailed plan should specify:

* learning outcomes;
* module/topic breakdown;
* academic references;
* practical exercises;
* applied project;
* assessment/evidence;
* expected workload;
* criteria for moving to the next block.

Only after that should the program transition from **PLAN** to **LEARN**.
