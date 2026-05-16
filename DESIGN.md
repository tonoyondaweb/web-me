---
version: alpha
name: Tonoy Page
description: A warm, editorial dark-mode design system with physical light interactions and print-inspired aesthetics.
colors:
  background: "#141210"
  card: "#1C1917"
  secondary: "#2A2520"
  primary: "#D4B99B"
  primary-foreground: "#141210"
  foreground: "#E8E0D4"
  secondary-foreground: "#E8E0D4"
  muted: "#8A8078"
  muted-foreground: "#A89E94"
  color-success: "#3A6B4A"
  color-success-foreground: "#E6F5EB"
  color-warning: "#6B5A2A"
  color-warning-foreground: "#F5F0E6"
  color-error: "#8B3A3A"
  color-error-foreground: "#F5E6E6"
  color-info: "#3A5A8B"
  color-info-foreground: "#E6EEF5"
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.1
  h1:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: 600
    lineHeight: 1.2
  h2:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: 500
    lineHeight: 1.3
  h3:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: 500
    lineHeight: 1.3
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.6
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1
  caption:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: 400
    lineHeight: 1
  mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
rounded:
  none: 0px
  sm: 4px
  md: 8px
  lg: 16px
  full: 9999px
spacing:
  xs: 4px
  sm: 8px
  md: 12px
  base: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  xxxl: 80px
components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.primary-foreground}"
    rounded: "{rounded.md}"
    padding: 12px
  button-secondary:
    backgroundColor: "{colors.secondary}"
    textColor: "{colors.secondary-foreground}"
    rounded: "{rounded.md}"
    padding: 12px
  button-outline:
    backgroundColor: "{colors.background}"
    textColor: "{colors.foreground}"
    rounded: "{rounded.md}"
    padding: 12px
  button-ghost:
    textColor: "{colors.muted-foreground}"
    rounded: "{rounded.md}"
    padding: 12px
  button-glow:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.primary-foreground}"
    rounded: "{rounded.md}"
    padding: 12px
  button-destructive:
    backgroundColor: "{colors.color-error}"
    textColor: "{colors.color-error-foreground}"
    rounded: "{rounded.md}"
    padding: 12px
  button-small:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.primary-foreground}"
    rounded: "{rounded.sm}"
    padding: 8px
  button-pill:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.primary-foreground}"
    rounded: "{rounded.full}"
    padding: 12px
  badge-default:
    backgroundColor: "{colors.card}"
    textColor: "{colors.foreground}"
    rounded: "{rounded.full}"
    padding: 6px
  badge-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.primary-foreground}"
    rounded: "{rounded.full}"
    padding: 6px
  badge-success:
    backgroundColor: "{colors.color-success}"
    textColor: "{colors.color-success-foreground}"
    rounded: "{rounded.full}"
    padding: 6px
  badge-warning:
    backgroundColor: "{colors.color-warning}"
    textColor: "{colors.color-warning-foreground}"
    rounded: "{rounded.full}"
    padding: 6px
  badge-error:
    backgroundColor: "{colors.color-error}"
    textColor: "{colors.color-error-foreground}"
    rounded: "{rounded.full}"
    padding: 6px
  badge-info:
    backgroundColor: "{colors.color-info}"
    textColor: "{colors.color-info-foreground}"
    rounded: "{rounded.full}"
    padding: 6px
  badge-outline:
    backgroundColor: "{colors.background}"
    textColor: "{colors.muted-foreground}"
    rounded: "{rounded.full}"
    padding: 6px
  card-base:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.md}"
    padding: 24px
  card-top-light:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.md}"
    padding: 24px
  card-edge-glow:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.md}"
    padding: 24px
  card-print:
    backgroundColor: "{colors.background}"
    rounded: "{rounded.none}"
    padding: 24px
  input-default:
    backgroundColor: "{colors.card}"
    textColor: "{colors.foreground}"
    rounded: "{rounded.md}"
    padding: 10px
  input-active:
    backgroundColor: "{colors.card}"
    textColor: "{colors.foreground}"
    rounded: "{rounded.md}"
    padding: 10px
  input-disabled:
    backgroundColor: "{colors.background}"
    textColor: "{colors.muted}"
    rounded: "{rounded.md}"
    padding: 10px
  tab-bar:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.full}"
    padding: 8px
---

## Overview

A warm, dark editorial design system inspired by print layouts and physical light interactions. The aesthetic combines **minimal, print-like layouts** with **tactile light effects** — edge highlights, inner glows, and grazing light — to create surfaces that feel grounded in physical reality.

