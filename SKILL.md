---
name: evidence-first-resume
description: "Write, review, shorten, translate, and restructure resumes/CVs in English or Chinese. Favor concise, evidence-backed accomplishments; preserve facts, metrics, scope, ownership, and project status across all industries and roles."
---

# Evidence-First Resume / 结果导向简历

A bilingual, role-agnostic agent skill. **Language rule:** Respond in the user's requested language; if unstated, follow the language of their prompt or working resume. Use the same factual evidence and claim strength in English and Chinese.

> **Core:** Problem → Action → Evidence/Impact. Keep real achievements visible without turning a resume into a tool inventory.

**Quick execution checklist / 快速执行检查**
1. Read the candidate's actual source materials; separate fact from assumption. / 先读事实来源。
2. Respect specified scope, sections, bullet counts, and language. / 尊重用户格式。
3. Give each bullet one distinct contribution and only essential technologies. / 一条一重点。
4. Describe confirmed outcome or verified capability, not invented improvement. / 只写可证实结果。
5. Separate deployed, implemented, tested, prototyped, designed, and proposed. / 区分实施状态。
6. Deliver copy-ready text first; keep commentary short. / 成品优先，解释简短。

---

# Evidence-First Resume — English Guide

## Purpose and activation
Use this skill to draft, critique, shorten, restructure, or translate a resume/CV. It is **role-agnostic**: do not impose a specific occupation, technology stack, or hiring rubric unless the user explicitly supplies one.

**Success criterion:** a reader can quickly understand what the candidate owned, which problem they addressed, what action they took, and what was actually delivered or verified. Optimize for clear evidence, not maximum keyword density.

## Operating rules (highest priority)
1. **Truth outranks polish.** Preserve supported facts, dates, metrics, scope, individual contribution, and project status. Never invent impact.
2. **One bullet, one main contribution.** Do not combine unrelated incidents or describe an entire architecture in a single bullet.
3. **Problem → Action → Evidence/Impact.** Prefer this reasoning pattern, but write naturally; no forced three-part syntax.
4. **Tools have a purpose.** Name only the 1–3 technologies essential to explain each action. Keep broader coverage in Skills.
5. **Outcomes need not be percentages.** Valid evidence includes shipped features, observed behavior, tests, recovered services, documented decisions, and usable operating capabilities.
6. **Respect the user's format.** Preserve explicitly chosen project selection, bullet counts, ordering, language, and sections unless asked to rethink them.
7. **Limit unnecessary commentary.** Deliver a polished, copy-ready revision first; explain only meaningful trade-offs or facts needing confirmation.

## Recommended resume layout
Use a clean, single-column, ATS-readable format by default. Adapt to the candidate and the user's requested structure.

- **Header:** name, working contact details, relevant professional links. Avoid unnecessary personal data.
- **Education:** institution, qualification, field, dates, and credible distinctions.
- **Work Experience:** organization, title, location/dates, selected accomplishments.
- **Projects:** project name, URL if relevant, and **explicit project status** (deployed product, local prototype, case study, research, etc.).
- **Skills:** group by function and evidence; normally 2–4 concise lines.
- **Certifications / Awards / Leadership:** include when they strengthen the story or are required by the user.

Order is flexible. Do not add sections simply because this list exists.

**Length guidance, not quotas:** lead experience usually 3–5 bullets; secondary experience 1–2; major project 3–4 (or more if warranted). English bullets often work at roughly 20–30 words, preferably 1–2 visual lines. These are defaults, **not** reasons to remove critical meaning or override the user's specified counts. For early-career English resumes, try a readable one-page layout first; use two balanced pages when justified, rather than shrinking text excessively.

## Writing accomplishments
Start with a concrete action verb and identify the most meaningful change.

> **[Action + ownership]** addressed **[specific problem]** through **[selective approach]**, leading to **[verified result or new capability]**.

The bracketed pattern is a drafting aid, **not** a literal sentence template. Lead with the strongest evidence when that scans better.

