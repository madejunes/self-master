# Current State

## Mode

**PLAN**

## Stage

**Curriculum Architecture — In Progress**

## Primary Goal

Build a self-directed, master's-level education focused on:

* Software Engineering
* Quality Engineering / QA
* AI Engineering

with a strong connection to real-world and current engineering problems.

The program is intended to approximate the intellectual breadth, depth, and
professional capability of a strong university master's-level education
without university enrollment.

## Planning Status

The initial high-level planning phase is complete.

The practical diagnostic phase is also complete.

The program is now transitioning from:

> diagnostic assessment → personalized curriculum architecture

The detailed curriculum is intentionally **not fully locked yet**.

The next planning step is to turn the personalized competency map into a
concrete learning structure containing:

* modules;
* learning outcomes;
* academic references;
* practical exercises;
* projects;
* assessment methods;
* realistic workload.

## User Profile

### Career Direction

The learner is currently a **Senior Software Engineer**.

Desired future direction:

* **70% Expert Software Engineer / IC track**
* **30% Managerial / technical leadership capability**

The goal is not primarily to become a manager.

The priority is developing strong technical depth while gaining enough
leadership capability to operate effectively as a technical lead.

### Current Strengths

The learner has substantial practical experience in:

* Requirements analysis
* System/API design
* Code review
* Refactoring
* Automated testing
* Integration testing
* Observability
* Production troubleshooting
* Technical/design decisions
* Maintaining existing codebases

The learner is stronger on the frontend side but has experience across the
broader software-development lifecycle.

### Development Areas

The learner wants to improve:

* Full-stack engineering fluency
* Backend engineering
* Database engineering
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
* Maestro

The learner's team has limited QA personnel, creating a potential real-world
opportunity to investigate QA automation and quality engineering.

Quality Engineering is therefore both:

1. a major educational competency area; and
2. a potential source of a future real-world project.

The diagnostic indicates that the learner has useful practical testing
experience but needs deeper theory around:

* risk-based testing;
* test adequacy;
* quality measurement;
* state-transition testing;
* concurrency testing;
* failure/recovery testing;
* reliability.

## AI

The learner uses LLMs extensively, including AI-assisted software
development.

The diagnostic indicates:

### Strengths

* skepticism toward unsupported AI accuracy claims;
* awareness of hallucination;
* awareness that LLMs make assumptions;
* awareness that more generated tests do not necessarily mean better QA;
* emerging understanding of evaluation and coverage.

### Development areas

* LLM mental model;
* machine-learning foundations;
* statistical/probabilistic reasoning;
* AI-system architecture;
* model/system evaluation;
* retrieval and grounding;
* tool use and agents;
* AI reliability;
* experimental evaluation.

AI learning should therefore go beyond prompt engineering and practical API
usage.

## Academic / CS Foundations

The learner has a Bachelor's degree in Informatics Engineering, completed
more than a decade ago.

Current self-assessment:

* Algorithms/data structures — weak
* Databases — weak
* Networking — weak
* Operating systems — weak
* Concurrency — weak
* Distributed systems — weak
* Probability/statistics — weak
* Discrete mathematics — weak

The diagnostic confirms that **databases and concurrency are immediate
priority gaps**.

These foundations should not be treated as a reason to repeat an entire
undergraduate CS curriculum.

Instead, foundations should be learned or refreshed just in time for the
higher-level engineering competencies they support.

## Engineering Environment

The learner's team primarily develops and maintains **mini apps inside a
fintech super-app ecosystem**.

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
7. Frontend deployment is often self-service through an established and stable
   system.
8. Backend deployment is more dependent on infrastructure developers / SRE,
   with the backend deployment system still emerging.

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

The system involves:

1. transaction creation;
2. payment;
3. funds being secured;
4. seller shipment/fulfillment;
5. buyer confirmation;
6. fund release.

### Team / Ownership

* One PM requested an estimate for the complete feature/system.
* A colleague provided a backend engineer so the learner could focus primarily
  on frontend work.
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

This case provides useful material for studying:

* requirements;
* estimation;
* FE/BE ownership;
* full-stack system understanding;
* state machines;
* database design;
* transactions;
* concurrency;
* testing strategy;
* risk-based testing;
* deployment;
* infrastructure dependencies;
* production reliability;
* technical decision-making.

This case study is **not currently a committed project**.

## Potential Flagship Project

A potential future flagship project is:

> A serious software system that automates or assists QA processes in an
> environment with limited dedicated QA capacity.

This remains a **candidate direction, not a commitment**.

The project must eventually be evaluated against:

* real team/business value;
* technical depth;
* current relevance;
* Software Engineering application;
* Quality Engineering application;
* possible AI application;
* measurable outcomes;
* potential for later research.

The project should not use AI merely because AI is fashionable.

The project should begin with:

> problem → evidence → requirements → design → implementation → measurement

rather than choosing technology first.

## Personalized Competency Map

The diagnostic indicates that the learner's practical engineering instincts
are generally stronger than their formal systems knowledge.

The curriculum should therefore:

* teach theory underneath existing practical intuition;
* avoid unnecessary repetition of basic software-development skills;
* use realistic engineering scenarios;
* connect CS foundations directly to production/system problems;
* emphasize reasoning, trade-offs, and evidence;
* use projects to integrate multiple competencies.

### 1. Software Engineering & Architecture

**Current:** practical foundation with important theoretical gaps.

Priority areas:

* software architecture;
* architectural decomposition;
* modularity;
* interfaces/contracts;
* state-machine design;
* domain modeling;
* quality attributes;
* architectural trade-offs;
* scalability;
* resilience;
* observability;
* technical decision-making;
* technical debt and evolution.

### 2. Data, Transactions & Concurrency

**Current:** significant gap; highest immediate foundation priority.

Priority areas:

* SQL;
* relational modeling;
* PostgreSQL;
* indexes;
* query planning;
* constraints;
* transactions;
* ACID;
* isolation;
* row-level locking;
* optimistic concurrency;
* pessimistic concurrency;
* race conditions;
* state transitions;
* invariants;
* idempotency;
* consistency.

This should be taught as an integrated area rather than isolated SQL lessons.

### 3. Distributed Systems

**Current:** significant gap.

Priority areas:

* network failure;
* timeouts;
* retries;
* duplicate messages;
* asynchronous processing;
* queues;
* consistency;
* distributed state;
* service boundaries;
* reconciliation;
* failure recovery;
* observability;
* distributed tracing.

### 4. Quality Engineering & Reliability

**Current:** practical strength with theoretical gaps.

Priority areas:

* risk-based testing;
* test adequacy;
* state-transition testing;
* property-based testing;
* mutation testing;
* concurrency testing;
* failure injection;
* reliability;
* performance;
* security testing;
* observability;
* incident response;
* quality measurement.

### 5. AI Engineering

**Current:** strong practical exposure with significant theoretical gaps.

Priority areas:

* ML foundations;
* probability/statistics;
* neural networks;
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
* cost/latency trade-offs.

### 6. AI + Software Quality

**Current:** promising interdisciplinary area; not yet developed formally.

Priority areas:

* AI test generation;
* evaluation methodology;
* benchmark desi*
