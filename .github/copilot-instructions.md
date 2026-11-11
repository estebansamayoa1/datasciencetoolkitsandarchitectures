# Copilot instructions

## Project
A project regarding a credit risk score model. 

## Stack
- Python 3.x, dependencies managed with uv (`uv add <pkg>`, never pip install)
- Run code with `uv run ...`

## Coding rules
- Follow PEP 8, use type hints and docstrings
- Small, single-purpose functions; no hard-coded paths or secrets (use .env)
- Write pytest tests for new functions in `tests/`

## Behaviour
- Ask before large refactors or adding new dependencies
- Keep edits minimal and explain changes briefly
- Update README.md if setup or usage changes