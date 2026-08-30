<div align="center">

[![Banner](banner.svg)](https://github.com/marcuspat)

**Los Angeles, CA · Agentic Systems Engineer**

[![Rust](https://img.shields.io/badge/-Rust-2b2b2b?style=flat-square&logo=rust&logoColor=dea584)](https://www.rust-lang.org)
[![Python](https://img.shields.io/badge/-Python-2b2b2b?style=flat-square&logo=python&logoColor=3776AB)](https://www.python.org)
[![Shell](https://img.shields.io/badge/-Shell-2b2b2b?style=flat-square&logo=gnubash&logoColor=white)](https://www.gnu.org/software/bash)
[![Kubernetes](https://img.shields.io/badge/-Kubernetes-2b2b2b?style=flat-square&logo=kubernetes&logoColor=326CE5)](https://kubernetes.io)
[![Terraform](https://img.shields.io/badge/-Terraform-2b2b2b?style=flat-square&logo=terraform&logoColor=7B42BC)](https://www.terraform.io)
[![ArgoCD](https://img.shields.io/badge/-ArgoCD-2b2b2b?style=flat-square&logo=argo&logoColor=EF7B4D)](https://argo-cd.readthedocs.io)
[![AWS](https://img.shields.io/badge/-AWS-2b2b2b?style=flat-square&logo=amazonaws&logoColor=FF9900)](https://aws.amazon.com)
[![GCP](https://img.shields.io/badge/-GCP-2b2b2b?style=flat-square&logo=googlecloud&logoColor=4285F4)](https://cloud.google.com)
[![Claude](https://img.shields.io/badge/-Claude-2b2b2b?style=flat-square&logo=anthropic&logoColor=d4a27f)](https://claude.ai)

I build autonomous multi-agent systems that let one engineer ship like a team.

[![Stars](https://img.shields.io/github/stars/marcuspat?style=flat-square&color=2b2b2b&logo=github&logoColor=white&label=Stars)](https://github.com/marcuspat?tab=repositories&sort=stargazers)
[![Crates](https://img.shields.io/badge/Crates.io-Rust_crates-2b2b2b?style=flat-square&logo=rust&logoColor=dea584)](https://crates.io/users/marcuspat)
[![Contributions](https://img.shields.io/badge/Contributions_(1yr)-3.6K%2B-2b2b2b?style=flat-square&logo=github&logoColor=white)](https://github.com/marcuspat)
[![Website](https://img.shields.io/badge/Website-marcuspatman.space-2b2b2b?style=flat-square)](https://marcuspatman.space)

`Autonomous Agent Orchestration` · `Multi-Agent Swarm Coordination` · `Cloud-Native Infrastructure` · `Rust Systems Tooling`

[Turbo-Flow Stack](#the-turbo-flow-stack) · [Developer Tooling](#developer-tooling) · [Rust Crates](#published-rust-crates) · [Technical Reviews](#technical-reviews) · [Organizations](#organizations)

</div>

---

## The Turbo-Flow Stack

| Tool | Stars | Lang | Purpose |
|---|---|---|---|
| [turbo-flow](https://github.com/marcuspat/turbo-flow) | ![](https://img.shields.io/github/stars/marcuspat/turbo-flow?style=flat-square&label=%E2%AD%90) | Shell / Python | Full agentic dev environment — 215+ MCP tools, cross-session memory (Beads), codebase knowledge graph (GitNexus), per-agent git-worktree isolation. One command bootstraps on DevPod, Codespaces, or Rackspace Spot. |
| [turbo-flow-wizard](https://github.com/adventurewave-labs/turbo-flow-wizard) | ![](https://img.shields.io/github/stars/adventurewave-labs/turbo-flow-wizard?style=flat-square&label=%E2%AD%90) | Shell | Guided setup wizard for turbo-flow — interactive generator for project-specific CLAUDE.md configs. 12 app types, 7 methodologies, 19 feature sets. |
| [loopgen](https://github.com/adventurewave-labs/loopgen-rs) | ![](https://img.shields.io/github/stars/adventurewave-labs/loopgen-rs?style=flat-square&label=%E2%AD%90) | Rust | Agentic loops for Claude Code — wizard, TOML configs, bash export, LOOP_STATUS protocol. Published on [crates.io](https://crates.io/crates/loopgen). |
| [tf-verify.sh](https://github.com/marcuspat/turbo-flow/blob/main/devpods/tf-verify.sh) | — | Shell | 50+ quality gates across 12 verification phases — dependency integrity, deployment state, artifact validation, and environment checks. Bundled in turbo-flow `devpods/`. |

### In motion

| [<img src="https://raw.githubusercontent.com/marcuspat/marcuspat/main/demos/turbo-flow-demo.gif" width="420" alt="turbo-flow running the real codespace_setup.sh chain, then a live tmux tour and claude launch">](https://github.com/marcuspat/turbo-flow) | [<img src="https://raw.githubusercontent.com/marcuspat/marcuspat/main/demos/turbo-flow-wizard-demo.gif" width="420" alt="turbo-flow-wizard generating a CLAUDE.pre from a live Q&A session">](https://github.com/adventurewave-labs/turbo-flow-wizard) |
|:---:|:---:|
| *turbo-flow — real install, real tmux workspace, real claude launch* | *turbo-flow-wizard — interactive CLAUDE.md generator* |

| [<img src="https://raw.githubusercontent.com/adventurewave-labs/loopgen-rs/main/demo.gif" width="650" alt="loopgen driving an agentic loop with --dry-run">](https://github.com/adventurewave-labs/loopgen-rs) |
|:---:|
| *loopgen — agentic loops for Claude Code: wizard, TOML, bash export* |

## Developer Tooling

| Tool | Stars | Lang | Purpose |
|---|---|---|---|
| [cargo-forge](https://github.com/marcuspat/cargo-forge) | ![](https://img.shields.io/github/stars/marcuspat/cargo-forge?style=flat-square&label=%E2%AD%90) | Rust | Rust project generator — 7 typed templates: CLI, API server, WebAssembly, game engine, embedded. |
| [netrain](https://github.com/marcuspat/netrain) | ![](https://img.shields.io/github/stars/marcuspat/netrain?style=flat-square&label=%E2%AD%90) | Rust | Matrix-style network packet monitor — real-time DDoS and port-scan detection in the terminal. |
| [Sentinel](https://github.com/marcuspat/Sentinel) | ![](https://img.shields.io/github/stars/marcuspat/Sentinel?style=flat-square&label=%E2%AD%90) | Rust | Safe agentic sysadmin — file operations, process control, network inspection with human-in-the-loop guardrails. |

### In motion

<div align="center">

<a href="https://github.com/marcuspat/netrain"><img src="https://raw.githubusercontent.com/marcuspat/netrain/main/demo.gif" width="650" alt="netrain — live packet log, threat detection, and hex dump in the terminal"></a>

*netrain — live packet monitor with threat detection*

</div>

| [<img src="https://raw.githubusercontent.com/marcuspat/Sentinel/main/demo.gif" width="420" height="412" alt="Sentinel listing capabilities and the deny-by-default policy">](https://github.com/marcuspat/Sentinel) | [<img src="https://raw.githubusercontent.com/marcuspat/cargo-forge/main/demo.gif" width="420" height="412" alt="cargo-forge scaffolding a new Rust project from a typed template">](https://github.com/marcuspat/cargo-forge) |
|:---:|:---:|
| *Sentinel — safe agentic sysadmin* | *cargo-forge — interactive Rust project generator* |

More tooling — `secret-scan`, `codescope`, and the rest of the lab — lives at [adventurewave-labs](https://github.com/adventurewave-labs).

---

### Lab / Demos

Experiments, proofs of concept, and agentic demos.

| Repo | What it explores |
|---|---|
| [agentic-powered-golden-path-demo](https://github.com/adventurewave-labs/agentic-powered-golden-path-demo) | NL → GitOps deployment via golden-path workflows (ArgoCD + OpenRouter) |
| [AI-Kubernetes-API-Generator-Demo](https://github.com/adventurewave-labs/AI-Kubernetes-API-Generator-Demo) | NL → Kubernetes API generation |
| [agentic-devops-extravaganza](https://github.com/adventurewave-labs/agentic-devops-extravaganza) · [live demo](https://agentic-devops-extravaganza.vercel.app/) | Working demo of K8sGPT and Robusta running against a real Kubernetes API + GLM-4.5 LLM |
| [agentic-platform-engineering-extravaganza](https://github.com/adventurewave-labs/agentic-platform-engineering-extravaganza) · [live demo](https://agentic-platform-engineering-extravaganza.vercel.app/) | Golden path + Score → Crossplane + real OPA policy gates + an authz-gated MCP server — 42 policy violations without a platform, 0 with one |
| [aops-sre-pipeline](https://github.com/adventurewave-labs/aops-sre-pipeline) · [live demo](https://aops-sre-pipeline.vercel.app/) | Alert-driven autonomous SRE pipeline — Prometheus → n8n → Popeye → Dify-lite → Ollama → Slack |
| [gitops-progressive-delivery-demo](https://github.com/adventurewave-labs/gitops-progressive-delivery-demo) · [live demo](https://gitops-progressive-delivery-demo.vercel.app/) | Argo CD + Argo Rollouts + Prometheus + K8sGPT progressive delivery — a canary trips an SLO violation, an AI SRE diagnoses it, and the rollout auto-rolls back in ~20s |

---

## Published Rust Crates

7 crates on crates.io — download counts below update automatically.

### Networking & Observability

| Crate | Downloads | Purpose |
|---|---|---|
| [netrain](https://crates.io/crates/netrain) | ![](https://img.shields.io/crates/d/netrain?style=flat-square&label=%E2%86%93) | Matrix-style network packet monitor with IP tracking and threat detection |
| [k8s-netinspect](https://crates.io/crates/k8s-netinspect) | ![](https://img.shields.io/crates/d/k8s-netinspect?style=flat-square&label=%E2%86%93) | Minimal Kubernetes network inspection — CNI and pod connectivity |

### Security & Cryptography

| Crate | Downloads | Purpose |
|---|---|---|
| [cargocrypt](https://crates.io/crates/cargocrypt) | ![](https://img.shields.io/crates/d/cargocrypt?style=flat-square&label=%E2%86%93) | Zero-config cryptographic operations for Rust projects |
| [secretscan](https://crates.io/crates/secretscan) | ![](https://img.shields.io/crates/d/secretscan?style=flat-square&label=%E2%86%93) | Blazing-fast secret scanner for codebases -- AWS keys, GitHub tokens, API secrets |

### Utilities

| Crate | Downloads | Purpose |
|---|---|---|
| [file-hasher](https://crates.io/crates/file-hasher) | ![](https://img.shields.io/crates/d/file-hasher?style=flat-square&label=%E2%86%93) | Fast SHA256 / SHA1 / MD5 file hashing CLI with progress output |
| [cargo-forge](https://crates.io/crates/cargo-forge) | ![](https://img.shields.io/crates/d/cargo-forge?style=flat-square&label=%E2%86%93) | Rust project generator -- 7 typed templates for CLI, API server, WebAssembly, game engine, embedded |

### Agent Tooling

| Crate | Downloads | Purpose |
|---|---|---|
| [loopgen](https://crates.io/crates/loopgen) | ![](https://img.shields.io/crates/d/loopgen?style=flat-square&label=%E2%86%93) | Agentic loops for Claude Code — wizard, TOML configs, bash export, LOOP_STATUS protocol |

---

## Technical Reviews

Technical reviewer for [Packt Publishing](https://www.packtpub.com) since 2021 — six titles, two credited in print. Most recent: *Operational AI with Docker* (2026), *Microsoft Foundry in Action* (2026), and *Claude Beyond the Prompt* (Oct 2026, credited).

Full list → [packt-technical-reviews](https://marcuspat.github.io/packt-technical-reviews/)

---

## Organizations

| Org | Focus |
|---|---|
| [adventurewave-labs](https://github.com/adventurewave-labs) | Open-source developer tooling for the Claude and agentic AI ecosystem — the lab behind turbo-flow |
| [creandotumatrix-labs](https://github.com/creandotumatrix-labs) | Agentic AI engineering and cloud-native solutions for Latin America |

---

`Rust` · `Python` · `Shell` · `Kubernetes` · `Terraform` · `ArgoCD` · `AWS` · `GCP` · `Azure` · `Claude Code` · `SPARC`

📧 marcus@adventureonthewave.com · [LinkedIn](https://linkedin.com/in/marcuspatman) · [marcuspatman.space](https://marcuspatman.space) · [X @marcuspat](https://x.com/marcuspat) · [YouTube @marcuspatmanagentics](https://youtube.com/@marcuspatmanagentics)
