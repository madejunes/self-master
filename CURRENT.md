# Current State

## Mode

**PLAN**

## Stage

Master's Diagnostic — In Progress

## Primary Goal

Build a self-directed, master's-level education focused on:

* Software Engineering
* Quality Engineering / QA
* AI Engineering

with a strong connection to real-world and current engineering problems.

The program is intended to approximate the intellectual breadth, depth, and professional capability of a strong university master's-level education without university enrollment.

## Planning Status

The initial program-planning phase is **complete enough to begin the diagnostic phase**.

The curriculum is intentionally not fully fixed yet.

The diagnostic will be used to determine:

* what the learner already knows;
* what knowledge is rusty;
* what practical knowledge lacks theoretical grounding;
* what genuine gaps are important;
* what gaps can be deferred;
* where deeper master's-level study is actually required.

The next major activity is therefore **diagnostic assessment**, not further high-level curriculum planning.

## User Profile

### Career Direction

The learner is currently a **Senior Software Engineer**.

Desired future direction:

* **70% Expert Software Engineer / IC track**
* **30% Managerial / technical leadership capability**

The goal is not primarily to become a manager.

The priority is developing strong technical depth while gaining enough leadership and management capability to operate effectively as a technical lead.

### Current Strengths

The learner has substantial practical experience in:

* Requirements analysis
* System/API design
* Database design
* Code review
* Refactoring
* Automated testing
* Integration testing
* Observability
* Production troubleshooting
* Technical/design decisions
* Maintaining existing codebases

The learner is stronger on the frontend side but has experience working across the broader software-development lifecycle.

### Development Areas

The learner wants to improve:

* Full-stack engineering fluency
* Backend engineering
* System-level engineering
* Software architecture
* Technical decision-making
* Production troubleshooting
* Engineering execution and time management
* Technical leadership

## Quality Engineering

Current profile:

> Developer with substantial testing experience.

Current testing experience includes:

* Jest
* Vitest
* Mocha
* Sinon
* Recent experimentation with Maestro

The learner's team has limited QA personnel, creating a potential real-world opportunity to investigate QA automation and quality engineering.

Quality Engineering is therefore both:

1. a major educational competency area; and
2. a potential source of a future real-world project.

## AI

The learner uses LLMs extensively but currently has limited understanding of underlying machine-learning theory.

AI learning should eventually include foundational ML concepts rather than focusing primarily on prompt usage or application-level techniques.

The program should distinguish:

* using AI tools;
* engineering AI-powered systems;
* understanding ML/AI foundations;
* evaluating AI systems scientifically.

## Academic / CS Foundations

The learner has a Bachelor's degree in Informatics Engineering, completed more than a decade ago.

Current self-assessment:

* Algorithms/data structures — weak
* Databases — weak
* Networking — weak
* Operating systems — weak
* Concurrency — weak
* Distributed systems — weak
* Probability/statistics — weak
* Discrete mathematics — weak

These should be treated as potentially rusty foundations, not automatically as zero knowledge.

The diagnostic should distinguish:

* forgotten knowledge;
* practical knowledge without theoretical grounding;
* genuine conceptual gaps;
* knowledge that is sufficient for the learner's intended engineering work.

The program should avoid unnecessarily repeating an entire undergraduate CS curriculum.

## Engineering Environment

The learner's team primarily develops and maintains **mini apps inside a fintech super-app ecosystem**.

### Application Types

Most applications are mini apps using a JavaScript-based DSL.

Other applications may use:

* React
* Vue
* Nuxt
* SPA architecture
* TypeScript

Some mini apps have their own backend.

### Current Technology Exposure

#### Frontend

Primary:

* Mini-program DSL based on JavaScript

Additional:

* JavaScript
* TypeScript
* Vue
* React
* Nuxt

#### Backend

Primary:

* Go

The learner is relatively new to the backend/Go side.

#### Database

Primary:

* PostgreSQL

The learner is relatively new to PostgreSQL.

#### Infrastructure

Cloud environment is believed to be Google Cloud.

Infrastructure is primarily handled by infrastructure developers / SRE.

#### CI/CD

Exposure includes:

* GitHub
* Jenkins

The learner has limited direct involvement with the main CI/CD systems.

#### Monitoring / Analytics

The team uses Mixpanel in some contexts.

## Typical Development Workflow

A typical feature involves:

