# Figma source of truth

Figma file: **CS Solutions Design System** (file key `Kygwsk1ysOyPryLJhwcmz2`).

| File here | Figma page | Contents |
|---|---|---|
| `../tokens.json`, `tokens.css`, `tokens.js` | Variables | Colors (Light and Dark), spacing, radius, fonts |
| `../typography.css` | Text styles | 22 text styles |
| `site-components.txt` | Site Components | considersentience.ai nav links, buttons, mobile headers, images |
| `avail-components.txt` | AVAIL Components | Inputs, dropdowns, textarea, AVAIL buttons, return to site |
| `bearclaw-components.txt` | BEARCLAW Components | Badges, cards, tables, nav, hero, footer, toggles |
| `../assets/` | Images | Wordmark, logos, favicons |

The component files are plain-text specs (layout, padding, radius, fill, stroke, font, size, color) so a build can match Figma exactly. `../nav-link.css` is the shipped code for the nav link.

Rule: Figma and this repo are updated together. A change in one is made in the other in the same pass.
