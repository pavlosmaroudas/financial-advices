# Codex Task — AAPL Portfolio Project

Work only on branch `codex-aapl-portfolio`.

The source package is:

`codex/AAPL_CODEX_PORTFOLIO_PACK.zip`

## Required workflow

1. Extract `codex/AAPL_CODEX_PORTFOLIO_PACK.zip` into the repository workspace.
2. Read `CODEX_MASTER_PROMPT.md` completely before changing code.
3. Treat `AAPL_Thesis_Portfolio_Source_REDACTED.ipynb` as the source notebook.
4. Treat `EXPECTED_THESIS_CHECKPOINTS.json` only as regression checkpoints. Never hard-code outputs to match them.
5. Perform the forensic audit first, then refactor the project into the portfolio-grade repository described in the master prompt.
6. Preserve scientific integrity: no test-set tuning, no look-ahead, no fabricated results, no silent changes to the h=5 thesis specification.
7. Run the requested tests, secret scan, notebook smoke check, and lightweight end-to-end smoke test.
8. Do not expose or reintroduce any API credential. The original Finnhub credential was removed from the supplied source.
9. Commit the completed work to this branch and provide a concise summary of changes, tests run, checkpoint mismatches, and remaining limitations.

Start now with the forensic audit. Do not ask for the original notebook again; the source package is already in the repository.