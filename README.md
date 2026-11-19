# Aquarius — Profile concept 1 (dashboard redesign demo)

Interactive HTML demo of the redesigned Aquarius profile / dashboard page, built from the Figma file "♒ Interfaces – Aqua" (section "Profile concept 1").

Open `index.html` in a browser. It is fully self-contained (icons and screenshots are inlined).

- **Balances** tab is the new design; other tabs show the old pages as screenshots, marked "Under construction".
- Interactions: sticky tabs, "How it works", XLM fee and total-balance tooltips, claims dropdown, account menu, Get AQUA modal, copy-address animation, asset search, column sorting (Asset / Pooled / Available) and "Hide small balances" checkbox.

## Variants

One file, three ways to show an asset's pools:

- `index.html` — **accordion** (main): click a row to expand its pools.
- `index.html?v=hover` — **hover**: the same pool details appear in a popover when hovering the Pooled bar.
- `index.html?v=plain` — **plain**: no pool details, just the table.
