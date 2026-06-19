# Legacy Modernization & Migration

**Move old code to modern stacks without a risky big-bang rewrite.** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

Brownfield work, encoded. Plan strangler-fig migrations, drive major framework and language-version upgrades, extract the business rules buried in tangled code, pin behavior with characterization tests, eliminate dead code with evidence, and decompose a monolith along real bounded-context seams.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/legacy-modernization](https://skillme.dev/pack/legacy-modernization) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add aouellets/legacy-modernization`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Strangler Fig Planner](skills/strangler-fig-planner/SKILL.md)** — Produces an incremental migration plan that runs the legacy and new systems side by side behind a routing layer, slicing and sequencing work to avoid a big-bang rewrite.
- **[Framework Upgrader](skills/framework-upgrader/SKILL.md)** — Drives a major-version framework upgrade using codemods, changelog diffing, and incremental PRs while keeping the app green throughout.
- **[Language Version Migrator](skills/language-version-migrator/SKILL.md)** — Ports a codebase across breaking language or runtime versions using shims, automated transforms, and layered verification.
- **[Business Rule Extractor](skills/business-rule-extractor/SKILL.md)** — Reads tangled legacy logic and documents the implicit business rules and edge cases it encodes before a rewrite, so behavior is preserved.
- **[Characterization Test Writer](skills/characterization-test-writer/SKILL.md)** — Writes pinning and characterization tests around untested legacy code to lock in current behavior before refactoring.
- **[Dead Code Eliminator](skills/dead-code-eliminator/SKILL.md)** — Finds unreachable, unused, and orphaned code with hard evidence and removes it safely without breaking dynamic callers.
- **[Monolith Decomposer](skills/monolith-decomposer/SKILL.md)** — Identifies bounded-context seams for extracting a service from a monolith, analyzing dependencies, data ownership, and anti-corruption layers, then sequences the extraction.
- **[Dependency Risk Audit](skills/dependency-risk-audit/SKILL.md)** — Assesses third-party dependency risk across CVEs, maintenance health, license exposure, and supply-chain hygiene.
- **[TDD Expert](skills/tdd-expert/SKILL.md)** — Enforces Red-Green-Refactor discipline: write the failing test first, then the minimum code to pass it.

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).
