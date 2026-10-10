# Evidence-First Resume

A reusable, role-agnostic Agent Skill for writing and editing resumes with concise, verifiable accomplishments.

**Core philosophy:** Problem → Action → Impact, with evidence before adjectives and readability before exhaustiveness.

## What it does

- Creates and revises resumes in English or Chinese.
- Rewrites experience into focused, scannable bullet points.
- Prioritizes measurable and verifiable results without fabricating metrics.
- Distinguishes production implementation, local prototypes, architectural design, and recommendations.
- Organizes projects, work experience, technical skills, education, and certifications.
- Preserves user-requested constraints such as bullet counts, sections, and language.

## Usage

Provide [`SKILL.md`](./SKILL.md) to an assistant that supports Agent Skills, together with your resume and any relevant background documents. Ask it to apply **Evidence-First Resume** to the whole resume or a specific section.

**Example request:**

> Apply Evidence-First Resume to my uploaded resume. Keep every claim accurate, remove repetitive implementation details, and write concise bullets that connect the problem, key action, and verified outcome. Give me one polished English version.

## Language

The skill instructions are primarily in Chinese and support output in both English and Chinese.

## Notes

- This is a general-purpose writing skill, not a job-specific resume template.
- It does not claim improved hiring outcomes or ATS scores.
- No personal resume details are included in this repository starter.