**Good evidence (highest specificity first):**
1. Recorded before/after metrics, counts, or outcomes **with the correct measurement scope**.
2. Completed and validated delivery: a working release, reproducible test suite, resolved incident, verified workflow.
3. Operational or stakeholder value: clearer diagnostics, traceable records, documented runbook, a decision informed by analysis.
4. Design or proposal: accurate decision rationale, trade-off analysis, or recommendation clearly labeled **not implemented**.

Use active verbs such as *Built, Implemented, Designed, Automated, Diagnosed, Resolved, Validated, Integrated,* and *Analyzed*. Use *Led, Owned, Productionized,* and *Improved* only if evidence supports that degree of responsibility and outcome.

Avoid vague expressions (*responsible for, familiar with, various, significantly improved*) without substantiation. Keep only the most distinctive verified numbers; multiple log values are usually interview detail, not resume copy.

### Before / after example (fictional placeholders)
**Weak:** Used Python, queues, databases, cloud services, and dashboards for a distributed platform.

**Better:** Built a [specific monitoring workflow] using [two key tools] to consolidate [fragmented signals], giving operators [demonstrated diagnostic capability].

**Better with a measured result:** Automated [manual process] with [key tool], reducing [verified failure mode] from [baseline] to [observed result].

Never replace the bracketed placeholders with fabricated numbers.

## Selecting and differentiating content
For every candidate bullet, ask:
- Does it reveal a real problem, meaningful delivery, decision, or contribution?
- Is the **candidate's** involvement clear rather than implying sole ownership of team work?
- Does it contribute a distinct capability, instead of repeating another bullet?
- Does the evidence survive technical follow-up?
- Is the detail important for a ten-second scan, or better saved for an interview?

Prioritize the strongest work; remove redundant tool lists. Give each experience a distinct narrative (delivery, diagnosis, architecture trade-off, testing, operations, analysis, etc.) rather than using identical labels for all projects.

## Implementation-status vocabulary
**Keep these claims separate:**
- **Deployed / productionized:** actually running in the stated environment.
- **Implemented / built:** completed code or functionality; does not alone imply production usage.
- **Validated / tested:** backed by tests or an experiment within the stated scope.
- **Prototyped locally:** demonstrated in a local prototype, not an AWS/cloud production deployment.
- **Designed / proposed / recommended:** architecture or remediation not necessarily implemented.
- **Investigated:** determined findings or likely cause; not automatically resolved.

A successful controlled experiment is **not** a long-term uptime/SLO claim. A design for 15,000 hypothetical daily requests is **not** actual traffic. Proposed fixes cannot become resolved incidents during editing.

## Skills section
Group capabilities by function (examples only): *Programming & Backend; Cloud & DevOps; Databases & Distributed Systems; Reliability & Testing*. Choose categories to match **actual experience** and available space.

- List specific languages, platforms, databases, tools, and demonstrable practices.
- Keep a useful overlap with the work bullets for scanability, but do not duplicate every technology.
- Separate **hands-on** technologies from **architecture design only** when their inclusion could mislead.
- Do not add trendy tools, certifications, or generic soft skills without evidence.
- Respect explicit limits (for example: 2 lines in Chinese, 4 in English).

## English and Chinese versions
- Match the **output language requested by the user**; if unstated, follow the language of their request or working draft.
- Translate **meaning and claim strength**, not word-for-word structure. Keep dates, metrics, ownership, product names, and status identical.
- Favor idiomatic English and clear, concise Chinese.
- Translate 主导 as *Led* only with real leadership evidence; translate 已设计、已验证、已上线 and 建议 into appropriately distinct claim strengths.
- When asked for *text only*, return copy-ready text, not a document artifact or a long explanation.
- When asked for both languages, make both versions semantically equivalent.

## Fact-check gate (mandatory before finalizing)
Check the source resume and any supplied project evidence. Do not silently reconcile disagreements.

- Names, degrees, titles, dates, locations, awards, certifications, and URLs.
- Numbers and units, time windows, baselines, experiment versus production scope.
- Individual ownership versus collective delivery.
- Diagnosed versus fixed; documented versus automated; built versus deployed.
- Passed tests versus planned tests; feature-gated functionality versus enabled functionality.
- Prototype/architecture case study versus live production environment.
- Whether each named tool is supported by the supplied project evidence.

