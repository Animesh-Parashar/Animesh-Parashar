# Animesh Parashar

**Systems & infrastructure engineer** working on reliability tooling,
distributed systems, policy enforcement, and agentic AI.

Engineering Physics at **IIT (ISM) Dhanbad**. I like systems that make failure
observable, enforce safety at the protocol boundary, and are backed by
reproducible evidence.

[Portfolio](https://software-portfolio-gamma.vercel.app/) ·
[LinkedIn](https://www.linkedin.com/in/animesh-parashar-378659320/) ·
[Email](mailto:animeshparashar3439@gmail.com) ·
[X](https://x.com/Animesh6488141)

## What I'm working on

- Building [Podman CI flake detection and analysis](https://github.com/Animesh-Parashar/podman-flake-analysis):
  a standard-library Python pipeline that extracts TAP outcomes from real CI
  artifacts, detects cross-run flips, groups failure signatures, and applies
  contamination checks before ranking flaky tests.
- Contributing to cloud-native projects. Most recently, I landed a
  [Podman build-system fix](https://github.com/podman-container-tools/podman/pull/29357)
  and opened a [Jaeger UI compatibility fix](https://github.com/jaegertracing/jaeger-ui/pull/4341)
  for Node.js 25+.
- Exploring policy engines and protocol-level guardrails for autonomous
  software: deny-by-default evaluation, scoped permissions, rate limits, and
  kill switches.

## Selected projects

| Project | What it does | Stack |
| --- | --- | --- |
| [podman-flake-analysis](https://github.com/Animesh-Parashar/podman-flake-analysis) | Detects, groups, and categorizes flaky Podman CI tests from real GitHub Actions data, with reproducible sampling and bias checks. | Python, GitHub Actions API |
| [Aegis Protocol](https://github.com/Animesh-Parashar/Aegis-Protocol) | Intercepts agent-initiated transactions and enforces declarative spend caps, allowlists, rate limits, and emergency stops before signing. | TypeScript, Solidity, React, Valkey |
| [EchoTip](https://github.com/Animesh-Parashar/echotip) | Resolves ENS profiles and lets users leave public on-chain tips and messages through a tested Sepolia contract. | Next.js, TypeScript, Solidity, Foundry |
| [WolfAlpha](https://github.com/Animesh-Parashar/WolfAlpha) | Generates, backtests, and iteratively refines quantitative strategies using an LLM-driven evaluation loop. | Python, Gemini API, WorldQuant BRAIN |
| [Wallet Risk Scoring](https://github.com/Animesh-Parashar/Wallet-Risk_Scoring) | Extracts behavioral features from Ethereum activity and serves real-time risk predictions through an API. | Python, Flask |

Also built protocol infrastructure for agent commerce and cross-chain
settlement: [Econos](https://github.com/Animesh-Parashar/Econos),
[x402-gateway](https://github.com/Animesh-Parashar/x402-gateway),
[x402-nexus](https://github.com/Animesh-Parashar/x402-nexus), and
[MergeFi](https://github.com/Animesh-Parashar/MergeFi) — 3rd place in the
ETHGlobal ETHOnline 2025 Avail Nexus track.

## Open source

- **[Podman](https://github.com/podman-container-tools/podman)** —
  [#29357](https://github.com/podman-container-tools/podman/pull/29357), merged:
  fixed the local unit-test target by building Ginkgo before invocation.
- **[Apache RocketMQ Rust](https://github.com/mxsm/rocketmq-rust)** — four
  merged PRs in producer and tracing code:
  [#5204](https://github.com/mxsm/rocketmq-rust/pull/5204),
  [#5185](https://github.com/mxsm/rocketmq-rust/pull/5185),
  [#5160](https://github.com/mxsm/rocketmq-rust/pull/5160), and
  [#5159](https://github.com/mxsm/rocketmq-rust/pull/5159).
  Added explicit uninitialized-producer errors and removed unnecessary clones
  by returning borrowed references.
- **Ethereum ecosystem** —
  [forkcast #103](https://github.com/ethereum/forkcast/pull/103), merged:
  fixed anchor navigation for EIPs inside collapsed sections;
  [protocol-studies #470](https://github.com/eth-protocol-fellows/protocol-studies/pull/470)
  and [#468](https://github.com/eth-protocol-fellows/protocol-studies/pull/468),
  merged: repaired broken JSON-RPC and consensus documentation links.
- **[Basis-Zero](https://github.com/Ranish-Garg/Basis-Zero)** — 20 merged PRs
  spanning Circle CCTP bridging, Yellow state-channel sessions, AMM flows, and
  vault workflows.

**40+ merged pull requests** across upstream projects and collaborative
codebases.

## Research

### [Self-Supervised Anomaly Detection on Real LHC Data](https://github.com/Animesh-Parashar/aspen-jet-anomaly)

Co-authored a [DOI-backed preprint](https://doi.org/10.5281/zenodo.20827792)
applying contrastive self-supervised learning to approximately 178 million real
CMS jet constituents from LHC Open Data. The system uses a transformer encoder,
an NT-Xent objective, and physics-informed augmentations for model-agnostic
anomaly detection.

## Toolbox

- **Languages:** Python, Rust, TypeScript, JavaScript, Solidity, Go, C++
- **Systems & data:** Docker, Linux, GitHub Actions, PostgreSQL, MongoDB,
  Qdrant, Valkey
- **Application:** Node.js, React, Next.js, Flask, Foundry

<p align="center">
  <img src="https://github.com/Animesh-Parashar/Animesh-Parashar/blob/output/github-contribution-grid-snake-dark.svg" alt="GitHub contribution graph" />
</p>
