---
name: evidence-first-resume
description: "Write, review, shorten, translate, and restructure resumes/CVs in English or Chinese. Favor concise, evidence-backed accomplishments; preserve facts, metrics, scope, ownership, and project status across all industries and roles."
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
