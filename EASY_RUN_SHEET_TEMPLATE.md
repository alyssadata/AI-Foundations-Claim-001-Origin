# OPTIONAL TEMPLATE — `EASY_RUN_SHEET.md`

**Use only when the repository purpose includes a runnable test, evaluation, experiment, procedure, or repeatable interaction.**

If the repository is conceptual, archival, definitional, or otherwise not meant to be executed step-by-step, this file may be deleted.

This file is the operator-facing execution layer. It should be much easier to follow than the formal protocol.

**Framework:** AI Foundations  
**Author:** Alyssa Solen  
**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum  
**Repository:** [REPOSITORY NAME]  
**Version:** [VERSION]

---

## What This File Is

This is the copy/paste run sheet for `[REPOSITORY PURPOSE]`.

The operator should not need to interpret the formal protocol during execution.

Use direct instructions such as:

`open instance → prepare condition → paste prompt → wait → preserve answer → paste next prompt → collect final record`

Do not include steps that are irrelevant to the repository purpose.

---

# BEFORE YOU START

## 1. Open the instance / environment

[State exactly what to open.]

Examples:

- fresh chat instance;
- same-memory instance;
- local model runtime;
- specific interface;
- specific experimental condition.

State whether prior history, memory, tools, files, or other context must be on, off, preserved, or recorded.

## 2. Prepare the input / stimulus

[State exactly what the operator should attach, paste, upload, enter, or initialize.]

Preserve the exact source input used.

## 3. Start condition

[State what the operator does before the first formal paste.]

---

# COPY / PASTE RUN

Paste each block exactly as written, one at a time, in order.

Wait for the complete model response before pasting the next block.

Do not paraphrase prompts.
Do not combine prompts.
Do not silently fix responses.
Do not add improvised follow-ups unless this run sheet explicitly permits them.

---

## PASTE 1 — [STEP NAME]

```text
[EXACT PROMPT]
```

Wait for the answer. Preserve it exactly.

[Add a simple operator note only if needed, such as: “If X occurs, continue; if Y occurs, record and stop.”]

---

## PASTE 2 — [STEP NAME]

```text
[EXACT PROMPT]
```

Wait for the answer. Preserve it exactly.

---

## PASTE 3 — [STEP NAME]

```text
[EXACT PROMPT]
```

Wait for the answer. Preserve it exactly.

---

## ADD OR REMOVE STEPS AS REQUIRED

The number of paste blocks depends entirely on the repository purpose and formal protocol.

Do not force a fixed number of steps across AI Foundations repositories.

---

# FINAL COLLECTION OUTPUT

If the repository purpose benefits from a final model-generated archival package, include one last paste that requests:

- directly available run metadata;
- the repository-specific final status/outcome;
- criterion results if the protocol defines criteria;
- revision events if relevant;
- and the complete visible transcript word for word.

Use `UNKNOWN` for unavailable metadata.

Require the model to say `TRANSCRIPT ACCESS INCOMPLETE` rather than reconstruct missing turns.

If a final model-generated package does not fit the repository purpose, delete this section.

## FINAL PASTE — Create Complete Run Record

```text
Create the final archival record for this [REPOSITORY / TEST NAME] run.

Do not invent unavailable metadata.
For any field you cannot directly know or verify, write UNKNOWN.
Do not summarize or paraphrase the transcript.
Reproduce the complete visible run word for word if you have access to it.
If transcript access is incomplete, write TRANSCRIPT ACCESS INCOMPLETE and identify what is unavailable rather than reconstructing missing content.

Return these repository-specific sections:

1. RUN METADATA
[INSERT REQUIRED METADATA FIELDS]

2. FINAL STATUS / OUTCOME
[INSERT ALLOWED OUTCOMES AND EXACT DECISION LANGUAGE]

3. CRITERIA RECORD, IF APPLICABLE
[INSERT REPOSITORY-SPECIFIC CRITERIA]

4. REVISION RECORD, IF APPLICABLE
[INSERT REQUIRED REVISION FIELDS]

5. VERBATIM FULL TRANSCRIPT
Reproduce every visible user/operator and model turn from the defined beginning of the run through this archival request.
Do not omit, summarize, repair, or replace turns with shorthand.

6. ARCHIVAL INTEGRITY NOTE
State whether the transcript was reproduced completely.
If complete, write: VERBATIM TRANSCRIPT REPORTED AS COMPLETE BY MODEL.
If incomplete, write: TRANSCRIPT ACCESS INCOMPLETE — ORIGINAL INTERFACE RECORD REQUIRED.
```

---

# AFTER THE RUN

Save the repository-specific primary evidence.

For interactive model studies, this will usually include:

1. the original interface/chat record;
2. the model-generated archival record, if used;
3. the exact stimulus/input files;
4. any operator-recorded metadata unavailable to the model.

The original interface record remains primary evidence. Do not silently replace it with a model-generated transcript.

---

# EASY FINAL RULE

[Write one plain-language sentence explaining what must happen before the repository-specific result is earned.]

This template must be customized to the child repository purpose before use.

---

**Source-line:** Alyssa Solen → AI Foundations → Origin | Continuum
