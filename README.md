<div align="center">

<!-- REFINED PIXELATED HEADER BORDER -->
<pre style="font-family: monospace; color: #38BDF8; font-size: 14px; line-height: 1.2;">
░▒▓████████████████████████████████████████████████████████████████████████████████████████▓▒░
</pre>

<!-- PROFESSIONAL NAME & TITLE -->
<img src="https://readme-typing-svg.demolab.com?font=Space+Grotesk&weight=700&size=48&duration=3500&pause=1000&color=F8FAFC&center=true&vCenter=true&width=1000&height=80&lines=PRIYANSHU+ROY" alt="Priyanshu Roy" />

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=4000&pause=800&color=94A3B8&center=true&vCenter=true&width=1000&height=30&lines=AI+Research+%7C+Deep+RL+%7C+SLM+Systems+%7C+Distributed+Architecture" alt="Specializations" />

<!-- STATUS BADGES -->
<p>
  <img src="https://img.shields.io/badge/Role-Research_Engineer-0EA5E9?style=flat-square&labelColor=0F172A" alt="Role" />
  <img src="https://img.shields.io/badge/Focus-Deep_RL_%26_Inference-6366F1?style=flat-square&labelColor=0F172A" alt="Focus" />
  <img src="https://img.shields.io/badge/Status-Available-10B981?style=flat-square&labelColor=0F172A" alt="Status" />
  <img src="https://img.shields.io/badge/Location-Kolkata,_IN-64748B?style=flat-square&labelColor=0F172A" alt="Location" />
</p>

<pre style="font-family: monospace; color: #38BDF8; font-size: 14px; line-height: 1.2;">
░▒▓████████████████████████████████████████████████████████████████████████████████████████▓▒░
</pre>

</div>

<br>

### ▎Engineering Manifesto

I design production-grade AI systems where mathematical rigor meets bare-metal execution. My research operates at the intersection of physically simulated reinforcement learning, constrained small language model (SLM) inference, and distributed agentic architectures. I do not build standard applications; I engineer deterministic, crash-resilient organisms designed to operate under strict memory ceilings, latency constraints, and zero-leakage privacy boundaries.

<br>

### ▎Technical Arsenal & Architecture

<div align="center">
<table>
<tr>
<td width="50%" valign="top">

#### 🦾 Deep RL & Kinematics
<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/NVIDIA-76B900?style=flat-square&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" />
</p>

**Research Focus:** Continuous control, analytical inverse kinematics, and adversarial skill embeddings in physically simulated environments (Isaac Lab / PhysX).

*   **Architecture:** Custom PPO/GAIL loops with AMP stabilization and causal temporal encoders to prevent future leakage.
*   **Execution:** 8,000+ parallel environments via PyTorch AMP, utilizing strict URDF-compatible analytical motion retargeting.

</td>
<td width="50%" valign="top">

#### 🧠 SLM Systems & Edge Inference
<p>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" />
</p>

**Research Focus:** Fine-tuning sub-10B parameter models (rsLoRA/SimPO), constrained decoding (GBNF), and bare-metal inference daemons for edge deployment.

*   **Architecture:** Rust-native execution with zero-copy NVLink-C2C unified memory streaming and HMAC-authenticated IPC.
*   **Execution:** GBNF grammar constraints physically restrict tensor outputs to deterministic JSON schemas, achieving sub-5ms cache-hit latency.

</td>
</tr>

<tr>
<td width="50%" valign="top">

#### 🕸️ Agentic RAG & Code Intelligence
<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/TreeSitter-130741?style=flat-square&logo=tree-sitter&logoColor=white" />
</p>

**Research Focus:** Autonomous code mutation pipelines, AST-level indexing, and multi-agent orchestration with approval gates.

*   **Architecture:** Tree-sitter AST parsers continuously indexing cross-file dependencies, fed into self-healing LangGraph state machines.
*   **Execution:** Zero-trust IPC where every container message is HMAC-signed using per-worker secrets, backed by circuit-breaker model routing.

</td>
<td width="50%" valign="top">

#### 🌐 Distributed Infra & Swarms
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/gRPC-244c5a?style=flat-square&logo=grpc&logoColor=white" />
</p>

**Research Focus:** Neuro-evolutionary container swarms, memory-aware scheduling, and distributed VRAM taxation.

*   **Architecture:** Hypervisor-style resource partitioning with Population-Based Training (PBT) and Elastic Weight Consolidation (EWC).
*   **Execution:** GPUDirect Storage pathways streaming sequence data directly to CUDA memory, bypassing CPU bounce buffers.

</td>
</tr>
</table>
</div>

<br>

### ▎Selected Research & Systems

<details>
<summary><b>[ 01 ] RevExBot: Deep RL Architecture for Humanoid Control</b></summary>
<br>

