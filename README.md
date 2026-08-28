# Bao Trinh — Trinh Ngoc Quoc Bao

**Architect who builds — and secures what he builds: what an agent may do, what a model may know. Running controls, not policy documents.**

I design systems from invariants — state what must hold, then build so violations are detectable, attributable and replayable. Proved it on a compiler (Springer/LNCS below), ran it on live money in the core of a Dubai crypto exchange (deterministic matching, atomic settlement, in-house MPC custody; core banking and payments before that), now applying it to AI — the agents that act on money, and the knowledge they act from. MSc in formal verification (JAIST, lab of Prof. Kokichi Futatsugi).

**[cause-justified-change-monitoring](https://github.com/baotnq/cause-justified-change-monitoring)** — a runtime-verification pattern for money-like state: *every observed change must have an authorized cause*. Exact set difference over compact bit vectors, fed by a change feed the application cannot influence — detection in 1–3 minutes, subscribe-only, zero critical-path impact. Generalizes unchanged to AI agents: tool-call effects reconciled against approved plans.

**[t-knowledge-system](https://github.com/baotnq/t-knowledge-system)** — the same rule applied to knowledge instead of state: *a claim becomes knowledge only with a basis and a named owner*. A basis is a committed principle, a sourced fact, or a derivation the owner can rebuild on the spot; records are append-only; stale claims are demoted, never deleted. Closes the gap that data, model and infrastructure sovereignty leave open.

**[operational-friction](https://github.com/baotnq/operational-friction)** — why the workaround is the vulnerability: Bybit, Ronin, MasterChef read as friction chains. Dependency and trust-boundary inventory fails where nobody wrote the dependency down.

**[easywebhub/tasks](https://github.com/easywebhub/tasks)** — the same discipline on people, published 2016: work-item-based communication, two roles with mutual obligations, estimates owned by the assignee and trade-offs decided by the requester — no silent moves. These rules ran my teams a decade before they governed AI agents. (Vietnamese; English summary at top.)

Verify the effect. Verify the operator. Verify the knowledge. One rule, three objects — and it started with how a team works.

**Paper** — D. Daudier, **T. Ngoc Quoc Bao**, K. Ogata. *A Proof Score Approach to Formal Verification of an Imperative Programming Language Compiler.* Springer **LNCS 10795**, SOFL+MSVL 2017, pp. 200–217 — [doi:10.1007/978-3-319-90104-6_13](https://doi.org/10.1007/978-3-319-90104-6_13). Builds on my MSc thesis and completes the correctness proof for all terminating programs.

**Independent R&D** — a zero-trust access platform where non-human actors (CI, scripts, AI agents) are first-class identities: no credential is minted without a traceable human authorization (fail-closed), 15-minute just-in-time grants, hash-chained signed ledger of every mint. Cross-platform Rust, reproducible Cosign-signed builds, in production.

**Working with:** Go · Rust · C++ · PostgreSQL · Redis · Kafka / NATS · gRPC · Kubernetes · runtime verification · MPC & threshold signing

Dubai, UAE · [LinkedIn](https://linkedin.com/in/bao-trinh-ngoc-quoc) · quocbao.tn@icloud.com
