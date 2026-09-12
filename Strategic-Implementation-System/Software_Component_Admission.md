# Software Component Admission

## Purpose

**Software Component Admission** defines how the **Agile Innovation Framework** determines whether a concrete software component, dependency, configuration or technical state is admissible for a defined scope of use.

The artifact closes the gap between architectural intent and executable assurance.

A technical component MUST NOT be considered admissible merely because it is functionally suitable, commonly used, strategically desirable, or technically integrable.

Admission requires explicit 
- acceptance criteria,
- reproducible procedures,
- observable results,
- validation and
- evidence.

## Rationale

Trustworthy software ist derived from requirements and architecture decisions plus it's dependencies:

1) A requirement may be valid.
2) An architecture decision may be reasonable.
3) A component may be technically suitable but must be trustful as well, primarily without malicious code. 

None of these facts proves that a concrete component version or technical state is admissible.

AIF therefore distinguishes:

- strategic relevance,
- architectural suitability,
- implementation feasibility,
- and technical admissibility.

This distinction is required because a strategically valuable or technically attractive component may still be inadmissible due to security, supply-chain, licensing, compliance, provenance, operational or evidence gaps.

Software Component Admission introduces the governed decision point that connects requirements and architecture to reproducible validation and evidence.

## Core Principle

*A technical state is admissible only when its applicable mandatory acceptance criteria are satisfied by reproducible validation supported by valid evidence.*

Admission MUST be derived from evidence-backed validation.

Admission MUST NOT be asserted solely by documentation, popularity, maintainer reputation, architectural preference or manual declaration.

## Software Component Admission View

The lifecycle-oriented view is:

Requirement
    ↓
Acceptance Criterion
    ↓
ADR
    ↓
Architecture Component
    ↓
Configuration
    ↓
Procedure
    ↓
Deployment
    ↓
Observation
    ↓
Validation
    ↓
Evidence
    ↓
Admission Decision

This view is intentionally readable as a lifecycle.

The underlying information model is NOT required to be linear.

AIF treats the underlying model as a directed, typed traceability graph.
An Acceptance Criterion may, for example, reference a Requirement,
Architecture Component, Validation Rule and required Evidence simultaneously.

## Relationship to the Strategic Implementation System

### Innovation Blueprint

The Innovation Blueprint defines what must be achieved and which constraints must be satisfied.

Normative technical requirements SHOULD be operationalized through explicit Acceptance Criteria where objective admission or verification is required.

### Innovation Matrix

The Innovation Matrix evaluates relevance, value, risk and priority.

Admission is a separate dimension.

High strategic value or priority MUST NOT override a failed mandatory Admission Criterion.

A candidate that is not admissible MAY remain strategically relevant but MUST NOT progress into a scope for which admission is required.

### Visionary Execution Roadmap

The Visionary Execution Roadmap identifies when admission and revalidation must occur.

Relevant roadmap events include:

- initial component selection,
- first production use,
- dependency or version change,
- material configuration change,
- new vulnerability or security advisory,
- policy change,
- evidence expiration,
- changed deployment scope,
- changed trust context.

## Relationship to TAM

The Technological Architecture Manifesto defines architectural principles, technology boundaries and architectural intent.

Software Component Admission evaluates concrete implementations of those principles.

Architecture suitability does not imply admission.

## Relationship to CSD

The Compliance & Security Doctrine defines normative security and compliance expectations.

Admission Criteria MAY derive from security controls, regulatory obligations, supply-chain requirements, licensing requirements and organizational policy.

Mandatory CSD requirements MUST be represented as blocking criteria where their violation makes the target state inadmissible.

## Relationship to Governance & Accountability

Admission is a governed decision.

The governance model MUST define:

- who owns the Admission Policy,
- who may author Acceptance Criteria,
- who may define Validation Rules,
- who may execute Procedures,
- who reviews Evidence,
- who may approve exceptions,
- and which events require revalidation.

Separation of duties SHOULD be applied where risk or regulation requires independent validation.

## Required Artifact Classes

Software Component Admission may use:

- Requirement
- Acceptance Criterion
- Architecture Decision Record
- Architecture Component
- Configuration
- Procedure Definition
- Procedure Execution
- Deployment
- Observation
- Validation Rule
- Validation Result
- Evidence
- Admission Decision

Not every admission profile MUST require every artifact class.

For example, dependency admission may occur before deployment and therefore does not require a Deployment artifact.

Profiles MUST define which artifact classes and relations are mandatory.

## Admission States

The minimum normative decision states are:

### ADMITTED

All applicable blocking Acceptance Criteria are satisfied and all required validation results and evidence are present and valid.

### REJECTED

At least one applicable blocking Acceptance Criterion has failed.

### BLOCKED

A deterministic decision cannot currently be derived because required validation, evidence, references or procedure results are missing, inconclusive or invalid.

The initial model intentionally uses only these three states.

Additional states require a normative change.

## Derived Decision

AdmissionDecision MUST be derived.

A producer MUST NOT make a technical state admissible merely by declaring:

`decision = ADMITTED`

The decision MUST be derivable from:

Acceptance Criteria
    ↓
Validation Results
    ↓
Evidence
    ↓
Admission Policy
    ↓
Admission Decision

## Evidence Requirements

Evidence MUST be attributable to the procedure or observation that produced it.

Evidence SHOULD include, where applicable:

- subject,
- producer,
- procedure execution,
- tool and tool version,
- timestamp,
- source,
- content digest,
- validity information,
- and the Validation Result it supports.

## Revalidation

Admission is not necessarily permanent.

A previously admitted state MUST be reconsidered when an applicable revalidation trigger occurs.

Examples include:

- component version changes,
- transitive dependency changes,
- new vulnerabilities,
- policy changes,
- configuration changes,
- evidence expiry,
- deployment scope changes.

## DSL Core Integration

AIF defines the method, governance and meaning of Software Component Admission.

DSL Core provides the machine-enforceable representation and deterministic validation mechanism.

DSL Core SHOULD provide:

- canonical artifact types,
- artifact contracts,
- typed graph relations,
- referential validation,
- graph validation,
- validation results,
- evidence relationships,
- and deterministic Admission Decision derivation.

## Initial Vertical Slice

The first reference use case is dependency admission for the RTP BFF.

Candidate:

`axum@0.8.9`

The purpose of this slice is not to declare axum trustworthy in advance.

Its purpose is to prove that AIF and DSL Core can determine reproducibly whether a concrete dependency version is admissible under an explicit dependency-admission policy.
