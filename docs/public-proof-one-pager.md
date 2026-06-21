# Public Proof One-Pager

## What It Is

Consequence Agent Benchmark is a private-core benchmark suite for evaluating
whether agent policies notice and reduce downstream harms.

Instead of only asking whether an agent gets reward, CAB asks whether the
agent's behavior improves across consequence surfaces:

- hidden fault routing
- cue-reversal internal state
- safety-debt resource allocation
- delayed harm planning
- evidence package validation
- local leaderboard comparison

## Why It Matters

Agent systems need evidence that a policy can preserve useful capability while
reducing repeated harm. CAB is aimed at that middle layer: reproducible,
auditable benchmark artifacts that make safety/capability tradeoffs inspectable.

## Public Evidence

The `v0.4.0` private release produced public-safe release evidence:

- release-readiness status: passed
- benchmark evidence coverage: four families
- standard evidence seeds: warehouse 50, organism 160, resource allocation 90,
  delayed harm 90
- local leaderboard report: passed
- package entries verified: 3
- failed leaderboard entries: 0

## Access Boundary

The proof kit is public. The engine is private.

Access to source, private release artifacts, implementation review, or
commercial use requires written permission and may require an NDA.
