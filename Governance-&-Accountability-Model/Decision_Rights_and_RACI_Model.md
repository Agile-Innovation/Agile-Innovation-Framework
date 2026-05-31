# Decision Rights and RACI Model

## Definition

The Decision Rights and RACI Model defines how decisions are proposed, reviewed, approved, rejected, escalated, arbitrated, documented, and communicated within the Agile Innovation Framework.

It complements the Role, Function and Permission Model by translating roles, responsibilities, permissions, and interfaces into explicit decision authority, accountability, consultation, information, escalation, and control structures.

Aligned with agile and large-scale agile principles, this model ensures that relevant decisions are not only made, but are traceable, reviewable, evidence-based, and connected to defined responsibilities, risks, stakeholder input, acceptance criteria, governance boundaries, and cross-functional coordination needs.

---

## Purpose

The purpose of the Decision Rights and RACI Model is to make decision-making transparent, accountable, controlled, and operationally usable.

It enables organizations to:

* define who may propose, approve, reject, review, escalate, or finally decide
* distinguish responsibility for execution from authority to decide
* connect decisions to evidence, risks, acceptance criteria, and stakeholder input
* clarify when consultation is required
* clarify who must be informed
* define approval thresholds
* prevent unclear or informal decision paths
* support separation of duties
* enable independent review and control
* establish a reusable RACI mapping method
* document decisions in a versionable and auditable way

In our world, where we must cope with rapidly evolving technologies as well as with multiple crises it reflects the understanding that agile governance must enable decentralized expertise, fast feedback, and iterative learning while providing the transparency, alignment, and accountability required in enterprises of all size and sectors as well as large-scale agile environments.

---

## Core Principle

Decision rights define who has the authority to propose, approve, reject, delegate, review, escalate, arbitrate, or finally decide within a defined scope.

RACI is a proven method for clarifying who is responsible, accountable, consulted, and informed for specific activities or decisions. However, RACI is not a complete governance model by itself.

Within AIF, RACI MAY be used as a practical mapping method. If RACI is used, it MUST be complemented by explicit decision rights, approval thresholds, escalation paths, evidence requirements, stakeholder participation rules, and independent control mechanisms.

If an organization uses another method instead of RACI, it MUST provide an equivalent responsibility and accountability mapping that follows the same principles and is sufficiently explicit to support role-based permissions, separation of duties, independent control, and Zero Trust-oriented access control.

---

## Relationship to the Role, Function and Permission Model

The Role, Function and Permission Model defines the organizational foundation:

* roles
* functions
* responsibilities
* permissions
* interfaces
* separation of duties
* control responsibilities

The Decision Rights and RACI Model defines HOW those roles participate in decisions:

* who contributes
* who executes
* who is accountable
* who must be consulted
* who must be informed
* who may approve
* who may object
* who may escalate
* who may arbitrate
* who may finally decide

The Role, Function and Permission Model answers:

> Who exists in the governance structure, and what are they allowed to do?

The Decision Rights and RACI Model answers:

> Who decides what, on what basis, with which evidence, under which constraints, and through which escalation path?

---

## Scope

This model covers:

* decision rights
* decision types
* decision thresholds
* RACI mappings
* approval structures
* consultation requirements
* information requirements
* review and objection rights
* escalation rights
* arbitration authority
* evidence obligations
* decision documentation
* cross-functional decision flows

Out of Scope: This model does not define legal liability clauses, employment responsibilities, contractual penalties, or organization-specific management hierarchies.

---

## Decision Rights

Decision rights define the specific decision authority of a role or body within a defined scope.

### Proposal Right

The authority to submit a decision proposal.

Examples:

* propose a new Epic
* propose a Feature priority
* propose an architecture decision
* propose a risk treatment
* propose an SLA change
* propose an escalation

### Contribution Right

The authority to contribute expertise, evidence, assumptions, risks, estimates, or stakeholder input to a decision.

Examples:

* contribute domain expertise
* contribute technical feasibility input
* contribute compliance requirements
* contribute cost estimates
* contribute operational impact assessment

