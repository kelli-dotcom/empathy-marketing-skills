# Empathy Marketing Skills — Agent Router (`AGENTS.md`)

> Model-agnostic progressive disclosure router for Claude, Gemini, GPT/Codex, Cursor, Windsurf, Antigravity, Copilot, OpenHands, and local LLMs.

## Progressive Disclosure Routing Table
Load **only** the skill file that matches the active marketing, research, or positioning task—never dump all five skills into context at once:

| User Intent / Task | Target Skill to Load |
| :--- | :--- |
| Understand real customer behavior, frustrations, fears, and Smallest Viable Audience (SVA) | [`skills/user-empathy-research/SKILL.md`](skills/user-empathy-research/SKILL.md) |
| Escape commodity pricing, sharpen category specifics, and define exclusion boundaries | [`skills/category-positioning-audit/SKILL.md`](skills/category-positioning-audit/SKILL.md) |
| Build a 10-to-1,000 True Fans engine and ship consistently without chasing virality | [`skills/true-fans-consistency-engine/SKILL.md`](skills/true-fans-consistency-engine/SKILL.md) |
| Craft Before/After transformation, healthy tension, status/affiliation signals, and word-of-mouth | [`skills/status-affiliation-storyteller/SKILL.md`](skills/status-affiliation-storyteller/SKILL.md) |
| Move from commodity freelancing to premium clients using proof assets and human-led AI workflows | [`skills/freelancer-to-premium-clients/SKILL.md`](skills/freelancer-to-premium-clients/SKILL.md) |

## Operating Guardrails (All Models)
1. **Concurrency Cap:** Run a maximum of **3 concurrent agents** per workflow (e.g., 1 Empathy Researcher + 1 Positioning Strategist + 1 Story/Proof Verifier).
2. **Zero File Duplication:** Reference skills via relative paths or the 1-line `AGENTS.md` pointer pattern rather than copying prose across repositories.
3. **Specifics Over Buzzwords:** Every output must name concrete people, observable behaviors, explicit trade-offs, and verifiable proof assets—never generic marketing slogans.
