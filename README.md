## Bao Trinh — Trinh Ngoc Quoc Bao

**I build security for AI and money systems — running controls, not policy documents.**

15+ years on correctness-critical systems: the core of a Dubai crypto exchange (deterministic matching, atomic settlement, in-house MPC custody), core banking and payments before that, and now the same discipline turned on AI agents that act on money. MSc in formal verification (JAIST, lab of Prof. Kokichi Futatsugi) — I design from invariants: state what must hold for all inputs, then build so violations are detectable, attributable and replayable.

**[cause-justified-change-monitoring](https://github.com/baotnq/cause-justified-change-monitoring)** — a runtime-verification pattern for money-like state: *every observed change must have an authorized cause*. Exact set difference over compact bit vectors, fed by a change feed the application cannot influence — detection in 1–3 minutes, subscribe-only, zero critical-path impact. Generalizes unchanged to AI agents: tool-call effects reconciled against approved plans.

**Paper** — D. Daudier, **T. Ngoc Quoc Bao**, K. Ogata. *A Proof Score Approach to Formal Verification of an Imperative Programming Language Compiler.* Springer **LNCS 10795**, SOFL+MSVL 2017, pp. 200–217 — [doi:10.1007/978-3-319-90104-6_13](https://doi.org/10.1007/978-3-319-90104-6_13). Builds on my MSc thesis and completes the correctness proof for all terminating programs.

**Independent R&D** — a zero-trust access platform where non-human actors (CI, scripts, AI agents) are first-class identities: no credential is minted without a traceable human authorization (fail-closed), 15-minute just-in-time grants, hash-chained signed ledger of every mint. Cross-platform Rust, reproducible Cosign-signed builds, in production.

**Working with:** Go · Rust · C++ · PostgreSQL · Redis · Kafka / NATS · gRPC · Kubernetes · runtime verification · MPC & threshold signing

Dubai, UAE · [LinkedIn](https://www.linkedin.com/in/bao-trinh-ngoc-quoc) · quocbao.tn@icloud.com