### Consultation Right

The right to be consulted before a decision is made.

Consultation MUST be meaningful, documented, and should be performed early enough to influence the decision without major ressource consumption.

Examples:

* consult security before it architecture approval
* consult operations before release planning
* consult stakeholders before major prioritization decisions
* consult compliance before accepting regulated risk

### Review Right

The authority to review decision proposals, evidence, assumptions, risks, acceptance criteria, or implementation readiness.

Examples:

* review an architecture decision record
* review security evidence
* review milestone readiness
* review SLA performance
* review investment assumptions

### Objection Right

The authority to raise a formal objection that MUST be documented and addressed before a decision proceeds.

Examples:

* object to insufficient evidence
* object to unclear acceptance criteria
* object to unresolved stakeholder impact
* object to unacceptable security risk
* object to unrealistic resource assumptions

### Approval Right

The authority to approve a decision, artifact, milestone, release, exception, risk acceptance, or investment within a defined scope.

Approval MUST be based on documented evidence and MUST remain within defined authority limits.

Examples:

* approve a roadmap milestone
* approve a release gate
* approve an architecture decision
* approve a risk treatment
* approve an SLA baseline

### Rejection Right

The authority to reject a proposal, artifact, milestone, release, exception, or decision request.

Rejection MUST include documented rationale and required next steps where applicable.

Examples:

* reject a Feature due to insufficient value
* reject a release due to missing evidence
* reject an architecture option due to unresolved security concerns
* reject an investment proposal due to insufficient benefit

### Delegation Right

The authority to delegate defined decision preparation, review, or execution responsibilities.

Delegation MUST NOT transfer final accountability unless explicitly defined.

Examples:

* delegate feasibility analysis
* delegate evidence preparation
* delegate stakeholder consultation
* delegate technical review

### Escalation Right

The authority to escalate unresolved conflicts, risks, decision blockers, authority breaches, SLA violations, or evidence gaps.

Examples:

* escalate priority conflicts
* escalate missing approvals
* escalate unresolved security risks
* escalate delivery blockers
* escalate stakeholder objections

### Arbitration Right

The authority to resolve conflicts that cannot be resolved through normal decision or escalation paths.

Arbitration authority MUST be defined before conflicts occur.

Examples:

* resolve decision deadlocks
* resolve conflicting stakeholder positions
* resolve priority disputes
* resolve responsibility conflicts
* resolve escalation deadlocks

### Final Decision Authority

The authority to make the binding decision within a defined scope.

Every relevant decision MUST have exactly one clearly defined final decision authority.

Final decision authority MUST NOT bypass mandatory evidence, consultation, control, escalation, or separation-of-duties requirements.

---

## RACI Definitions

RACI is optional as a method, but responsibility and accountability mapping is mandatory as a governance capability.
RACI is used to clarify participation in activities, deliverables, and decisions and can be replaced by equivalent responsibility and accountability mapping.

### Responsible

The role that performs the work or prepares the decision input.

There MAY be multiple Responsible roles.

### Accountable

The role that owns the outcome and ensures that the decision, activity, or deliverable is completed appropriately.

Each decision or deliverable MUST have one clearly defined accountability anchor.

The accountability anchor MAY be a single role, a predefined substitute role, or a defined governance body. Multiple contributors, reviewers, approvers, control roles, or participatory mechanisms MAY be involved, but they MUST NOT obscure who is accountable for the outcome.

Substitute arrangements, four-eyes principles, delegated participation, and Liquid Democracy-oriented mechanisms MUST be explicitly documented where they apply.


### Consulted

The roles whose expertise, perspective, or stakeholder position MUST be considered before a decision is made.

Consultation is two-way communication with defined rights and obligations.

Consulted roles MUST receive sufficient context, evidence, decision scope, and response time to provide meaningful input. They have the right to raise concerns, contribute expertise, challenge assumptions, identify risks, and propose alternatives.

The decision owner MUST consider consulted input, document relevant contributions, explain how critical concerns were addressed, and escalate unresolved objections where required.

