<div align="center">

# Incident Commander Lab

### AI agents for incident response that know when *not* to act

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23276215.svg)](https://doi.org/10.5281/zenodo.23276215)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/incident-commander-lab/incident-commander/blob/main/LICENSE)
[![Python 3.11+](https://img.shields.io/badge/python-3.11%2B-3776AB.svg?logo=python&logoColor=white)](https://github.com/incident-commander-lab/incident-commander)
[![Policy: OPA](https://img.shields.io/badge/policy-OPA-7D9199.svg)](https://www.openpolicyagent.org/)

Graduation research at **Alryada University**

</div>

---

## About

Autonomous incident response fails the moment an agent acts on a guess. Our research asks a different question: not *how* an agent should fix production, but **when it has enough evidence to act at all**, and when it should stop and hand the incident to a human.

The condition for autonomy is **reversibility, not confidence**.

## Research focus

| | Area | What we study |
|:-:|---|---|
| 🔎 | **Decision-theoretic investigation** | An LLM proposes competing root-cause hypotheses; a fixed, auditable rule (Bayesian updating + value of information) picks the next check and decides when to stop. |
| 🛡️ | **Policy-gated action** | Every action must be approved by a policy engine (OPA) that sits outside the agent and cannot be bypassed. |
| 🔁 | **Verify, revert, escalate** | Recovery is confirmed on fresh telemetry; a fix that does not hold is undone and escalated. |
| 🧾 | **Verifiable evidence** | Each decision is a leaf in a Merkle tree, signed with Ed25519, so a third party can audit it offline. |

## Projects

<table>
<tr>
<td width="70%">

### [incident-commander](https://github.com/incident-commander-lab/incident-commander)
Research prototype of an autonomous SRE agent with policy-as-code governance and a cryptographically verifiable evidence chain. Includes a live console, an OPA policy layer and offline-verifiable postmortems.

`Python` · `OPA / Rego` · `Docker` · `OpenTelemetry`

</td>
<td width="30%" align="center">

**v1.0.0**<br>
[Archived on Zenodo](https://doi.org/10.5281/zenodo.23276215)

</td>
</tr>
</table>

## Team

<table>
<tr>
<td align="center" valign="top" width="220">
<a href="https://github.com/nourseen6"><img src="https://github.com/nourseen6.png?size=160" width="80" height="80" alt=""><br><b>Nourseen Tarek</b></a><br>
<sub>Co-founder · Researcher</sub>
</td>
<td align="center" valign="top" width="220">
<a href="https://github.com/S2800-0"><img src="https://github.com/S2800-0.png?size=160" width="80" height="80" alt=""><br><b>Shahesta Salama</b></a><br>
<sub>Co-founder · Researcher</sub>
</td>
</tr>
</table>

## Cite our work

```bibtex
@software{salama_tarek_2026_incident_commander,
  author    = {Salama, Shahesta and Tarek, Nourseen},
  title     = {Incident Commander: an autonomous SRE agent that decides when not to act},
  year      = {2026},
  publisher = {Zenodo},
  doi       = {10.5281/zenodo.23276215},
  url       = {https://doi.org/10.5281/zenodo.23276215}
}
```

---

<div align="center">
<sub>Incident Commander Lab · Alryada University · Released under the MIT License</sub>
</div>