If versions conflict, use the latest **explicitly confirmed** source; otherwise flag the conflict briefly as **Needs verification**, without guessing. Do not invent uptime, latency, throughput, business revenue, cost savings, MTTR, or hiring/ATS scores.

## Layout and delivery checks
Use consistent spacing, capitalization, tense, dates, headers, and bullets. Make company/project, role, period, and evidence easy to scan. Avoid keyword-heavy bolding, icons, graphics, skill bars, and awkward page splits unless requested.

If creating DOCX/PDF, render the document and check page breaks, line wrapping, links, visual balance, and readability.

**Deliverable behavior:**
- **Edit one section:** return that complete revised section, with minimal explanation.
- **Edit entire resume:** return one coherent, copy-ready resume; do not scatter inline critiques into it.
- **Review:** give a clear conclusion, the top 2–4 issues, and replacement text where useful.
- **Translate:** preserve all claims and numbers across languages.
- **Generate a file:** only when requested; verify the output before linking.

## Never
Invent results; turn research into hands-on operations; upgrade proposals into deployments; overclaim leadership; force identical bullet lengths or counts; inflate a skills list; or produce a technical manual disguised as a resume.

**Final test:** For each line, can a reader explain what problem the candidate addressed, what they did, and what verifiable value resulted? If not, rewrite or remove it.

---

# Evidence-First Resume — 中文指南

## 使用场景与目标
用于编写、审阅、精简、重组、翻译各类简历（Resume/CV），**不预设特定岗位**。只有用户明确提出目标岗位或职位描述时，才针对性调整关键词与内容顺序。

目标是让读者快速看懂：**候选人负责了什么、解决了什么问题、采取了什么行动、实际交付或验证了什么结果。** 重证据，不堆名词。

## 最高优先级原则
1. **真实高于润色。** 保留可证实的日期、数字、项目范围、个人贡献及实施状态，不虚构任何结果。
2. **一条 Bullet 一项主要贡献。** 不把无关事故或整份架构说明塞进同一条。
3. **Problem → Action → Evidence/Impact。** 这是思考框架，不要求机械三段式。
4. **工具服务于问题。** 每条正文尽量只写 1–3 个关键工具，其他技能放入 Skills。
5. **结果不一定是百分比。** 已上线功能、验证测试、事故恢复、可追溯记录、可复用诊断流程都可能是有效成果。
6. **尊重用户约束。** 项目取舍、条数、顺序、语言、章节已有明确要求时，不擅自修改。
7. **先给可直接使用的成品。** 少做与请求无关的长篇解释，有事实冲突时简短标注。

## 内容结构与篇幅
默认采用简洁单栏、ATS 易解析的结构，视用户原稿调整顺序：

- **姓名与联系方式**：姓名、邮箱、电话、重要职业链接。
- **教育经历**：学校、学位/专业、时间、已核实的 GPA 或荣誉。
- **工作经历**：公司、职位、时间/地点、精选成果 Bullet。
- **项目经历**：项目名称、链接和项目类型，明确区分生产系统、本地原型、架构案例、研究。
- **Skills**：按实际能力用途分成通常 2–4 行。
- **证书 / 奖项 / 领导经历**：按重要性和篇幅安排，不强制出现。

默认参考：核心工作 3–5 条，次要经历 1–2 条，核心项目 3–4 条。英文 Bullet 常以 20–30 词、视觉上 1–2 行为目标；中文同样尽量保持 1–2 行。**这不是硬性规定，不能凌驾于真实含义和用户指定条数之上。**

早期职业阶段优先尝试可读的一页英文简历；内容确实丰富时用视觉均衡的两页，不靠缩小字体硬塞。

## Bullet 写法
参考表达：

> **[动作/承担责任]** 针对 **[具体问题]** 使用 **[最关键方案]** 完成 **[交付]**，形成 **[有证据的结果或能力]**。

按照实际情况自然组织，不强制每条以问题开头。优先保留最能让人记住的动词、具体产物与可信数字。

