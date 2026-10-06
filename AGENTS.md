# AGENTS.md

Greenfield repo: `115-1 computer programming` coursework codebase.

## State

- Only `README.md` + Python `.gitignore` exist; single `Initial commit`, no source, no manifests, no tests, no CI/lint config.
- `.gitignore` is the stock Python template — implies Python, but no interpreter version, venv, or dependency tool is pinned yet.

## 規範

- 所有的回應都使用繁體中文。
- 專案所使用的程式語言為 Python。
- 使用 conda 管理 Python 套件，環境名稱為 `iem_python`（例如：`conda run -n iem_python python ...`）。

## Guidance

- Do not assume a build/test/lint toolchain beyond conda + Python; check what was added before running commands.
- When introducing Python code, also establish the missing pieces (layout, `requirements`/`pyproject`, run/test commands) and document them here.
