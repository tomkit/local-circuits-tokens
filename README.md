# Local Circuits

Local Circuits is a warm, editorial design system built on a forest-and-gold palette, cream paper surfaces, and a serif-led type voice. It aims for a tactile, printed feel — deep evergreen ink, brushed-gold accents, and a faint paper grain — that reads as crafted and local rather than synthetic.

## Visual Theme & Atmosphere

The system is grounded in nature and print. Deep forest greens carry structure and text, a single brushed gold does the talking for actions and highlights, and everything sits on warm cream and paper tones instead of clinical white. A subtle paper-grain overlay gives surfaces an expensive, tactile quality, and motion stays quiet: short eased transitions and one slow signature pulse rather than anything flashy.

Two modes share one identity. A light paper mode builds on cream with forest ink; a dark espresso mode inverts onto near-black greens, with the gold accent brightening toward leaf where contrast needs it.

## Color Palette & Roles

Canonical UI roles (these drive the design-system swatches):

- **Background:** `#faf7f0`
- **Foreground:** `#1a1a1a`
- **Border:** `#e7dfd2`
- **Accent:** `#e0a82e`

### Greens — structure, text, brand
- **Forest** (`#1c3a2a`): primary brand green for heading ink, primary buttons, and the sidebar.
- **Espresso** (`#142a1e`): the deepest green; dark-mode canvas and heavy anchors.
- **Pine** (`#2d6a4f`): mid green for focus rings, charts, and secondary emphasis.
- **Leaf** (`#52b788`): bright green for success states, the dark-mode accent, and data viz.
- **Leaf Soft** (`#7fcba4`): a tint for subtle fills and chart steps.

### Gold — action & highlight
- **Gold** (`#e0a82e`): the single accent, used for primary actions, links, and highlights.
- **Gold Deep** (`#c8901f`): hover and pressed accent, and the warning tone.
- **Accent Ink** (`#3a2a05`): text and icons placed on gold.

### Surfaces & neutrals
- **Cream** (`#faf7f0`): the page background.
- **Paper** (`#f1ece2`): a secondary warm surface and muted fill.
- **Card** (`#ffffff`): lifted containers.
- **Ink** (`#1a1a1a`): primary body text.

## Typography

- **Display and headings — Fraunces** (serif): editorial and high-contrast, used for hero and section headings with tightened tracking.
- **Body and UI — Inter** (sans): a calm, legible workhorse for paragraphs, controls, and dense interface text.
- **Mono and code — Space Grotesk**: labels, code, and technical metadata.

The type scale runs from `0.75rem` captions to a `3rem` display, with generous body leading (1.55) and tight display leading (1.15).

## Radius, Spacing & Motion

- **Radius:** soft rather than pill — `0.45rem` small, `0.6rem` medium, `0.75rem` large; full pills are reserved for tags and toggles.
- **Spacing:** a 4px base step (4, 8, 12, 16, 24, 32, 48) with a responsive section rhythm of 96 / 68 / 48px from desktop to phone.
- **Motion:** 150ms fast and 200ms base on a standard `cubic-bezier(0.2, 0, 0, 1)` ease; a slow 2.8s pulse is the one signature flourish.

## Components & Usage

- **Buttons:** primary is a forest fill with cream text; the accent button is a gold fill with accent-ink text. Keep gold to one clear action per view.
- **Cards:** white on cream, a hairline `#e7dfd2` border, large radius, and a whisper-soft shadow.
- **Inputs:** a paper or white field with an `#e7dfd2` border and a pine focus ring.
- **Focus:** always visible, using a 2px forest outline (or a gold ring) with a 2px offset.

## Design Principles

1. One loud color. Gold is the only accent; greens and neutrals carry everything else.
2. Warm, not white. Prefer cream and paper over pure white for large fields.
3. Serif for voice, sans for work. Fraunces states; Inter operates.
4. Tactile restraint. Paper grain and gentle motion, never decoration for its own sake.

## About this repository

Public, token-only mirror of the Local Circuits design system, for importing into Open Design. `globals.css` holds the canonical shadcn + Tailwind v4 token layer (brand palette, typography, radius, light and dark) plus an Open Design import-contract block at the top of the file. No application code lives here.

Import in Open Design via: `https://github.com/tomkit/local-circuits-tokens`
