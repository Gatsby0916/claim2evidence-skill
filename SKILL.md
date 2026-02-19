---
name: writing-ai-paper
description: End-to-end workflow for planning, drafting, revising, and pre-submission auditing of AI research papers. Use when users ask to transform ideas and experiment logs into a full manuscript, improve section quality (especially Introduction, Related Work, Method, and Experiments), tighten claim-evidence alignment, prepare rebuttal-ready material, or run reviewer-style quality checks before submission.
---

# Writing AI Paper

## Overview
Convert fragmented research notes into a clear, defensible manuscript. Prioritize novelty clarity, evidence coverage, and reviewer readability.

## Workflow Decision
Choose one mode before writing:
- Build mode: generate section drafts from notes, results, and target venue constraints.
- Improve mode: rewrite existing sections for logic flow, precision, and brevity.
- Audit mode: return only prioritized risks, missing evidence, and concrete fixes.

## Required Inputs
Collect these inputs first:
- target venue, deadline, and format constraints
- one-sentence thesis claim
- three to five concrete contributions
- experimental setup, baselines, and key metrics
- known limitations, failure cases, and scope boundaries
- must-cite related work clusters

If critical inputs are missing, ask focused questions before drafting full sections.

## Core Workflow
1. Frame claim and boundaries.
- State thesis as "We solve X with Y and improve Z under condition C."
- List explicit non-claims to avoid overreach.

2. Map claims to evidence.
- Create a claim-to-evidence table before long-form writing.
- Require at least one direct evidence item per contribution.

3. Build section blueprint.
- Assign one job sentence to each section.
- Ensure logical handoff across Abstract, Intro, Method, Experiments, and Conclusion.

4. Draft sections in high-yield order.
- Write Introduction and Experiments first.
- Write Method after experiment narrative stabilizes.
- Write Abstract and title last.

5. Run quality gates.
- Gate A: each claim is testable and scoped.
- Gate B: each table/figure is interpreted in prose.
- Gate C: limitations are explicit and non-defensive.
- Gate D: contribution wording is consistent across sections.

6. Prepare submission and rebuttal assets.
- Build concise claim-to-evidence map.
- Pre-write responses for likely reviewer objections.

## Output Contract
When generating output, always include:
- revised text or draft sections
- a short list of unresolved risks
- a concrete next-action checklist

## Resources
- Read `references/paper-writing-playbook.md` for templates, checklists, and anti-patterns.