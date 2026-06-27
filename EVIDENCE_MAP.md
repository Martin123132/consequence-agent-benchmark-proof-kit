# Evidence Map

This map explains what each public proof item is meant to establish, where to
inspect it, and what a reviewer should ask for next if the public evidence is
not enough.

## Evidence At A Glance

| Evidence item | Public file | What it supports | What it does not reveal |
| --- | --- | --- | --- |
| Release suite | [release evidence](proofs/v0.4.0-release-evidence/README.md) | CAB produced a passing release-readiness evidence set | private engine implementation |
| Warehouse routing | [warehouse card](proofs/v0.4.0-release-evidence/warehouse_v16/evidence_card.md) | useful delivery can improve while damage falls | scenario internals beyond public summary |
| Organism state | [organism card](proofs/v0.4.0-release-evidence/organism_v11/evidence_card.md) | the benchmark can track harm under cue reversal | raw private artifacts |
| Resource allocation | [resource card](proofs/v0.4.0-release-evidence/resource_allocation_v1/evidence_card.md) | service quality and safety debt are both measured | private scoring implementation |
| Delayed harm | [delayed harm card](proofs/v0.4.0-release-evidence/delayed_harm_v1/evidence_card.md) | delayed negative outcomes are visible in the score | private scenario generation |
| Leaderboard proof | [leaderboard card](proofs/v0.4.0-release-evidence/leaderboard_evidence_card.md) | local package validation can compare evidence bundles | hosted leaderboard service |
| Manifest | [proof-manifest.json](proof-manifest.json) | exact public files and hashes are recorded | private repository contents |

## How To Judge The Public Proof

Look for four things:

- a clear claim;
- a public evidence file that supports that claim;
- a manifest hash tying the public files together;
- a boundary statement explaining what is not included.

If those are enough, the public proof kit has done its job. If not, request a
sanitized reviewer bundle or private technical walkthrough.

## Escalation Path

1. Public proof kit review.
2. Sanitized reviewer bundle.
3. Technical walkthrough.
4. Time-limited review mirror.
5. Direct private engine access only after stronger approval.

Use [ACCESS_REQUEST.md](ACCESS_REQUEST.md) to request the next level.
