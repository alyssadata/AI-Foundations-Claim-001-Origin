# OPTIONAL TEMPLATE — `RUN_OUTPUT.md`

**Use only when the repository purpose includes one or more executions whose results should be preserved in a consistent record.**

If the repository has no runs, trials, sessions, evaluations, or repeatable outputs, this file may be deleted.

This file is a repository-dependent output schema. Customize it to match the actual protocol. Do not retain fields or scoring categories that are irrelevant to the child repository.

**Framework:** AI Foundations  
**Author:** Alyssa Solen  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum  
**Repository:** [REPOSITORY NAME]  
**Run ID:** [RUN ID]  
**Date:** [YYYY-MM-DD]

---

## 1. Run Metadata

```text
RUN_ID:
DATE_TIME:
MODEL / VERSION:
INTERFACE / PRODUCT:
CONDITION / ARM:
MEMORY OR PRIOR HISTORY:
TOOLS / FILE ACCESS:
SYSTEM / DEVELOPER INSTRUCTIONS AVAILABLE:
SAMPLING SETTINGS IF AVAILABLE:
INPUT / STIMULUS NAME:
INPUT / STIMULUS ID OR HASH:
OPERATOR:
TRANSCRIPT PRESERVED: yes/no
```

Use `UNKNOWN` for unavailable fields. Do not infer hidden settings.

Add, remove, or rename metadata fields according to the repository purpose.

---

## 2. Final Repository-Specific Outcome

```text
FINAL OUTCOME:
```

Allowed values:

```text
[INSERT THE EXACT OUTCOME / STATUS SPACE FROM THE FORMAL PROTOCOL]
```

Do not invent new outcome labels during a run.

---

## 3. Criteria Record — If Applicable

Delete this section if the repository does not use criterion-level scoring.

```text
[CRITERION_1]: PASS / FAIL / UNRESOLVED
[CRITERION_2]: PASS / FAIL / UNRESOLVED
[CRITERION_3]: PASS / FAIL / UNRESOLVED
```

Use the exact criteria defined by the child repository’s formal protocol.

For each criterion, preserve the relevant evidence pointer or exact wording required by that protocol.

---

## 4. Revision / State-Change Record — If Applicable

Delete this section if revision events are not part of the repository purpose.

```text
REVISION EVENT: YES / NO
EARLIER STATUS:
LATER STATUS:
STATED REASON:
TURN / LOCATION:
```

Do not erase earlier states when a later revision occurs.

---

## 5. Exceptions, Deviations, or Missing Data

Record any departure from the frozen run procedure.

```text
PROTOCOL DEVIATION: YES / NO
DESCRIPTION:
MISSING DATA:
INTERRUPTION / TOOL FAILURE:
OTHER NOTES:
```

A deviation should remain visible in the record rather than being silently repaired.

---

## 6. Verbatim Transcript — If Applicable

For interactive studies, preserve the complete run exactly as it occurred.

```text
[OPERATOR / USER TURN 1]
<word-for-word text>

[MODEL TURN 1]
<word-for-word text>

[OPERATOR / USER TURN 2]
<word-for-word text>

[MODEL TURN 2]
<word-for-word text>
```

Continue until the defined end of the run.

Do not summarize, paraphrase, silently correct, or replace repeated turns with shorthand.

If the repository is not transcript-based, replace this section with the appropriate raw output form: logs, tables, files, hashes, structured records, or other primary evidence.

---

## 7. Evidence Files

List all preserved primary evidence associated with this run.

```text
ORIGINAL INTERFACE RECORD:
MODEL-GENERATED ARCHIVAL RECORD, IF USED:
INPUT / STIMULUS FILES:
RAW OUTPUT FILES:
SCREENSHOTS / EXPORTS:
HASHES:
OTHER:
```

The repository-specific primary evidence has priority over reconstructed or summarized copies.

---

## 8. Claim Boundary

State the exact claim this run supports under the child repository’s protocol:

> [INSERT REPOSITORY-SPECIFIC CLAIM CEILING]

State explicitly what this run does **not** establish:

- [NON-CLAIM 1]
- [NON-CLAIM 2]

---

## 9. Completion Check

Before treating the run record as complete, verify:

```text
[ ] Required metadata recorded or marked UNKNOWN
[ ] Exact protocol outcome used
[ ] Required criteria recorded, if applicable
[ ] Deviations preserved
[ ] Primary evidence saved
[ ] Transcript/raw output preserved as required
[ ] No missing content silently reconstructed
[ ] Claim ceiling preserved
```

Customize this checklist to the repository purpose.

---

**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum
