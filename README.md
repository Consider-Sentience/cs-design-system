# cs-design-system

Shared design tokens for Consider Sentience projects (AVAIL, BEARCLAW, FACTS). The Figma file "CS Solutions Design System" is the source of truth; this repo holds the same values as code.

- `tokens.css` – CSS custom properties. Import once and use `var(--color-rust)`, `var(--spacing-8)`, `var(--radius-md)`.
- `tokens.json` – the same values for tools that read JSON.

Variable names match the Figma variables, with `/` replaced by `-`.

In a Tailwind project, install with `npm install github:Consider-Sentience/cs-design-system` and spread `colors`, `spacing`, `radius` and `fontFamily` from `cs-design-system` into `theme.extend`.

## Components

- `nav-link.css` – the "[ label ]" nav link (Figma: "what we do", default and hover). Import it with `import 'cs-design-system/nav-link.css'` or `@import 'cs-design-system/nav-link.css'`, then use the markup in the file header: a `.cs-nav-link` anchor containing `__dot--left`, `__bracket`, `__label`, `__bracket`, `__dot--right`. It needs Nunito (200, 300), IBM Plex Sans and Source Serif 4 italic 500 to be loaded.

## Typography, assets and Figma specs

- `typography.css`: classes for every Figma text style (for example `.cs-text-heading-card`).
- `assets/`: Consider Sentience wordmark, BEARCLAW logo and favicon, AVAIL logo and favicon.
- `figma/`: plain-text component specs and the sync rule. See `figma/README.md`.
- Dark backgrounds (AVAIL): swap cloud and ink. Every other color stays the same.
