# Current State

## Mode

**PLAN**

## Stage

Pre-program / Curriculum Interview

## Primary Goal

Build a self-directed, master's-level education focused on:

* Software Engineering
* Quality Engineering / QA
* AI Engineering

with a strong connection to real-world and current engineering problems.

## User Profile

### Career Direction

The learner is currently a **Senior Software Engineer**.

Desired future direction:

* **70% Expert Software Engineer / IC track**
* **30% Managerial / technical leadership capability**

The goal is not primarily to become a manager. The priority is developing
strong technical depth while gaining enough leadership and management
capability to operate effectively as a technical lead.

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

The learner is stronger on the frontend side but has experience working
across the broader software-development lifecycle.

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

### Quality Engineering

Current profile:

> Developer with substantial testing experience.

Current testing experience includes:

* Jest
* Vitest
* Mocha
* Sinon
* Recent experimentation with Maestro

The learner's team has limited QA personnel, creating a potential real-world
opportunity to investigate QA automation and quality engineering.

### AI

The learner uses LLMs extensively but currently has limited understanding
of underlying machine-learning theory.

AI learning should eventually include foundational ML concepts rather than
focusing primarily on prompt usage or application-level techniques.

### Academic / CS Foundations

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

These should be treated as potentially rusty foundations, not automatically
as zero knowledge. Future diagnostic exercises should distinguish forgotten
knowledge, practical knowledge without theoretical grounding, and genuine gaps.

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
7. Frontend deployment is often self-service through an established and stable system.
8. Backend deployment is more dependent on infrastructure developers / SRE,
   with the backend deployment system still emerging.

## Real-World Case Study: Escrow Mini App

A recent example is a new mini app for an **escrow transaction**.

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

Because escrow involves transactions, future analysis should pay particular
attention to failure modes beyond the happy path.

This case study is **not currently a committed project**.

## Potential Flagship Project

A strong candidate for a future major project is:

> Build a serious software system that automates or assists QA processes,
> motivated by the learner's current team having limited QA personnel.

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

Foundations should be learned or refreshed **just in time** where possible,
rather than forcing the learner through a complete undergraduate CS curriculum
again.

## Master's-Level Assessment Model

The target is approximately the level expected from a strong university
master's graduate.

Assessment should focus on demonstrated capability rather than topic
completion.

Proposed progression:

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

Can independently formulate and investigate a meaningful question using
appropriate evidence and methodology.

The eventual Master's target is primarily **Levels 5–6**, supported by strong
Levels 3–4 across the relevant engineering competencies.

No competency should be marked as mastered merely because it was discussed.

## Diagnostic Phase

Before beginning substantial coursework, conduct a practical diagnostic
phase using realistic engineering problems rather than primarily
recall-based questions.

The diagnostic should assess:

* engineering reasoning;
* system/design thinking;
* architectural reasoning;
* testing/quality reasoning;
* debugging and production reasoning;
* CS foundations;
* ability to evaluate trade-offs;
* ability to explain and defend decisions.

The diagnostic should distinguish:

* already strong;
* rusty and requiring refresh;
* practical but theoretically weak;
* important genuine gap;
* low-priority gap that can be deferred.

The learner does **not** need to pass the diagnostic before starting.
The diagnostic exists to personalize the curriculum.

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

ChatGPT should function as an academic and engineering partner that helps
with explanation, questioning, critique, literature navigation, project
design, and research methodology.

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

## Next Planning Session

Continue the curriculum interview by examining the learner's actual
engineering environment in more detail, including:

* detailed technology stack;
* programming languages;
* frontend/backend responsibilities;
* databases;
* APIs and integrations;
* deployment/infrastructure;
* CI/CD;
* testing tools and practices;
* system scale and complexity;
* team structure;
* typical engineering problems;
* desired future technical capabilities.

After the curriculum interview:

1. Design the detailed competency map.
2. Design the diagnostic phase.
3. Conduct the diagnostic.
4. Use the results to construct the personalized curriculum.
5. Begin coursework.

Do not begin substantial coursework until the learner explicitly decides
to start.
