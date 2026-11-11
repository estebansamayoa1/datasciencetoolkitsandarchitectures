---
name: code-review
description: Use when reviewing a pull request or code changes before merging into main.
---
# Code review

1. Understand the purpose of the change from the PR description and related requirements.
2. Correctness: does the code do what it should? Check logic, edge cases and error handling.
3. Readability: clear names, small functions, docstrings, type hints, no dead or commented-out code.
4. Tests: are there tests for new or changed behaviour, and do they pass?
5. Project rules: follows copilot-instructions.md, uses uv for dependencies, no new dependencies without reason.
6. Security and hygiene: no secrets, credentials, .env files, large data files or .venv committed.
7. Documentation: README and decision log updated if needed.
8. Give feedback grouped by priority:
   - Must fix (bugs, security, broken tests)
   - Should fix (design, readability)
   - Nitpicks (style, optional)
9. Be specific: point to the file and line and suggest a fix.