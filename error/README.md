# Error Demo

This folder contains a tiny Python project with a deliberate bug and a CI workflow that posts failures to your Self-Healing Codebase Sentinel.

Contents:
- `app_demo/math_ops.py` – buggy `add` function (returns subtraction)
- `tests/test_math_ops.py` – failing pytest
- `.github/workflows/ci.yml` – runs tests and on failure notifies Sentinel
- `requirements.txt` – pytest dependency

Push this folder as the root of a repo (e.g., `Sridhar2089/Error-Code`).
