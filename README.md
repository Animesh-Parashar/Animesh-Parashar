
- 🛠️ **Systems & infrastructure engineer**: distributed messaging, policy
  enforcement layers, and agentic AI pipelines.
- 📦 Upstream contributor to **Apache RocketMQ (Rust)**: 4 merged PRs in the
  producer and tracing subsystems.
- 🧩 Build **policy engines**: request interception, declarative rule
  evaluation, deny-by-default enforcement, kill switches.
- 🤖 Build **agentic AI systems**: retrieval pipelines over vector stores,
  automated hyperparameter search, LLM-driven generate-and-evaluate loops.
- 🔬 Co-author of a DOI-backed preprint on **self-supervised anomaly detection**
  applied to ~178M real CMS jet constituents (LHC Open Data).
- 🎯 Engineering philosophy: *behavior should be constrained at the protocol
  level, not left to user trust or UI warnings.*
- 🚀 Currently learning **Go** and **Kubernetes**, with the goal of contributing
  to cloud native infrastructure projects.

## Open Source Contributions

**[mxsm/rocketmq-rust](https://github.com/mxsm/rocketmq-rust)**: Rust
implementation of Apache RocketMQ, a distributed messaging and streaming platform.

- [#5204](https://github.com/mxsm/rocketmq-rust/pull/5204): Surfaced explicit
  errors on the `send_by_accumulator` path when the producer is uninitialized,
  replacing a silent-failure path.
- [#5185](https://github.com/mxsm/rocketmq-rust/pull/5185): Same class of fix
  on `send_direct`; made uninitialized-producer state an explicit error rather
  than undefined behavior.
- [#5160](https://github.com/mxsm/rocketmq-rust/pull/5160): Changed the
  `produce_accumulator` getter to return a borrowed reference instead of an
  owned clone, removing an allocation from a hot path.
- [#5159](https://github.com/mxsm/rocketmq-rust/pull/5159): Same borrow-vs-clone
  fix applied to `trace_dispatcher`.

**Ethereum org repositories**: [forkcast
#101](https://github.com/ethereum/forkcast/pull/101),
[#103](https://github.com/ethereum/forkcast/pull/103) ·
[kohaku #28](https://github.com/ethereum/kohaku/pull/28) ·
[protocol-studies #470](https://github.com/eth-protocol-fellows/protocol-studies/pull/470),
[#468](https://github.com/eth-protocol-fellows/protocol-studies/pull/468)

**40+ merged PRs** across upstream projects and collaborative codebases.


## Selected Projects

**[Aegis Protocol](https://github.com/Animesh-Parashar/Aegis-Protocol)**:
*Admission control for autonomous AI agents.*
A middleware enforcement layer that intercepts agent-initiated transactions
before execution, evaluates each request against a declarative policy store
(per-agent spend caps, allowlisted targets, rate limits), and denies by default.
Agents submit structured intent requests and never hold signing keys, a signer
proxy materializes the request only after every policy check passes. Includes an
instant kill switch, a real-time observability dashboard, and a chaos simulator
that adversarially fuzzes the policy engine with synthetic malicious behavior.
Enforcement layer in Node.js/TypeScript; policy store implemented as on-chain
contracts.

**[AlphaRag / WolfAlpha](https://github.com/Animesh-Parashar/WolfAlpha)**:
*Agentic retrieval pipeline for automated strategy generation.*
Python service that proposes, backtests, and iteratively refines quantitative
strategies. RAG over a Qdrant vector store, Optuna-driven hyperparameter search,
Gemini API in the generate-and-evaluate loop, containerized with Docker.
Evaluated against the WorldQuant BRAIN API.

**[Wallet-Risk_Scoring](https://github.com/Animesh-Parashar/Wallet-Risk_Scoring)**:
*Feature-extraction and inference API.*
Flask service that ingests on-chain activity, derives behavioral features, and
returns real-time risk predictions from a remote ML model.

**Web3 protocol work**: [MergeFi](https://github.com/Animesh-Parashar/MergeFi)
(ETHGlobal ETHOnline 2025, 3rd place, Avail Nexus track),
[Basis-Zero](https://github.com/Ranish-Garg/Basis-Zero) (20 merged PRs:
cross-chain bridging, state-channel sessions, AMM and vault workflows),
[x402-nexus](https://github.com/Animesh-Parashar/x402-nexus) (agent payment
protocol).

---

## Research

**Self-Supervised Anomaly Detection on Real LHC Data**: Preprint, Jun 2026 ·
[DOI: 10.5281/zenodo.20827792](https://doi.org/10.5281/zenodo.20827792)
Contrastive self-supervised learning (transformer encoder, NT-Xent objective,
physics-informed augmentations) applied to ~178M real CMS jet constituents
(AspenOpenJets, LHC Open Data, √s = 13 TeV) for model-agnostic anomaly detection.

Also: gravitational-wave echo detection from LIGO strain data. PyTorch, CUDA, GWpy, PyCBC.

---

<div align = "center">
<!-- <img src="https://user-images.githubusercontent.com/74038190/225813708-98b745f2-7d22-48cf-9150-083f1b00d6c9.gif" width="500"> -->

 <div align="center">
  <h2><b>Can Connect With Me On</b></h2>
  </div>

<div align="center">
<a href="mailto:acryptovoyager@gmail.com"><img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/animesh-parashar-378659320/"><img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
</a>
<a href="https://x.com/Animesh6488141"><img alt="X" src="https://img.shields.io/badge/X-%23000000.svg?style=for-the-badge&logo=X&logoColor=white"/></a>

</div>
<br>
<p align = "center"> <img src = "https://github.com/Animesh-Parashar/Animesh-Parashar/blob/output/github-contribution-grid-snake-dark.svg?" alt = "Snake Game"/> </p>

 # 💻 Tech Stack: 
<p>
<img src="https://skillicons.dev/icons?i=rust,go,ts,solidity,py,cpp,bash,js,html,css,react,nextjs,nodejs,express,md,postgres,mysql,ipfs,mongodb,git,vscode,docker,postman,linux,ubuntu,htmx,github"/>
</p>
<br />
</div>


