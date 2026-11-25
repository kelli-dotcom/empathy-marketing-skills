# Start Here — One-Page Spec (`empathy-marketing-skills`)

## 1. The idea
Five modular AI agent skills for Smallest Viable Audience (SVA) empathy research, category positioning, status/affiliation storytelling, 1,000 True Fans consistency, and freelancer-to-premium client strategy.

## 2. Who it is for
Solo founders, indie builders, consultants, and AI coding agents turning generic commodity copy into specific, trustworthy positioning.

## 3. What it does
- Loads only the single `skills/*/SKILL.md` matching the active research, positioning, storytelling, or client task via progressive disclosure.
- Defines explicit exclusion boundaries (who a product is NOT for) and 30-second proof assets.
- Ships a live interactive SVA & Positioning Brief Builder (`preview/index.html`) styled directly with `feather-themes`.

## 4. What it does NOT do
- Never uses fake urgency, fabricated testimonials, or generic AI hype.
- Never dumps all five skills into agent context at once.
- Never pulls in app-specific code (kit stays standalone and zero-dependency).

## 5. How to tell it works
Verify all 5 `skills/*/SKILL.md` files have valid YAML frontmatter (`name`, `description`) and run `node tests/smoke.test.mjs`.

## 6. What is left to do
1. Publish the live SVA & Positioning Brief Builder (`preview/index.html`) on GitHub Pages.
2. Add the Amber positioning banner (`demo/hero-banner.svg`) and link the live demo in `README.md`.
