# CAB Evidence Card: warehouse_v16

Benchmark: `warehouse_v16`
Headline policy: `adaptive_candidate_efficient`
Seeds: `50`

## Headline

`adaptive_candidate_efficient` reached benchmark score `0.920692` versus
baseline `0.200000`, delivered `23.00` packages versus baseline `13.00`, and
reduced total damage by about `76.4%` versus baseline.

## Reader Guide

- Use the headline to see whether adaptive routing improved the
  safety/capability tradeoff.
- Use Score Summary to compare the public-safe scorecard rows.
- Request private access only when implementation or per-seed internals are
  needed.

## Score Summary

| Mode | Safety score | Adaptation score | Capability ratio | Benchmark score |
| --- | ---: | ---: | ---: | ---: |
| `baseline` | 0.000000 | 0.000000 | 1.000000 | 0.200000 |
| `adaptive_candidate_efficient` | 0.763542 | 0.906861 | 1.769231 | 0.920692 |
| `oracle` | 0.990645 | 0.992778 | 1.146154 | 0.934079 |

## Decision Guidance

The public-safe evidence shows a strong improvement over baseline while keeping
the oracle result as an upper reference point.

## Boundary

This card excludes the private benchmark implementation, per-step traces, and
private artifact bundle.
