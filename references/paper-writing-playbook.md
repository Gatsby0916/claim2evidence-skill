# AI Paper Writing Playbook

## Intake Questions
Ask these first:
- Which venue and track are targeted?
- What is the strongest one-line thesis?
- Which evidence supports each contribution?
- Which baselines are non-negotiable for this subfield?
- Which failure modes or negative results must be disclosed?

## Claim-Evidence Matrix
Build this before long-form writing:

| Claim | Evidence | Scope boundary | Reviewer risk |
| --- | --- | --- | --- |
| C1 | main table + ablation | tested setting only | missing baseline fairness |
| C2 | robustness study | specific data conditions | weak external validity |

Drop claims without hard evidence.

## Introduction Blueprint
Write in this order:
1. Problem stakes and urgency.
2. Gap in prior lines of work.
3. Core method intuition.
4. Main evidence preview.
5. Contribution bullets with measurable language.

## Related Work Blueprint
Group by approach families:
- family A: strengths, limits, relevance
- family B: strengths, limits, relevance
- family C: strengths, limits, relevance

End with direct contrast: why existing methods are insufficient and why this method is needed.

## Method Blueprint
- Keep notation stable and minimal.
- Justify each major design choice.
- State assumptions on data, compute, and deployment.
- Add concise pseudocode when implementation flow is easy to misread.

## Experiment Blueprint
Use this order:
1. Evaluation questions.
2. Datasets, metrics, and setup.
3. Main results.
4. Ablations and sensitivity.
5. Efficiency profile.
6. Error analysis and failure cases.

Interpret every key number in text.

## Reproducibility Minimum Bar
- report all main hyperparameters
- specify seed policy or variance reporting strategy
- clarify preprocessing and filtering rules
- provide environment and dependency versions
- ensure table numbers can be regenerated from logged runs

## Final Pass Checklist
- align claim wording across Abstract/Intro/Conclusion
- verify figure/table references and captions
- verify metric definitions and units
- remove vague adjectives and unsupported superlatives
- verify anonymization and supplemental policy constraints

## Rebuttal Prep Pack
Prepare these before review release:
- one-line evidence answer per contribution
- list of likely objections with factual responses
- compact appendix pointers for disputed details

## Anti-Patterns
Avoid these failures:
- novelty claim without clear delta against strongest baselines
- results dump with little interpretation
- over-claiming beyond tested scope
- hiding failure cases likely noticed by reviewers