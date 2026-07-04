# Vishesh Rawal

I write Go and Rust for things that need to be fast.
I write Python when I need it done by Tuesday.
I've been wrong about architecture exactly as many times as I've been right.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/visheshrawal)
[![Website](https://img.shields.io/badge/visheshrawal.in-000000?logo=google-chrome&logoColor=white)](https://visheshrawal.in)
[![npm](https://img.shields.io/badge/npm-%40blackvult%2Fdevkit-CB3837?logo=npm&logoColor=white)](https://www.npmjs.com/package/@blackvult/devkit)
[![X](https://img.shields.io/badge/X-%23000000.svg?logo=X&logoColor=white)](https://x.com/visheshrawal_in)

---

### What I'm currently working on

- Leading a **Django to Go strangler-fig migration** on AWS EKS at [Repos Energy](https://repos.energy). Still in flight. The pprof graphs are beautiful.
- Building **[Blackvult](https://blackvult.org)** — starting with [`@blackvult/devkit`](https://npmjs.com/package/@blackvult/devkit), an MCP server toolkit. Long game.
- Writing *The Backend Dispatch* — a technical series I keep telling myself I'll finish.

---

### Things I find genuinely interesting

**Heap profiling.** Most people look at CPU. The allocator tells you more.

**Strangler-fig migrations.** Incrementally replacing a monolith in production without a rewrite big bang is harder than it sounds and more satisfying than it should be.

**Logical replication in PostgreSQL.** Underused. Wildly powerful for pre-prod isolation and CDC.

**When ClickHouse is the right answer** — and more often, when it isn't.

**The gap between "observable" and "actually understood in production."** Prometheus tells you a service is slow. It doesn't tell you why. Closing that gap — with structured logs, traces, and pprof — is where the real work is.

**Building observability from zero.** Standing up Prometheus + Grafana + Loki from scratch, wiring up alerting, and then watching it catch something in production before a user does. That feedback loop never gets old.

---

### Things I've contributed to

- **[google-deepmind/open_spiel](https://github.com/google-deepmind/open_spiel)** — PR #1426. Windows `pip install` support. Small fix, took longer than expected, ships in the 2.0 blog post. Marc Lanctot was kind enough to call it out.
- **[idempotent.dev](https://idempotent.dev)** — Go microservice. Idempotency-as-a-service for HTTP APIs. Upstash Redis backend. Live.
- **Prometheus + Grafana + Loki observability stack** — built end-to-end at Repos Energy. The heap reduction story came out of this: found a ~61% allocation problem that nobody knew existed until the dashboards said otherwise.
- **97 articles** on [visheshrawal.in](https://visheshrawal.in). Written because I got tired of re-explaining the same things in PRs.
- **IEEE Xplore** — one paper. Zero-Trust in distributed API infrastructure. Written during my final year, holds up reasonably well.

---

### Stack I actually use

```
Daily          Go, Python, TypeScript
Occasionally   Rust, C, C++
Databases      PostgreSQL (primary), Redis, ClickHouse, Kafka/MSK
Infra          AWS EKS, Docker, Kubernetes
Observability  Prometheus, Grafana, Loki, pprof, OpenTelemetry
```

---

### How I think about this

I don't think the goal is to write clever code. The goal is to write code that a tired engineer at 2am during an incident can read, understand, and fix without calling you. Everything else is secondary.

I've been on both ends of that 2am call.

---

<details>
<summary>GitHub activity</summary>

![GitHub Stats](https://github-readme-stats-eight-theta.vercel.app/api?username=visheshrwl&show_icons=true&theme=solarized-dark&include_all_commits=true&count_private=true)

![Top Languages](https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=visheshrwl&layout=compact&langs_count=8&theme=solarized-dark)

![Profile Summary](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=visheshrwl&theme=solarized_dark)

</details>

---

[vishesh.rawal@proton.me](mailto:vishesh.rawal@proton.me)