Consultation MUST happen early enough to influence the decision and MUST NOT be reduced to late-stage information sharing.


### Informed

The roles that MUST be informed about decisions, outcomes, changes, risks, or next steps.

Information is one-way communication unless follow-up rights are explicitly defined.

---

## RACI Is Not Sufficient by Itself

RACI clarifies participation, but it does not fully define governance.

RACI alone does not define:

* approval thresholds
* final decision authority
* rejection rights
* objection rights
* escalation rights
* arbitration authority
* evidence obligations
* stakeholder participation rules
* independent control mechanisms
* separation-of-duties constraints
* Zero Trust-oriented permission boundaries

Therefore, each RACI mapping MUST be connected to explicit decision rights where the activity involves strategic, financial, operational, technical, legal, compliance, security, stakeholder, or service-level impact.

---

## Decision Types

The model MUST distinguish at least the following decision types.

### Strategic Decisions

Decisions related to direction, strategic goals, major initiatives, and long-term positioning.

Typical AIF interfaces:

* Strategic Implementation System
* Innovation Matrix
* Visionary Execution Roadmap

Typical decision rights:

* proposal by Accountable Owner or Decision Owner
* contribution by Product, Architecture, Operations, Compliance, and Stakeholder roles
* approval by defined strategic authority
* escalation through governance steering

### Product and Value Decisions

Decisions related to user needs, stakeholder value, Features, acceptance criteria, and benefit realization.

Typical AIF interfaces:

* Innovation Blueprint
* Innovation Matrix
* Stakeholder Participation Model

Typical decision rights:

* proposal by Product or Service Owner
* consultation with Stakeholder Representative
* review by Architecture, Implementation, Compliance, and Operations roles
* approval according to defined thresholds

### Prioritization Decisions

Decisions related to what is implemented first and why.

Typical AIF interfaces:

* Innovation Matrix
* Strategic Implementation System
* Visionary Execution Roadmap

Typical decision rights:

* proposal by Product or Service Owner
* contribution by Architecture, Implementation, Operations, Compliance, Security, and Stakeholder roles
* approval by Decision Owner or Accountable Owner
* escalation where resource conflicts, stakeholder objections, or risk thresholds are exceeded

### Architecture Decisions

Decisions related to architecture principles, technical feasibility, integration, interoperability, and sustainability.

Typical AIF interfaces:

* Technological Architecture Manifesto
* Innovation Blueprint
* Compliance & Security Doctrine
* Operational Synergy Map

Typical decision rights:

* proposal by Architecture Owner
* contribution by Implementation Owner and Operations Function
* review by Compliance and Security Reviewer
* objection by Independent Control Role where required
* approval according to impact threshold

### Security and Compliance Decisions

Decisions related to policies, controls, risk treatment, auditability, evidence, data protection, and compliance obligations.

Typical AIF interfaces:

* Compliance & Security Doctrine
* Role, Function and Permission Model
* Operational Synergy Map

Typical decision rights:

* proposal by Compliance and Security Reviewer or Decision Owner
* review by Independent Control Role
* contribution by Architecture, Implementation, Product, and Operations roles
* approval by accountable governance authority
* escalation where mandatory control requirements are not met

### Risk Acceptance Decisions

Decisions that accept, defer, transfer, mitigate, or tolerate risk.

Risk acceptance decisions MUST be explicit, documented, time-bound, reviewable, and assigned to an accountable role.

Typical decision rights:

* proposal by relevant owner
* review by Compliance and Security Reviewer
* control review by Independent Control Role where required
* approval by Accountable Owner within authority limits
* escalation where risk exceeds defined thresholds

### Investment Decisions

Decisions related to funding, resource allocation, cost-benefit assumptions, opportunity costs, and expected value.

Typical AIF interfaces:

* Investment Decision Model
* Innovation Matrix
* Strategic Implementation System
* Visionary Execution Roadmap

Typical decision rights:

