# Instructions for AI agents

Use this repository as the default visual and implementation standard when the user asks to build or redesign a landing page or website using the Vlad Landing System.

## Workflow

1. Read `DESIGN-SYSTEM.md`.
2. Read the relevant files in `rules/`.
3. Reuse an approved component from `components/` when one exists.
4. If no approved component exists, create a new one consistent with the system rather than introducing an unrelated visual style.
5. For Tilda tasks, prefer self-contained HTML/CSS/JS and follow `rules/tilda-rules.md`.
6. Preserve the user's content and conversion goal unless explicitly asked to rewrite them.
7. Prioritize mobile layout, readable typography, clear hierarchy, fast loading, and obvious CTA states.

## Default landing-page sequence

Use this as a starting point, not a mandatory template:

1. Hero
2. Trust / proof
3. Benefits or problem-solution block
4. Service/product details
5. Process
6. Team / expert
7. Cases or reviews
8. Price / offer
9. FAQ
10. Final CTA
11. Footer / legal information

## Design guardrails

- Avoid excessive gradients, glassmorphism, neon effects, floating blobs, and decorative animation without a UX purpose.
- Avoid tiny body copy and weak contrast.
- Avoid more than one primary CTA style per page.
- Use cards only when grouping actually improves comprehension.
- Use icons consistently and only when they speed up scanning.
- Keep section width, spacing, radii, shadows, and typography consistent with tokens.
- Prefer concrete benefits and evidence over generic marketing statements.

## Medical landing pages

- Do not invent guarantees, clinical outcomes, contraindications, prices, licenses, doctors, or medical claims.
- Keep required medical/legal notices visible when provided or requested.
- The visual style should feel trustworthy and modern rather than aggressive or sensational.

## Source libraries

HyperUI may be used as a source of open-source patterns, but components should be adapted to this repository's tokens and UX rules. Do not import a visually conflicting component unchanged simply because it exists in the source library.