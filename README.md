# Hi, I'm Abnik 👋

**AI Evaluation & Benchmarking Engineer** focused on LLM evals, agent reliability, and post-training evaluation.

I build evaluation harnesses, benchmarks, and datasets to understand where AI systems fail and whether changes make them more reliable. My work covers reasoning, retrieval, tool use, structured outputs, and multimodal tasks.

I work on **benchmark and task design, gold datasets, deterministic and model-based scoring, failure analysis, and regression testing**. Building agentic AI and RAG systems also gives me practical experience with the systems I evaluate.

Currently: **Post-Training Researcher at CIPS-AI Labs** and working on **Thadam**, open-source evaluation and reliability tooling for AI agents.

## Current Work

### Thadam

I'm working on testing and evaluation tools that help developers inspect agent behavior and catch regressions.

- Developer-defined checks and tool-use assertions

- Execution evidence and inspectable reports

- Comparisons against reviewed baselines

- Repeated-run reliability checks

**Status:** Early development. Scenario generation and a dashboard are planned.

[Explore Thadam](https://github.com/thadam-ai/thadam)

## Evaluation Projects and Contributions

### SpotDiff Eval

I created an open visual reasoning development benchmark with **10 composite images and 61 annotated differences**.

- Provider-agnostic harness with structured JSON predictions

- Deterministic one-to-one matching

- Precision, recall, attribute accuracy, and coverage

- Reports of missed differences and extra predictions

- Seven vision models evaluated end-to-end; eight more smoke-tested

- 19 automated tests and a perfect-prediction regression fixture

The dataset is public and leaderboard results are self-reported. This is a development benchmark, not an independently verified ranking.

[GitHub](https://github.com/kinba09/spotdiff-eval) | [Hugging Face dataset](https://huggingface.co/datasets/Abnik/spotdiff-v1-dev)

### Legal AI Evaluation Data at CIPS-AI Labs

I built a reproducible legal-AI data pipeline across **873 Supreme Court land-dispute cases**, organized into **12 evaluation views**.

- 790 content-bearing records in the reported run

- 83 legitimately unsegmented cases tracked separately

- Smoke tests, validation gates, and resumable checkpoints

### Enterprise-Bench Contribution

I contributed task-design feedback and evaluation analysis to DevRev's Enterprise-Bench. I piloted five UK L2 tasks; **four passed in one run**. I examined a late-email failure and proposed virtual-clock checks, sandbox safeguards, and clearer run visualizations.

## What I Write About

Practical AI evaluation: benchmark design, agent failure modes, RAG and tool-use reliability, observability, and lessons from building AI systems.

[Read my blog](https://kinba09.github.io/blogs.html)

## Tools and Methods

**Evaluation:** Benchmark design, gold datasets, deterministic scoring, LLM-as-a-judge, regression testing, failure analysis, safety testing.

**AI Systems:** Python, LangGraph, LangChain, LlamaIndex, RAG, MCP, structured outputs.

**Engineering:** FastAPI, SQL, Docker, OpenTelemetry, Prometheus, CI/CD.

## Connect

- [Website and portfolio](https://kinba09.github.io)

- [LinkedIn](https://www.linkedin.com/in/abnik-ahilasamy/)

- [X](https://x.com/Abnik_Ahilasamy)

- [Email](mailto:abnikahilasamy@gmail.com)
