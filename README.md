# Writing AI Paper Skill

这是我维护的一个 **AI 顶会论文写作 Skill**。

我做这个仓库的目标很直接：当我手里只有实验日志、草稿段落和一些零散思路时，我希望能快速产出一份结构清晰、证据充分、能经得起 reviewer 追问的论文初稿，并且能在投稿前做系统化自检。

## 我希望它解决什么问题
- 我经常卡在“有结果但讲不清楚贡献”。
- 我经常在投稿前才发现 claim 和 evidence 对不上。
- 我希望写作流程对齐 NeurIPS / ICML / ICLR / CVPR / ACL 这类顶会标准，而不是泛泛而谈。

## 这个仓库里有什么
- `SKILL.md`：核心工作流（Build / Improve / Audit 三种模式）
- `references/paper-writing-playbook.md`：论文写作模板与可执行检查清单
- `references/top-conference-rubric.md`：顶会导向评审标准、拒稿高风险点与 rebuttal 模式
- `agents/openai.yaml`：Skill UI 元信息

## 我如何使用
示例提示词：
- `$writing-ai-paper 用我的实验记录起草 Introduction + Experiments，先给 claim-evidence map`
- `$writing-ai-paper 重写我的 Related Work，突出和最强 baseline 的差异`
- `$writing-ai-paper 用顶会标准审计我的全文，只输出高优先级风险`

## 我当前的写作原则
- 我先定义 claim，再写段落。
- 我坚持“每条贡献都能定位到硬证据”。
- 我把失败案例和限制写在明处，而不是藏起来。
- 我把 rebuttal 当成投稿前就要准备的资产，而不是事后补救。

## 适用范围
我主要针对机器学习、计算机视觉、NLP 等 AI 论文写作场景设计它；如果是其他学科，也可以复用结构，但需要替换相应的实验与评审标准。