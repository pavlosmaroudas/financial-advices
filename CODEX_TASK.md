# Codex Task — AAPL Portfolio Project

You are starting from the repository `pavlosmaroudas/financial-advices` on `main` because the Codex UI may not allow the user to select another branch.

The source package is already in this repository:

`codex/AAPL_CODEX_PORTFOLIO_PACK.zip`

## Important isolation rule

Do **not** modify or delete the existing FinScope website files (for example `index.html`). Build the AAPL project inside a separate top-level directory named:

`aapl-return-forecasting-ml/`

If branch creation/switching is available inside the task, create or switch to `codex-aapl-portfolio`. If it is not available, continue from `main` but keep **all** new portfolio work isolated under `aapl-return-forecasting-ml/`. Do not stop or ask the user to select a branch.

## Required workflow

1. Extract `codex/AAPL_CODEX_PORTFOLIO_PACK.zip` into a temporary workspace.
2. Read `CODEX_MASTER_PROMPT.md` completely before changing code.
3. Treat `AAPL_Thesis_Portfolio_Source_REDACTED.ipynb` as the source notebook.
4. Treat `EXPECTED_THESIS_CHECKPOINTS.json` only as regression checkpoints. Never hard-code outputs to match them.
5. Perform the forensic audit first, then refactor the project into the portfolio-grade repository described in the master prompt.
6. Place the completed project under `aapl-return-forecasting-ml/`.
7. Preserve scientific integrity: no test-set tuning, no look-ahead, no fabricated results, no silent changes to the h=5 thesis specification.
8. Run the requested tests, secret scan, notebook smoke check, and lightweight end-to-end smoke test.
9. Do not expose or reintroduce any API credential. The original Finnhub credential was removed from the supplied source.
10. Commit the completed work when possible and provide a concise summary of changes, tests run, checkpoint mismatches, and remaining limitations.

Start now with the forensic audit. Do not ask for the original notebook again; the source package is already in the repository. Do not require any file upload from the user.