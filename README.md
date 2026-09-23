<a href="https://www.sparkeefy.com/">
  <img src="./assets/sparkeefy-banner.jpeg" width="100%" alt="Sparkeefy banner showing two hands reaching toward a glowing heart.">
</a>

<picture>
  <source media="(max-width: 600px)" srcset="./assets/founder-system-mobile.svg">
  <img src="./assets/founder-system.svg" width="100%" alt="Sarthak Verma's founder system panel with Sparkeefy, founder details, technology and contact information.">
</picture>

## Core Systems & Engineering Architecture

High-performance AI infrastructure, GPU compiler design, durable execution, and distributed systems written in Python, C/Metal, and Go:

- **[Cairn](https://github.com/vermasarthak/cairn)** — High-throughput transactional outbox & reservation engine in Go. Guarantees atomic event publishing, worker lease fencing, and distributed job scheduling against PostgreSQL/Redis. 100% test coverage.
- **[Relay](https://github.com/vermasarthak/relay)** — Deterministic human-in-the-loop orchestration runtime. Provides state-machine approval routing, SLA escalation timers, tenant RBAC, and replayable execution. 14/14 unit tests green.
- **[Recall](https://github.com/vermasarthak/recall)** — Temporal entity memory engine for long-horizon agents. Combines bidirectional temporal knowledge graphs, exponential recency decay, and WebSocket streaming. 31/31 unit tests green.
- **[TileForge](https://github.com/vermasarthak/tileforge)** — Native Metal GPU Tensor Compiler. Translates high-level SSA IR into C++ Metal Shading Language (MSL) with threadgroup shared-memory tiling (`threadgroup float tileA[16][16]`), SIMD barriers, and SSA optimization passes. 67/67 unit tests green, verified hardware execution on Apple Silicon.
- **[PagedServe](https://github.com/vermasarthak/pagedserve)** — High-throughput LLM inference runtime featuring block-based PagedAttention KV-cache management, continuous batching, prefix caching, and speculative decoding. 290/290 unit tests green.
- **[Oriel](https://github.com/vermasarthak/oriel)** — Evaluation-driven model router & benchmark suite. Employs contextual Thompson sampling, request hedging, and Wilson score confidence bounds to dynamically route traffic across LLM endpoints under latency/cost constraints. 52/52 unit tests green.
- **[Anvil](https://github.com/vermasarthak/anvil)** — Isolated execution engine & agent workspace with gVisor sandbox integration, LSP protocol client, and session state persistence. 13/13 unit tests green.

---

### Verification & CI Quality Matrix

| Repository | Domain | Core Tech | Test Suite Status | CI Workflow |
| :--- | :--- | :--- | :--- | :--- |
| **[Cairn](https://github.com/vermasarthak/cairn)** | Transactional Outbox | Go 1.22 / PostgreSQL | ✅ 100% Passed | GitHub Actions |
| **[Relay](https://github.com/vermasarthak/relay)** | Human-in-the-Loop Orchestration | FastAPI / SQLite / Alembic | ✅ 14/14 Passed | GitHub Actions |
| **[Recall](https://github.com/vermasarthak/recall)** | Temporal Memory Engine | FastAPI / SQLite WAL / Pydantic | ✅ 31/31 Passed | GitHub Actions |
| **[TileForge](https://github.com/vermasarthak/tileforge)** | GPU Compiler & IR | C++ Metal MSL / Python SSA | ✅ 67/67 Passed | GitHub Actions |
| **[PagedServe](https://github.com/vermasarthak/pagedserve)** | LLM Inference & KV Cache | PagedAttention / PyTorch | ✅ 290/290 Passed | GitHub Actions |
| **[Oriel](https://github.com/vermasarthak/oriel)** | Model Router & Evals | Thompson Sampling / FastAPI | ✅ 52/52 Passed | GitHub Actions |
| **[Anvil](https://github.com/vermasarthak/anvil)** | Agent Execution & LSP | gVisor / SQLite / Python | ✅ 13/13 Passed | GitHub Actions |

---

<table width="100%">
  <tr>
    <td valign="middle">
      <a href="mailto:sarthakverma0802@gmail.com"><img src="./assets/contact-email.svg" width="32" height="32" alt="Email Sarthak"></a>&nbsp;&nbsp;&nbsp;
      <a href="https://www.linkedin.com/in/sarthakvermaa/"><img src="./assets/contact-linkedin.svg" width="32" height="32" alt="Sarthak on LinkedIn"></a>&nbsp;&nbsp;&nbsp;
      <a href="https://www.instagram.com/sarthk_._/"><img src="./assets/contact-instagram.svg" width="32" height="32" alt="Sarthak on Instagram"></a>
    </td>
    <td align="right" valign="middle">
      <img src="https://komarev.com/ghpvc/?username=vermasarthak&amp;color=b58cff&amp;style=flat-square&amp;label=profile%20views" alt="Profile views">
    </td>
  </tr>
</table>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/vermasarthak/vermasarthak/output/github-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/vermasarthak/vermasarthak/output/github-snake.svg" width="100%" alt="Sarthak's GitHub contribution graph animated as a snake.">
</picture>
