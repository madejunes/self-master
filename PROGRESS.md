# Progress Record

## Overall Status

**Diagnostic in progress — Parts A, B, and C completed**

This percentage is intentionally not a measure of academic ability.

It represents progress through the planned program.

The program has moved beyond high-level planning and is now gathering evidence about the learner's current capabilities.

## Demonstrated Competencies

No competency has yet been formally marked as mastered.

The diagnostic provides evidence about current strengths and gaps, but the evidence collected so far is not sufficient to certify master's-level mastery.

## Completed Planning Work

* [x] Identified goal: master's-level competence without university enrollment.
* [x] Identified primary field: Software Engineering.
* [x] Identified major adjacent fields: Quality Engineering / QA and AI Engineering.
* [x] Chosen project-driven learning.
* [x] Chosen light initial intensity.
* [x] Decided to use real academic/authoritative references.
* [x] Decided GitHub will be the persistent source of truth.
* [x] Defined PLAN / LEARN / BUILD / RESEARCH / CAPSTONE modes.
* [x] Defined real-world/current-project preference.
* [x] Defined master's-level target.
* [x] Defined engineering competency spine.
* [x] Defined supporting CS foundations.
* [x] Defined evidence-based mastery levels.
* [x] Defined diagnostic purpose.
* [x] Defined just-in-time foundation strategy.
* [x] Identified potential flagship project direction.
* [x] Closed initial high-level planning phase.
* [x] Established diagnostic as the next major milestone.

## Diagnostic Progress

### Part A — System Design

**Status: Completed**

Scenario:

Fintech escrow transaction mini-app involving:

* transaction creation;
* payment;
* secured funds;
* seller fulfillment;
* buyer confirmation;
* fund release.

#### Observed Strengths

* Practical requirements instincts
* Domain-flow modeling
* API decomposition
* Awareness of idempotency
* Awareness of recovering frontend state from backend state

#### Observed Gaps

* Explicit assumption validation
* Financial domain/data modeling
* FE/BE responsibility boundaries
* State-machine enforcement
* Database transactions and constraints
* Indexing
* Concurrency
* Distributed failure semantics
* Retry safety
* Source-of-truth reasoning
* Risk-based testing

### Part B — Quality Engineering

**Status: Completed**

The learner was asked to reason about quality strategy for the same escrow system with limited QA capacity.

#### Observed Strengths

* Strong practical/domain-risk awareness
* Awareness of regulatory/business failure
* Familiarity with unit/integration/API/E2E/manual testing
* Awareness of duplicate-operation risks
* Awareness of auditability
* Existing testing automation mindset

A particularly useful observation was the learner's immediate concern that a seller might already be at a regulatory balance limit and therefore be unable to receive disbursed funds.

#### Observed Gaps

* Risk-based test prioritization
* Systematic test strategy
* Failure/recovery testing
* State-transition testing
* Concurrency testing
* Financial consistency testing
* Test adequacy reasoning
* Understanding limits of code coverage
* Distinguishing QA as a role from quality as an engineering responsibility

The learner initially prioritized:

* payment success;
* disbursement success.

The learner proposed:

> unit → integration → API → E2E → manual

This shows familiarity with testing layers but suggests that test selection is currently more strongly driven by test type/order than by explicit risk analysis.

The learner identified:

* duplicate payment;
* duplicate transaction creation;
* payment failure;
* auditability failure

as edge cases.

The learner was uncertain about whether 90% unit-test coverage would be enough to release and still viewed QA as a quality gate.

This is useful evidence for developing stronger risk-based quality reasoning.

### Part C — Production Troubleshooting

**Status: Completed**

Scenario:

A buyer paid Rp1,000,000.

* The payment provider reports `SUCCESS`.
* The buyer sees "Payment successful".
* The seller's transaction still shows `WAITING_FOR_PAYMENT`.

The learner was asked how they would investigate the incident, generate hypotheses, distinguish causes, recover the customer situation, and prevent recurrence.

#### Observed Strengths

