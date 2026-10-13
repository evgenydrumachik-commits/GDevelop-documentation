> **Portfolio policy (owner decision D-045):** For engineering work in this owner-controlled repository, read [Hermes Infra GLOBAL_ENGINEERING_POLICY.md](https://github.com/evgenydrumachik-commits/Hermes-Infra/blob/main/GLOBAL_ENGINEERING_POLICY.md) once at task start. The default workflow is **FAST** (rapid reversible changes, no blanket Issue/PR/review), with **CAREFUL** for material safety/data/irreversibility risks. **FAST is never the Codex product Fast option.** Coding: GPT-6 Luna/native MAX; UI/UX design: Claude Sonnet 5.5. T3 first, safe automatic fallback. Docs-only may commit directly without PR. This policy supersedes older generic process gates only; preserve project-specific requirements. Preserve upstream documentation writing conventions; policy only governs changes in this owner-controlled fork.

# Important Writing Style And Architecture Constraints

- Do NOT document non-user-facing implementation details. Focus only on information
  that is relevant to users creating games with GDevelop, not internal engine behavior.
- Do NOT list all actions/conditions in a list or table: the reference documentations are already
  automatically generated for this.
- Do not specify the default values. Don't feel forced to list all the properties of a
  behavior/object/condition/action: prefer to explain use cases, examples and how it's useful
  for the end user which will create a game with it.
- Do not explain standard default/shortcuts (the UI is supposed to make this clear already).