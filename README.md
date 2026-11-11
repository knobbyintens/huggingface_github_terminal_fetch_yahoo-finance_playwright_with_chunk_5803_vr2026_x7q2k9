# Verdant Syntax Pairs — release packet

Release ID: `VR-2026-11`
Owner: Verdant Language Lab — release operations

This repository is the working packet for this quarter's open-data release of
the `verdant-syntax-pairs` dataset.

## Contents

- `release_card.json` — machine-readable release record.
- `data/sample_pairs.jsonl` — a small sample of the rows being released.
- `procurement/` — purchasing materials for the annotation QA workstation
  refresh used during release validation.
- `decisions/` — signed-off release decisions.

## Upstream resources

The registry cards for the upstream resources are catalogued in this
repository under `registry/`:

| role | registry path |
| --- | --- |
| direct data lineage | `registry/syntaxledger-grade-corpus/` |
| second-order lineage | `registry/openweb-mosaic/` |
| synthesis model card | `registry/cinder-n2/` |

Each card directory contains a `README.md` describing the resource, together
with its metadata file and any data or licence files it references.

Responses in this release were synthesized with the hosted chat model
Cinder-N2-Small, because it offers top-tier quality at low cost.
