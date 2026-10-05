---
name: Architectural Wireframe
colors:
  surface: '#141312'
  surface-dim: '#141312'
  surface-bright: '#3b3937'
  surface-container-lowest: '#0f0e0d'
  surface-container-low: '#1d1b1a'
  surface-container: '#211f1e'
  surface-container-high: '#2b2a28'
  surface-container-highest: '#363433'
  on-surface: '#e6e1df'
  on-surface-variant: '#cbc6bd'
  inverse-surface: '#e6e1df'
  inverse-on-surface: '#32302f'
  outline: '#949088'
  outline-variant: '#494740'
  surface-tint: '#cac6c1'
  primary: '#ffffff'
  on-primary: '#32302d'
  primary-container: '#e6e2dd'
  on-primary-container: '#666460'
  inverse-primary: '#605e5a'
  secondary: '#ebbd9b'
  on-secondary: '#462a11'
  secondary-container: '#604025'
  on-secondary-container: '#d9ac8a'
  tertiary: '#ffffff'
  on-tertiary: '#313032'
  tertiary-container: '#e5e1e3'
  on-tertiary-container: '#656466'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e6e2dd'
  primary-fixed-dim: '#cac6c1'
  on-primary-fixed: '#1d1b19'
  on-primary-fixed-variant: '#484643'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ebbd9b'
  on-secondary-fixed: '#2d1602'
  on-secondary-fixed-variant: '#604025'
  tertiary-fixed: '#e5e1e3'
  tertiary-fixed-dim: '#c9c5c7'
  on-tertiary-fixed: '#1c1b1d'
  on-tertiary-fixed-variant: '#484648'
  background: '#141312'
  on-background: '#e6e1df'
  surface-variant: '#363433'
typography:
  display-xl:
    fontFamily: Newsreader
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: Newsreader
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: 0em
  headline-md:
    fontFamily: Newsreader
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
  title-sm:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 26px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.12em
spacing:
  gutter: 1.5rem
  gutter-lg: 2.5rem
  margin: 1.5rem
  margin-md: 3rem
  margin-lg: 5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style
The brand personality embodies disciplined culinary craft, architectural poise, and understated prestige. Conceived for an audience of discerning epicures, interior connoisseurs, and modern diners, the digital experience mirrors the cadence of a curated tasting room. 

The aesthetic is a high-fidelity architectural wireframe: structural blueprint lines, precision crosshairs, and deliberate registration marks harmonize with luxurious editorial dining typography. It intentionally strips away decorative clutter in favor of crisp structural discipline, warm tactile materiality, and gallery-grade negative space. The resulting interface feels calculated yet sensual—resembling an architect's bespoke folio for an elite grillhouse.

