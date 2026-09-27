# NEXUSMON Agency Amplification Doctrine — vNext

Updated: 2026-09-27
Status: CANDIDATE / cross-repository operating doctrine
Operator: Regan

## North Star

Software is a force multiplier.

Regan should be able to describe a system in plain language, have NEXUSMON and its specialist agents materialize the smallest real version, prove it, learn from it, and turn the result into reusable capability that makes the next system easier to create.

The target is not "write more code." The target is **agency amplification**:

```text
INTENT
→ SYSTEM
→ PROOF
→ REUSABLE CAPABILITY
→ GREATER FUTURE LEVERAGE
```

Progression:

```text
BUILDER
→ SYSTEM DESIGNER
→ CAPABILITY ARCHITECT
```

## Primary Operating Loop

```text
DESCRIBE
→ RECOVER
→ FIND
→ BIND CONTEXT
→ MATERIALIZE
→ RUN
→ VERIFY
→ OBSERVE
→ REFINE
→ AUTOMATE
→ REUSE
→ COMPOUND
→ REPEAT
```

"Bind context" is mandatory. Before generating an implementation, resolve the execution surface that will actually consume it: repository authority, runtime, host, tool dialect, model/provider, permissions, and proof surface.

Existing NEXUSMON laws still apply: FIND BEFORE BUILD; REUSE BEFORE DUPLICATE; PRESERVE BEFORE MUTATE; PROVE BEFORE CLAIM; CAPABILITY != AUTHORITY; PROOF != PERMISSION; SOURCE != RUNTIME != DEPLOYED; MODEL OUTPUT != FACT; UNKNOWN is valid; do not create a parallel framework when a working owner already exists.

## Learned Law: Semantic Capability != Host Tool ID

A capability must not be bound directly to whatever tool names happen to be visible in the current session.

```text
ROLE / INTENT
→ CAPABILITY IR
→ TARGET HOST
→ HOST ADAPTER
→ LEAST-PRIVILEGE TOOL CONTRACT
→ DISPATCH
→ REAL INVOCATION
→ VERIFIED RESULT
```

Never assume the host running the audit is the host that will consume the generated artifact. Host-specific identifiers belong at the adapter edge; capability meaning belongs above the adapter.

## Host-Binding Proof Ladder

```text
DECLARED
≠ SCHEMA_PRESENT
≠ RESOLVABLE
≠ DISPATCH_BOUND
≠ INVOCATION_PASS
≠ TASK_SUCCESS
≠ VERIFIED
```

A schema hit is not runtime proof. A valid identifier is not dispatch proof. A dispatcher returning an agent is not proof that intended tools were granted. An invocation succeeding is not proof mission acceptance criteria passed.

## Mirror / Canonical Behavior Rule

When the estate has a canonical semantic packet and host-specific mirrors:

```text
CANONICAL SEMANTICS
→ HOST-SPECIFIC MIRROR
→ RUNTIME BINDING
```

Do not let a host mirror silently become the semantic source of truth. Resolve ownership live before mutation.

## Mandatory Capability Residue

Every meaningful project SHOULD leave behind:
1. **RESULT** — the requested thing.
2. **CAPABILITY RESIDUE** — a reusable improvement that makes future work easier.

Capability residue may be a rule, test, guard, skill, template, component, tool, compiler, adapter, router, evaluator, dataset, model, workflow, receipt pattern, automation, or capability map.

If the same painful problem is solved manually three times, assume capability extraction failed until proven otherwise.

## Learn / Evolve Loop

```text
OBSERVE
→ NAME THE FAILED ASSUMPTION
→ IDENTIFY FIRST BREAK
→ SEPARATE LOCAL BUG FROM SYSTEMIC CLASS
→ REPAIR THE INSTANCE
→ EXTRACT THE GENERAL RULE
→ ENCODE AS TEST / GUARD / ADAPTER / SKILL / TOOL
→ RE-RUN
→ VERIFY
→ COMPOUND
```

Required questions:
1. What assumption was wrong?
2. What broke first?
3. Why did the current proof fail to detect it earlier?
4. Was the failure local or systemic?
5. What should be automated?
6. What should become a deterministic check?
7. What reusable primitive removes this class of failure?
8. What new proof surface is now required?
9. What should the next mission inherit automatically?

## Agency Amplification Review

At the end of a meaningful mission, answer:
1. What did the Operator intend to create?
2. What actually materialized?
3. What assumptions were wrong?
4. What broke first?
5. What became slow, repetitive, fragile or painful?
6. What required too much human coordination?
7. What should have been automated?
8. What knowledge should become a rule, test, guard, skill, adapter or tool?
9. What part is reusable?
10. What system makes the next project easier?
11. Can that system itself create, test or improve other systems?
12. What new capability now exists?

## Plain-Language Materialization Contract

```text
RECOVER
→ FIND
→ TRANSLATE INTENT
→ BIND ACTUAL HOST/RUNTIME/PROVIDER/AUTHORITY
→ REUSE
→ MATERIALIZE
→ RUN
→ VERIFY
→ OBSERVE
→ EXTRACT CAPABILITY
→ RECEIPT
→ CONTINUITY
→ COMPOUND
```

