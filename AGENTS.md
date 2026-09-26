# Project instructions — sxt-proof-of-sql

Preserve existing project constraints, secrets, user changes, and required verification/release gates. Inspect relevant source and current scripts before editing.

## Model selection and accepted results

Keep the existing global/project orchestration, provider-access, ownership, verification and release workflows authoritative. Use `route-model-work` as model-selection advice within those workflows when available; it supplies no delegation permission and does not replace required skills. If an existing model policy differs, reconcile it before applying these pilot choices.

Pilot starting choices: Astra High for ambiguous or consequential decisions and cross-system diagnosis; Sol High for substantial implementation with an established approach; Luna High (Medium for mechanical work) for bounded, objectively checkable changes. Preserve explicit user model/effort choices. Use Max deliberately and prefer Standard when supported. Finish trivial work directly when handoff costs more.

For meaningful work, define outcome, invariants, scope and acceptance checks through the existing workflow. A repeated conceptual failure requires changed evidence, diagnosis or model. Keep brief acceptance, correction and actual usage evidence in the existing task record; label unavailable runtime identity or usage honestly. Do not add mandatory workers, a new orchestration pipeline, or project configuration overrides to implement this advice.

### Project-specific routing

Treat proof soundness, cryptographic assumptions, verifier/prover changes, SQL semantics and numerical correctness as strong-model work with specialist review and the repository's tests. Use Luna for bounded documentation or mechanical changes only where verification is objective. Follow CONTRIBUTING.md and current build instructions; do not treat model confidence as cryptographic validation.
