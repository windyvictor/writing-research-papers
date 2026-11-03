# writing-research-papers

English | [中文](README.cn.md)

An end-to-end research-paper and literature-review writing skill covering search records, synthesis, argument design, section drafting, revision, submission, review responses, and thesis preparation.

## Use it for

- Writing or revising a paper, thesis, or individual section
- Building a literature matrix and argumentative review
- Recording searches and tracing claims to source passages
- Checking claim-evidence alignment
- Revising abstracts, introductions, methods, experiments, discussions, and conclusions
- Preparing cover letters, reviewer responses, and defense materials
- Designing a systematic review or bibliometric workflow when explicitly requested

## Scope-sensitive workflow

A paragraph edit stays a paragraph edit. A theoretical paper is not forced into IMRaD. Ordinary background research uses a lightweight search record; systematic reviews use complete database queries, deduplication, screening decisions, and applicable PRISMA reporting.

## Contents

- `SKILL.md`: task routing and evidence rules
- `references/search-and-evidence-record.md`: search and claim traceability
- `references/literature-review-workflow.md`: review workflow
- `references/systematic-review-and-bibliometrics.md`: specialized review boundary
- `references/introduction.md`, `abstract.md`, `method.md`, `experiments.md`: section guides
- `references/examples/`: real-paper pattern library
- `scripts/check_manuscript.py`: mechanical manuscript hints
- `evals/`: behavioral cases

## Core rule

Match evidence to the type of claim. Theoretical claims require definitions, assumptions, and proofs; empirical claims require data and analysis; literature claims require source verification. Do not infer novelty from a search miss.

## Quick check

```bash
python3 scripts/check_manuscript.py manuscript.md
```

The checker reports mechanical hints. It does not assess scientific validity or guarantee acceptance.

## Install

```bash
git clone https://github.com/windyvictor/writing-research-papers.git
ln -s "$PWD/writing-research-papers" ~/.agents/skills/writing-research-papers
```

## License

MIT. Public examples, quotations, and third-party writing guides retain their original rights.

