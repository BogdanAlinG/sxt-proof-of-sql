# Project instructions — sxt-proof-of-sql

Preserve existing project constraints, secrets, user changes, and required verification/release gates. Inspect relevant source and current scripts before editing.

## Model selection and accepted results

Use the global `route-model-work` skill when available. Its model choices are pilot defaults, not guarantees: **Astra High** for ambiguity, architecture, consequential research or cross-system diagnosis; **Sol High** for substantial implementation with an established approach; **Luna High** (Medium for mechanical work) for bounded changes with reliable checks. Use Max deliberately and prefer Standard speed when supported. Finish tiny tasks directly when handoff would cost more.

Before meaningful work, establish outcome, invariants, permitted scope, unresolved decisions and acceptance checks. After a diagnosed correction, a repeated conceptual failure requires changed evidence, diagnosis or model. Check rendered fidelity as well as technical correctness for visual work.

This policy and the `.codex/agents/model-policy-*.toml` roles do not grant delegation permission or override any existing safety, provider, review or release rule. When delegation is permitted, use at most two concurrent workers, one writer per worktree, and explicit model plus effort. Do not assume a role label or configuration proves which model ran. Hosted chat model selection remains explicit.

For meaningful tasks, add requested/effective settings and evidence (or unavailable), acceptance/checks, correction rounds, measured usage/intervention (or unavailable), and follow-up defects to the existing task/PR record. Count planning, workers, reviews and retries; do not estimate subscription usage from API prices. Keep trivial tasks free of extra paperwork.

### Project-specific routing

Treat proof soundness, cryptographic assumptions, verifier/prover changes, SQL semantics and numerical correctness as strong-model work with specialist review and the repository's tests. Use Luna for bounded documentation or mechanical changes only where verification is objective. Follow CONTRIBUTING.md and current build instructions; do not treat model confidence as cryptographic validation.
