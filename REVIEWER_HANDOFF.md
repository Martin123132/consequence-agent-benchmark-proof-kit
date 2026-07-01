# Reviewer Handoff

This page is the shortest path for a reviewer seeing Consequence Agent
Benchmark, or CAB, for the first time.

## What CAB Is

CAB is a private-core benchmark technology for evaluating whether agent
policies reduce downstream harm while preserving useful capability.

The private engine runs benchmark scenarios, packages evidence, validates
hashes, compares runs, and produces local/static leaderboard reports.

## What Is Public

This proof kit is public-safe evidence, not the engine source code.

It includes:

- the CAB claim and product boundary;
- public-safe evidence cards from the `v0.4.0` release-readiness checkpoint;
- local leaderboard evidence;
- file, directory, and manifest hashes;
- access, NDA, commercial-use, and licensing notes.

Start with:

1. [Why CAB](WHY_CAB.md)
2. [Evidence map](EVIDENCE_MAP.md)
3. [Public proof one-pager](docs/public-proof-one-pager.md)
4. [Five-minute reviewer walkthrough](docs/reviewer-walkthrough.md)
5. [Proof manifest](proof-manifest.json)

## What Remains Private

The public proof kit does not include:

- private engine source code;
- private benchmark internals;
- raw private evidence bundles;
- private release wheels or source distributions;
- private prompts, traces, credentials, customer material, or NDA documents;
- commercial-use rights.

## What The Hashes Prove

The proof manifest records every public file included in this checkpoint. The
directory hash ties those files together, and the manifest hash ties the
manifest to the exact public proof export.

Current public proof identifiers are recorded in
[proof-manifest.json](proof-manifest.json). The headline public evidence is in
[proofs/v0.4.0-release-evidence](proofs/v0.4.0-release-evidence/README.md).

## How To Verify

For a public review:

1. Confirm the README, evidence map, evidence cards, and proof manifest are
   present.
2. Check that `proof-manifest.json` lists the files being reviewed.
3. Confirm the publication-gate checks in the manifest are passing.
4. Compare any copied or archived proof kit against the published manifest,
   directory hash, and file hashes.

For a deeper private review, ask for a sanitized reviewer bundle or private
technical walkthrough. Direct private engine access is reserved for approved
cases and may require an NDA.

## How To Request Access

Use [ACCESS_REQUEST.md](ACCESS_REQUEST.md) for private verification, technical
review, pilot discussion, or commercial licensing.

Commercial use requires separate written permission from TWO HANDS NETWORK LTD.
Contact details are listed in [LICENSE.md](LICENSE.md) and
[COMMERCIAL-LICENSE.md](COMMERCIAL-LICENSE.md).