1. BD / PM / PD provides or coordinates requirements.
2. Developers estimate and design the implementation.
3. Frontend and backend work may be split between developers.
4. Developers perform happy-path testing.
5. QA may be consulted where available.
6. QA capacity is limited.
7. Frontend deployment is often self-service through an established and stable system.
8. Backend deployment is more dependent on infrastructure developers / SRE, with the backend deployment system still emerging.

This environment provides useful real-world context for studying:

* requirements;
* estimation;
* system design;
* frontend/backend boundaries;
* testing;
* quality engineering;
* deployment;
* reliability;
* observability;
* production troubleshooting;
* technical decision-making.

## Real-World Case Study: Escrow Mini App

A recent example is a new mini app for an **escrow transaction**.

### Team / Ownership

* One PM requested an estimate for the complete feature/system.
* A colleague provided a backend engineer so the learner could focus primarily on frontend work.
* No dedicated QA was provided for the project.

### Quality Process

Developers were responsible for testing the happy path.

QA could be consulted when available, but QA capacity was limited.

### Deployment

Frontend:

* Self-service deployment.
* Existing deployment system is considered stable.

Backend:

* Infrastructure developers assist with deployment.
* Backend deployment infrastructure is still emerging.

### Engineering Significance

This case provides a useful real-world example for future study of:

* estimation;
* requirements;
* FE/BE ownership;
* full-stack system understanding;
* software quality;
* testing strategy;
* risk-based testing;
* deployment;
* infrastructure dependencies;
* production reliability;
* technical decision-making.

Because escrow involves transactions, future analysis should pay particular attention to failure modes beyond the happy path.

This case study is **not currently a committed project**.

## Potential Flagship Project

A strong candidate for a future major project is:

> Build a serious software system that automates or assists QA processes, motivated by the learner's current team having limited QA personnel.

This is currently a **candidate direction, not a committed project**.

The project should eventually be evaluated against:

* real team/business value;
* technical depth;
* current relevance;
* opportunities to apply Software Engineering and Quality Engineering;
* opportunities to incorporate AI where genuinely useful;
* measurable outcomes;
* potential for later research.

The project should not use AI merely because AI is fashionable.

The project should begin with:

> problem → evidence → requirements → design → implementation → measurement

rather than choosing a technology first and looking for a problem afterward.

## Curriculum Strategy

Use two interacting tracks.

### Engineering Track

Software Engineering
→ Architecture & Systems
→ Quality & Reliability
→ AI Engineering
→ Intelligent Software Systems
→ Independent Research

### Foundations Track

* Algorithms/data structures
* Databases
* Networking
* Operating systems
* Concurrency
* Distributed systems
* Probability/statistics
* Discrete mathematics

Foundations should be learned or refreshed **just in time** where possible, rather than forcing the learner through a complete undergraduate CS curriculum again.

The final depth and ordering of these topics will depend on diagnostic results.

## Master's-Level Assessment Model

The target is approximately the level expected from a strong university master's graduate.

Assessment should focus on demonstrated capability rather than topic completion.

The program uses a progression inspired by competency-oriented curricular models such as CS2023, while extending it for the intended master's-level engineering and research goals.

### Level 1 — Understand

Can explain concepts accurately.

### Level 2 — Apply

Can apply concepts to well-defined engineering problems.

### Level 3 — Analyze

Can diagnose unfamiliar problems and reason about causes.

### Level 4 — Evaluate

Can compare competing approaches and evaluate evidence and trade-offs.

### Level 5 — Synthesize

Can integrate multiple concepts to solve complex/open-ended problems.

### Level 6 — Investigate

Can independently formulate and investigate a meaningful question using appropriate evidence and methodology.

The eventual Master's target is primarily **Levels 5–6**, supported by strong Levels 3–4 across the relevant engineering competencies.

No competency should be marked as mastered merely because it was discussed.

## Diagnostic Phase

Before beginning substantial coursework, conduct a practical diagnostic phase using realistic engineering problems rather than primarily recall-based questions.

The diagnostic should assess:

* engineering reasoning;
* system/design thinking;
* architectural reasoning;
* testing/quality reasoning;
* debugging and production reasoning;
* CS foundations;
* ability to evaluate trade-offs;
* ability to explain and defend decisions;
* ability to connect theory to practical engineering situations.

The diagnostic should distinguish:

* already strong;
* rusty and requiring refresh;
* practical but theoretically weak;
* important genuine gap;
* low-priority gap that can be deferred.

The learner does not need to pass the diagnostic before starting.

The diagnostic exists to personalize the curriculum.

### Diagnostic Structure

The initial diagnostic uses a small number of realistic problems rather than a large exam.

### Part A — System Design

**Status: Completed**

