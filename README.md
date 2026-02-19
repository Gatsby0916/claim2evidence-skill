# claim2evidence-skill

An AI-paper writing skill for top conferences: turn ideas and experiment logs into clear, evidence-backed, submission-ready drafts.

## Why I Built This
I built this repository to solve a recurring problem in my own workflow: I often have strong experiments but weak narrative structure under deadline pressure. This skill helps me turn scattered notes into a defensible paper with explicit claim-evidence alignment.

## What Is Inside
- `SKILL.md`: Core workflow with three modes (`Build`, `Improve`, `Audit`).
- `references/paper-writing-playbook.md`: Practical drafting templates and execution checklists.
- `references/top-conference-rubric.md`: Top-conference review expectations, rejection risks, and rebuttal patterns.
- `references/official-links.md`: Curated official conference and submission links.
- `agents/openai.yaml`: UI metadata for skill invocation.

## Official Links (Quick Access)
I keep official conference and submission resources in `references/official-links.md`.

Common entry points:
- NeurIPS: https://neurips.cc/
- ICML 2026: https://icml.cc/Conferences/2026
- ICLR 2026: https://iclr.cc/Conferences/2026
- CVPR 2026: https://cvpr.thecvf.com/Conferences/2026
- ECCV 2026: https://eccv.ecva.net/Conferences/2026
- ACL 2026: https://2026.aclweb.org/
- OpenReview Venues: https://openreview.net/venues
- ARR: https://aclrollingreview.org/

## How I Use It
Prompt examples:
- `$writing-ai-paper Draft Introduction + Experiments from my run logs, and start with a claim-evidence map.`
- `$writing-ai-paper Rewrite my Related Work to clarify positioning against the strongest baselines.`
- `$writing-ai-paper Audit my full draft with top-conference standards and return only high-severity issues.`
- `$writing-ai-paper Check official conference policy links first, then give me a final pre-submission checklist.`

## Writing Principles I Enforce
- Define claims before writing paragraphs.
- Keep every contribution backed by hard evidence.
- Make failure cases and limitations explicit.
- Treat rebuttal preparation as part of pre-submission work.
- Re-check official conference pages at every critical milestone.

## Scope
This skill is mainly designed for AI paper writing in machine learning, computer vision, and NLP. The structure is reusable in other fields, but domain-specific evaluation and review standards should be replaced accordingly.