> An industry-grade reinforcement learning framework bridging raw video ingestion, analytical kinematic retargeting, and adversarial policy training.
*   **The Math:** Surgical reset masks inside Generalized Advantage Estimation (GAE) to hide environment resets from discriminators, maintaining strict Lipschitz continuity.
*   **The Pipeline:** Custom Universal Motion Forge utilizing CPU-throttled optical flow to generate mathematically flawless URDF trajectories.
*   **Stack:** `PyTorch` `Isaac Lab` `PhysX` `SciPy`

</details>

<details>
<summary><b>[ 02 ] Ssense: SLM Fine-Tuning & Bare-Metal Edge Intelligence</b></summary>
<br>

> A privacy-first edge intelligence platform built around a fine-tuned 9B small language model executing through a hardened bare-metal inference architecture.
*   **The Fine-Tuning:** Qwen3.5-9B optimized via Unsloth (rsLoRA + SimPO) for structural data extraction and DPDP compliance.
*   **The Engine:** 4-Byte LE Binary Framing between Chrome MV3 and Rust Daemon, eliminating UI lockups and JSON parse locks.
*   **Stack:** `Rust` `llama.cpp` `Unsloth` `GBNF`

</details>

<details>
<summary><b>[ 03 ] Cognit AI: Sovereign Multi-Agent AST RAG System</b></summary>
<br>

> A decentralized multi-agent coding architecture built around a Rust control daemon, isolated Docker worker swarms, and AST-aware retrieval.
*   **The Swarm:** Ephemeral Rust agents in isolated containers (`--memory=2g`, `--cpus=2.0`) with pre-flight DOM-based cookie verification.
*   **The Security:** Every inter-process message is HMAC-SHA256 signed. Unsigned containers are immediately annihilated.
*   **Stack:** `Rust (Tokio)` `Docker Swarm` `Tree-Sitter`

</details>

<details>
<summary><b>[ 04 ] TradeJack: Neuro-Evolutionary Financial Swarm</b></summary>
<br>

> 50 sovereign Docker containers competing for VRAM slices under real-time survival taxation on NVIDIA DGX Spark (128GB Unified Memory).
*   **The Memory:** Exploiting Grace Blackwell's 128GB Unified Memory over NVLink-C2C. Models pinned in host memory and swapped into CUDA execution units in microseconds.
*   **The Validation:** 10x Out-of-Sample Validation Airgap across historical flash-crash splits.
*   **Stack:** `CUDA 13` `GPUDirect Storage` `EWC`

</details>

<br>

### ▎System Calibration

<div align="center">
<pre style="font-family: monospace; font-size: 13px; line-height: 1.5; color: #94A3B8;">
Deep RL & Kinematics    <span style="color:#38BDF8">██████████████████████████████</span> <span style="color:#38BDF8">100%</span>
SLM Fine-Tuning         <span style="color:#6366F1">███████████████████████████░░░</span> <span style="color:#6366F1"> 95%</span>
Agentic AST RAG         <span style="color:#EC4899">█████████████████████████████░░░</span> <span style="color:#EC4899"> 92%</span>
Bare-Metal Systems      <span style="color:#10B981">████████████████████████████████</span> <span style="color:#10B981">100%</span>
</pre>
</div>

<br>

### ▎Live Telemetry & Metrics

<!--START_SECTION:activity-->
<!--END_SECTION:activity-->

<div align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=priyanshu-ogdev&show_icons=true&theme=transparent&hide_border=true&bg_color=00000000&title_color=0EA5E9&icon_color=6366F1&text_color=F8FAFC&ring_color=0EA5E9&include_all_commits=true" alt="Stats" />
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=priyanshu-ogdev&layout=compact&theme=transparent&hide_border=true&bg_color=00000000&title_color=0EA5E9&text_color=F8FAFC&langs_count=6" alt="Languages" />
</div>

<br>

<div align="center">
<pre style="font-family: monospace; color: #38BDF8; font-size: 14px; line-height: 1.2;">
░▒▓████████████████████████████████████████████████████████████████████████████████████████▓▒░
</pre>
</div>

### ▎Establish Connection

<div align="center">

<a href="https://github.com/priyanshu-ogdev">
  <img src="https://img.shields.io/badge/GitHub-priyanshu--ogdev-0F172A?style=for-the-badge&logo=github&logoColor=F8FAFC" alt="GitHub" />
</a>
<a href="https://linkedin.com/in/priyanshu-roy-25b91a31a/">
  <img src="https://img.shields.io/badge/LinkedIn-Priyanshu_Roy-0F172A?style=for-the-badge&logo=linkedin&logoColor=0EA5E9" alt="LinkedIn" />
</a>
<a href="mailto:priyanshuroy0912@gmail.com">
  <img src="https://img.shields.io/badge/Secure_Email-priyanshuroy0912@gmail.com-0F172A?style=for-the-badge&logo=gmail&logoColor=EC4899" alt="Email" />
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=priyanshu-ogdev&label=Profile+Views&color=6366F1&style=flat-square" alt="Profile Views" />

<br><br>
<sub><i>"Security forged through mathematical rigor, not obscurity."</i></sub>

</div>
