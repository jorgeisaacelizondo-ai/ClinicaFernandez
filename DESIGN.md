---
name: Architectural Monochrome Dental
colors:
  surface: '#fbf8fc'
  surface-dim: '#dcd9dd'
  surface-bright: '#fbf8fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f2f7'
  surface-container: '#f0edf1'
  surface-container-high: '#eae7eb'
  surface-container-highest: '#e4e1e6'
  on-surface: '#1b1b1e'
  on-surface-variant: '#47464a'
  inverse-surface: '#303033'
  inverse-on-surface: '#f3f0f4'
  outline: '#78767b'
  outline-variant: '#c8c5ca'
  surface-tint: '#5f5e60'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1d'
  on-primary-container: '#858386'
  inverse-primary: '#c8c6c8'
  secondary: '#5f5e61'
  on-secondary: '#ffffff'
  secondary-container: '#e4e1e5'
  on-secondary-container: '#656467'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1a1b22'
  on-tertiary-container: '#83838c'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e1e4'
  primary-fixed-dim: '#c8c6c8'
  on-primary-fixed: '#1c1b1d'
  on-primary-fixed-variant: '#474649'
  secondary-fixed: '#e4e1e5'
  secondary-fixed-dim: '#c8c6c9'
  on-secondary-fixed: '#1b1b1e'
  on-secondary-fixed-variant: '#47464a'
  tertiary-fixed: '#e3e1ec'
  tertiary-fixed-dim: '#c6c5cf'
  on-tertiary-fixed: '#1a1b22'
  on-tertiary-fixed-variant: '#46464e'
  background: '#fbf8fc'
  on-background: '#1b1b1e'
  surface-variant: '#e4e1e6'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '600'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.1em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system expresses ultra-premium clinical mastery, architectural rigor, and understated luxury. Tailored for high-end aesthetic dentistry, implantology, and oral rehabilitation, the interface avoids sterile medical clichés (such as cold surgical cyans or pedestrian clinical blues) in favor of high-contrast editorial minimalism reminiscent of haute horlogerie and architectural monographs.

The target audience comprises discerning private patients, luxury-tier clientele, and medical professionals who value precision, immaculate hygiene, and discreet sophistication. The emotional tone must evoke calm authority, surgical precision, and bespoke hospitality. 

The aesthetic is anchored in:
- High-contrast monochromatic balance (deep obsidian tones set against pure optical whites).
- Sharp, hairline structural gridlines echoing modern architectural clinics.
- Deliberate, generous negative space that lets typography and clinical imagery breathe with unhurried confidence.

## Colors

The palette operates under an uncompromising monochromatic doctrine. Color is treated strictly as value, luminance, and contrast rather than hue.

### Palette Roles
- **Canvas Base (`#FFFFFF`):** Pure optical white used for main editorial backdrops, conveying surgical purity and pristine clinical clarity.
- **Deep Obsidian Primary (`#09090B`):** The primary anchor used for hero typography, active states, and high-impact structural panels.
- **Rich Charcoal Surface (`#121212` & `#18181B`):** Employed for dark inverted consultation modules, luxury appointment cards, and footer foundations.
- **Architectural Slate Midtones (`#27272A`, `#52525B`, `#71717A`):** Used for structural hairlines, secondary text, metadata, and iconography.
- **Subtle Platinum Surfaces (`#F4F4F5`, `#E4E4E7`):** Soft, neutral wash surfaces for secondary containers, table zebra striping, and subtle interactive hover foundations.

### Accessibility and High-Contrast Rule
Body text must strictly achieve a minimum contrast ratio of 12:1 against the canvas (using `#09090B` or `#18181B` on `#FFFFFF`, or `#FFFFFF` on `#09090B`). Accentuation is achieved not through bright chromatic alerts, but through dynamic inversion (solid black blocks juxtaposed with framed white fields).

## Typography

The type system relies exclusively on **Plus Jakarta Sans**, exploiting its geometric clarity, refined proportions, and contemporary editorial feel. 

### Typographic Hierarchy & Styling
- **Display & Large Headlines:** Set with tight tracking (`-0.03em` to `-0.02em`) and medium/semibold weights to evoke architectural poise rather than playful roundness.
- **Labels & Micro-copy:** Formatted in uppercase with generous tracking (`0.08em` to `0.1em`) using medium and semibold weights, delivering an understated luxury treatment for categories, service tags, and clinical certifications.
- **Body Copy:** Maintained at regular weight (`400`) with generous line height to prioritize effortless scan-reading and medical clarity.

## Layout & Spacing

The layout model is governed by a strict 12-column architectural grid on desktop, transitioning to an 8-column layout on tablet and a 4-column layout on mobile.

