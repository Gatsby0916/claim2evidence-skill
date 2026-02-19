---
name: writing-ai-paper
description: End-to-end workflow for top-tier AI conference paper development, from idea framing to rebuttal preparation. Use when users need to draft, rewrite, or audit papers for NeurIPS, ICML, ICLR, CVPR, ECCV, ACL, EMNLP, or similar venues; align claims with evidence; strengthen novelty positioning; improve experimental rigor and reproducibility; and run final pre-submission and rebuttal checks.
---

# Writing AI Paper

## Overview
Transform scattered research notes into a top-conference-ready manuscript with strong novelty framing, rigorous evidence, and reviewer-friendly clarity.

## Choose Working Mode
Select one mode before producing content:
- Build mode: generate sections from notes, logs, and result tables.
- Improve mode: rewrite existing sections for stronger argument flow and precision.
- Audit mode: output prioritized risks, missing evidence, and repair actions.

## Collect Required Inputs
Collect these inputs first:
- target venue, track, deadline, and page/format limits
- one-sentence thesis claim and explicit non-claims
- 3-5 contributions with measurable success criteria
- datasets, baselines, metrics, and compute budget
- ablations, robustness tests, and failure cases
- reproducibility artifacts (code status, seed policy, config completeness)

If critical inputs are absent, ask focused questions before drafting full text.

## Top-Conference Workflow
1. Frame contribution bar.
- Define why the problem matters now.
- State novelty against strongest nearby baselines.
- Scope claims to tested conditions only.

2. Build claim-evidence map.
- Create a table linking each contribution to exact evidence.
- Reject contributions without direct empirical or theoretical support.

3. Draft high-impact sections first.
- Draft Introduction and Experiments before Method details.
- Draft Method only after evaluation questions stabilize.
- Draft Abstract and title after core claims settle.

4. Enforce experiment rigor.
- Ensure baseline fairness and hyperparameter transparency.
- Include multiple seeds or uncertainty reporting when applicable.
- Cover ablations, sensitivity, efficiency, and error analysis.
- Explain each major table/figure in prose.

5. Enforce venue constraints.
- Fit page limits without hiding critical evidence.
- Verify anonymization and supplemental policy compliance.
- Align terminology with venue community expectations.

6. Prepare rebuttal assets.
- Pre-build claim-to-evidence matrix.
- Pre-list likely reviewer objections and factual responses.
- Keep concise appendix pointers for disputed points.

## Section Rules
Apply these rules when generating or rewriting:
- Introduction: problem stakes -> prior gap -> method intuition -> main evidence -> contribution bullets.
- Related Work: compare by approach families, not timeline.
- Method: explain design choices, assumptions, and complexity tradeoffs.
- Experiments: organize by evaluation questions, not by random table order.
- Conclusion: restate scope-limited takeaways and boundaries.

## Quality Gates
Pass all gates before final output:
- novelty is explicit within first two paragraphs of Introduction
- each contribution is testable and evidenced
- claims remain consistent across Abstract, Intro, and Conclusion
- limitations are explicit and technically honest
- reviewer can identify the paper's delta in under two minutes

## Output Contract
Always return:
- revised section text or full draft block
- high-severity risks first
- specific next-step checklist with fix priority

## Resources
- Read `references/paper-writing-playbook.md` for templates and submission workflows.
- Read `references/top-conference-rubric.md` for venue-level review expectations and final checks.
- Read `references/official-links.md` when user asks for official conference/CFP/author-guide URLs.