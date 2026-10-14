# PYTHON

![license](https://img.shields.io/badge/license-MIT-blue) ![offline-first](https://img.shields.io/badge/offline--first-air--gap-green) ![audit](https://img.shields.io/badge/audit-SHA3--256-orange) ![category](https://img.shields.io/badge/category-space_aerotech-lightgrey)

> Anticloud-hardened packaging of the upstream project `PYTHON` in category **SPACE AEROTECH**. Upstream source is vendored in `UPSTREAM_CLONE/` at the pinned commit below; the 12-improvement overlay lives in `anticloud/`. Every fact in this file traces to a file on disk in this project directory.

**Category:** SPACE AEROTECH · **Upstream:** https://github.com/TheAlgorithms/Python · **Upstream pin:** `215c1f0710f610aaf5ebaeab04edacec3f5308cd` · **Vendor:** Anticloud FZ LLE

---

## What This Project Does

<div align="center">
<!-- Title: -->
  <a href="https://github.com/TheAlgorithms/">
    <img src="https://raw.githubusercontent.com/TheAlgorithms/website/1cd824df116b27029f17c2d1b42d81731f28a920/public/logo.svg" height="100">
  </a>
  <h1><a href="https://github.com/TheAlgorithms/">The Algorithms</a> - Python</h1>

<!-- Labels: -->
  <!-- First row: -->
  <a href="https://gitpod.io/#https://github.com/TheAlgorithms/Python">
    <img src="https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod&style=flat-square" height="20" alt="Gitpod Ready-to-Code">
  </a>
  <a href="https://github.com/TheAlgorithms/Python/blob/master/CONTRIBUTING.md">
    <img src="https://img.shields.io/static/v1.svg?label=Contributions&message=Welcome&color=0059b3&style=flat-square" height="20" alt="Contributions Welcome">
  </a>
  <img src="https://img.shields.io/github/project-size/TheAlgorithms/Python.svg?label=project%20size&style=flat-square" height="20">
  <a href="https://the-algorithms.com/discord">
    <img src="https://img.shields.io/discord/808045925556682782.svg?logo=discord&colorB=7289DA&style=flat-square" height="20" alt="Discord chat">
  </a>

  <!-- Second row: -->
  <br>
  <a href="https://github.com/TheAlgorithms/Python/actions">
    <img src="https://img.shields.io/github/actions/workflow/status/TheAlgorithms/Python/build.yml?branch=master&label=CI&logo=github&style=flat-square" height="20" alt="GitHub Workflow Status">
  </a>
  <a href="https://github.com/pre-commit/pre-commit">
    <img src="https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white&style=flat-square" height="20" alt="pre-commit">
  </a>
  <a href="https://docs.astral.sh/ruff/formatter/">
    <img src="https://img.shields.io/static/v1?label=code%20style&message=ruff&color=black&style=flat-square" height="20" alt="code style: black">
  </a>

<!-- Short description: -->
  <h3>All algorithms implemented in Python - for education 📚</h3>
</div>

Implementations are for learning purposes only. They may be less efficient than the implementations in the Python standard library. Use them at your discretion.

## 🚀 Getting Started

📋 Read through our [Contribution Guidelines](CONTRIBUTING.md) before you contribute.

## 🌐 Community Channels

We are on [Discord](https://the-algorithms.com/discord)! Community channels are a great way for you to ask questions and get help. Please join us!

## 📜 List of Algorithms

See our [directory](DIRECTORY.md) for easier navigation and a better overview of the project.

*Quoted from the upstream `README.md` file in `UPSTREAM_CLONE/`.*
Project-specific facts detected in this directory:

- Ecosystem: **Python** (manifests: pyproject.toml; scanned in UPSTREAM_CLONE)
- Top-level source layout: `audio_filters/`, `backtracking/`, `bit_manipulation/`, `blockchain/`, `boolean_algebra/`, `cellular_automata/`, `ciphers/`, `computer_vision/`, `conversions/`, `data_compression/`, `data_structures/`, `digital_image_processing/`
- Snapshot size: **1709 files**, **151268 lines of code** (measured; see Benchmarks)
- Primary languages: `.py` (1604), `.txt` (38), `.md` (32), `.jpg` (9), `.sh` (7), `(none)` (6)
- Upstream commit pinned for this packaging: `215c1f0710f610aaf5ebaeab04edacec3f5308cd`

---

## Installation

</a>
  <a href="https://github.com/pre-commit/pre-commit">
    <img src="https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white&style=flat-square" height="20" alt="pre-commit">
  </a>
  <a href="https://docs.astral.sh/ruff/formatter/">
    <img src="https://img.shields.io/static/v1?label=code%20style&message=ruff&color=black&style=flat-square" height="20" alt="code style: black">
  </a>

<!-- Short description: -->
  <h3>All algorithms implemented in Python - for education 📚</h3>
</div>

Implementations are for learning purposes only. They may be less efficient than the implementations in the Python standard library. Use them at your discretion.

*Section quoted from the upstream readme.*
Overlay install (this project):

```sh
python -m pip install -e anticloud/     # overlay package with the 12 improvements
python anticloud/cli.py --help          # 13 subcommands, JSON stdout
```

---

## Usage

No usage section was found in the upstream readme. Entry points detected in this project directory:

```sh
python -m python    # module entry point, when the package layout matches
```

Anticloud overlay CLI (available in every project):

```sh
python anticloud/cli.py --help     # 13 subcommands, JSON stdout
python anticloud/cli.py checks     # run the 16-check suite
```

---

## API

The upstream API surface is defined by the `PYTHON` source tree vendored in `UPSTREAM_CLONE/` (Python ecosystem). Public entry points:

- Source modules: `audio_filters/`, `backtracking/`, `bit_manipulation/`, `blockchain/`, `boolean_algebra/`, `cellular_automata/`, `ciphers/`, `computer_vision/`
- The snapshot declares 16 dependency references across 1 ecosystem(s); see Dependencies below.
- Overlay API: `anticloud/cli.py` exposes 13 subcommands with JSON stdout; `anticloud/bench/runner.py` runs the 16-check suite; `anticloud/provenance/chain.py` exposes the SHA3-256 + Ed25519 provenance chain.

---

## Dependencies

| Metric | Value |
|--------|-------|
| Ecosystem | Python |
| Manifests detected | pyproject.toml |
| Files in snapshot | 1709 |
| Lines of code | 151268 |
| Dependency references | 16 |
| Dependencies by ecosystem | pypi: 16 |
| Upstream license | MIT |
| Overlay license | Anticommons 0.1.0 |

Top dependency references recorded in the benchmark snapshot:

| Ecosystem | Name | Version | Source file |
|-----------|------|---------|-------------|
| pypi | beautifulsoup4 | >=4.15 | pyproject.toml |
| pypi | cython | >=3.1.2 | pyproject.toml |
| pypi | fake-useragent | >=1.5.1 | pyproject.toml |
| pypi | httpx2 | >=2.0.1 | pyproject.toml |
| pypi | imageio | >=2.36.1 | pyproject.toml |
| pypi | lxml | >=6 | pyproject.toml |
| pypi | matplotlib | >=3.9.3 | pyproject.toml |
| pypi | numpy | >=2.1.3 | pyproject.toml |
| pypi | pandas | >=2.3.3 | pyproject.toml |
| pypi | pillow | >=11.3 | pyproject.toml |
| pypi | rich | >=13.9.4 | pyproject.toml |
| pypi | scikit-learn | >=1.9.1 | pyproject.toml |
| pypi | scipy | >=1.18.1 | pyproject.toml |
| pypi | statsmodels | >=0.14.4 | pyproject.toml |
| pypi | sympy | >=1.13.3 | pyproject.toml |
| ... | (1 more) | | |

Pinned lockfile: `anticloud/requirements.lock` (hash-pinned, PEP 508). SBOM: `sbom.cdx.json` (CycloneDX 1.5, pinned to the upstream SHA).

---

## Configuration

No configuration section was found in the upstream readme. Configuration-relevant files detected in this project directory:

- `pyproject.toml`

Overlay configuration (Anticloud):

- `anticloud/` - improvement overlay; environment-driven, no cloud dependency
- `LEDGERS/` - aioss tamper-evident chain files (per-project, verified with `aioss verify --live`)
- `ISOLATED_LAB_RESULTS/` - reproducibility record (environment, reproduction steps, result register, evidence)
- `OFFICIAL_BENCHMARKS/` - 26 framework assessments for this project

---

## Contributing

*Excerpt from upstream `CONTRIBUTING.md`:*

# Contributing Guidelines

## Before Contributing

Welcome to [TheAlgorithms/Python](https://github.com/TheAlgorithms/Python)! Before submitting your pull requests, please ensure that you __read the entire guidelines__. If you have any doubts about the contributing guide, please feel free to [state them clearly in an issue](https://github.com/TheAlgorithms/Python/issues/new) or ask the community on [Gitter](https://gitter.im/TheAlgorithms/community).

## Contributing

### Contributor

We are delighted that you are considering implementing algorithms and data structures for others! This project is referenced and used by learners from all over the globe. By being one of our contributors, you agree and confirm that:

- You did your work — no plagiarism allowed.
  - Any plagiarized work will not be merged.
- Your work will be distributed under the [MIT License](LICENSE.md) once your pull request is merged.
- Your submitted work fulfills or mostly fulfills our styles and standards.

__New implementations__ are welcome! For example, new solutions for a problem, different representations for a graph data structure, or algorithm designs with different complexities. However, __identical implementations__ of an existing one are not allowed. Please check whether the solution is already implemented before submitting your pull request.

__Improving comments__ and __writing proper tests__ are also highly welcome.

### Contribution

We appreciate any contribution — from fixing a grammar mistake in a comment to implementing complex algorithms. Please read this section if you are contributing your work.

Your contribution will be tested by our [automated testing on GitHub Actions](https://github.com/TheAlgorithms/Python/actions) to save time and mental energy. After you have submitted your pull request, you should see the GitHub Actions tests start to run at the bottom of your submission page.

If those tests fail, then click on the ___details___ button to read through the GitHub Actions output to understand the failure. If you do not understand, please leave a comment on your submission page, and a community member will try to help.

#### Issues

If you are interested in resolving an [open issue](https://github.com/TheAlgorithms/Python/issues), simply make a pull request with your proposed fix. __We do not assign issues in this repo__, so please do not ask for permission to work on an issue.

__Do not__ create an issue to contribute an algorithm. Please submit a pull r

Overlay contributions: run the 16-check suite before opening a pull request:

```sh
python anticloud/bench/runner.py --cwd anticloud
```

---

## License

**Upstream license: MIT** (evidence: `LICENSE.md` in the upstream snapshot).

License file excerpt:

```text
## MIT License

Copyright (c) 2016-2022 TheAlgorithms and contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
```

### Anticommons 0.1.0 overlay

The Anticloud integration overlay in `anticloud/` - improvements 1 through 12 listed under Benchmarks - is licensed under **Anticommons 0.1.0**. Upstream code remains under its original MIT terms. See `ANTICOMMONS_LICENSE.md` in this directory for the overlay terms and contact.

SPDX: `MIT` (upstream) + Anticommons 0.1.0 (overlay, dual).

---

## Upstream

- **Project:** `PYTHON` (category: SPACE AEROTECH)
- **Upstream URL:** https://github.com/TheAlgorithms/Python
- **Pinned commit (SHA):** `215c1f0710f610aaf5ebaeab04edacec3f5308cd`
- **Branch:** master
- **Pin provenance:** GitHub API commits/master. The parent-project stamp is explicitly rejected for this project.
- **Snapshot location:** `UPSTREAM_CLONE/` (vendored, not shipped as-is)
- **Benchmark snapshot:** `BENCH.json`

---

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`e8a14a4b4ccbbb974ec26054e03d13628445923bd50773b7601a725aa19fcdcf`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.

