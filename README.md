# cs-design-system

Shared design tokens for Consider Sentience projects (AVAIL, BEARCLAW, FACTS). The Figma file "CS Solutions Design System" is the source of truth; this repo holds the same values as code.

- `tokens.css` – CSS custom properties. Import once and use `var(--color-rust)`, `var(--spacing-8)`, `var(--radius-md)`.
- `tokens.json` – the same values for tools that read JSON.

Variable names match the Figma variables, with `/` replaced by `-`.

In a Tailwind project, install with `npm install github:lish-stack/cs-design-system` and spread `colors`, `spacing`, `radius` and `fontFamily` from `cs-design-system` into `theme.extend`.
