# Verification scope and results

## Retained framework and prototype release checks

The following checks belong to the earlier prepared release. They were **not rerun** while finalizing the GameFactory Agents presentation. The prototype's 21 gameplay checks below predate the three polished releases documented in the [current case study](../examples/little-star-jump/README.md).

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

## GameFactory Agents presentation checks — 21 October 2026

This pass changed presentation and recorded existing game releases. It did not run new game production, change gameplay or rerun the framework regression suite.

| Check | Actual result |
| --- | --- |
| Main README and detailed example | GitHub REST Markdown API rendered both successfully |
| Local preview of that HTML | PASS in headless Edge at 1280, 390 and 320 pixels; all images loaded, no page overflow; example details expanded |
| README sequence | PASS; GameFactory in Action is the final main section |
| Relative files and heading anchors | PASS across the public Markdown documents |
| Exact prompts and retained outcomes | PASS against the actual Director receipts and versioned demo verification records |
| Gameplay GIFs | Four actual release recordings; all decoded; sampled content and framing inspected; 936,513 bytes combined |
| Recorded executable hashes | PASS against the retained release artifact hashes |
| Public demo release links | All three source tags match the recorded commits; Windows assets are present |
| Preservation | Three diagrams, Applied AI case study and copyright notice unchanged; core and demo checkouts unchanged |
| Publication scope | Documentation, diagrams, media and public evidence only; no framework source or new license |
| Whitespace | git diff --check passed |

[Machine-readable presentation evidence](../examples/little-star-jump/evidence/presentation-checks.json) · [Recording provenance](../examples/little-star-jump/MEDIA.md)

The initial renderer check used GitHub's Markdown API plus local GitHub-style CSS. After owner authorization, the [public showcase](https://github.com/burakync/gamefactory-agents) was published on 21 October 2026. All 38 published files matched the prepared package. The live GitHub README and detailed example then passed headless Edge checks at 1280 and 390 pixels: all diagrams and GIFs loaded, with no page overflow. Review was performed by the same Codex operator; owner visual acceptance remains a manual check.
