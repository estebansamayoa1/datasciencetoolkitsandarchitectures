---
name: debugging
description: Use when code throws an error, a test fails, or results are wrong or unexpected.
---
# Debugging

1. Reproduce the problem reliably and note the exact steps, input and full error message or traceback.
2. Read the whole traceback and identify where the error actually originates, not just where it surfaces.
3. Write a failing test that captures the bug, if possible.
4. Form one hypothesis at a time and check it (print/log values, inspect data shapes and types, use the debugger).
5. Check common causes: wrong data types or shapes, missing values, off-by-one errors, wrong file paths, environment or dependency issues (is the uv environment active?).
6. Fix the root cause with the smallest change possible; do not add workarounds that hide the error.
7. Run the failing test and the full test suite to confirm the fix and that nothing else broke.
8. Explain the cause of the bug and the fix in a short summary.