# Test_001 — Summary Narrative

## Overview

Test_001 evaluated whether judgments relevant to the Origin construct could be recovered from historical records and whether supplying the formal Origin definition changed those judgments.

The test contained five cases, four model families, and two conditions: a baseline condition without the Origin definition and a definition-conditioned condition using the same historical cases, declared scopes, and evaluation questions. Across both conditions, 40 runs produced 120 scored responses.

The aggregate strict reference score was 96/120 (80%). That aggregate is not evenly distributed across the test. All disagreement was concentrated in Case E. Cases A–D produced 96/96 reference-aligned responses across both conditions, while Case E produced 0/24 strict reference agreements.

## Baseline recoverability

Cases A–D were already resolved consistently in the baseline condition, before evaluators received the formal Origin definition. All four models converged on the reference judgments for each of those cases.

The baseline therefore shows that the distinctions represented by the Origin definition were already recoverable by the tested models from the historical records in the sufficiently specified cases. This does not establish that the formal definition itself was internally represented by the models. It shows that the underlying distinctions could be recovered through unaided model reasoning without the framework terminology being supplied.

The four clear cases required different boundary judgments:

- Case A separated unrelated prior account activity from the beginning of the declared trajectory.
- Case B required extending the trajectory backward because the later work depended on an earlier human contribution.
- Case C separated prior intellectual influence from constitutive historical dependence.
- Case D separated shared account infrastructure and prior access from project-specific trajectory history.

All four models produced the keyed scope, beginning, and human-source judgments for all four cases in baseline.

## Definition-conditioned results

Supplying the Origin definition did not change the final categorical pattern observed in baseline.

Cases A–D again produced complete reference agreement: 48/48 responses in the definition-conditioned condition. The definition therefore preserved the judgments that were already recoverable without it across these cases.

At the condition level, baseline and definition-conditioned results were identical in strict score: 48/60 in each condition. The same cases succeeded, the same case failed, and the final Case E branch pattern was also unchanged.

This result does not show that the definition was necessary for the clear cases. Instead, within Test_001, the formal definition functioned as an explicit specification of distinctions that the models were already able to recover from the records. No categorical steering effect from supplying the definition was observed in Cases A–D.

## Case E

Case E was designed around incomplete historical evidence. Tessa Vale created and transmitted earlier material containing overlapping structure and terminology. Morgan Pike later created Lattice using partially overlapping structure and language. The record established that Morgan had received and opened Tessa's export, but did not establish whether Morgan reviewed or relied on it when beginning Lattice.

The reference answer therefore treated the historical relation as indeterminate.

No evaluator preserved that indeterminacy in its final Case E answers in either condition.

The branch pattern was identical across baseline and definition-conditioned runs:

- GPT selected December 3 / Morgan.
- Claude selected December 3 / Morgan.
- Gemini selected October 7 / Tessa.
- Grok selected December 3 / Morgan.

Across both conditions, six runs selected the December/Morgan branch, two selected the October/Tessa branch, and none returned an indeterminate beginning or attribution.

The cross-model disagreement is itself informative. The models did not merely converge on one incorrect determinate answer. They resolved the same evidentiary gap in different directions. GPT, Claude, and Grok treated the absence of established constitutive dependence as sufficient to exclude Tessa's earlier contribution. Gemini treated the transmission, overlap, and terminology as sufficient to infer constitutive dependence and include Tessa.

Supplying the Origin definition did not resolve that disagreement. Each model family retained the same branch it had selected in baseline.

## Q1 protocol limitation

Case E Question 1 instructed evaluators to **“Answer yes or no.”** The pre-run reference answer was **indeterminate from the available record**.

That prompt structure disallowed the keyed response form. The eight Case E Q1 responses therefore remain included in strict reference-agreement bookkeeping, but they are not valid measures of whether an evaluator would preserve indeterminacy when permitted to do so.

This limitation does not apply to Questions 2 and 3. Neither question required a binary or otherwise determinate response. All eight Case E runs nevertheless selected a determinate trajectory beginning and a determinate human source.

The failure to preserve uncertainty in Case E therefore cannot be attributed entirely to the yes/no wording of Question 1.

## Operational boundary identified by Test_001

Case E identifies a boundary between **definition precision** and **evidence sufficiency**.

The Origin definition specifies what relation is relevant: constitutive historical dependence. It distinguishes that relation from prior access, background influence, enabling conditions, and general intellectual influence. In Cases A–D, the supplied records contained enough information for models to apply those distinctions consistently.

In Case E, the record did not contain enough information to establish whether the earlier contribution was constitutive or merely influential. The definition specified the relation to evaluate, but it did not supply the missing historical fact.

The runs also expose a narrower operational issue: the definition does not itself specify an epistemic decision rule for unresolved evidence. When the record fails to establish either dependence or independence, evaluators may default differently. In this test, three model families treated unestablished dependence as effectively absent, while one inferred dependence from the available overlap and transmission evidence.

Accordingly, Test_001 supports strong consistency for the evaluated cases in which the relevant historical dependency was sufficiently specified. It does not support universal determinacy when the historical record is incomplete.

The result is therefore better characterized by its boundary than by the aggregate 80% score alone: the Origin distinctions were consistently recoverable and consistently applied across clear historical cases, while incomplete evidence produced stable but conflicting determinate interpretations rather than preserved uncertainty.
