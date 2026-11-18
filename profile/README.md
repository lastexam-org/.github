<p align="center">
  <img src="https://raw.githubusercontent.com/lastexam-org/lastexam/main/assets/avatar.png" alt="LastExam logo" width="160" height="160">
</p>

<h1 align="center">LastExam</h1>

<p align="center"><strong>Challenging, reproducible evaluations for AI systems and agents.</strong></p>

<p align="center">
  <a href="https://pypi.org/project/lastexam/"><img src="https://img.shields.io/pypi/v/lastexam" alt="PyPI version"></a>
  <a href="https://github.com/lastexam-org/lastexam"><img src="https://img.shields.io/badge/source-GitHub-181717?logo=github" alt="Source repository"></a>
  <a href="https://github.com/lastexam-org/lastexam/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Apache--2.0-blue" alt="Project license: Apache-2.0"></a>
</p>

## About

LastExam develops verifiable tasks and evaluation tools for AI systems and agents across scientific and technical domains. The first suite focuses on quantum computing, quantum information, quantum many-body physics, quantum chemistry, quantum error correction and quantum compilation.

面向 AI 与智能体的挑战性任务和可复现测评，首期覆盖六个量子科学方向。

## Install

```bash
pip install lastexam
```

## Try it

```bash
lastexam list
lastexam show quantum.chemistry.hubbard
lastexam export > quantum-prompts.jsonl
```

## Available today

- 12 original Quantum seed tasks across six domains.
- Deterministic structured-answer grading, per-domain reports and custom JSON suites.
- Python API and CLI with no runtime dependencies.

The current suite is a working seed release. Task difficulty has not yet been calibrated against models or humans; it is not presented as a validated frontier-difficulty benchmark.

## Start here

- **[Source repository](https://github.com/lastexam-org/lastexam)** — implementation, examples and contributions.
- **[Documentation and quick start](https://github.com/lastexam-org/lastexam#readme)** — APIs, commands and methodology.
- **[PyPI package](https://pypi.org/project/lastexam/)** — installation and release files.
- **[Issues and proposals](https://github.com/lastexam-org/lastexam/issues)** — bugs, new tasks and feature requests.

## Benchmark family

| Project | Focus | Package |
| --- | --- | --- |
| [LastExam](https://github.com/lastexam-org) | AI and agent task evaluation | [lastexam](https://pypi.org/project/lastexam/) |
| [SDKBench](https://github.com/sdkbench-org) | SDK performance and correctness | [sdkbench](https://pypi.org/project/sdkbench/) |
| [QCBench](https://github.com/qcbench-org) | Quantum computer hardware characterization | [qcbench](https://pypi.org/project/qcbench/) |
