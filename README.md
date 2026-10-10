# Evidence-First Resume

A reusable **bilingual (English + Chinese)** Agent Skill for creating, reviewing, translating, and simplifying resumes without sacrificing technical substance or factual accuracy.

**Core philosophy:** **Problem → Action → Evidence / Impact**. Show what you solved and verified—not a long inventory of tools.

## Choose a guide / 选择语言

| File | Description |
| --- | --- |
| [**SKILL.md**](./SKILL.md) | **Canonical bilingual skill**: full English and Chinese instructions in one file. Recommended default for agents. |
| [**SKILL.en.md**](./SKILL.en.md) | Complete **English-only** version for English-language workflows. |

The skill is **role-agnostic** and applies to engineering, business, analytics, and other resumes. It does not assume a job description unless you supply one.

## What it covers

- Concise, results-oriented bullet points, typically **Problem → Action → Evidence/Impact**.
- Selecting distinctive achievements, avoiding repetition and technology keyword overload.
- Resume structure: Education, Experience, Projects, Skills, Certifications, and optional sections.
- Length and formatting guidance that **defers to the user's requested bullet counts and constraints**.
- Skills grouped by demonstrated function, not arbitrary keyword lists.
- Exact distinction among **deployed**, **implemented**, **validated**, **prototyped**, **designed**, and **proposed** work.
- English ↔ Chinese translation with equivalent facts, responsibility, and claim strength.
- Mandatory checks for metrics, dates, ownership, implementation status, and layout.

## How to use

Add the content of [`SKILL.md`](./SKILL.md) to an assistant or Agent Skills workflow, then provide your current resume and any supporting project notes.

**English example:**
> Use Evidence-First Resume to revise my resume. Preserve every verifiable fact, write short accomplishment-oriented bullets, keep four bullets for my most important project, and return the final text in English.

**中文示例：**
> 请按照 Evidence-First Resume 优化这份简历。保留真实数据，每条只突出一项贡献，核心项目保留四条 Bullet，直接输出中文最终稿。

## Notes

- The purpose is clearer presentation, **not** inflated claims or an asserted ATS score.
- Never mistake a local prototype or architecture proposal for a production deployment.
- This repository contains writing instructions only; it does not contain the author's private resume data.
