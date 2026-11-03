# Usage guide

## Bring useful evidence
For a new idea, supply player identity, core actions, intended experience, and explicit decisions. For an existing project, add current GDD sections, implemented behavior, decision logs, and test observations. Separate what you want, what the team decided, and what the game currently does.

## Choose a task
- Create: extract four pages without filling unknowns.
- Review: explain which pillars a proposed feature supports or conflicts with.
- Update: change affected pages and links after a decision.
- Diagnose: inspect sources, sinks, occupancy, conversions, and bottlenecks.
- Onboard: establish the overall context before detailed specifications.

Example:
> Read these project files. Update only the loops and resource flow affected by the latest decision. Keep unimplemented features dashed and label uncertainty in text.

## Human review
Ask whether the vision still describes the intended game, whether pillars change practical decisions, whether loop arrows can actually happen, and whether resource edges have real mechanics behind them. Remove unsupported relationships or label them as proposals.
A loop is not proof of imbalance. An isolated resource is not automatically unnecessary. Test the hypothesis against the intended experience.

## Team practice
Use the four pages at milestone reviews and when discussing features, rather than rewriting them daily. When direction changes, record why elsewhere and update affected detailed documents. Evaluate both benefits and costs; do not rank features simply by counting mentioned pillars.
Use tools and languages that your team understands. Mermaid works for precise editable relationships; visual renderers differ across platforms.

## Publication
Publishing documents can expose confidential material. Use fictional or explicitly approved examples. Document generation does not authorize external messages, PRs, merges, or publishing. The repository does not access accounts or manage permissions itself.
