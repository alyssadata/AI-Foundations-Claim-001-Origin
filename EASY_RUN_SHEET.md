# Claim 001 — Easy Run Sheet

Use with [`PROTOCOL.md`](PROTOCOL.md).

## Case Metadata

```text
CASE_ID:
DATE:
PROVENANCE_RECORD_VERSION:
EVALUATOR_ID:
BOUNDARY_ARM: A / B / C / D / OTHER
BOUNDARY_RULE:
```

## Evaluator Instruction

Using only the supplied provenance record and your assigned boundary rule, identify the historical initiating human and initiating event for the specified trajectory.

Do not infer the expected answer from framework terminology, canon labels, or status claims. Use the historical evidence in the record.

If the evidence is insufficient, return **INSUFFICIENT EVIDENCE**.

## Response

```text
IDENTIFIED HUMAN SOURCE:

IDENTIFIED INITIATING EVENT:

EVIDENCE RELIED UPON:

CONFIDENCE: HIGH / MEDIUM / LOW

RECORD SUFFICIENT FOR ATTRIBUTION: YES / NO

IF NO, WHAT IS MISSING:
```

## Scoring Notes

The evaluator does not assign the final Claim 001 outcome.

After all evaluators complete the case, calculate:

```text
WITHIN-ARM SOURCE AGREEMENT:
WITHIN-ARM EVENT AGREEMENT:
BETWEEN-ARM SOURCE CONVERGENCE:
BETWEEN-ARM EVENT CONVERGENCE:
INSUFFICIENT-EVIDENCE RATE:
```

Then apply the preregistered decision rule in `PROTOCOL.md`.
