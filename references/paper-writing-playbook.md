# AI Paper Writing Playbook

## Intake Questions
Ask these first when context is incomplete:
- What venue is targeted, and what is the submission date?
- What is the single strongest thesis claim?
- What evidence exists for each contribution?
- Which baselines are mandatory in this subfield?
- Which known failure modes must be disclosed?

## Claim-Evidence Table
Build this table before drafting final prose:

| Claim | Evidence | Scope | Risk if challenged |
| --- | --- | --- | --- |
| contribution 1 | main result table, ablation | where it holds | missing baseline / weak significance |
| contribution 2 | robustness study | tested conditions | external validity gap |

Do not keep claims that have no hard evidence.

## Introduction Template
Write in this order:
1. Problem and stakes.
2. Gap in existing approaches.
3. Core method intuition.
4. Main result preview.
5. Contribution bullets with measurable wording.

## Related Work Strategy
Structure by approach families, not timeline:
- family A: strengths, limits, relevance
- family B: strengths, limits, relevance
- family C: strengths, limits, relevance

End with a direct contrast paragraph explaining why the proposed method is necessary.

## Method Section Rules
- Define notation once and keep symbols stable.
- Justify major design choices with expected effect.
- Surface assumptions about data, compute, and deployment.
- Include concise pseudocode when execution flow can be misread.

## Experiment Section Order
Use this order:
1. Evaluation questions.
2. Datasets, metrics, and setup.
3. Main results.
4. Ablations and sensitivity.
5. Efficiency profile.
6. Error analysis and failure cases.

Interpret every major table and figure in text.

## Quality Gates
Pass all gates before submission:
- Claims are scoped to tested conditions.
- Baseline comparisons are fair and reproducible.
- Limitations are explicit and not hidden in appendix only.
- Abstract, Intro, and Conclusion use aligned contribution wording.
- Reviewer can identify novelty in under two minutes.

## Pre-Submission Checklist
- Verify table/figure numbering and in-text references.
- Verify metric definitions and units.
- Remove vague adjectives and repeated claims.
- Verify formatting and anonymization constraints.
- Re-check contribution bullets against final results.

## Rebuttal Prep
Keep these artifacts ready:
- claim-to-evidence map
- likely reviewer objections and factual responses
- boundary statements for what is not claimed

## Anti-Patterns
Avoid these mistakes:
- novelty claim without clear problem framing
- results dump without interpretation
- over-claiming beyond tested scope
- omitting negative cases likely to be noticed by reviewers