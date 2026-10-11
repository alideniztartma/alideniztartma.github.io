# Design system

## Direction

The biography surface uses a signal-map language: open-source contributions appear as connected, living evidence instead of a generic profile card. The visual mood is focused, curious, and technical without turning monospace into costume.

## Palette

- `--bg`: graphite night / pale mineral light mode base.
- `--surface` and `--surface-2`: layered panels that separate work from the canvas.
- `--text` / `--muted` / `--faint`: a clear reading hierarchy.
- `--cyan`: primary action and open-source signal.
- `--lime`: status, active path, and secondary emphasis.
- `--violet`: project and React signal.
- `--warm`: NASA signal.

Dark mode is the default because the site is meant to feel like a focused late-night workspace; light mode remains available for bright ambient conditions and system preference.

## Typography

- Bricolage Grotesque is the expressive display face for the name and section titles.
- Manrope is the readable body and interface face.
- DM Mono is reserved for coordinates, statuses, contribution references, and short metadata.
- Display type uses tight tracking and large scale; body copy stays at a comfortable measure.

## Composition

- A restrained top bar keeps navigation and theme control available without competing with the first viewport.
- The hero is split between the oversized identity statement and a contribution constellation.
- Contributions use a two-column editorial list with dividers, not nested cards.
- Projects use a wide featured tile and a compact companion tile.
- Sections are separated by rules and generous vertical rhythm; panels are used only when they describe a real unit of work.

## Motion and interaction

- The contribution map uses slow orbit and node pulse animations to make the network feel alive.
- Hero and section content reveal with an upward ease-out when it enters the viewport.
- Links and contribution rows use small translations and border/background changes for feedback.
- `prefers-reduced-motion: reduce` disables authored motion and makes content immediately visible.

## Responsive rules

- Below 800px, the hero stacks, the map becomes a full-width second block, and contribution/project layouts collapse to one column.
- Touch targets remain at least 44px high for primary controls.
- Footer content stacks on narrow screens.
- The map keeps its label and nodes legible without requiring horizontal scrolling.

## Content rules

Keep the factual contribution and project descriptions grounded in the repository's confirmed content. Do not add metrics, testimonials, clients, dates, or claims without evidence.