The color palette is a **dark beige scheme**: deep charcoal-brown backgrounds (`#141210`) with warm off-white text (`#E8E0D4`) and golden-brown accents (`#D4B99B`). Typography pairs **Playfair Display** (serif) for headlines and display text with **Inter** (sans-serif) for body copy, creating a classic editorial hierarchy. **JetBrains Mono** is reserved for code snippets.

Three design principles guide the system:

1. **Minimal & Print-Like** — Clean layouts with generous whitespace, strong typography hierarchy, and ruled dividers that evoke printed matter.
2. **Physical Light** — Subtle light interactions on key components: edge highlights, inner glows, and spot effects. Warm, tactile, and grounded.
3. **Dark Beige Palette** — A warm dark mode derived from beige tones rather than cool grays. Deep backgrounds, warm text, golden accents.

## Colors

The palette is rooted in warm, earthy neutrals with a single golden accent.

- **Background (#141210):** A deep charcoal-brown that serves as the canvas. Warmer than pure black, it feels like dark paper.
- **Card (#1C1917):** Slightly lighter brown for elevated surfaces and content containers.
- **Secondary (#2A2520):** A mid-tone used for secondary buttons, borders, and subtle dividers.
- **Foreground (#E8E0D4):** Warm off-white for primary text. Softer than pure white, easier on the eyes.
- **Primary (#D4B99B):** A golden-beige accent — the sole driver for primary actions, links, and highlights.
- **Muted (#8A8078):** A desaturated brown for labels, captions, and secondary metadata.
- **Muted Foreground (#A89E94):** Slightly lighter than muted, used for body text in secondary contexts.

Semantic colors are present but subdued to match the warm palette:

- **Success (#3A6B4A):** A muted forest green.
- **Warning (#6B5A2A):** An earthy amber.
- **Error (#8B3A3A):** A deep rust red.
- **Info (#3A5A8B):** A steel blue.

## Typography

The typography strategy uses two distinct typefaces to create an editorial feel: **Playfair Display** for headlines and display text, and **Inter** for body copy, labels, and UI elements.

- **Display:** Playfair Display at 48px, weight 700. Reserved for hero sections and page titles. Commands attention with its high-contrast serif forms.
- **H1:** Playfair Display at 36px, weight 600. Section headers and major headings.
- **H2:** Playfair Display at 28px, weight 500. Sub-sections and card titles.
- **H3:** Playfair Display at 22px, weight 500. Tertiary headings within content.
- **Body (16px):** Inter Regular at 16px with 1.6 line height. The workhorse for comfortable long-form reading.
- **Body Small (14px):** Inter Regular at 14px. Used for descriptions, card content, and secondary text.
- **Labels (12px):** Inter Medium at 12px, uppercase with letter spacing for badges, overlines, and metadata.
- **Captions (11px):** Inter Regular at 11px. The smallest text, used for color swatch labels and type spec labels.
- **Mono:** JetBrains Mono at 14px. Reserved for code snippets and technical content.

A Bengali typeface (**Noto Serif Bengali**) is used alongside English display text for the hero name treatment.

## Layout

The layout follows a **fixed-max-width grid** model with a maximum width of 1200px. Content is centered with generous horizontal padding (48px on desktop).

A flexible spacing scale is used, ranging from 4px micro-adjustments to 80px section breaks. The scale is not strictly mathematical but provides enough granularity for editorial rhythm.

Cards use generous internal padding (24px) to emphasize the soft, approachable nature of the brand. Related items are grouped with 12-16px gaps, while distinct sections are separated by 32-48px.

The home page features a floating pill-shaped tab bar in the top-right corner with background blur, providing navigation between "My Work" and "Reads" sections.

## Elevation & Depth

Depth is achieved through **tonal layers** combined with **physical light effects** rather than heavy drop shadows.

- **Base surfaces** sit on the dark background (`#141210`) with no elevation.
- **Cards** (`#1C1917`) are one step lighter, creating subtle separation through color contrast alone.
- **Top Light** cards add a warm grazing light effect: a linear gradient from primary color fading to transparent at the top edge, combined with a subtle outer shadow (`0 1px 2px rgba(212, 185, 155, 0.2)`).
- **Edge Glow** cards feature a radial glow around the perimeter, creating a luminous halo effect (`0 0 12px rgba(212, 185, 155, 0.15)`).
- **Print Style** cards use sharp corners (`0px` radius) with ruled divider lines, evoking printed editorial layouts.

Light interaction patterns:

- **Grazing Light:** Light skimming the surface from above, brightest at the top edge and fading downward. Applied via linear gradients.
- **Radial Glow:** Light emanating from a central point, like a candle behind frosted glass. Applied via radial gradients.
- **Spot Light:** A focused beam of warm light, offset from center. Applied via radial gradients with off-center origin.

## Shapes

The shape language balances **editorial sharpness** with **modern softness**.

- **0px (none):** Print style. Used for print-style cards and editorial dividers. Sharp corners evoke the tactile feel of printed matter.
- **4px (sm):** Subtle rounding. Used for small buttons and compact controls.
- **8px (md):** Default. Used for most buttons, cards, and inputs. Provides just enough softness to feel modern while maintaining structure.
- **16px (lg):** Soft rounding. Used for larger containers and featured elements.
- **Full (9999px):** Pills and badges. Used for the tab bar, badge labels, and pill-shaped buttons.

## Components

### Buttons

Buttons come in several variants, all using Inter at 14px, weight 500.

- **Primary:** Golden fill (`#D4B99B`) with dark text. Can include an icon (e.g., arrow-right). Rounded 8px, padding 12px 24px.
- **Secondary:** Dark secondary background (`#2A2520`) with light text. Same sizing as primary.
- **Outline:** Transparent background with subtle border (`rgba(232, 224, 212, 0.15)`). Light text.
- **Ghost:** No background or border. Muted text color. Minimal presence.
- **Light Glow:** Primary fill with a warm outer glow shadow (`0 0 16px rgba(212, 185, 155, 0.3)`). The most prominent button variant.
- **Small:** Compact variant with 8px 16px padding, 13px text, and 4px corner radius.
- **Pill:** Full rounded corners (9999px) with generous horizontal padding (28px).
- **Destructive:** Deep rust red fill (`rgba(139, 58, 58, 0.8)`) with light red text.

### Badges & Labels

All badges are pill-shaped (full rounded corners) with 6px 12px padding and 12px Inter Medium text.

- **Default:** Card background with foreground text and subtle border.
- **Primary:** Semi-transparent primary fill with dark text.
- **Success/Warning/Error/Info:** Semantic colors with matching semi-transparent fills and light foreground text.
- **Outline:** Transparent background with border, muted text.

### Cards

Cards are the primary content containers, all using 24px internal padding.

- **Base Card:** Card background (`#1C1917`), 8px radius, subtle border (`rgba(232, 224, 212, 0.12)`).
- **Top Light Card:** Base card plus grazing light gradient at top edge and dual outer shadows.
- **Edge Glow Card:** Base card plus radial glow shadow around perimeter.
- **Print Card:** Background color (`#141210`), sharp corners (0px), includes horizontal divider line at top.

### Inputs

Inputs use a label + field pattern with 8px gap between them.

- **Default:** Card background, 8px radius, subtle border. Placeholder text in muted color.
- **Active/Focused:** Same as default but with primary-colored border (`rgba(212, 185, 155, 0.4)`) and warm glow shadow.
- **Disabled:** Background color, muted text and label, very subtle border.

### Tab Bar

A floating pill-shaped navigation bar positioned in the top-right corner. Semi-transparent card background (`rgba(28, 25, 23, 0.8)`) with 80px backdrop blur, full rounded corners, and 8px internal padding. Contains tab items with icon + text, 20px 24px padding each. The active tab has a gradient border highlight.

### Icon Texture

The home page features a scattered background texture of Lucide icons at 8% opacity. Icons include code, cpu, brain, palette, sparkles, terminal, camera, lightbulb, and others — varying in size from 32px to 56px. Creates a subtle, tech-creative atmosphere.

## Do's and Don'ts

- Do use the primary golden color (`#D4B99B`) only for the single most important action per screen
- Do maintain the warm beige palette — avoid introducing cool grays or pure blacks
- Do use Playfair Display for headlines and Inter for body text — don't mix additional typefaces
- Don't mix sharp (0px) and rounded corners in the same view unless intentionally contrasting print vs digital
- Do use light effects (grazing, radial, spot) sparingly — they should feel tactile, not decorative
- Do maintain WCAG AA contrast ratios (4.5:1 for normal text) — the warm palette is designed to meet this
- Don't use more than two font weights on a single screen
- Do use the tab bar for primary navigation — it should float and feel lightweight
- Don't overload cards with shadows — prefer tonal layering and subtle light effects
- Do use the spacing scale consistently — avoid arbitrary pixel values