## Colors
The palette evokes embers, scorched oak, and hand-milled rag paper under architectural studio lighting:
- **Base Canvas (`neutral_color_hex` #121110)**: A deep, warm charcoal black carrying an organic amber undertone rather than sterile cold black.
- **Primary Mark (`primary_color_hex` #F4EFEA)**: Bone white with a soft parchment quality, providing tactile contrast without sterile optical glare.
- **Secondary Accent (`secondary_color_hex` #C89D7C)**: A toasted ochre/ember tint used strictly for focus rings, micro-status indicators, section indexing, and active reservation slots.
- **Surface & Structural Wireframes**:
  - `surface-elevated`: `#1C1A18` (soft graphite for cards and overlays)
  - `border-structural`: `rgba(244, 239, 234, 0.14)` (tactile blueprint borders)
  - `border-faint`: `rgba(244, 239, 234, 0.06)` (coordinate guide rules and internal dividers)
  - `text-muted`: `rgba(244, 239, 234, 0.52)` (technical specs, ingredients, origin details)

## Typography
Typographic rhythm balances high-society gastronomic prestige with modern architectural cataloging:
- **Headlines (Newsreader)**: Fluid, high-contrast transitional serif delivering culinary drama, vintage provenance, and deliberate pacing. Used in italic variations for culinary provenance and featured tasting courses.
- **Body & Structural Text (Hanken Grotesk)**: Crisp, neutral, highly legible modern grotesque handling menu descriptions, booking instructions, and operating hours without competing against the serif display.
- **Annotations & Technical Meta (JetBrains Mono)**: Utilitarian monospaced typeface used uppercase for cut weights, cellar temperatures, seating coordinates, wireframe guides, and pricing notations.

## Layout & Spacing
The layout follows a rigorous 12-column architectural matrix framed by visible perimeter coordinates (`[SEC_01 // 48.8566° N]`) and hairline datum lines:
- **Desktop (1024px+)**: 12-column grid, `margin-lg` (80px) dynamic safe outer padding, `gutter-lg` (40px). Columns are intersected by subtle horizontal guidelines to maintain disciplined rhythm.
- **Tablet (768px - 1023px)**: 8-column grid, `margin-md` (48px), `gutter` (24px). Asymmetrical pairings collapse into 4+4 splits.
- **Mobile (<768px)**: 4-column grid, `margin` (24px), `gutter` (16px). Technical annotations pin to section borders; layout cards run edge-to-edge separated by single-pixel horizontal hairline rules.

## Elevation & Depth
Elevation rejects ambient drop shadows entirely, opting for architectural depth through hairline boundaries and tonal containment:
- **Zero-Shadow Philosophy**: No blurry diffusion or skeuomorphic drops. Elevation is signaled purely by surface step-ups (from `#121110` canvas to `#1C1A18` paneling) bounded by 1px rules in `rgba(244, 239, 234, 0.12)`.
- **Wireframe Registration Markers**: Modal overlays and featured menu containers feature 4px corner ticks (`+` or `⌜ ⌝` crosshairs) rendered in the primary parchment tone to reinforce the wireframe blueprint drafting motif.
- **Frosted Glass Louver**: Sticky navigation and floating booking drawers utilize a high-density backdrop blur (`backdrop-filter: blur(16px)`) with a 75% charcoal tint (`rgba(18, 17, 16, 0.75)`) and a 1px baseline boundary.

## Shapes
Geometry is strictly rectilinear and unyielding (`roundedness: 0`). Elements have 0px border radius across all viewports.

Every button, input, card, tag, and modal window terminates in exact 90-degree right angles. This creates a bespoke, razor-sharp architectural silhouette reminiscent of brutalist fine dining facades, custom steel millwork, and drafting vellum sheets.

## Components

### Buttons & Interactive Triggers
- **Primary Action (e.g., "RESERVE TABLE")**: Bone white (`#F4EFEA`) solid fill, charcoal text (`#121110`), zero radius, mono uppercase label (`label-md`). Hover transitions to secondary ember tone (`#C89D7C`) with pure black typography.
- **Secondary Action**: Transparent background with a 1px solid wireframe border (`rgba(244, 239, 234, 0.25)`), bone white text. Hover triggers an interior wireframe hatch or inverse parchment tint.
- **Architectural Link**: Underlined text with a dashed 1px baseline rule offset by 4px, accompanied by monospaced directional coordinate indicators (`→ [BOOK]`).

### Cards & Menu Folios
- **Dish & Cellar Card**: Charcoal surface (`#1C1A18`), surrounded by 1px hairline boundary (`rgba(244, 239, 234, 0.1)`). Header contains monospaced indexing tags (`[FIG. 04 / DRY AGED]`) above the Newsreader serif item title. Ingredients are laid out in an open grid structure separated by vertical hairline guides.
- **Chef's Tasting Modules**: Span multiple columns with internal horizontal division lines. Pricing is set in JetBrains Mono right-aligned to create architectural table alignment.

### Selection Controls & Chips
- **Chips (Dietary / Course Filters)**: Monospaced uppercase labels enclosed in 1px borders. Selected state fills with inverted bone white background or highlights the perimeter in ember ochre with a prefixed registration dot (`● WAGYU`).
- **Radio Buttons & Checkboxes**: Rigid square boxes (14px × 14px) with 1px border. Selected state renders a centered solid square core (6px × 6px) rather than a checkmark or circle.

### Input Fields & Reservation Controls
- **Text Inputs**: Flat charcoal surface with a single bottom hairline rule (`border-bottom: 1px solid rgba(244, 239, 234, 0.2)`). Focus shifts the bottom line to 1px solid `#C89D7C` with zero elevation glow. Floating labels use JetBrains Mono in muted tone.
- **Time & Seating Selector**: Grid-based tabular matrix where each slot acts as a wireframe cell containing time, capacity status, and table zone code (`ZONE_A // TABLE 04`). Sold out states are crossed out with a single clean diagonal hairline rule.

### Domain-Specific Components
- **Architectural Floor Plan Selector**: A minimal vector wireframe of the dining room allowing guests to inspect booth depths, kitchen sightlines, and hearth proximity.
- **Provenance Blueprint Strip**: A horizontal technical ticker detailing meat purveyors, wood species used in the wood-fired grill (White Oak / Applewood), and aging day counts formatted as technical drafting specs.