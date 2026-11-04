<div align="center">

# Utkarsh Sinha

**Research software &nbsp; · &nbsp; Machine learning &nbsp; · &nbsp; Open source**

From mathematical ideas to software others can inspect, reproduce, and build upon.

BCA graduate (2025) &nbsp; | &nbsp; BS Data Science student, IIT Madras

[Research](#research) &nbsp; / &nbsp; [Open source](#open-source) &nbsp; / &nbsp; [Projects](#selected-projects) &nbsp; / &nbsp; [Academic direction](#academic-direction)

</div>

---

## Research

My interests lie at the intersection of **graph computation**, **machine learning**, and **reproducible research software**. I enjoy turning an idea into an implementation, then examining where it works, where it fails, and how others can reproduce the result.

### K GraphFuse

**A research software project for sparse graph computation.**

K GraphFuse explores reusable graph-filter plans, directional sensitivities, and optional GPU execution. Its accompanying manuscript studies similarity-aware evaluation and selective GPU compensation, with benchmarks and reproducibility materials alongside the code.

At its core, a graph polynomial combines an operator $A$, coefficients, and an input signal:

$$p(A)x = \sum_{k=0}^{d} c_k A^k x$$

**[Explore the repository ↗](https://github.com/Utkarsh-Sinha0/k-graphfuse)** &nbsp; · &nbsp; **[Read the manuscript ↗](https://utkarsh-sinha0.github.io/k-graphfuse/research/paper/)** &nbsp; · &nbsp; [PDF](https://github.com/Utkarsh-Sinha0/k-graphfuse/blob/main/docs/research/k-graphfuse-paper.pdf) &nbsp; · &nbsp; [Benchmark evidence](https://utkarsh-sinha0.github.io/k-graphfuse/benchmarks/results/)

<sub>Technical preprint draft; not peer-reviewed. Results should be read within their documented experimental scope.</sub>

<details>
<summary>View a figure from the controlled experiments</summary>
<br>

<a href="https://utkarsh-sinha0.github.io/k-graphfuse/benchmarks/results/">
  <img src="https://raw.githubusercontent.com/Utkarsh-Sinha0/k-graphfuse/main/docs/assets/controlled_matched_degrees.png" alt="A figure from the K GraphFuse experiments; follow the link for benchmark context and evidence." width="75%">
</a>

<sub>Controlled synthetic workloads on two GPUs; resident compute only. See the linked results for methodology and limitations.</sub>

</details>

---

## Open source

Contributing to the tools and shared standards behind reliable software.

**OpenTelemetry** &nbsp; / &nbsp; [Browser Fetch client conformance](https://github.com/open-telemetry/semantic-conventions-conformance/pull/162) · merged

**qtop** &nbsp; / &nbsp; [Scheduler error handling](https://github.com/qtop/qtop/pull/510) · [Terminal-size fallback and OAR file handling](https://github.com/qtop/qtop/pull/511) · merged

<details>
<summary>More OpenTelemetry work — in review or development as of November 2026</summary>
<br>

[XMLHttpRequest conformance](https://github.com/open-telemetry/semantic-conventions-conformance/pull/163) · [MCP span classification](https://github.com/open-telemetry/semantic-conventions-conformance/pull/149) · [Entity identity coverage](https://github.com/open-telemetry/semantic-conventions-conformance/pull/346) · [Python GenAI test requirements](https://github.com/open-telemetry/opentelemetry-python-genai/pull/934) · [State-change conventions](https://github.com/open-telemetry/semantic-conventions-genai/pull/483) · [LangGraph instrumentation](https://github.com/open-telemetry/opentelemetry-python-genai/pull/507) *(draft; dependent on the conventions proposal)*

</details>

---

## Selected projects

**[ReproLearn](https://github.com/Utkarsh-Sinha0/ReproLearn)** &nbsp; — &nbsp; Claim-level reproducibility with inspectable research evidence.

**[AgentAgri](https://github.com/Utkarsh-Sinha0/AgentAgri)** &nbsp; — &nbsp; Agricultural information across crop health, weather, markets, and farmer-owned memory.

**[SNAPV](https://github.com/Utkarsh-Sinha0/SNAPV)** &nbsp; — &nbsp; Local-first screenshot exports across Chrome, Firefox, and Edge.

**[AXIOM Urban](https://github.com/Utkarsh-Sinha0/AXIOM)** &nbsp; — &nbsp; Traffic-corridor analysis using FastAPI and a gRPC simulation engine.

**[NeuroGolf 2026](https://github.com/Utkarsh-Sinha0/NeruraGolf)** &nbsp; — &nbsp; Compact ONNX solvers and reproducible visual-transformation experiments.

**SciBoat** *(private repository)* &nbsp; — &nbsp; Rust-backed continuity, reviewed execution, and receiver-attested replay.

---

## Academic direction

I am seeking **funded graduate research and scholarship opportunities** in machine learning, data science, and research software. I hope to contribute to work grounded in careful evaluation, open collaboration, and useful, reproducible tools.

<sub>Tools: Python · TypeScript · Rust · React · FastAPI · Docker · PostgreSQL · ONNX · GitHub Actions</sub>