* Good instinct for trace IDs and correlated logs
* Awareness that user actions and API calls should be traceable
* Reasonable initial hypothesis generation
* Awareness of callback failure/timeout possibilities
* Awareness of cache invalidation as a possible cause
* Willingness to acknowledge operational experience limitations

The learner's own assessment was that their end-to-end log investigation experience is limited and is currently more frontend-focused.

#### Observed Gaps

The learner initially proposed refunding the buyer before establishing the actual system state.

This exposed a gap in safe financial recovery reasoning.

A financial incident should first establish the relationship between:

* payment-provider state;
* internal payment state;
* escrow state;
* database state;
* relevant events/callbacks.

The learner subsequently recognized that both the external payment provider and internal database can be authoritative for different aspects of the system, and that disagreement requires reconciliation.

Important areas for development:

* backend incident investigation;
* distributed tracing in practice;
* backend/database evidence correlation;
* system invariants;
* reconciliation;
* safe recovery;
* distributed failure analysis;
* incident response.

### Initial Diagnostic Interpretation

| Area                                   | Initial interpretation                                       |
| -------------------------------------- | ------------------------------------------------------------ |
| Requirements / product flow            | Relatively strong practical instinct                         |
| Domain-flow reasoning                  | Good initial capability                                      |
| API decomposition                      | Good practical starting point                                |
| Business/regulatory risk awareness     | Strong practical instinct                                    |
| State-machine thinking                 | Emerging                                                     |
| FE/BE boundaries                       | Gap                                                          |
| Failure-mode reasoning                 | Emerging                                                     |
| Idempotency                            | Good instinct; theory needs development                      |
| Database reasoning                     | Significant gap to investigate                               |
| Concurrency                            | Not yet demonstrated                                         |
| Distributed systems                    | Significant gap to investigate                               |
| Quality strategy                       | Practical but currently test-layer/happy-path oriented       |
| Risk-based testing                     | Needs development                                            |
| Test adequacy / coverage reasoning     | Needs development                                            |
| QA vs engineering quality ownership    | Needs development                                            |
| Production troubleshooting             | Frontend-oriented; backend/distributed experience limited    |
| Observability / tracing                | Good conceptual instinct; operational depth not demonstrated |
| Incident investigation                 | Emerging                                                     |
| Reconciliation / consistency reasoning | Significant gap to investigate                               |
| Architecture evaluation                | Not yet assessed                                             |

These observations are provisional and should not yet be converted into final competency grades.

## Formal Assessment

No competency has been formally certified.

The diagnostic is incomplete.

## Projects

No projects started.

Potential future flagship direction:

* QA automation/assistance system for environments with limited dedicated QA capacity.

This remains a candidate and is not yet committed.

## Research

No research started.

## Current Diagnostic Plan

### Part D — CS Foundations

Assess selected practical areas:

* data structures and algorithms;
* SQL/database reasoning;
* networking;
* concurrency;
* operating systems;
* probability/statistics.

The goal is not to test every undergraduate topic.

### Part E — AI Engineering

Assess:

* AI-system evaluation;
* defining useful outcomes;
* experiment design;
* failure modes;
* measurement;
* limitations;
* engineering trade-offs.

## Current Next Steps

1. Complete Part D — CS Foundations.
2. Complete Part E — AI Engineering.
3. Analyze all diagnostic evidence.
4. Build the detailed competency map.
5. Identify foundation refresh requirements.
6. Identify advanced competencies already demonstrated.
7. Construct the personalized curriculum.
8. Select the first learning/build project.
9. Begin substantial coursework.

## Important Rule

Do not mark a competency as mastered merely because it was discussed.

Record evidence such as:

* project artifact;
* exam/oral explanation;
* written analysis;
* experiment;
* research synthesis;
* debugging investigation;
* system design;
* implementation;
* another defensible assessment.

## Program Principle

The objective is not to maximize the number of topics completed.

The objective is to develop durable master's-level capability that can be demonstrated through reasoning, engineering work, evidence, and independent investigation.
