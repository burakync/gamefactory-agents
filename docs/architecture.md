# Architecture and execution boundaries

![Architecture](../assets/architecture.svg)

The Owner controls design authority and final publication. The Studio Manager / Director coordinates relevant context, bounded roles and readiness checks. Shared Context holds requirements, decisions and project state. QA and review consume evidence; neither a plan nor a test result grants every later action.

Game Design, Development, Art Direction / Production and QA & Regression are responsibility boundaries. External workers may fill those roles. The current native Director is deterministic software, and the external host interface does not itself call Codex, Claude or Cursor. No independent model swarm is claimed.

The implementation includes task/result contracts, isolated production workspaces, explicit application, source/semantic/tool freshness, recovery journals and human approval. The diagram intentionally omits proprietary implementation details.

![Loop](../assets/production-loop.svg)

A failed check returns work to diagnosis or bounded revision. It does not create a successful evidence record. A failed or stale authorization stops publication. Human review remains necessary for design and visual acceptance. Retry is bounded by the selected workflow, not an unlimited automatic loop.

![Concept map](../assets/applied-ai-map.svg)

Evaluation dimensions describe a rubric. They are not five independently verified autonomous scoring models. See the [case study](applied-ai-case-study.md).
