# v0.4.0 Release Evidence

This folder contains public-safe evidence from the private CAB `v0.4.0`
release-readiness run.

The original private evidence bundle was generated from the standard evidence
workflow on `2026-06-20`.

## Suite Result

| Check | Status |
| --- | --- |
| Release readiness | passed |
| Package version | 0.4.0 |
| Evidence artifacts | passed |
| Release provenance | passed |
| Release SBOM | passed |
| Leaderboard report | passed |

Public-safe files:

- [suite evidence card](suite_evidence_card.md)
- [suite results CSV](results.csv)
- [leaderboard proof](leaderboard_evidence_card.md)

## Benchmarks

| Benchmark | Seeds | Public-safe evidence |
| --- | ---: | --- |
| warehouse_v16 | 50 | [card](warehouse_v16/evidence_card.md) |
| organism_v11 | 160 | [card](organism_v11/evidence_card.md) |
| resource_allocation_v1 | 90 | [card](resource_allocation_v1/evidence_card.md) |
| delayed_harm_v1 | 90 | [card](delayed_harm_v1/evidence_card.md) |

## Release Snapshot

| Check | Detail |
| --- | --- |
| Package | `consequence-agent-benchmark` |
| Version | `0.4.0` |
| Commit | `56aec0b420d0564f721385f70bb4f9ce9bb28d86` |
| Provenance hash | `55219805894298b3cadc8d3bb835b5263979ce473e386e0b8f3394c102938c3d` |
| SBOM hash | `90fe56a318dbde8d3aa94e6898cc37b5ca881f57ca11847601851d4482d6a869` |

## Public Boundary

This folder intentionally excludes private benchmark implementation, private
threshold configuration files, source code, package artifacts, and full private
evidence bundles.
