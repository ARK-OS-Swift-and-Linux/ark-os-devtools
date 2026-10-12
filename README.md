# ARK-OS Developer Tools

## Overview

The `devtools/` repository contains developer tooling, automated quality verification scripts, and release orchestration utilities for the ARK-OS project.

---

## Directory Organization

- `check/` - Code linting, license header checkers, ASCII compliance validators, and static analysis runners used in pre-commit and CI workflows.
- `release/` - Release preparation scripts, changelog generators, artifact bundling verification, and provenance tooling.

---

## Usage and Principles

- Tools in this directory are intended to assist developers in maintaining codebase hygiene and adhering to [AGENTS.md](file:///home/aarav/repo/arkos/AGENTS.md) regulations.
- Validation scripts must run deterministically, output actionable error messages, and avoid side-effects on unrelated files.

---

## License

This repository is licensed under the Apache License, Version 2.0. See [LICENSE](file:///home/aarav/repo/arkos/devtools/LICENSE) for the full license text.
