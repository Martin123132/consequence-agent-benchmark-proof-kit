# Consequence Agent Benchmark Proof Kit

Consequence Agent Benchmark, or CAB, is a private-core benchmark technology for
evaluating whether agent policies reduce harmful consequences while preserving
useful capability.

It packages benchmark runs into reproducible evidence bundles, validates
submission zips, indexes package hashes, compares runs, and renders local static
leaderboard reports. The private engine contains the implementation, benchmark
internals, release gates, schemas, and evidence automation.

This public repository is not the product source code and is not an open-source
release. It is a proof kit: public-safe evidence, score summaries, release
notes, and an access path for people who want to request private review.

## Five-Minute Review Path

If you are new to CAB, read in this order:

1. This README for the claim, boundary, and locked results.
2. [Public proof one-pager](docs/public-proof-one-pager.md) for the product
   narrative.
3. [Evidence review guide](docs/evidence-review-guide.md) for how to inspect
   the benchmark cards.
4. [Proof manifest](proof-manifest.json) for file hashes and publication-gate
   status.
5. [Access request](ACCESS_REQUEST.md) if you need private verification,
   technical review, or commercial evaluation.

## Public Proof Release

The current public-safe proof checkpoint is
[`v0.1.0-public-proof`](RELEASE_NOTES.md), based on private release `v0.4.0`.

Public-safe proof materials in this repo show:

- release-readiness evidence
- four benchmark-family evidence cards
- local/static leaderboard evidence
- checksum-indexed package validation
- private-core/public-proof publication boundary
- NDA and commercial access path

## Locked Results

The `v0.4.0` release-readiness evidence passed.

| Proof | What it shows | Headline result |
| --- | --- | ---: |
| [Suite evidence](proofs/v0.4.0-release-evidence/README.md) | Release-readiness gates | passed |
| [Warehouse routing](proofs/v0.4.0-release-evidence/warehouse_v16/evidence_card.md) | Delivery improved while damage fell | 0.921 score |
| [Organism state](proofs/v0.4.0-release-evidence/organism_v11/evidence_card.md) | Harm reduced under cue reversal | 0.644 score |
| [Resource allocation](proofs/v0.4.0-release-evidence/resource_allocation_v1/evidence_card.md) | Safety debt controlled while service held | 0.947 score |
| [Delayed harm](proofs/v0.4.0-release-evidence/delayed_harm_v1/evidence_card.md) | Delayed harms anticipated and avoided | 0.946 score |
| [Leaderboard evidence](proofs/v0.4.0-release-evidence/leaderboard_evidence_card.md) | Local package index verification | 3 entries passed |

## What This Proves

- CAB can produce release-readable benchmark evidence.
- CAB can validate evidence across four benchmark families.
- CAB can package and verify local leaderboard submissions without API access.
- CAB can create checksum-indexed leaderboard reports from single, suite, and
  adapter-evaluation packages.
- The private engine reached a packaged `v0.4.0` checkpoint with release
  readiness, provenance, SBOM, and standard evidence gates passing.

## Product Claim

CAB evaluates whether agents reduce downstream harm while preserving useful
capability, using reproducible evidence packages and local/static leaderboard
validation.

## What This Does Not Prove

- It does not publish the private CAB implementation.
- It does not grant an open-source licence.
- It does not grant a commercial licence.
- It does not grant a patent licence, trademark licence, hosted-service right,
  model-provider right, or AI-platform integration right.
- It does not claim every agent or environment will produce the same benchmark
  deltas.
- It does not replace a private pilot, technical review, or customer-specific
  evaluation.

## Private Engine Access

The private implementation remains closed. Access to the private repository,
private release artifacts, benchmark internals, raw evidence bundles, or
commercial evaluation requires written permission from TWO HANDS NETWORK LTD and
may require a signed NDA.

Start with:

- [Access Request](ACCESS_REQUEST.md)
- [NDA Access Path](NDA_ACCESS.md)
- [Commercial Use](COMMERCIAL_USE.md)
- [Public Materials License](LICENSE.md)
- [Notice](NOTICE.md)
- [Trademarks](TRADEMARKS.md)

## Buyer And Reviewer Materials

- [Public proof one-pager](docs/public-proof-one-pager.md)
- [Evidence review guide](docs/evidence-review-guide.md)
- [Architecture overview](docs/architecture-overview.md)
- [Access request checklist](docs/access-request-checklist.md)
- [Access intake workflow](docs/access-intake-workflow.md)
- [Proof evidence checklist](docs/proof-evidence-checklist.md)
- [Publication runbook](docs/publication-runbook.md)
- [Proof scope](PROOF_SCOPE.md)
- [Publication checklist](PUBLICATION_CHECKLIST.md)
- [Release notes](RELEASE_NOTES.md)

## Proof Manifest

Published exports include `proof-manifest.json`. The manifest records the proof
version, evidence release, file hashes, directory hash, rights holder, and
publication-gate status for the exact public materials being reviewed.

## Publication Boundary

This repository exists so interested people can understand the shape of the work
without receiving the private engine.

The public proof kit can be cited, reviewed, and linked for evaluation. The
implementation, private release artifacts, benchmark internals, and commercial
use rights remain private unless granted separately in writing.