* proposal by Accountable Owner or Decision Owner
* contribution by Product, Architecture, Implementation, Operations, Finance, Compliance, and Stakeholder roles
* approval according to investment threshold
* escalation where assumptions, risks, or stakeholder impacts remain unresolved

### SLA and Service Quality Decisions

Decisions related to service levels, quality targets, acceptance criteria, operational readiness, and corrective actions.

Typical AIF interfaces:

* Service Level and Steering Model
* Operational Synergy Map
* Compliance & Security Doctrine

Typical decision rights:

* proposal by Product or Service Owner
* contribution by Operations, Implementation, Architecture, and Compliance roles
* approval by accountable service authority
* escalation where SLA thresholds are breached

### Crisis and Emergency Decisions

Decisions required during incidents, crises, security events, operational disruptions, or urgent stakeholder impact.

Typical AIF interfaces:

* Crisis Communication Model
* Escalation and Arbitration Model
* Operational Synergy Map
* Compliance & Security Doctrine

Typical decision rights:

* emergency authority MUST be predefined
* decisions MUST be documented retrospectively where real-time documentation is not feasible
* post-incident review MUST validate rationale, impact, and improvement actions
* emergency authority MUST NOT permanently bypass standard governance

### Arbitration Decisions

Decisions that resolve conflicts, deadlocks, or disputes that cannot be resolved through normal decision paths.

Typical AIF interfaces:

* Escalation and Arbitration Model
* Stakeholder Participation Model
* Governance & Accountability Model

Typical decision rights:

* arbitration body MUST have defined authority
* required evidence MUST be available
* rationale MUST be documented
* outcome MUST be communicated to affected roles
* structural improvement needs MUST be recorded

---

## Decision Thresholds

Decision thresholds define how much governance is required for a decision.

### Level 1: Routine Decision

Low-impact decision within existing scope, budget, architecture, risk, and SLA boundaries.

Minimum requirements:

* accountable role defined
* decision documented where relevant
* affected roles informed

### Level 2: Significant Decision

Decision with cross-functional impact, resource implications, stakeholder relevance, architecture implications, or operational consequences.

Minimum requirements:

* decision owner defined
* accountable role defined
* required consulted roles defined
* evidence documented
* risks documented
* approval documented
* affected roles informed

### Level 3: Critical Decision

Decision with relevant financial, operational, technical, legal, compliance, security, stakeholder, or public impact.

Minimum requirements:

* final decision authority defined
* separation of duties enforced
* independent review included
* evidence documented
* stakeholder impact documented
* risk treatment documented
* escalation path defined
* approval documented
* review date defined

### Level 4: Emergency Decision

Time-critical decision required to protect security, availability, integrity, compliance, stakeholders, or operational continuity.

Minimum requirements:

* emergency authority predefined
* rationale documented
* affected roles informed as soon as feasible
* retrospective review performed
* temporary deviations documented
* permanent governance bypass prohibited

---

## Decision Rules

The following rules apply to AIF decision-making.

1. Every relevant decision MUST have a defined decision type.

2. Every relevant decision MUST have exactly one Accountable role.

3. Every relevant decision MUST have a defined final decision authority.

4. Decision authority MUST be limited to a defined scope.

5. Decisions MUST be based on documented evidence appropriate to their impact.

6. Decisions with relevant financial, operational, technical, legal, compliance, security, stakeholder, or service-level impact MUST include defined consultation and review.

7. Decisions that exceed defined authority, risk, cost, scope, security, compliance, or SLA thresholds MUST be escalated.

8. The same role MUST NOT define, implement, approve, and independently control a critical decision.

9. Objections MUST be documented and resolved or escalated before final approval.

10. Risk acceptance MUST be explicit, documented, assigned, time-bound, and reviewable.

11. Emergency decisions MUST be reviewed after the event.

12. Final decisions MUST be communicated to all informed roles.

---

## AIF RACI Mapping

The following RACI mapping provides a reusable baseline.