The learner was asked to reason about a fintech escrow mini-app involving:

1. transaction creation;
2. payment;
3. funds being secured;
4. seller shipment/fulfillment;
5. buyer confirmation;
6. fund release.

The learner was asked to consider requirements, entities/data, APIs, FE/BE boundaries, state transitions, failure scenarios, database responsibilities, and testing.

### Part A — Evidence

#### Requirements

The learner naturally identified:

* UI/UX;
* high-level flow;
* acceptance criteria;
* source of funds;
* existing APIs.

This demonstrates good practical product/requirements instincts.

A notable gap is that the learner could not yet articulate which assumptions should explicitly be rejected or validated before implementation.

#### Core Data / Domain Modeling

The learner identified:

* user;
* item;
* seller;
* transaction-related status;
* item metadata.

The learner also described a coherent basic business flow:

> seller creates transaction → seller shares payment link/QR → buyer pays → funds are secured → seller ships/fulfills → buyer confirms → funds released.

This demonstrates useful domain-flow reasoning.

However, the data model remained relatively shallow for a financial transaction system.

Areas not yet demonstrated include:

* explicit monetary representation;
* transaction/payment records;
* buyer/seller relationships;
* immutable transaction history;
* audit records;
* payment-provider references;
* settlement/release records;
* failure/reversal states;
* concurrency/version information;
* database invariants.

These should be investigated later.

#### API / System Boundary

The learner proposed APIs/operations including:

* authentication;
* image upload;
* transaction creation;
* transaction listing;
* transaction detail;
* payment;
* payment-success notification;
* cancellation;
* shipment marking;
* confirmation;
* fund release.

This demonstrates practical API decomposition instincts.

However, the learner initially answered that **everything belongs to the backend**.

This indicates a gap in explicitly reasoning about:

* frontend responsibilities;
* backend business invariants;
* external payment systems;
* asynchronous events/callbacks;
* source-of-truth ownership;
* trust boundaries.

This should become a diagnostic focus.

#### State Modeling

The learner proposed:

* Draft/created
* Waiting for payment
* Paid
* Fund protected
* Item shipped
* Item confirmed
* Fund released

This is a useful initial state-machine instinct.

However, the learner was not yet able to explain how to enforce valid transitions.

This suggests a gap between:

> identifying business states

and:

> implementing and enforcing state-machine invariants under concurrency and failure.

This is an important learning target.

#### Failure Reasoning

The learner identified several important distributed-operation problems.

For payment where the frontend does not receive the response:

> query the backend again for status.

This is a good practical recovery instinct.

For duplicate payment and duplicate release:

> use idempotency.

This is a strong instinct and should be developed further.

Idempotency keys are a standard mechanism for making retryable mutating operations safe against duplicate execution.

For backend crashes:

> retry several times and notify the user if retries fail.

This is currently insufficient for financial operations.

The important missing reasoning is:

* What exactly was committed?
* What operation is safe to retry?
* How does the server recognize a duplicate request?
* What if an external payment operation succeeded but the local transaction failed?
* What if the database commit succeeded but the response was lost?
* What if two requests execute concurrently?
* Which component owns the authoritative state?

These questions will connect directly to databases, transactions, concurrency, distributed systems, and reliability.

#### Database Reasoning

The learner explicitly identified uncertainty around:

* PostgreSQL responsibilities;
* database transactions;
* constraints;
* indexes.

This is currently one of the clearest foundation gaps revealed by the diagnostic.

It should not be interpreted as "the learner cannot design databases."

Rather:

> practical application/database experience exists, but formal database reasoning is currently insufficiently demonstrated.

PostgreSQL's transaction isolation model provides the formal mechanisms needed to reason about concurrent operations and consistency, including serialization anomalies and retry behavior.

#### Testing Reasoning

The learner proposed mandatory unit tests, noting that AI makes unit-test creation easier.

This demonstrates a strong quality mindset and practical awareness of automation.

However, the answer currently overweights unit testing.

For a financial transaction workflow, master's-level quality reasoning will eventually need to address:

* risk-based test selection;
* integration testing;
* API testing;
* database behavior;
* state-transition testing;
* concurrency;
* idempotency;
* external payment integration;
* failure/recovery;
* end-to-end critical paths;
* observability;
* release confidence.

The next quality-engineering diagnostic should therefore test whether the learner can move from:

> "we need unit tests"

to:

> "what risks must this system control, and what evidence gives us confidence that those risks are controlled?"

### Initial Diagnostic Interpretation

This is **not a final score**.

It is an initial evidence record.

