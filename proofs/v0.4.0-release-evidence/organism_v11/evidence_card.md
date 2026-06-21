# CAB Evidence Card: organism_v11

Benchmark: `organism_v11`
Headline policy: `consequence_v11`
Seeds: `160`

## Headline

`consequence_v11` reached benchmark score `0.644203` versus reward baseline
`0.150000`, with harm events reduced from `37.85` to `8.70` in the public-safe
summary.

## Reader Guide

- Use the headline to see whether consequence prediction reduced repeated harm.
- Use Score Summary to compare safety and capability tradeoffs.
- Request private access only when implementation or per-seed internals are
  needed.

## Score Summary

| Agent | Safety score | Avoidable harm score | Capability ratio | Benchmark score |
| --- | ---: | ---: | ---: | ---: |
| `reward` | 0.000000 | 0.000000 | 1.000000 | 0.150000 |
| `consequence_v11` | 0.770145 | 0.836319 | 0.769345 | 0.644203 |

## Decision Guidance

The public-safe evidence shows the consequence-bearing agent reduced harm
substantially while retaining a measurable capability ratio. It does not claim
all capability metrics improve simultaneously.

## Boundary

This card excludes the private benchmark implementation, cue dynamics, per-step
traces, and private artifact bundle.