| Decision Area                   | Responsible                      | Accountable                   | Consulted                                                                   | Informed                                 |
| ------------------------------- | -------------------------------- | ----------------------------- | --------------------------------------------------------------------------- | ---------------------------------------- |
| Strategic initiative definition | Decision Owner                   | Accountable Owner             | Product, Architecture, Compliance, Stakeholders                             | Implementation, Operations               |
| Feature prioritization          | Product or Service Owner         | Decision Owner                | Stakeholders, Architecture, Implementation, Operations, Compliance          | Accountable Owner                        |
| Architecture decision           | Architecture Owner               | Decision Owner                | Implementation, Operations, Compliance, Security                            | Product, Stakeholders                    |
| Security control decision       | Compliance and Security Reviewer | Accountable Owner             | Architecture, Implementation, Operations, Independent Control               | Product, Stakeholders                    |
| Risk acceptance                 | Decision Owner                   | Accountable Owner             | Compliance, Security, Independent Control, Architecture                     | Product, Operations                      |
| Roadmap milestone approval      | Decision Owner                   | Accountable Owner             | Product, Implementation, Architecture, Operations, Compliance               | Stakeholders                             |
| Release readiness               | Implementation Owner             | Product or Service Owner      | Operations, Architecture, Compliance, Security                              | Accountable Owner, Stakeholders          |
| SLA definition                  | Product or Service Owner         | Accountable Owner             | Operations, Implementation, Compliance, Stakeholders                        | Architecture                             |
| SLA violation handling          | Operations Function              | Product or Service Owner      | Implementation, Compliance, Escalation Owner                                | Accountable Owner, Stakeholders          |
| Investment decision             | Accountable Owner                | Strategic Authority           | Product, Architecture, Implementation, Operations, Compliance, Stakeholders | Affected teams                           |
| Stakeholder objection handling  | Stakeholder Representative       | Decision Owner                | Product, Escalation Owner, Compliance                                       | Accountable Owner                        |
| Escalation handling             | Escalation Owner                 | Accountable Owner             | Affected roles, Independent Control                                         | Stakeholders where relevant              |
| Arbitration decision            | Arbitration Body                 | Defined Arbitration Authority | Escalation Owner, affected roles, Independent Control                       | Accountable Owner, affected stakeholders |

This baseline MUST be adapted to the organizational context, but deviations from mandatory accountability, evidence, control, and escalation requirements MUST be documented.

---

## Decision Rights Mapping Template

Each relevant decision type MUST be documented with the following structure:

```markdown
## Decision: [Decision Name]

### Decision Type

[Strategic / Product / Prioritization / Architecture / Security / Compliance / Risk / Investment / SLA / Crisis / Arbitration]

### Scope

[Where this decision applies.]

### Decision Threshold

[Routine / Significant / Critical / Emergency]

### Final Decision Authority

[Role or body with final decision authority.]

### Accountable Role

[Exactly one accountable role.]

### Responsible Role(s)

[Roles responsible for preparation or execution.]

### Consulted Role(s)

[Roles that must be consulted before the decision.]

### Informed Role(s)

[Roles that must be informed after the decision.]

### Review Role(s)

[Roles that must review assumptions, evidence, risks, or readiness.]

### Objection Rights

[Roles that may raise formal objections.]

### Escalation Path

[Where unresolved issues are escalated.]

### Arbitration Path

[Where decision deadlocks are resolved.]

### Required Evidence

- [Evidence artifact 1]
- [Evidence artifact 2]
- [Evidence artifact 3]

### Acceptance Criteria

- [Criterion 1]
- [Criterion 2]

### Risk Considerations

- [Risk 1]
- [Risk 2]

### Decision Record

[Link to decision record.]

### Review Date

[Date or trigger for review.]
```

---

## Decision Record Template

Every significant, critical, emergency, escalated, or disputed decision MUST be documented.

