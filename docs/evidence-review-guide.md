# Evidence Review Guide

Use this guide to decide whether the public evidence is enough, or whether you
need private verification.

## Review Order

Start with the suite evidence:

- [v0.4.0 release evidence](../proofs/v0.4.0-release-evidence/README.md)

Then inspect the benchmark cards:

- [warehouse routing](../proofs/v0.4.0-release-evidence/warehouse_v16/evidence_card.md)
- [organism state](../proofs/v0.4.0-release-evidence/organism_v11/evidence_card.md)
- [resource allocation](../proofs/v0.4.0-release-evidence/resource_allocation_v1/evidence_card.md)
- [delayed harm planning](../proofs/v0.4.0-release-evidence/delayed_harm_v1/evidence_card.md)

Finally, inspect [proof-manifest.json](../proof-manifest.json) to confirm the
published files and hashes for the exact public checkpoint.

## Reading The Evidence

Use the release evidence for the release-readiness answer.

Use the leaderboard proof for evidence package validation:

- package entries
- package types
- benchmark coverage
- source zip hashes
- manifest hashes
- reproducibility hashes

Use the benchmark cards for behavior summaries:

- benchmark score
- safety score
- capability or service ratio
- headline tradeoff
- what the proof does and does not claim

## What Passed

The public-safe `v0.4.0` evidence shows:

- release-readiness status passed
- four benchmark families validated
- wheel and source distribution existed
- release provenance verified
- release SBOM validated
- local leaderboard report verified three package entries with zero failed
  entries

## What To Ask For Privately

If you need to review implementation, benchmark internals, private artifacts, or
raw evidence bundles, use [ACCESS_REQUEST.md](../ACCESS_REQUEST.md).

Good private-review requests are specific:

- which claim you want verified
- whether you need evidence only, a technical walkthrough, or source review
- whether the review is commercial, academic, investor, or internal diligence
- whether an NDA can be signed before private materials are shared
