# starter Canonical Agent Rules

## Authority

Starter templates (couche 4) of the Libre AI constellation: the wave-1
exit-gate template and the bun-app template, letting a new project start
constellation-conformant in minutes by consuming the workshop bricks
(`@libre-ai/{ui,auth-web,contracts,web-platform}`) pinned by SHA. Fleet
doctrine and the gate template live upstream:
https://raw.githubusercontent.com/libre-ai/governance/main/AGENTS.md

## Boundaries

- Brick implementations are canonical in their own repositories; a brick
  evolution here is a pin bump in the template manifests, never an edit.
- Current exposure and acceptance state live in this repository's own
  `project.v1.yaml`, aggregated by governance — never duplicated here.

## Quality gates

Run `bun run check` before pushing; never hide a red test.

## Agents

- Read actual state before editing.
- Stage files before running tree-walking gates.
- Security > quality > performance > completeness.
