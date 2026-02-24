# AR/VR/XR Top Venue Rubric

## Venue-Specific Emphasis
Use this quick rubric when tuning AR/VR/XR submissions:

| Venue family | Typical emphasis | Frequent rejection trigger |
| --- | --- | --- |
| IEEE ISMAR | technical novelty in 3D registration/tracking/interaction + strong real-world validation | limited realism, weak baselines, or unclear deployment setting |
| IEEE VR | immersive interaction quality + user-study rigor + system performance | underpowered user study or poor reporting of latency/comfort |
| ACM VRST | interaction technique novelty + prototyping quality + empirical support | insufficient evaluation depth or missing comparison to strong prior techniques |
| CHI / UIST (XR papers) | human-centered problem framing + study validity + design implications | weak task relevance, insufficient triangulation, or unclear contribution delta |
| SIGGRAPH / Eurographics (XR systems/graphics) | rendering/system innovation + visual fidelity + performance trade-offs | missing ablations or unrealistic runtime conditions |

## Reviewer Questions You Must Pre-Answer
- What exact XR scenario is targeted, and why is that scenario important now?
- Are hardware constraints (HMD type, controllers, tracking setup) clearly specified?
- Is motion-to-photon latency measured and reported with reproducible methodology?
- Are comfort and safety considerations (e.g., cybersickness, fatigue) measured and discussed?
- Does the evaluation compare fairly against strong interaction/system baselines?

## XR Experiment Reporting Minimum Bar
- Report device model, refresh rate, runtime environment, and sensing setup.
- Report sample size, recruitment criteria, inclusion/exclusion rules, and study power rationale when possible.
- Provide latency/performance metrics with measurement protocol.
- Include at least one failure analysis (tracking loss, occlusion, interaction breakdown, etc.).
- Distinguish objective metrics (task time/error) from subjective metrics (workload, presence, comfort).

## Rebuttal Response Pattern (XR)
1. acknowledge concern and restate tested XR condition
2. point to exact quantitative/qualitative evidence
3. clarify hardware/protocol details if ambiguity exists
4. avoid broad generalization beyond tested devices/populations

## Red Flags Before Submit
- no explicit reporting of runtime latency or frame stability
- user study lacks baseline task parity or balanced counterbalancing
- comfort/safety issues are omitted despite immersive interaction claims
- novelty claim is mostly implementation engineering without validated research delta
