---
name: implementation
description: Use when writing new code or features once requirements are clear.
---
# Implementation

1. Read the requirements and copilot-instructions.md first.
2. Propose a short plan (files to create or change, functions, data flow) and wait for approval on larger changes.
3. Implement in small steps; each step should run.
4. Follow project conventions: Python, PEP 8, type hints, docstrings, small single-purpose functions.
5. Manage dependencies with uv (`uv add <package>`); never use pip install directly.
6. No hard-coded paths, credentials or secrets; use config or a .env file.
7. Write pytest tests in `tests/` for new functions, covering normal cases and edge cases.
8. Run the tests with `uv run pytest` and make sure they pass.
9. Update README.md if installation or usage changed.
10. Summarize what was changed and why.