<a href="https://www.sparkeefy.com/">
  <img src="./assets/sparkeefy-banner.jpeg" width="100%" alt="Sparkeefy banner showing two hands reaching toward a glowing heart.">
</a>

<picture>
  <source media="(max-width: 600px)" srcset="./assets/founder-system-mobile.svg">
  <img src="./assets/founder-system.svg" width="100%" alt="Sarthak Verma's founder system panel with Sparkeefy, founder details, technology and contact information.">
</picture>

## Core Systems & Engineering Architecture

High-performance AI infrastructure, GPU compiler design, temporal memory benchmarks, and distributed systems written in Python, C/Metal, and Go:

- **[LongArc](https://github.com/vermasarthak/longarc)** — Open, reproducible benchmark for temporal memory, privacy boundaries, and safe proactivity in long-horizon AI agents. 1,200 synthetic scored queries across 15 task families. 33/33 unit & property tests green.
- **[Cairn](https://github.com/vermasarthak/cairn)** — Durable, policy-aware delivery runtime with transactional reservations, outbox persistence, worker lease fencing, and simulated CDC reconciliation in Go. Full unit & outbox test suite green.
- **[TileForge](https://github.com/vermasarthak/tileforge)** — Native Metal GPU Tensor Compiler. Translates high-level SSA IR into C++ Metal Shading Language (MSL) with threadgroup shared-memory tiling, SIMD barriers, and semantics-preserving optimization passes. 71/71 tests green.
- **[Oriel](https://github.com/vermasarthak/oriel)** — Evaluation-driven model router & benchmark suite. Employs Thompson sampling over Beta posteriors, request hedging, and Wilson score confidence bounds to dynamically route traffic under latency/cost constraints. 54/54 unit tests green.
- **[Recall](https://github.com/vermasarthak/recall)** — Bitemporal entity and fact memory engine for long-horizon agents. Combines point-in-time state reconstruction, half-open validity intervals, and concurrency stress testing. 32/32 unit tests green.
- **[PagedServe](https://github.com/vermasarthak/pagedserve)** — High-throughput LLM inference systems reference featuring block-based PagedAttention KV-cache management, continuous batching, prefix caching, and speculative verification. 290/290 unit tests green.

---

### Verification & CI Quality Matrix

| Repository | Domain | Core Tech | Test Suite Status | CI Workflow |
| :--- | :--- | :--- | :--- | :--- |
| **[LongArc](https://github.com/vermasarthak/longarc)** | Temporal Agent Benchmark | Python 3.11+ / Pydantic / DuckDB | ✅ 33/33 Passed | GitHub Actions |
| **[Cairn](https://github.com/vermasarthak/cairn)** | Transactional Outbox & Delivery | Go / PostgreSQL | ✅ Passed | GitHub Actions |
| **[TileForge](https://github.com/vermasarthak/tileforge)** | GPU Compiler & IR | C++ Metal MSL / Python SSA | ✅ 71/71 Passed | GitHub Actions |
| **[Oriel](https://github.com/vermasarthak/oriel)** | Model Router & Evals | Thompson Sampling / FastAPI | ✅ 54/54 Passed | GitHub Actions |
| **[Recall](https://github.com/vermasarthak/recall)** | Bitemporal Memory Engine | FastAPI / SQLite WAL / Pydantic | ✅ 32/32 Passed | GitHub Actions |
| **[PagedServe](https://github.com/vermasarthak/pagedserve)** | LLM Inference & KV Cache | PagedAttention / PyTorch | ✅ 290/290 Passed | GitHub Actions |

---

<p>
  <a href="mailto:sarthakverma0802@gmail.com"><img src="./assets/contact-email.svg" width="32" height="32" alt="Email Sarthak"></a>&nbsp;&nbsp;&nbsp;
  <a href="https://www.linkedin.com/in/sarthakvermaa/"><img src="./assets/contact-linkedin.svg" width="32" height="32" alt="Sarthak on LinkedIn"></a>&nbsp;&nbsp;&nbsp;
  <a href="https://www.instagram.com/sarthk_._/"><img src="./assets/contact-instagram.svg" width="32" height="32" alt="Sarthak on Instagram"></a>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/vermasarthak/vermasarthak/output/github-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/vermasarthak/vermasarthak/output/github-snake.svg" width="100%" alt="Sarthak's GitHub contribution graph animated as a snake.">
</picture>
