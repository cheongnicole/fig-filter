---
name: Artisanal Warmth
colors:
  surface: '#fff8f8'
  surface-dim: '#e1d8d9'
  surface-bright: '#fff8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf1f2'
  surface-container: '#f5eced'
  surface-container-high: '#efe6e7'
  surface-container-highest: '#e9e0e1'
  on-surface: '#1e1b1c'
  on-surface-variant: '#4d444b'
  inverse-surface: '#342f30'
  inverse-on-surface: '#f8eeef'
  outline: '#7e747c'
  outline-variant: '#cfc3cc'
  surface-tint: '#755377'
  primary: '#331736'
  on-primary: '#ffffff'
  primary-container: '#4a2c4d'
  on-primary-container: '#ba94bb'
  inverse-primary: '#e3b9e3'
  secondary: '#7d5700'
  on-secondary: '#ffffff'
  secondary-container: '#ffc55f'
  on-secondary-container: '#755100'
  tertiary: '#1b2500'
  on-tertiary: '#ffffff'
  tertiary-container: '#303b0f'
  on-tertiary-container: '#98a66f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd6fe'
  primary-fixed-dim: '#e3b9e3'
  on-primary-fixed: '#2c1030'
  on-primary-fixed-variant: '#5b3c5e'
  secondary-fixed: '#ffdeaa'
  secondary-fixed-dim: '#f5bd58'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5f4100'
  tertiary-fixed: '#dbe9ac'
  tertiary-fixed-dim: '#bfcd92'
  on-tertiary-fixed: '#161f00'
  on-tertiary-fixed-variant: '#404b1e'
  background: '#fff8f8'
  on-background: '#1e1b1c'
  surface-variant: '#e9e0e1'
  surface-cream: '#FAF6F0'
  surface-warm-subtle: '#F3EDE2'
  border-warm: '#E8DEC8'
  fig-deep: '#4A2C4D'
  amber-accent: '#D9A441'
  ink-nearblack: '#221E1F'
  ink-muted: '#6E6264'
typography:
  headline-display:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-display-mobile:
    fontFamily: Playfair Display
    fontSize: 34px
    fontWeight: '600'
    lineHeight: 42px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1.25rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-xxl: 4rem
---

## Brand & Style

The design system embodies the sensory, unpretentious atmosphere of a craft neighbourhood coffee roastery and bakery. It pairs the quiet confidence of small-batch culinary pride with approachable hospitality. The tone is warm, plainspoken, and slightly dry-humoured—avoiding hyperbole and corporate polish in favour of honest utility.

The visual style blends **Tactile Craft Minimalism** with warm editorial touches. It takes inspiration from vintage café ledgers, letterpress paper menus, and warm ceramic tones:
- Generous, thoughtful negative space evoking an unhurried morning table.
- Subtle physical paper qualities conveyed through warm off-white canvas surfaces, soft tinted containers, and delicate tactile borders instead of cold artificial dropshadows.
- Clear structural hierarchy designed mobile-first as an effortless, legible single-column read.

## Colors

The palette is rooted in the rich purple skin of ripe figs, golden morning espresso crema, and natural unbleached paper.

- **Primary (`#4A2C4D`)**: Deep fig purple. Used for key headlines, dominant interactive buttons, and strong identity anchors.
- **Secondary / Accent (`#D9A441`)**: Warm amber. Reserved exclusively for small visual callouts, status badges, highlight rules, and dietary pills. It is never used for running body copy to preserve high contrast and readability.
- **Canvas & Neutral (`#FAF6F0` & `#221E1F`)**: Warm off-white acts as the paper canvas, pairing with near-black ink for readable, high-comfort typography. Secondary neutral `#6E6264` handles secondary annotations, dietary descriptions, and metadata.
- **Borders & Dividers (`#E8DEC8`)**: Delicate, unbleached-linen tones provide structure to menu grids and cards without the harshness of neutral cool grays.

## Typography

Typography establishes an editorial cadence reminiscent of independent culinary quarterlies.

- **Headlines**: Set in **Playfair Display** to supply crafted personality, distinctive italic flourishes where needed, and an artisanal presence. Headings maintain tight letter spacing and proportional leading to feel grounded on narrow screens.
- **Body & Functional UI**: Set in **Plus Jakarta Sans** for pristine legibility across small viewport screens, menu price listings, opening hour schedules, and dietary tags.
- **Hierarchy Rules**: 
  - Section titles use `headline-lg` or `headline-md` with warm fig colouring.
  - Menu item names use `headline-sm` accompanied by `label-lg` aligned pricing.
  - Contextual metadata, hours, and dietary chips rely on uppercase or semi-bold `label-md` and `label-sm`.

