---
name: Modern Overlander
colors:
  surface: '#001710'
  surface-dim: '#001710'
  surface-bright: '#233e35'
  surface-container-lowest: '#00120b'
  surface-container-low: '#042018'
  surface-container: '#08241c'
  surface-container-high: '#132f26'
  surface-container-highest: '#1f3a30'
  on-surface: '#cae9db'
  on-surface-variant: '#c7c6cd'
  inverse-surface: '#cae9db'
  inverse-on-surface: '#1a352c'
  outline: '#909097'
  outline-variant: '#46464c'
  surface-tint: '#c2c5db'
  primary: '#c2c5db'
  on-primary: '#2c3041'
  primary-container: '#2d3142'
  on-primary-container: '#9599ad'
  inverse-primary: '#5a5d70'
  secondary: '#ffb59e'
  on-secondary: '#5d1800'
  secondary-container: '#ca3e01'
  on-secondary-container: '#fff1ee'
  tertiary: '#a5d0b9'
  on-tertiary: '#0e3727'
  tertiary-container: '#103929'
  on-tertiary-container: '#7aa38e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dee1f8'
  primary-fixed-dim: '#c2c5db'
  on-primary-fixed: '#171b2b'
  on-primary-fixed-variant: '#424658'
  secondary-fixed: '#ffdbd0'
  secondary-fixed-dim: '#ffb59e'
  on-secondary-fixed: '#390b00'
  on-secondary-fixed-variant: '#842500'
  tertiary-fixed: '#c1ecd4'
  tertiary-fixed-dim: '#a5d0b9'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#274e3d'
  background: '#001710'
  on-background: '#cae9db'
  surface-variant: '#1f3a30'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-sm:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.05em
  mono-data:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.02em
spacing:
  unit: 4px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 48px
  container-max: 1440px
---

## Brand & Style

The design system is engineered for the high-end gear enthusiast—the "overlander" who demands military-grade precision paired with a premium, tech-forward aesthetic. It moves away from traditional, soft "camping" tropes into an **Experimental Tech-Forward Outdoor** identity.

The visual narrative is "Tactical Elegance." It focuses on a dark-mode-first experience that mimics the high-contrast visibility of GPS interfaces and rugged equipment displays. The interface is unapologetically sharp and structural, prioritizing information density and technical clarity. It evokes a sense of readiness, durability, and extreme reliability, positioning the product not just as equipment, but as essential instrumentation for exploration.

## Colors

This design system utilizes a high-contrast, dark-centric palette to maintain focus in variable lighting conditions. 

- **Primary Canvas:** The seed color `#2D3142` (Dark Slate) acts as the foundation for structural elements and navigation containers.
- **Action Accents:** `#D9480F` (Burnt Orange) is used exclusively for primary calls-to-action and critical status indicators, providing high visibility against the dark background.
- **Nature Integration:** `#1B4332` (Forest Green) and `#708D81` (Sage) are used for success states and thematic labeling, bridging the gap between hardware and the natural environment.
- **Technical Surface:** A deep `#0F111A` background ensures that the sharp-edged UI elements feel etched into the screen rather than floating on it.

## Typography

The typography strategy pairs technical precision with aggressive geometry. 

**Space Grotesk** is used for all headlines. Its geometric construction and idiosyncratic "tech" terminals provide a futuristic, instrument-cluster feel. It should be tracked slightly tighter in large displays to maximize impact.

**Geist** serves as the body and functional typeface. Its monospaced-influenced metrics ensure high legibility for technical specifications and gear dimensions. For data-heavy points (weight, dimensions, temperature ratings), use the `mono-data` style to reinforce the "instrumentation" aesthetic. Labels should always be uppercase to maintain a "label-maker" or military stencil vibe.

## Layout & Spacing

The layout follows a rigid 4px baseline grid, reflecting the precision of engineered outdoor gear. 

- **Grid System:** A 12-column fluid grid on desktop, transitioning to a 4-column grid on mobile. 
- **The "Technical Border":** Instead of wide margins, use structural 1px borders to define content zones.
- **Density:** High information density is encouraged. Elements should feel tightly packed and efficient, like a well-organized tactical backpack. 
- **Negative Space:** Use white space intentionally as a separator for high-level sections, but within components, keep spacing compact to maintain the "gear dashboard" feel.

## Elevation & Depth

This design system eschews soft shadows in favor of **Tonal Layering** and **High-Contrast Outlines**.

Hierarchy is established through surface color shifts rather than Z-axis depth. 
- **Level 0 (Background):** `#0F111A` — The base layer.
- **Level 1 (Cards/Sections):** `#1B1E2B` — Subtle lift with a 1px solid border of `#2D3142`.
- **Level 2 (Popovers/Modals):** `#2D3142` — Maximum contrast with a secondary accent border in Sage (`#708D81`) to indicate interactivity.

Avoid blurs. Surfaces should feel solid, opaque, and metallic. If a shadow must be used for extreme clarity, it should be a "hard shadow" (0 blur, 2px offset) to maintain the brutalist, tech-forward edge.

## Shapes

The shape language is strictly **Sharp (0px)**. 

Every component—buttons, cards, input fields, and images—must have 90-degree corners. This evokes the aesthetic of ruggedized flight cases, machined metal components, and architectural structures. The absence of curves reinforces the professional, "no-nonsense" utility of the brand. Structural integrity is visualised through these hard edges.

## Components

### Buttons
Primary buttons use a solid `#D9480F` (Burnt Orange) background with black or high-contrast white text. They are rectangular with 0px radius. Secondary buttons should be ghost-style with a 1px `#708D81` border and no fill. Use a "corner notch" or "crosshair" icon for a tactical hover state.

### Input Fields
Inputs are dark-filled `#1B1E2B` with a bottom-only border in `#2D3142`. Upon focus, the border should shift to the primary orange. Labels are always `label-md` (uppercase) positioned above the field.

### Cards
Cards do not use shadows. They are defined by a 1px border. Product cards should feature a "spec-strip" at the bottom—a small monospaced data row showing weight or SKU number, mimicking a manufacturer's tag.

### Navigation
The navigation bar should feel like an instrument panel. Use thin 1px separators between menu items. Active states are indicated by a simple orange under-line or a "selected" indicator that looks like a technical bracket `[ ]`.

### Progress Indicators
Use stepped, blocky progress bars rather than smooth continuous ones. This reinforces the mechanical, notched feel of outdoor equipment like rucksacks or carabiners.