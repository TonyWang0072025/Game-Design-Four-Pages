# Game Design Four Pages
[简体中文](README.md) · [MIT](LICENSE)

A lightweight workflow for aligning game direction, evaluating features, explaining play, and inspecting resource trade-offs. Use it as an AI skill or as a manual team practice.

**v0.1.0 is an initial public release**, with one independent early-project trial. Broad compatibility, different genres, and larger production teams still need evaluation. These documents support design reasoning; they do not prove fun, balance, or production readiness.

| Document | Question | Format |
| --- | --- | --- |
| Vision | What game are we making? | A sentence to a paragraph |
| Pillars | What principles guide our trade-offs? | Usually 3–5 actionable principles |
| Game loops | What does the player repeatedly do? | Actions and causal or temporal arrows |
| Resource flow | What does the player invest, exchange, or gain? | Resources and conversion relationships |

Start with [usage](docs/usage.md), [templates](templates/README.md), and the [fictional example](examples/night-bookshop.md).

## Use as a skill
Install the complete [skills/game-design-four-pages](skills/game-design-four-pages/SKILL.md) directory through your tool's supported skill installation workflow. Some Codex environments support explicit invocation with `$game-design-four-pages`. Other tools may need manual selection or direct reading of the instruction file and references. Installation and execution are not verified across all AI products.

Example prompt:
> Use game-design-four-pages to read my latest project documents and create four concise design pages. Distinguish confirmed decisions, assumptions, proposals, and unknowns. Draw readable diagrams; do not invent mechanics or numbers.

For existing projects:
> Update the affected pages from this decision log and playable build description. Evaluate the proposed feature against the pillars and identify resource-flow hypotheses to test.

No API keys, background processes, or paid dependencies are required by the repository. AI usage is subject to your platform's billing and limits. You can also copy the templates and work without an AI agent.

## Across development
Create vision, pillars, and a rough loop early. Refine loops against the prototype. Build concrete resource flow after a first playable; label unimplemented relations. Review direction at milestones, filter new content through pillars, and use diagrams to propose tests. Keep implementation details in the GDD and history outside the concise pages.

See [validation and roadmap](docs/validation-and-roadmap.md), [contributing](CONTRIBUTING.md), and [attribution](ATTRIBUTION.md).
Original project materials are MIT licensed. Inspired by Ian Schreiber's GDC 2025 talk; not affiliated with or endorsed by the speaker or GDC. Third-party video, slides, and captions are not redistributed or covered by this license.