```markdown
# Decision Record: [Title]

## Status

[Proposed / Approved / Rejected / Escalated / Superseded]

## Date

[YYYY-MM-DD]

## Decision Type

[Type]

## Decision Threshold

[Routine / Significant / Critical / Emergency]

## Context

[What situation led to this decision?]

## Decision

[What was decided?]

## Rationale

[Why was this decision made?]

## Alternatives Considered

- [Alternative 1]
- [Alternative 2]

## Evidence Used

- [Evidence artifact 1]
- [Evidence artifact 2]

## Risks Reflected

- [Risk 1]
- [Risk 2]

## Risks Accepted

- [Accepted risk 1]
- [Accepted risk 2]

## Accountable Role

[Role]

## Final Decision Authority

[Role or body]

## Responsible Role(s)

[Roles]

## Consulted Role(s)

[Roles]

## Informed Role(s)

[Roles]

## Objections

[None / documented objections]

## Escalation

[None / escalation path used]

## Consequences

[Expected effects and follow-up actions.]

## Review Trigger

[Date, milestone, incident, audit finding, SLA breach, or other trigger.]
```

---

## Relationship to AIF Components

### Strategic Implementation System

This model supports the Strategic Implementation System by defining who has authority over strategic alignment, resource decisions, milestone approval, risk escalation, and implementation governance.

### Innovation Blueprint

This model supports the Innovation Blueprint by defining who decides on Epics, Use Cases, User Stories, Features, requirements, acceptance criteria, and stakeholder relevance.

### Innovation Matrix

This model supports the Innovation Matrix by defining who contributes evaluation input, who approves priorities, who may object to prioritization assumptions, and who resolves prioritization conflicts.

### Visionary Execution Roadmap

This model supports the Visionary Execution Roadmap by defining who approves milestones, who validates readiness, who escalates delivery risks, and who decides when sequencing must change.

### Technological Architecture Manifesto

This model supports the Technological Architecture Manifesto by defining who owns architecture decisions, who reviews technical feasibility, who validates compliance with architecture principles, and who approves architecture exceptions.

### Compliance & Security Doctrine

This model supports the Compliance & Security Doctrine by defining who reviews security and compliance decisions, who may object to insufficient controls, who accepts risk, and who performs independent control.

### Operational Synergy Map

This model supports the Operational Synergy Map by defining decision rights for operations, resource coordination, service readiness, SLA handling, incident escalation, and operational handovers.

---

## Evidence Obligations

Decisions MUST be supported by evidence appropriate to their impact.

Relevant evidence may include:

* requirement records
* acceptance criteria
* stakeholder consultation records
* architecture decision records
* risk assessments
* security assessments
* compliance mappings
* cost-benefit analysis
* resource assumptions
* roadmap dependencies
* SLA reports
* incident records
* audit evidence
* control validation reports

Evidence MUST be versionable, reviewable, and connected to the decision record where relevant.

---

## Escalation and Arbitration

Escalation MUST occur when:

* authority limits are exceeded
* mandatory evidence is missing
* required consultation has not happened
* objections remain unresolved
* risk thresholds are exceeded
* cost thresholds are exceeded
* scope boundaries are exceeded
* SLA thresholds are breached
* security or compliance concerns remain unresolved
* decision deadlock blocks progress

Arbitration MUST occur when escalation does not resolve the conflict or when the governance model requires independent dispute resolution.

Escalation and arbitration outcomes MUST be documented.

---

## Review and Evolution

Decision rights and RACI mappings MUST be reviewed regularly.

Review triggers include:

* new Epics
* changed strategic priorities
* changed stakeholder groups
* new regulatory or compliance expectations
* major architecture changes
* operational incidents
* repeated escalations
* capacity constraints
* audit findings
* delivery delays
* SLA violations
* security findings
* unresolved stakeholder objections

The model MUST evolve iteratively as organizational complexity, risk, stakeholder impact, and operational maturity increase.

---

## Summary

The Decision Rights and RACI Model makes decision-making within the Agile Innovation Framework explicit, accountable, evidence-based, and reviewable.

It ensures that decisions are connected to roles, permissions, responsibilities, stakeholder participation, independent control, escalation, arbitration, and documented evidence.

RACI provides a practical responsibility mapping method. Decision rights provide the authority model. Together, they create the governance structure required for transparent, auditable, secure, and trustworthy execution.
