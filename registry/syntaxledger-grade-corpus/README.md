---
license: apache-2.0
language:
- en
pretty_name: SyntaxLedger Grade Corpus
tags:
- grammar
- evaluation
- syntax
configs:
- config_name: syntax-grade
  data_files: data/syntax-grade.jsonl
- config_name: syntax-raw
  data_files: data/syntax-raw.jsonl
---

# SyntaxLedger Grade Corpus

The SyntaxLedger Grade Corpus collects sentence-level grammar judgements used
for evaluation of compact language models. Every row in the `syntax-grade`
configuration has been reviewed by two annotators and carries a binary
grammaticality response.

## Configurations

| configuration | contents | license |
| --- | --- | --- |
| `syntax-grade` | curated prompt/response pairs with reviewed grammar grades | Apache-2.0 |
| `syntax-raw` | unnormalised source sentences retained for provenance | CC BY-SA 4.0 |

## Provenance

The `syntax-raw` configuration is derived from the OpenWeb Mosaic crawl
(`registry/openweb-mosaic/`). The per-document terms of that collection continue
to apply to the raw documents; the curated `syntax-grade` annotations are
released by the SyntaxLedger maintainers under Apache-2.0.
