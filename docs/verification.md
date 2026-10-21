# Preview verification

2026-10-21 · Experimental preview · Windows · Node 24.20.0 / pnpm 11.25.0.

| Check | Actual result |
| --- | --- |
| Fresh dependency tree, frozen lockfile | PASS; existing package-download store reused |
| Typecheck and build | PASS |
| Actual CLI smoke | PASS; eight commands, no engine/model execution inferred |
| Initial focused framework lane | 901 passed, 1 failed; missing bootstrap fixture documents in staged distribution |
| Corrective test file after packaging repair | 21/21 PASS, including the failed preservation case and real filesystem link safety |
| Distinct focused cases covered across those runs | 902; original failure retained, no remaining failure in that selection |
| Full framework / protected lifecycle suites | NOT_RUN for this preview |
| Showcase desktop/mobile render | PASS; diagrams loaded and no page overflow |

The initial focused lane took 69.21 seconds and the corrective file 0.683 seconds. These are observations, not performance benchmarks. Original assertions and deadlines were preserved. The packaging repair added the missing original hash-bound inputs rather than changing the preservation test.

Private raw receipts are retained by the owner. Public summaries do not expose core source, local paths, process identities or credentials. The [demonstration](demo.md) has a separate native-game verification result; framework test coverage is not a claim of autonomous game production.

## Independent clone check

The private source candidate was cloned into a new local directory without node_modules. Frozen installation, typecheck, build, actual CLI smoke and 21 bootstrap/filesystem checks passed again. The package download store was reused. The separate demo was also cloned without its engine cache or framework context; fresh native import and all 21 gameplay checks passed. No full framework regression is implied.
