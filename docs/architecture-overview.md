# Architecture Overview

This is a public-safe architecture overview. It describes the shape of the
private benchmark engine without publishing its implementation.

## Core Idea

CAB evaluates whether agent policies can reduce harmful consequences while
preserving useful capability. It packages benchmark runs into reproducible
evidence so reviewers can inspect the result, validation status, hashes, and
leaderboard entry without needing API access.

The private engine currently contains these product concepts:

- benchmark families for routing, internal-state adaptation, resource
  allocation, and delayed harm
- built-in baseline and consequence-aware policies
- adapter evaluation for local, recorded/manual, and future API-backed agents
- evidence packages with manifests, hashes, and reproducibility metadata
- batch validation and checksum-indexed leaderboard reports
- release provenance, SBOM, and release-readiness gates

## Public Benchmark Domains

The proof kit uses four public-safe domains:

- warehouse routing under shifting hidden fault zones
- organism/internal-state adaptation under cue reversal
- resource allocation with safety debt
- multi-step planning with delayed harms

These are benchmark and proof surfaces. They are not the only possible use
cases.

## Private Implementation Boundary

This repository does not include:

- source code
- algorithms
- benchmark internals
- private package artifacts
- private release automation
- unpublished notebooks

The architecture overview is intentionally high level.
