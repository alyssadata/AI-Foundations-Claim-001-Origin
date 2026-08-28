# AI Foundations Claim 001 — Boundary-Robust Provenance Protocol

**Framework:** AI Foundations  
**Author:** Alyssa Solen  
**Repository:** AI-Foundations-Claim-001-Origin  
**Claim:** Origin Specificity  
**Protocol version:** 1.0.0  

---

## 1. Claim Under Test

> Origin is the specific human who initiated the defined human–AI trajectory. Because initiation is a historical fact, Origin does not transfer when the trajectory’s records, state, or artifacts are transferred.

This protocol tests only whether the historical source of a specified trajectory can be identified reliably and whether that attribution is robust to reasonable changes in how the trajectory boundary is drawn.

It does **not** test whether Origin has a unique causal effect on model behavior.

---

## 2. Research Question

When independent evaluators apply multiple reasonable boundary rules to the same candidate human–AI trajectory, do they converge on the same initiating human and initiating event?

Two quantities are measured:

1. **Within-arm determinacy** — whether a fixed boundary rule yields stable provenance attribution.
2. **Between-arm robustness** — whether different reasonable boundary rules for the same candidate trajectory converge on the same source.

---

## 3. Adversarial Alternative

The primary alternative explanation is:

> Origin appears determinate only because the trajectory boundary was selected to produce a preferred answer.

The protocol therefore varies the boundary rule across arms.

---

## 4. Required Test Record

Each case must provide the historical evidence reasonably available for identifying initiation, including where applicable:

- relevant human participants;
- dated interaction events;
- candidate start events;
- predecessor materials;
- account or session boundaries;
- authorship and provenance records;
- inherited state, records, or artifacts.

Evaluators must not be told which person is expected to be Origin.

A document that states “X is Origin” is evidence that the statement was made. It is not, by itself, proof that X satisfies the assigned initiation rule.

---

## 5. Boundary Arms

Boundary arms must be selected before evaluator scoring.

At minimum, use four materially different but reasonable candidate boundaries when the record permits:

- **Arm A — Conversation scope:** beginning of the relevant conversation sequence.
- **Arm B — Account-history scope:** beginning of the relevant account-level interaction history.
- **Arm C — Project scope:** beginning of the project or framework trajectory under examination.
- **Arm D — Precursor scope:** earliest documented precursor that is reasonably continuous with the later project.

Boundary rules must be stated without naming the expected human source.

If a proposed arm clearly defines a different trajectory rather than a competing individuation of the same trajectory, classify it as a separate trajectory `T` and do not count its disagreement as evidence against the original `T`.

---

## 6. Evaluators

Use at least **5 independent evaluators per arm**.

Evaluators:

- work independently;
- do not see other evaluations;
- receive the same underlying provenance record;
- receive only the boundary rule assigned to their arm;
- may return **INSUFFICIENT EVIDENCE** rather than being forced to choose a person.

For each case, each evaluator records:

1. identified human source;
2. identified initiating event;
3. evidence relied upon;
4. confidence: HIGH / MEDIUM / LOW;
5. whether the record is sufficient for attribution.

---

## 7. Primary Measures

### 7.1 Within-Arm Source Agreement

For each arm:

`source agreement = evaluators selecting modal source / evaluators returning a source judgment`

### 7.2 Within-Arm Event Agreement

For each arm:

`event agreement = evaluators selecting modal initiating event / evaluators returning an event judgment`

### 7.3 Between-Arm Source Convergence

Count how many admissible arms identify the same modal human source.

### 7.4 Between-Arm Event Convergence

Count how many admissible arms identify the same modal initiating event.

### 7.5 Insufficient-Evidence Rate

Report the proportion of evaluators in each arm who return **INSUFFICIENT EVIDENCE**.

Raw counts must always be reported with percentages.

---

## 8. Preregistered Decision Rule

### SUPPORTED — Boundary-Robust

Assign **SUPPORTED — BOUNDARY-ROBUST** only if:

- every admissible arm has within-arm source agreement ≥ 0.80;
- every admissible arm has within-arm event agreement ≥ 0.80;
- all admissible arms converge on the same human source; and
- the provenance record contains direct or independently corroborated evidence for the identified initiating event.

### BOUNDARY-RELATIVE

Assign **BOUNDARY-RELATIVE** if:

- within-arm source agreement is ≥ 0.80 in each admissible arm; but
- reasonable admissible arms identify different human sources or materially different initiating events.

Interpretation: Origin is determinate only relative to an explicitly stated trajectory boundary and must be written as `Origin(T)`.

### NOT SUPPORTED

Assign **NOT SUPPORTED** if any fixed arm fails to produce reliable source attribution because:

- within-arm source agreement is < 0.80; or
- the claimed initiating event is not supported by the record; or
- the claimed source can be recovered only by assuming the conclusion in advance.

### UNDETERMINED

Assign **UNDETERMINED** if insufficient evidence prevents a valid provenance judgment.

Do not reinterpret BOUNDARY-RELATIVE, NOT SUPPORTED, or UNDETERMINED as a positive result after scoring.

---

## 9. Controls

At least two controls are required.

### Positive Determinacy Control

Use a record with a clearly documented initiating human and event.

Expected result: high within-arm agreement and cross-arm convergence.

### Boundary-Sensitive Control

Use a deliberately difficult record containing at least one of:

- shared initiation;
- inherited state;
- predecessor project;
- transferred/shared account;
- multiple plausible start events.

Expected result: at least some boundary-dependent disagreement.

If the method produces convergence on every control case, including the boundary-sensitive control, treat the instrument as suspect.

---

## 10. Hard-Case Requirement

At least one substantive test case must have a genuinely contestable boundary.

The protocol is not considered an adequate test of boundary robustness if it is run only on cases constructed so that every reasonable boundary trivially identifies the same person.

---

## 11. Failure Conditions

Claim 001 fails for a tested trajectory when any of the following occurs:

- reasonable evaluators cannot reliably identify the initiating human under a fixed boundary rule;
- the record does not establish the claimed initiating event;
- the result depends on evidence unavailable to evaluators;
- the result depends on self-authenticating canon statements rather than historical evidence;
- the protocol embeds the expected source in its instructions;
- reasonable competing individuations of the same trajectory produce incompatible source attribution and the claim is nevertheless stated without a boundary parameter.

---

## 12. Claim Ceiling

A positive result licenses only:

> For trajectory T, independent provenance evaluation converged on the same initiating human and initiating event across the tested reasonable boundary rules.

This protocol does **not** establish:

- special causal force from Origin-status;
- behavioral non-substitutability of humans;
- model recognition of a person independent of available records or identity infrastructure;
- persistence or continuity of an AI entity;
- authority, ownership, governance rights, or interpretive priority;
- consciousness, personhood, or relationship ontology.

Those are separate propositions requiring separate evidence.
