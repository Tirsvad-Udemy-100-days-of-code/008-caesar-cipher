# 🔐 Caesar Cipher

A beginner-friendly Python program that encodes and decodes messages with the Caesar cipher.

## 📚 Table of Contents

- [Overview](#-overview)
- [Requirements](#-requirements)
- [Setup](#-setup)
- [Run](#-run)
- [Tests](#-tests)
- [License](#-license)
- [Links](#-links)
- [Appendix: Project documents](#-appendix-project-documents)

## 🧭 Overview

The Caesar cipher shifts every letter by a fixed number of places (with a shift of 3, `E` becomes `H`). This project, from Udemy's *100 Days of Code: The Complete Python Pro Bootcamp* (Day 8), finds letter positions with `list.index` and wraps around the alphabet with the modulo operator. The interactive program lets you encode or decode as many messages as you like. Code lives in `src/`, tests in `tests/`, docs in `docs/`.

## 📋 Requirements

- Python 3.13 or newer
- `pytest` (development only; no runtime dependencies)
- Optional: [Doxygen](https://www.doxygen.nl/) to build the API docs

## 🛠️ Setup

Create and activate a local virtual environment, then upgrade pip and install the project:

```bash
python -m venv .venv
```

Activate it:

```bash
# Linux / macOS
source .venv/bin/activate
# Git Bash on Windows
source .venv/Scripts/activate
```

```powershell
# Windows PowerShell
.venv\Scripts\Activate.ps1
```

```bash
python -m pip install --upgrade pip
python -m pip install -e ".[dev]"
```

## ▶️ Run

```bash
python -m caesar_cipher
```

or, after installation, `caesar-cipher`.

![Caesar cipher running in a terminal](docs/images/screenshot.svg)

## 🧪 Tests

```bash
python -m pytest
```

Build the API docs with `doxygen Doxyfile` (output in `docs/doxygen/html`).

## 📄 License

GNU AGPL-3.0 – see [LICENSE][license].

## 🔗 Links

- [Repository][repository]
- [Documentation][documentation]
- [Issue tracker][issues]

## 📎 Appendix: Project documents

The documents a newcomer needs, in reading order.

| Document | What it tells you |
| --- | --- |
| [Business Case][BC-001] | Why the project exists, its scope and success criteria |
| [Stakeholder Analysis][SA-001] | Who is involved; the stakeholder IDs used for owners and reviewers |
| [Project Plan][PP-001] | The gateways and their schedule |
| [Milestones][milestones] | One document per gateway: Go/No-Go criteria and tasks |
| [Artifact registry][registry] | Where each artifact type lives, the next version, the PO language and domain |
| [Traceability matrix][TM-001] | How the artifacts link and when each was last reviewed |

---

[repository]: https://git.tirsystem.com/Tirsvad-Udemy-100-days-of-code/008-caesar-cipher
[documentation]: https://git.tirsystem.com/Tirsvad-Udemy-100-days-of-code/008-caesar-cipher/wiki
[issues]: https://git.tirsystem.com/Tirsvad-Udemy-100-days-of-code/008-caesar-cipher/issues
[license]: ./LICENSE
[BC-001]: ./docs/business-case.md
[SA-001]: ./docs/stakeholder-analysis.md
[PP-001]: ./docs/project-plan.md
[milestones]: ./docs/milestones/
[registry]: ./docs/artifact-registry.md
[TM-001]: ./docs/sqa/traceability-matrix.md
