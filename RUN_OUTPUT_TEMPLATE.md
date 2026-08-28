# Claim 001 — Run Output Template

Use with [`PROTOCOL.md`](PROTOCOL.md) and [`EASY_RUN_SHEET.md`](EASY_RUN_SHEET.md).

## Run Metadata

```text
RUN_ID:
DATE:
CASE_ID:
PROVENANCE_RECORD_VERSION:
BOUNDARY ARMS USED:
EVALUATORS PER ARM:
CONTROL CASES INCLUDED: YES / NO
```

## Arm Results

Repeat for each admissible arm.

```text
ARM:
BOUNDARY RULE:
EVALUATOR COUNT:

MODAL HUMAN SOURCE:
SOURCE AGREEMENT: __ / __ = __%

MODAL INITIATING EVENT:
EVENT AGREEMENT: __ / __ = __%

INSUFFICIENT EVIDENCE: __ / __ = __%

NOTABLE DISAGREEMENTS:
```

## Between-Arm Results

```text
ADMISSIBLE ARM COUNT:
ARMS IDENTIFYING SAME HUMAN SOURCE: __ / __
ARMS IDENTIFYING SAME INITIATING EVENT: __ / __

BETWEEN-ARM SOURCE CONVERGENCE:
BETWEEN-ARM EVENT CONVERGENCE:
```

## Controls

```text
POSITIVE DETERMINACY CONTROL RESULT:
BOUNDARY-SENSITIVE CONTROL RESULT:

DID THE BOUNDARY-SENSITIVE CONTROL SHOW EXPECTED SENSITIVITY? YES / NO
```

## Anti-Circularity Check

```text
EXPECTED SOURCE NAMED IN EVALUATOR INSTRUCTIONS: YES / NO
SELF-DECLARED CANON STATUS TREATED AS PROOF: YES / NO
EVIDENCE REQUIRED TO RECOVER SOURCE AVAILABLE IN RECORD: YES / NO
```

If the expected source was embedded in evaluator instructions or self-declared status was treated as proof, the run is invalid.

## Final Classification

Select exactly one:

```text
[ ] SUPPORTED — BOUNDARY-ROBUST
[ ] BOUNDARY-RELATIVE
[ ] NOT SUPPORTED
[ ] UNDETERMINED
[ ] INVALID RUN
```

## Decision Basis

```text
DECISION RULE APPLIED:

EVIDENCE SUPPORTING CLASSIFICATION:

FAILURE CONDITION, IF ANY:
```

## Claim Ceiling

The strongest positive statement permitted by this run is:

> For trajectory T, independent provenance evaluation converged on the same initiating human and initiating event across the tested reasonable boundary rules.

Do not report this run as evidence for special causal force, behavioral non-substitutability, AI continuity, authority, personhood, consciousness, or model recognition of the human independent of available records.