**证据优先级：**
1. 真实测量的前后变化或完成数，并写清测量范围。
2. 已交付且验证的功能、测试、部署或故障修复。
3. 实际运营价值：监控可追溯、排障更明确、支持决策等。
4. 架构设计与修复建议，必须标明尚未实施的状态。

谨慎使用“主导”“解决”“显著提升”“生产化”等强表述；只在证据支持时使用。没有性能百分比就写已验证的实际能力，**绝不编造数字**。

**示例（仅模板，不代表任何真实经历）：**

不佳：使用 Python、队列、数据库、云服务和仪表板维护分布式平台。

更好：基于[两个关键工具]构建[具体监控流程]，整合[分散信号]，使运营人员能够[已验证的诊断能力]。

如果没有已测量的提升，不应为了强化表达杜撰“降低 40%”等指标。

## 内容取舍与去重
逐条判断：是否有真实问题或有价值的交付？个人职责是否准确？是否与同一项目的其他 Bullet 重复？是否能经受技术追问？是否值得在快速浏览时看到？

优先选择能说明**交付、故障诊断、设计取舍、测试验证、运营结果**的不同贡献。重复技术名词可移至 Skills；过细的实现留到面试。

## 实施状态必须区分
- **Deployed/生产部署**：系统确实在指定环境运行。
- **Implemented/已实现**：功能或代码已完成，不等于上线。
- **Validated/已验证**：在明确的实验/测试范围内验证。
- **Local prototype/本地原型**：本地验证，不等于云上生产。
- **Designed/Proposed/Recommended/设计或建议**：没有自然推导成已实现。
- **Investigated/已调查**：得到故障发现，不自动等于已修复。

受控实验的成功率不能说成长期系统可用性；假设负载不能说成真实用户流量；功能开关默认关闭的代码不能写成已在生产全面启用。

## Skills 写法
按能力用途分类，如 Programming & Backend、Cloud & DevOps、Databases & Distributed Systems、Reliability & Testing；根据实际经历选择名称，不绑定岗位。

只写有事实支撑的语言、平台、数据库、工具与技能。关键技术在正文与 Skills 可以适度重复，但不要把每个名词都重复一遍。把仅用于架构设计、未部署的技术标注为 **Architecture Design** 等，不冒充实操经验。

用户要求两行就压缩为两行；允许英文版比中文版略展开，但必须遵守当次明确要求。

## 中英文转换
遵循用户请求的语言；未说明时参考用户本次语言或当前草稿。**优先保持事实与语气强度等价，而非逐字翻译。**

所有技术名称、数字、日期、职责范围和项目实施状态要一致。中文“主导”只有在事实支持时译为 *Led*；“已设计 / 已验证 / 已上线 / 建议”需对应不同英文动词。要求“直接输出文字”就给可复制稿，不擅自创建文件。

## 真实性终检（必须）
核对姓名、学校、日期、职位、证书、奖项、链接；数字、单位、测量范围；个人/团队贡献；排查/修复区别；已实现/已部署区别；已执行测试/计划测试区别；原型/生产环境区别。

如果多个版本的数字互相冲突，以用户**最新明确确认**的事实为准；否则标记“待核实”，**不擅自猜测**。不编造运行时间、成本、吞吐、可用性、MTTR、收益或 ATS 分数。

## 排版、质量检查和交付
单栏、层级清晰、日期格式统一、少量有意义的加粗。避免把项目标题与第一条拆页、第一页挤满而第二页留白、字体过小、装饰性图标或技能进度条。若生成 DOCX/PDF，应渲染检查分页、换行、链接及可读性。

- **只改一块内容**：直接输出完整修改稿，解释尽量简短。
- **整份简历**：输出连贯可复制版本，不在成品中穿插评论。
- **评价**：明确结论、最重要的 2–4 个问题及可替换文字。
- **翻译**：中英两版事实完全对应。
- **文件交付**：仅用户要求时创建，并验证成品。

**最终标准：每一行都能帮助读者回答——解决了什么问题、采取了什么行动、产出了什么可验证的价值。**
