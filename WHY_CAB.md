# Why CAB

Most agent evaluations ask whether an agent completes a task. CAB asks a
different question: does the agent preserve useful capability while reducing
downstream harm?

CAB exists because many real failures are not single bad actions. They are
chains of small choices that create safety debt, stale assumptions, hidden
damage, or delayed harm. A useful benchmark should make those patterns visible
without requiring a hosted service or private API access.

## The Product Idea

CAB is a private-core benchmark engine with public-safe proof materials. The
private engine runs controlled benchmark scenarios, packages evidence, validates
hashes, compares runs, and produces local/static reports. The public proof kit
shows enough of that evidence story for review without publishing the engine.

## What Makes It Different

- It measures consequence reduction, not only task completion.
- It keeps capability in view, so safety does not mean doing nothing.
- It produces auditable files, hashes, manifests, and reproducibility metadata.
- It supports no-API review paths through recorded/manual adapters.
- It keeps commercial use and private engine access behind written permission.

## Who It Is For

- technical reviewers deciding whether CAB is worth deeper review;
- AI teams looking for consequence-aware evaluation methods;
- investors or partners checking whether the benchmark has product shape;
- commercial teams considering a private pilot or licensing discussion.

## What To Read Next

Start with [EVIDENCE_MAP.md](EVIDENCE_MAP.md), then follow the
[five-minute reviewer walkthrough](docs/reviewer-walkthrough.md).
