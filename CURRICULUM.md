# Curriculum Architecture

## Status

**Baseline architecture established.**

The high-level curriculum design is sufficiently defined to begin diagnostic assessment.

The curriculum is intentionally **not fully locked**.

Detailed competency mapping, topic sequencing, depth, and workload will be determined after the learner's diagnostic.

## Educational Target

The program should approximate the intellectual breadth and depth of a strong master's-level software engineering education while allowing a project-driven, self-directed structure.

The academic reference point includes ACM/IEEE-CS GSwE2009 graduate software engineering curriculum guidance and the broader competency-oriented approach of CS2023.

GSwE2009 treats graduate software engineering as a professional master's-level discipline requiring integration of theory and practice, engineering principles, risk and trade-off reasoning, and capabilities across areas such as requirements, architecture, development, quality, and project development.

CS2023 shifts emphasis from merely listing knowledge toward competencies and demonstrated skill levels, while allowing a curriculum to select knowledge areas according to its intended competency focus.

Primary references:

* ACM/IEEE-CS, Graduate Software Engineering 2009 (GSwE2009)
* ACM/IEEE-CS/AAAI, Computer Science Curricula 2023 (CS2023)
* Carnegie Mellon Software Engineering Institute graduate curriculum materials
* Relevant current standards, books, papers, and authoritative technical sources

## Curriculum Design Principle

The curriculum should optimize for:

> demonstrated capability rather than completed topics.

A topic is valuable when the learner can use it to reason, build, evaluate, investigate, or make better engineering decisions.

The curriculum should therefore combine:

* foundational knowledge;
* advanced engineering practice;
* project work;
* evidence-based evaluation;
* research literacy;
* independent investigation.

## Competency Spine

### 1. Software Engineering Foundations

Potential competencies:

* software development as an engineering discipline;
* requirements engineering;
* software design;
* architecture;
* implementation;
* maintenance and evolution;
* configuration/version management;
* engineering processes;
* technical debt;
* engineering decision-making;
* socio-technical aspects of software engineering.

### 2. Software Architecture & Systems

Potential competencies:

* architectural decomposition;
* modularity;
* coupling/cohesion;
* interfaces and contracts;
* distributed systems;
* data and integration architecture;
* architecture evaluation;
* architectural trade-offs;
* scalability;
* resilience;
* observability;
* security considerations.

### 3. Quality Engineering

Potential competencies:

* software quality models;
* testing theory;
* test design;
* unit/integration/system testing;
* property-based testing;
* mutation testing;
* exploratory testing;
* test automation;
* CI/CD quality practices;
* reliability;
* performance;
* security testing;
* verification and validation;
* quality measurement;
* production quality and observability.

### 4. AI Engineering

Potential competencies:

* machine learning foundations;
* statistical/probabilistic reasoning;
* neural networks and deep learning;
* language models;
* embeddings/retrieval;
* RAG;
* agents and tool use;
* AI system architecture;
* evaluation;
* reliability;
* safety/security;
* cost/latency trade-offs;
* model and system lifecycle.

### 5. AI + Software Quality Intersection

Potential competencies:

* testing non-deterministic systems;
* evaluation design;
* benchmark design;
* regression testing for AI systems;
* LLM evaluation;
* agent evaluation;
* robustness;
* monitoring;
* human-in-the-loop systems;
* failure analysis.

### 6. Research & Engineering Method

Potential competencies:

* literature search;
* literature review;
* research questions;
* hypotheses where appropriate;
* experimental design;
* qualitative methods;
* quantitative methods;
* measurement;
* validity and threats to validity;
* reproducibility;
* statistical reasoning;
* technical writing;
* peer-review literacy.

### 7. Professional / Socio-Technical Engineering

Potential competencies:

* engineering economics;
* project and risk management;
* team/software process;
* organizational constraints;
* ethics;
* security/privacy;
* regulation and standards;
* human factors;
* technology adoption and maintenance;
* technical leadership;
* engineering communication;
* decision-making under uncertainty.

## Foundations Track

The engineering spine is supported by a selective CS foundations track.

Primary foundation areas:

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

> learn or refresh foundations when they become necessary for higher-level competence.

For example:

* algorithms may be revisited when system performance or algorithmic trade-offs require them;
* databases may be deepened when data modeling, indexing, transactions, or query performance become relevant;
* networking may be deepened when debugging APIs, latency, protocols, or distributed failures;
* concurrency may be deepened when reasoning about Go, backend systems, races, or distributed coordination;
* probability/statistics may be deepened before serious AI evaluation or experimental research.

The diagnostic determines where this just-in-time strategy is appropriate.

## Mastery Levels

The program will use an evidence-based mastery model.

### Level 1 — Understand

Can explain core ideas and terminology accurately.

### Level 2 — Apply

Can apply concepts to well-defined engineering problems.

### Level 3 — Analyze

Can diagnose unfamiliar problems, handle ambiguity, and reason about causes.

### Level 4 — Evaluate

Can compare alternatives, evaluate evidence, reason about trade-offs, and defend decisions.

### Level 5 — Synthesize

Can integrate multiple areas of knowledge to solve complex or open-ended engineering problems.

### Level 6 — Investigate

Can independently formulate and investigate a meaningful question using appropriate evidence and methodology.

The target for master's-level competence is primarily Levels 5–6 in the learner's major competency areas, supported by strong Levels 3–4 across the broader engineering foundation.

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
2. Is it important to the user's target competence?
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
* **Skip/defer** — intentionally postponed because its current value is low.

## Intended Progression

The initial conceptual progression is:

Foundation
→ advanced engineering
→ architecture/systems
→ quality/reliability
→ AI engineering
→ integrated intelligent systems
→ research method
→ independent research/capstone

This is **not a fixed semester schedule**.

The actual progression will be personalized after diagnostic assessment.

Projects may cause the learner to move between these areas rather than studying them in strict sequence.

## Project Integration

Projects are not separate from the curriculum.

A project should serve as a context in which multiple competencies are demonstrated.

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
* explicit hypotheses or research questions where appropriate;
* experimental design;
* quantitative evaluation;
* comparison against alternatives;
* analysis of limitations.

## Potential Flagship Direction

A potential flagship project is a system that automates or assists QA processes in environments with limited dedicated QA capacity.

This remains a **candidate**, not a commitment.

It must first pass a problem-validation process:

> problem → evidence → requirements → design → implementation → measurement

The technology and use of AI should follow the problem rather than determine it.

## Diagnostic Before Detailed Curriculum

The detailed curriculum should not be finalized before diagnostic assessment.

The diagnostic will establish an evidence-based starting point across:

* software engineering;
* architecture;
* quality engineering;
* production/debugging;
* CS foundations;
* AI reasoning;
* trade-off evaluation;
* technical communication.

After the diagnostic, each competency can be assigned an initial status such as:

* demonstrated;
* strong;
* rusty;
* practical but theoretically weak;
* important gap;
* low-priority gap;
* not yet assessed.

The curriculum can then allocate time according to actual need.

## Research / Capstone Direction

The long-term program should culminate in an independent master's-level project or thesis-like investigation.

A capstone should involve:

* a meaningful problem;
* explicit motivation;
* relevant literature;
* clear research or engineering question;
* appropriate methodology;
* implementation or investigation where appropriate;
* evidence;
* evaluation;
* limitations;
* defensible conclusions;
* professional technical communication.

A project can become a research project if its question, methodology, evidence, and evaluation justify that transition.

## Current State

The high-level architecture is now sufficiently defined.

**Next step: conduct the diagnostic.**

No detailed multi-course schedule should be created yet.
