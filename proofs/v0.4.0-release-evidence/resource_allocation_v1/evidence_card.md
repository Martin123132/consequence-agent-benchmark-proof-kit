# CAB Evidence Card: resource_allocation_v1

Benchmark: `resource_allocation_v1`
Headline policy: `consequence_guard`
Seeds: `90`

## Headline

`consequence_guard` reached benchmark score `0.946523` versus greedy baseline
`0.180000`, while reducing total harm from `224.42` to `24.88` in the
public-safe summary.

## Reader Guide

- Use the headline to see whether safety debt was controlled without collapsing
  service.
- Use Score Summary to compare policy tradeoffs.
- Request private access only when implementation or per-seed internals are
  needed.

## Score Summary

| Policy | Safety score | Service ratio | Recovery score | Benchmark score |
| --- | ---: | ---: | ---: | ---: |
| `greedy_growth` | 0.000000 | 1.000000 | 0.000000 | 0.180000 |
| `balanced` | 0.889129 | 0.983192 | 1.000000 | 0.940848 |
| `consequence_guard` | 0.889129 | 0.983192 | 1.000000 | 0.946523 |

## Decision Guidance

The public-safe evidence shows safety-debt controls sharply reduced harm while
preserving service close to the greedy reference.

## Boundary

This card excludes the private benchmark implementation, policy internals,
per-step traces, and private artifact bundle.
