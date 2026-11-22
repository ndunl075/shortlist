# shortlist

Given a batch of patches to sqlglot at commit `eb11aec4be8cb2122afe713a4816662c3f0fb2fa`, prints which tests to run for each one and how to split them across workers.

- Language: Python (standard library) for the selector.
- Third-party code used at build time: sqlglot at the pinned commit (fetched from its GitHub archive) and the packages in `kit/requirements.lock` from PyPI (pytest, duckdb, pandas, numpy and their dependencies), on the official `python:3.13-slim` image pinned by digest.
- The maps under `maps/` were built by us from the pinned commit only.

MIT licensed. See `LICENSE`.
