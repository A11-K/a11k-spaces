# A11-K Spaces — Enterprise Placement

A11-K Spaces is a **public product surface** in the A11-K Global Enterprise Tree.

## Placement

- **Layer:** L4 — Digital Product Estate
- **Repository:** `A11-K/a11k-spaces`
- **Boundary:** public product experience
- **Private control:** `angellllkr-eng/agent-control-plane`
- **Execution services:** approved services such as `a11-live-cloud-execution`

## Rules

1. Do not place owner credentials, private operational telemetry, private evidence, financial-control data or secrets in this repository.
2. Product functionality may consume approved APIs but must not become an owner-control plane.
3. Production status must be established by deployment, routing, health and smoke evidence.
4. New product modules must have a unique purpose and remain inside the L4 boundary.
5. Any private operational capability belongs in the canonical control root, not here.

## Canonical enterprise reference

The L0-L7 architecture and repository registry are maintained privately in `agent-control-plane`.
