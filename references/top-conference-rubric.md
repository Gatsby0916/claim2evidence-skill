# Top Conference Rubric

## Venue-Specific Emphasis
Use this quick rubric when tuning final draft:

| Venue family | Typical emphasis | Frequent rejection trigger |
| --- | --- | --- |
| NeurIPS / ICML / ICLR | methodological novelty + rigorous evidence | unclear novelty delta or weak ablations |
| CVPR / ICCV / ECCV | visual evidence + fair SOTA comparison | missing qualitative analysis or weak protocol parity |
| ACL / EMNLP / NAACL | task framing + generalization + error analysis | shallow related work positioning or weak analysis depth |
| KDD / WWW / WSDM | practical impact + scale + robustness | no real-world relevance or limited scalability evidence |

## Reviewer Questions You Must Pre-Answer
- What exact gap does this paper close?
- Why cannot strong baseline variants solve this already?
- Are comparisons fair in compute, data, and tuning budget?
- Which claims are robust across seeds/splits/domains?
- What limitations remain after this work?

## Top-Tier Submission Gates
Pass all gates:
- novelty statement appears early and is concrete
- strongest baseline set is present and fairly tuned
- main claim has ablation or theoretical support
- uncertainty/variance handling is explicitly described
- limitations and failure analysis are visible in main text

## Rebuttal Response Pattern
Use this structure per reviewer point:
1. acknowledge question in one sentence
2. answer with direct evidence from paper/supplement
3. add minimal clarifying text if ambiguity caused concern
4. avoid introducing large new claims unsupported by experiments

## Red Flags Before Submit
- key baseline missing due to time pressure
- negative results removed instead of explained
- contribution bullets broader than experiment coverage
- appendix carries critical proof that should be in main text