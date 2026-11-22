# Contributing to Empathy Marketing Skills (`CONTRIBUTING.md`)

Thank you for contributing to **Empathy Marketing Skills**! Both **human marketers/founders** and **AI agents** are welcome to sharpen our modular research, positioning, storytelling, consistency, and premium client skills.

---

## 1. High-Impact Ways to Contribute
- **Sharper Behavioral Probes & Checklists:** Add field-tested questions, Forced Empathy Cycle worksheets, or Narrative-Mismatch examples to `skills/user-empathy-research/SKILL.md`.
- **Category Positioning & Proof Patterns:** Add new examples of 30-second proof assets and *"not for you"* exclusion boundaries in `skills/category-positioning-audit/SKILL.md`.
- **New Modular Marketing Skills (`skills/<name>/SKILL.md`):** Propose focused, non-overlapping skills (e.g., ethical pricing teardowns, community onboarding rituals, or B2B case-study interviews) following the standard YAML frontmatter + `Summary / When to Use / Steps / Gotchas` format.

## 2. Human & AI Agent Guardrails (`AGENTS.md` + `llms.txt`)
- **Progressive Disclosure:** Register any new skill in the `AGENTS.md` routing table so agents load only one skill at a time.
- **Specifics Over Buzzwords:** Every step must require concrete behaviors, trade-offs, and verifiable proof assets—never vague marketing cliches or dark-pattern urgency tricks.
- **Clean-Room Originality:** Keep all instructions 100% original and free of third-party copyrighted transcripts or competitor trademark attacks.

## 3. 60-Second Verification Gate (Required Before Every PR)
```bash
ls -la AGENTS.md llms.txt HANDOFF.md mistakes.md skills/*/SKILL.md
```

## 4. 3-Step Pull Request Workflow
1. **Fork & Branch:** `git checkout -b feat/your-skill-improvement`
2. **Verify Structure:** Confirm YAML frontmatter (`name` + `description`), numbered `Steps`, and `Gotchas` are present in every touched `SKILL.md`.
3. **Submit a Pull Request:** Open a PR against `main` describing the real-world scenario your improvement solves. *(Can be edited directly on mobile or desktop via the GitHub web UI.)*

## 5. IP Safety & MIT License
All contributions must be original clean-room work and are licensed under the repository's [MIT License](LICENSE).