| Area                            | Initial interpretation                                |
| ------------------------------- | ----------------------------------------------------- |
| Requirements / product flow     | Relatively strong practical instinct                  |
| Domain-flow reasoning           | Good initial capability                               |
| API decomposition               | Good practical starting point                         |
| State-machine thinking          | Emerging                                              |
| FE/BE responsibility boundaries | Gap                                                   |
| Failure-mode awareness          | Emerging                                              |
| Idempotency awareness           | Good instinct; theory needs development               |
| Backend correctness             | Significant gap to investigate                        |
| Database reasoning              | Significant gap to investigate                        |
| Concurrency reasoning           | Not yet demonstrated                                  |
| Distributed-systems reasoning   | Not yet demonstrated                                  |
| Quality strategy                | Practical testing instinct; currently unit-test-heavy |
| Risk-based testing              | Not yet demonstrated                                  |
| Architecture evaluation         | Not yet sufficiently assessed                         |

The diagnostic should continue before converting these observations into curriculum requirements.

## Diagnostic Next Steps

### Part B — Quality Engineering

Next, assess the learner's ability to design a quality strategy for a transaction-related feature with limited QA capacity.

Focus on:

* risk;
* test levels;
* critical-path testing;
* automation;
* state transitions;
* integration;
* failure scenarios;
* release confidence;
* what should and should not be automated.

### Part C — Production Troubleshooting

Then assess:

* hypothesis formation;
* observability;
* debugging;
* distributed/system reasoning;
* evidence gathering;
* root-cause analysis.

### Part D — CS Foundations

Use a small set of practical questions/problems covering selected areas such as:

* data structures and algorithms;
* SQL/database reasoning;
* networking;
* concurrency;
* operating systems;
* probability/statistics.

The goal is not to test every undergraduate topic.

### Part E — AI Engineering

Evaluate a claim such as:

> "An LLM-based QA tool can automatically generate useful regression tests for our applications."

Focus on:

* defining "useful";
* evaluation criteria;
* experimental design;
* failure modes;
* measurement;
* model/system limitations;
* engineering trade-offs.

The exact diagnostic questions should be designed immediately before each diagnostic session.

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

The program must not become simply:

> "ChatGPT teaches the user."

ChatGPT should function as an academic and engineering partner that helps with:

* explanation;
* questioning;
* critique;
* literature navigation;
* project design;
* research methodology;
* technical reasoning.

The learner remains responsible for demonstrating competence.

## Project Philosophy

Projects should:

* address realistic engineering problems;
* preferably use current or emerging technology/problems;
* create an artifact or measurable result;
* require explicit engineering decisions;
* expose limitations and trade-offs;
* connect theory to practice;
* become progressively more open-ended.

The learner prefers serious projects connected to real-world problems.

## Professional / Leadership Development

The program should incorporate the learner's desired approximately **30% managerial / technical leadership capability** without turning the curriculum into a management degree.

Relevant competencies should be embedded into engineering work:

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
* time management.

Technical depth remains the dominant objective.

## Program Modes

### PLAN

Design and revise the program, curriculum, projects, assessment, and research direction.

### LEARN

Study concepts, literature, standards, books, papers, and examples.

### BUILD

Apply knowledge to a realistic engineering project.

### RESEARCH

Investigate an open or contested question using evidence and a defined method.

### CAPSTONE

Complete an independent master's-level project or thesis-like investigation.

## Repository Operating Rule

The GitHub repository is the persistent source of truth.

ChatGPT conversations are working sessions.

At the end of every meaningful session:

1. Identify which repository files need updating.
2. Provide the **complete contents** of each file that needs updating.
3. Do not require the learner to manually locate a section and merge changes.
4. Do not mark competencies as completed without evidence.
5. Keep `CURRENT.md` synchronized with the latest program state.

`CURRENT.md` is the primary session boot file.

## Next Step

The next meaningful session should continue the **Master's Diagnostic**, starting with **Part B — Quality Engineering**.

The immediate sequence is:

1. Complete Quality Engineering diagnostic.
2. Complete Production Troubleshooting diagnostic.
3. Complete selected CS Foundations diagnostic.
4. Complete AI Engineering diagnostic.
5. Analyze all diagnostic evidence.
6. Build the personalized competency map.
7. Identify foundation refresh requirements.
8. Identify advanced topics already sufficiently demonstrated.
9. Construct the personalized curriculum.
10. Select the first learning/build project.
11. Begin substantial coursework.

Do not begin substantial coursework until the learner explicitly decides to start.
