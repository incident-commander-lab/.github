<div align="center">

# Incident Commander Lab

**Research on AI agents for incident response that know when *not* to act.**

Graduation research · Alryada University

</div>

---

## What we work on

Autonomous incident response breaks trust when an agent acts on a guess. We study agents that:

- **Investigate with a budget.** An LLM proposes competing root-cause hypotheses; a fixed, auditable decision rule (Bayesian updating + value of information) chooses which check to run next and when to stop.
- **Ask before acting.** Every action is gated by a policy engine (OPA) that sits outside the agent.
- **Verify and undo.** Recovery is checked on fresh telemetry, and a fix that doesn't hold is reverted and escalated to a human.
- **Leave a receipt.** Every decision is sealed in a Merkle tree and signed with Ed25519, verifiable offline by a third party.

## Projects

| Project | What it is |
|---|---|
| [**incident-commander**](https://github.com/incident-commander-lab/incident-commander) | Research prototype: an autonomous SRE agent with policy-as-code governance and a verifiable evidence chain. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23276215.svg)](https://doi.org/10.5281/zenodo.23276215) |

## Team

| | |
|---|---|
| **Shahesta Salama** | [@S2800-0](https://github.com/S2800-0) |
| **Nourseen Tarek** | [@nourseen6](https://github.com/nourseen6) |

## Citing

If you use our work, please cite the archived release: [doi.org/10.5281/zenodo.23276215](https://doi.org/10.5281/zenodo.23276215).
