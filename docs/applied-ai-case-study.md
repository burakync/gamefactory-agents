# GameFactory V2: from Applied AI concepts to engineering constraints

## 1. Background and motivation

Burak Yenice developed GameFactory in connection with Applied AI studies at DTU. The private Module 2 report described a Fleet-based Studio Manager prototype: shared context, specialized roles, observability and human escalation. The report explicitly acknowledged missing direct build/test execution and incomplete trace evidence. This case study does not republish the submission or claim that its proposed capabilities were already operational.

V2 is a subsequent local TypeScript implementation. Its aim is to make decisions, tasks, changes and evidence explicit enough to inspect. It is still experimental commercial software, not a demonstrated autonomous studio.

## 2. From coursework concepts to system architecture

The course report's AI-native process-redesign idea appears in the workflow itself: requirements become shared context; work is routed; proposed changes are evaluated before they gain authority. V2 implements deterministic services around external workers. It does not substitute a new model for every service.

| Principle | Application and actual component | State | Lesson |
| --- | --- | --- | --- |
| AI-first process redesign | Director routes work around shared context and explicit approvals | EXPERIMENTAL workflow | The handoff process needs design as much as the prompt |
| Multi-agent systems | Game Design, Development, Art and QA task boundaries | VERIFIED contracts; external execution EXPERIMENTAL | A role name is not a running agent |
| Harness engineering | Instructions/contracts, tool limits, isolation and recovery | VERIFIED tested boundaries | The surrounding system controls what a worker may claim |
| Context engineering | Requirements, decisions, scoped context bundles and dependencies | VERIFIED local mechanisms | Persistent text alone is insufficient without relevance and authority |
| Tool use and orchestration | CLI, manual external task handoff, Godot and native art adapters | EXPERIMENTAL integration | Test the actual tool, not only its fixture |
| Observability | Task records, process outcomes and immutable history | VERIFIED local traces | Retain failed attempts and distinguish observation from approval |
| Evaluation | Mechanical QA, evidence checks and review obligations | PARTIAL / EXPERIMENTAL | A passing technical check cannot decide artistic suitability |
| Hill-climbing | Bounded rework plus human-directed diagnosis | EXPERIMENTAL mechanism; autonomous optimizer UNSUPPORTED | A correction is not a measured general improvement |
| Human-in-the-loop | Exact approvals, Commit Gate and separate visual review | VERIFIED tested authority boundaries | Approval must bind the actual proposal, not a vague intention |

## 3. Why specialized agents were introduced

The report separates design intent, development, QA/regression and production coordination. V2 adds explicit task roles and result contracts. This separation helps prevent a developer's implementation observation from silently becoming an approved design decision. It does not prove that multiple model workers execute independently or coordinate successfully without a human.

## 4. Context engineering and project state

Canonical project context separates requirements, decisions, questions and history. Relevant records can be selected into bounded bundles. Dependencies and source/semantic freshness help detect when evidence no longer describes the current work. These mechanisms are implemented and tested; maintaining a complete and correct design model still requires careful authoring.

## 5. Orchestration and tool execution

A deterministic Director plans and routes. External host contracts allow tasks and structured results to cross a deliberate boundary. Godot and Pixelorama experiments demonstrate some real native actions. Fixture hosts remain valuable for adversarial tests but cannot certify a real model or editor. Native Codex/Claude/Cursor adapters are not included.

## 6. Observability and evaluations

The Module 2 report names five evaluation dimensions. V2 does not implement a proven general-purpose scorer for all five:

| Dimension | Present mechanism | Gap |
| --- | --- | --- |
| Requirement Adherence | Requirement records, task scope and protected behavior | No verified autonomous judgment of arbitrary requirement satisfaction |
| Functional Correctness | Executed tests and structured outcomes | Coverage is limited to actual assertions |
| Regression Safety | Freshness checks, dependency tracking and test suites | A focused lane is not a full regression |
| Design Intent Alignment | Decision authority and review/checkpoint obligations | Subjective alignment still requires human review |
| Escalation Correctness | Question/authority gates and rejection tests | No general model-level escalation benchmark is claimed |

Local traces record commands and results. Historical failures remain useful evidence. There is no verified LangSmith integration or autonomous learning-log optimizer in this release.

## 7. Human oversight and change control

The report reserves major design, destructive and release decisions for humans. V2's Commit Gate, scoped grants and review boundaries implement part of this principle. A technical PASS is evidence about a test; it is not permission to publish, approve art or supersede owner intent.

## 8. Experiments and verification

The private release is checked through clean dependency installation, typecheck, compilation, real CLI smoke and a named focused test lane. Results are reported in [verification](verification.md). The tiny [Little Star Jump experiment](demo.md) separately records native gameplay tests and actual framework participation. No performance comparison or autonomous success rate is inferred from those checks.

## 9. Star Greenhouse 2: limitations and lessons

Star Greenhouse 2 produced technically inspectable native assets and a runnable scene, yet failed the owner's intended artistic outcome and was discontinued. It is not presented as completed production. No further art repair is part of this release.

The experiment exposed two practical distinctions: structural validity does not imply coherent art, and a documented agent architecture does not establish operational autonomy. These are engineering observations from one project, not invented research findings or a statistically evaluated claim.

## 10. Future engineering directions

Possible future work is limited to a clearer supported external-host path, representative task evaluations, proportionate verification cost and better separation of technical and subjective acceptance. These items are proposals, not shipped features. Commercial terms and supported platforms require separate review.

### Evidence and attribution

This account draws on the owner's private Module 2 coursework report, current V2 source/contracts, retained experiment receipts and fresh release/demo checks. The original report, student identifier, private paths, proprietary source and raw logs are deliberately excluded. The report describes an earlier Fleet prototype and does not independently prove V2 runtime behavior. DTU has not endorsed this product.

Copyright © 2026 Burak Yenice. All rights reserved.