## Layout & Spacing

The layout is built mobile-first, engineered to deliver key decision-making information (location, opening hours, current bakes) immediately on small phone viewports before expanding gracefully on desktop.

- **Grid Strategy**:
  - **Mobile (< 768px)**: Strict single-column flow (`margin: 1.25rem`). Hero headers, menu categories, and catering bundles stack neatly to avoid horizontal eye fatigue. Critical logistical data (address, hours) occupies upper screen real estate.
  - **Desktop (≥ 768px)**: Constrained content max-width (capped at 960px to 1040px) to preserve intimate reading widths. Menu categories display in a maximum of two balanced columns; catering tier packages align in a 3-column side-by-side comparison.
- **Vertical Rhythm**: Generous section spacing (`space-xxl` on desktop, `space-xl` on mobile) produces a peaceful, relaxed cadence, preventing the dense information crowding common in food service interfaces.

## Elevation & Depth

This design system avoids high-tech blur filters and heavy black dropshadows. Depth is articulated through **tactile surface layering and low-contrast warm outlines**:

- **Paper Layering**: Visual hierarchy is created by resting subtly tinted warm paper cards (`#F3EDE2`) on the default canvas (`#FAF6F0`).
- **Crisp Warm Borders**: Panels, catering comparison cards, and operating hours tables utilise a 1px solid warm border (`#E8DEC8`), providing an artisanal print feel.
- **Subtle Ambient Lift**: Where elevated interactive floating elements occur (e.g., sticky action bar or focused modal card), depth is conveyed via an extra-soft, warm-tinted ambient shadow: `0 8px 24px -4px rgba(74, 44, 77, 0.08)`.

## Shapes

The design system utilizes **Soft** corner geometry (`roundedness: 1`):
- Standard cards, interactive inputs, and image containers use `0.25rem` (4px) to `0.5rem` (8px) corner radius, preserving the crisp lines of printed stationery and timber café menu boards.
- Badges and dietary tags (`V`, `VG`, `GF`) adopt soft micro-curved rectangular shapes or restrained circular stamps rather than hyper-modern exaggerated pills.
- Photography features slight corner softening (4px–8px) while honoring the uncropped geometry of shopfront and culinary imagery.

## Components

### Buttons
- **Primary Action**: Filled background with deep fig purple (`#4A2C4D`), text in warm off-white (`#FAF6F0`), font weight 600 (`label-lg`), with 8px horizontal padding rhythm and 4px rounded radius. Exactly one primary action is highlighted per screen view (e.g., "Find us", "Order catering").
- **Secondary & Text Links**: Clean, understated text links rendered in near-black (`#221E1F`) with a delicate 1px warm border underline offset by 4px, transitioning to primary fig on hover. Never styled as loud competing buttons.

### Menu Item Rows & Lists
- Styled as editorial ledger entries: item title (`headline-sm`) on the left, dotted leader line or balanced spacer, and price (`label-lg`) right-aligned.
- Item descriptions sit below in `body-sm` (`#6E6264`).
- Categories are separated by horizontal rules in `#E8DEC8`.

### Badges & Dietary Markers
- Compact typographic markers for `V`, `VG`, `GF`.
- Set with `surface-warm-subtle` background, fine `border-warm` border, and warm amber (`#D9A441`) typography or accent indicator dot. Never distracting; easily scanned by diners with dietary constraints.

### Cards (Catering & Profiles)
- Outlined with 1px `border-warm` over `surface-warm-subtle`.
- Catering package cards feature package name in `headline-md`, price per person in bold primary fig, followed by bulleted items separated by hairline rules.
- Founder profiles integrate portrait photography with warm caption cards directly beneath.

### Input Fields & Email Triggers
- Form and enquiry fields feature clean, unbleached backgrounds (`#FAF6F0`), 1px `border-warm` borders, and high-contrast placeholder copy in `#6E6264`. Focus states glow with a 1.5px border in `#4A2C4D`.

### Hours & Location Table
- Designed as a structured grid table with zero distractions: days paired with exact operating hours, alternating with subtle row dividing lines, ensuring zero scroll friction on mobile viewports.