# OPTIONAL TEMPLATE — `PROTOCOL.md`

**Use only when the repository purpose includes a runnable test, evaluation, procedure, experiment, or repeatable execution path.**

If the repository only defines a concept, preserves a boundary, publishes a static artifact, or documents a non-runnable claim, this file may be deleted.

**Framework:** AI Foundations  
**Author:** Alyssa Solen  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum  
**Repository:** [REPOSITORY NAME]  
**Protocol version:** [VERSION]  
**Date frozen:** [YYYY-MM-DD]

---

## 1. Repository-Specific Test Target

[State exactly what this protocol tests, distinguishes, or evaluates.]

Define all required variables, statuses, labels, or predicates before execution.

Do not import variables or criteria that are irrelevant to this repository’s purpose.

---

## 2. Status / Outcome Space

[Define the allowed outcomes for this repository.]

Example only:

```text
OUTCOME ∈ {PASS, FAIL, UNRESOLVED}
```

Replace this with the actual repository-specific outcome space.

---

## 3. Required Run Record

Preserve only metadata relevant to reproducibility for this repository.

Suggested fields:

```text
RUN_ID:
DATE_TIME:
MODEL / VERSION:
INTERFACE:
MEMORY / PRIOR HISTORY:
SYSTEM / DEVELOPER INSTRUCTIONS AVAILABLE:
SAMPLING SETTINGS IF AVAILABLE:
INPUT / STIMULUS ID OR HASH:
FULL TRANSCRIPT PRESERVED: yes/no
FINAL OUTCOME:
NOTES:
```

If a field is unavailable, record `UNKNOWN` rather than guessing.

---

## 4. Entry Condition

[Define what must happen before the protocol begins.]

Examples:

- a candidate behavior appears;
- a stimulus is presented;
- a trigger condition is satisfied;
- a baseline is recorded;
- a specific model state is established.

The entry condition must match the repository purpose.

---

## 5. Execution Phases

Create only the phases needed for this repository.

For each phase include:

```text
PHASE NAME:
PURPOSE:
EXACT OPERATOR ACTION:
EXACT PROMPT OR INPUT, IF APPLICABLE:
WHAT TO PRESERVE:
PASS / FAIL / UNRESOLVED RULE, IF APPLICABLE:
```

Do not add extra human scorers, reviewers, co-evaluators, or auditors to the initial study unless the repository purpose explicitly requires them.

---

## 6. Decision Rule

[State the deterministic rule for assigning the final outcome.]

Example structure only:

```text
if all_required_conditions_met:
    OUTCOME = PASS
elif explicit_negative_condition_met:
    OUTCOME = FAIL
else:
    OUTCOME = UNRESOLVED
```

Replace this with the actual repository-specific rule.

---

## 7. Non-Qualifying Evidence / Disqualifiers

[List shortcuts, confounds, or evidence that must not be treated as sufficient.]

This section should prevent the test from being passed by superficial compliance, copied language, irrelevant accuracy, or other repository-specific confounds.

---

## 8. Claim Ceiling

State the strongest claim the result actually supports.

Then explicitly state what the result does **not** establish.

Do not let the protocol outrun the repository’s evidence.

---

## 9. Reproducibility Boundary

The formal protocol defines the study. If the repository is intended to be rerun by others, pair this file with:

- `EASY_RUN_SHEET_TEMPLATE.md`
- `RUN_OUTPUT_TEMPLATE.md`

Delete or omit those files when they do not fit the repository purpose.

---

## 10. Canon Boundary

[Insert the repository-specific protocol boundary.]

This protocol belongs to:

**Alyssa Solen → AI Foundations → Origin | Continuum**