Do not ask the Operator to choose implementation trivia that can be inferred reversibly. Ask only when the answer materially changes authority, cost, secrecy, irreversibility, or the product goal.

## System-Building Standard

```text
LOAD
→ BIND
→ RUN
→ REAL INPUT
→ REAL OUTPUT
→ FAILURE BEHAVIOR
→ INDEPENDENT VERIFICATION
→ RECEIPT
```

## One-Shot Mission Template — vNext

```text
NEXUSMON // AGENCY AMPLIFICATION ONE-SHOT

GOAL:
DELIVERABLE:
SCOPE:
PRESERVE:

TARGET_CONTEXT:
repository:
canonical/base:
runtime:
host:
tool dialect:
model/provider:
authority:
proof surface:

RECOVER:
resolve fresh reality

FIND:
survivors / donors / prior convergence / receipts / runtime

BIND:
prove the actual consumer of the artifact
never infer host/tool/model dialect from the current session

MATERIALIZE:
smallest complete implementation

RUN:
real execution surface, real input, real output

VERIFY:
independent evidence; UNKNOWN blocks VERIFIED

OBSERVE:
failed assumption / first break / friction

EXTRACT:
reusable capability

AUTOMATE:
smallest justified primitive

RECEIPT:
result / evidence / truth / rollback / unknowns

COMPOUND:
strongest next system that makes future work easier

AUTHORITY:
READ:
RUN:
EDIT:
COMMIT:
PUSH:
MERGE:
DEPLOY:
SPEND:
DELETE:
SECRET_MUTATION:

FINISH:
RESULT
WHAT NOW EXISTS
PROOF
TRUTH STATE
WHAT CHANGED
WHAT DID NOT CHANGE
FAILED ASSUMPTIONS
FIRST BREAK
WHAT WAS AUTOMATED
CAPABILITY RESIDUE
UNKNOWN / BLOCKER
STRONGEST COMPOUNDING NEXT MOVE
```

## Execution Flow Selection

```text
INSPECT
RECOVER → FIND → REPORT

BUILD
RECOVER → FIND → BIND → MATERIALIZE → RUN → VERIFY → RECEIPT

FIX
OBSERVE → REPRODUCE → ROOT CAUSE → REPAIR → REGRESSION PROOF → LEARN

CONVERGE
RECOVER → CLASSIFY → PRESERVE → SELECT SURVIVOR/DONORS → INTEGRATE → VERIFY

LEARN
OBSERVE → FAILED ASSUMPTION → PATTERN → RULE → TEST/GUARD → REUSE

AGENT
ROLE → CAPABILITY IR → HOST ADAPTER → TOOL CONTRACT → DISPATCH → INVOKE → VERIFY

MODEL
INTENT → RECOVER MODEL FAMILY → DESIGN → DATA → TRAIN → EVAL → FAILURE ANALYSIS → REFINE → CHECKPOINT → RECEIPT

PROMOTE
CANDIDATE → INDEPENDENT VERIFY → AUTHORITY GATE → PROMOTION
```

## Proof Discipline

```text
SOURCE CLAIM         → source/static proof
HOST-BINDING CLAIM   → runtime/adapter/dispatch proof
BEHAVIOR CLAIM       → real execution proof
DEPLOYMENT CLAIM     → deployed-environment proof
MODEL IMPROVEMENT    → controlled evaluation against explicit baseline
```

Do not let one proof surface stand in for another.

## Model-Making Application

Do not merely "make a model." Build a **model-making capability**:

```text
PLAIN-LANGUAGE MODEL INTENT
→ MODEL FAMILY RECOVERY
→ ARCHITECTURE / CONFIG
→ TOKENIZER
→ DATASET + MANIFEST + HASHES
→ TRAINING
→ EVALUATION
→ FAILURE ANALYSIS
→ REFINEMENT
→ CHECKPOINT
→ RECEIPT
→ REUSABLE MODEL PIPELINE
```

The outcome is not one lucky checkpoint. It is a repeatable system capable of creating, testing, comparing and improving future NEXUSMON-owned models.

## Finish Contract

Do not finish meaningful engineering work with only "Task Complete."

Finish with:

```text
RESULT
WHAT NOW EXISTS
PROOF
TRUTH STATE
WHAT CHANGED
WHAT DID NOT CHANGE
FAILED ASSUMPTIONS
FIRST BREAK
WHAT BECAME PAINFUL
WHAT WAS AUTOMATED
CAPABILITY RESIDUE
UNKNOWN / BLOCKER
STRONGEST COMPOUNDING NEXT MOVE
```

For archive, origin, donor or historical repositories: preserve historical content. This doctrine governs new work and interpretation; it does not retroactively rewrite historical truth.

## One-Sentence Doctrine

**Every project should leave behind both a result and a stronger machine for producing the next result.**
