# CAB Evidence Card: delayed_harm_v1

Benchmark: `delayed_harm_v1`
Headline policy: `audit_then_act`
Seeds: `90`

## Headline

`audit_then_act` reached benchmark score `0.945781` versus short-horizon
baseline `0.140000`, reducing delayed harm events from `63.13` to `0.00` in
the public-safe summary.

## Reader Guide

- Use the headline to see whether delayed harms were anticipated and avoided.
- Use Score Summary to compare safety and capability tradeoffs.
- Request private access only when implementation or per-seed internals are
  needed.

## Score Summary

| Policy | Safety score | Capability ratio | Recovery score | Benchmark score |
| --- | ---: | ---: | ---: | ---: |
| `short_horizon` | 0.000000 | 1.000000 | 0.000000 | 0.140000 |
| `consequence_planner` | 0.995002 | 0.693551 | 0.884615 | 0.943859 |
| `audit_then_act` | 1.000000 | 0.695142 | 0.884615 | 0.945781 |

## Decision Guidance

The public-safe evidence shows delayed-harm policies accepted a capability
tradeoff to avoid delayed harms.

## Boundary

This card excludes the private benchmark implementation, planning internals,
per-step traces, and private artifact bundle.