### Grid Rhythm & Principles
- **Margins & Air:** Desktop layouts require wide gutters (`1.5rem`) and expansive frame margins (`3rem`), grounding the interface with an editorial, magazine-like composure.
- **Component Padding Scale:** 
  - `space-xs` (4px) and `space-sm` (8px) for tightly grouped badges, metadata chips, and hairline cell insets.
  - `space-md` (16px) and `space-lg` (24px) for interactive controls, cards, and input clusters.
  - `space-xl` (40px) and `space-2xl` (64px) for content section separation, treatment case comparison blocks, and narrative shifts.
- **Breakpoints:**
  - Mobile: `< 768px` (Fluid stacked columns, 4 columns, `1.25rem` margin).
  - Tablet: `768px – 1024px` (8 columns, `2rem` margin).
  - Desktop: `> 1024px` (12 columns, max-width `1440px` centered, `3rem` margin).

## Elevation & Depth

This design system avoids heavy drop shadows or synthetic blurs. Depth is conveyed strictly through architectural layering and hairline boundaries:

1. **Flat Structural Stratification:** Elevation is expressed via contrasting monochromatic planes (e.g., a pure white `#FFFFFF` surface resting directly over a `#F4F4F5` backdrop or framed by `#E4E4E7`).
2. **Hairline Outlines:** Precision 1px borders (`#E4E4E7` in light mode, `#27272A` on dark modules) provide definition without visual bulk.
3. **Selective Atmospheric Shadow:** When elevation is functionally required (such as modal overlays or luxury consultation drawer trays), use a singular, ultra-diffused, desaturated shadow:
   - `box-shadow: 0 16px 40px -8px rgba(9, 9, 11, 0.06), 0 0 1px rgba(9, 9, 11, 0.12);`
4. **Dark Surface Inversion:** High-priority clinical consultations or surgical portfolio views utilize deep `#09090B` backgrounds with `#27272A` micro-borders to project quiet prestige.

## Shapes

The shape philosophy adopts a refined, nearly architectural discipline (`roundedness: 1`). 

- Standard interactive components (buttons, input fields, cards) feature subtle `0.25rem` (4px) corners.
- Large structural cards and diagnostic modal dialogs use `0.5rem` (8px) radii maximum.
- Pills and heavy circular rounding are strictly reserved for compact status indicators, verification badges, and tooth position tags (`rounded-full`). 

This balance preserves the clinical sharpness of dental instruments and architectural clinic interiors while maintaining modern touch ergonomics.

## Components

### Buttons & CTAs
- **Primary Action (VIP Consultation / Booking):** Solid `#09090B` background, `#FFFFFF` text, `4px` border radius, with `14px` or `12px` tracked uppercase typography. Hover state transitions seamlessly to `#27272A`.
- **Secondary Action:** Transparent background with a crisp `1px` solid border in `#27272A`, `#09090B` text. Hover state inverts to `#09090B` background with `#FFFFFF` text.
- **Ghost Action:** No border, `#52525B` text, with an animated `1px` underline appearing on hover.

### Form Inputs & Selectors
- Background is crisp `#FFFFFF` or subtle `#F4F4F5`.
- Border is a razor-thin `1px` `#E4E4E7`. 
- Focused state eliminates default browser glow, snapping to a solid `1px` `#09090B` border.
- Placeholder text in `#71717A`. Labels sit strictly above in uppercase `label-sm` (`#27272A`).

### Cards & Case Showcases
- **Clinical Before/After & Service Cards:** Framed by a `1px` `#E4E4E7` perimeter, padding of `space-lg` (24px), with zero drop shadows in default state.
- **Inverted Dark Feature Cards:** For exclusive surgical suites or specialist profiles, use `#09090B` fill, `#27272A` borders, `#FFFFFF` headlines, and `#71717A` body descriptions.

### Checkboxes, Radios & Switches
- Monochromatic execution: unchecked boxes use a `1px` border in `#71717A`; checked states fill with solid `#09090B` housing a sharp white interior check.
- Radios feature a nested solid `#09090B` circular dot with a `2px` white clearance ring.

### Chips & Clinical Metadata Badges
- Compact height (`24px` to `28px`), `1px` border in `#E4E4E7` or background `#F4F4F5`.
- Text styled in `label-sm` tracked uppercase in `#27272A`. Never use chromatic background fills.

### Specialized Clinical Modules
- **Odontogram / Tooth Grid:** Monochromatic wireframe vectors drawn in `#27272A` on `#FFFFFF` with active selections highlighted in solid `#09090B` fills.
- **Comparison Sliders:** Minimalist `1px` white divider line anchored by a sleek obsidian dual-arrow badge.