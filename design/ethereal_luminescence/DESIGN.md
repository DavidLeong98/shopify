---
name: Ethereal Luminescence
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#4b463f'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#7d766e'
  outline-variant: '#cec5bc'
  surface-tint: '#645d55'
  primary: '#645d55'
  on-primary: '#ffffff'
  primary-container: '#f5ebe0'
  on-primary-container: '#706a61'
  inverse-primary: '#cec5bb'
  secondary: '#675d54'
  on-secondary: '#ffffff'
  secondary-container: '#ebddd2'
  on-secondary-container: '#6b6158'
  tertiary: '#6d5b4f'
  on-tertiary: '#ffffff'
  tertiary-container: '#ffe8db'
  on-tertiary-container: '#7a675b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ebe1d6'
  primary-fixed-dim: '#cec5bb'
  on-primary-fixed: '#1f1b14'
  on-primary-fixed-variant: '#4c463e'
  secondary-fixed: '#eee0d5'
  secondary-fixed-dim: '#d2c4b9'
  on-secondary-fixed: '#211a14'
  on-secondary-fixed-variant: '#4e453d'
  tertiary-fixed: '#f7decf'
  tertiary-fixed-dim: '#dac2b4'
  on-tertiary-fixed: '#261910'
  on-tertiary-fixed-variant: '#544339'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '400'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  section-gap: 120px
---

## Brand & Style
The design system embodies **Quiet Luxury**—a philosophy of restraint, quality, and sensory calm. Targeting a discerning audience seeking wellness and high-end skincare, the UI evokes an emotional response of serenity and clinical trust.

The aesthetic is **Refined Minimalism** with a focus on editorial composition. By utilizing expansive whitespace (negative space), the system allows product photography to breathe, treating each item like a piece of art. Transitions should be fluid and slow, mimicking the deliberate pace of a self-care ritual.

## Colors
The palette is rooted in human skin tones and natural minerals. 
- **Primary (Cream):** Used for large surface areas to provide a warm, inviting backdrop that is softer than pure white.
- **Secondary (Blush):** Reserved for subtle highlights, interactive states, and soft containers.
- **Tertiary (Nude):** Used for depth, such as borders, disabled states, or secondary backgrounds.
- **Neutral (Charcoal):** Employed exclusively for typography and high-contrast UI elements to ensure AA accessibility and a sophisticated "ink on paper" feel.

## Typography
The typographic scale relies on the juxtaposition of a romantic, high-contrast serif and a modern, technical sans-serif. 

**Playfair Display** is used for editorial headlines and product titles, often set with slightly tighter letter spacing for a premium feel. **Plus Jakarta Sans** provides a clean, breathable experience for long-form descriptions and functional labels. Use "Label-SM" for metadata and eyebrow headers, always in uppercase with generous tracking to maintain the luxury feel.

## Layout & Spacing
This design system utilizes a **Fixed Grid** for desktop and a **Fluid Grid** for mobile. The layout is intentionally sparse. 

- **Desktop:** A 12-column grid with a maximum width of 1280px. Use large 120px vertical gaps between sections to distinguish content blocks without the need for dividers.
- **Mobile:** A 4-column fluid grid.
- **Rhythm:** All spacing must be a multiple of 8px. Elements within a card use 16px (2u) or 24px (3u) padding to maintain an airy feel.

## Elevation & Depth
To maintain a minimalist profile, the design system avoids heavy shadows. Depth is achieved through **Tonal Layering** and **Low-Contrast Outlines**.

- **Surfaces:** Use subtle shifts between Primary (Cream) and Secondary (Blush) colors to indicate hierarchy.
- **Outlines:** Use 1px solid lines in Tertiary (Nude) for input fields and card boundaries.
- **Shadows:** When necessary for high-level modals, use a "Soft Ambient" shadow: `0 20px 40px rgba(47, 47, 47, 0.05)`. This creates a lifted effect without visual "noise."

## Shapes
The shape language is "Soft-Modern." Elements feature subtle 4px corner radii (Soft) to feel approachable yet architectural. High-radius or pill shapes are avoided to prevent the UI from looking too "playful" or "tech-focused." Images should remain sharp-edged or use extremely subtle rounding to mimic high-end print magazines.

## Components
- **Buttons:** Primary buttons are solid Charcoal with White/Cream text, rectangular with 4px rounding. Secondary buttons use a Charcoal outline with no fill.
- **Input Fields:** Bottom-border only (minimalist style) or full 1px Tertiary-colored outlines. Labels are always small, uppercase, and placed above the field.
- **Cards:** Background-less or very light Blush background. Use generous padding (32px+) and no heavy borders. Images should be the hero of the card.
- **Chips:** Used for skincare categories (e.g., "Vegan," "Paraben-Free"). Small, uppercase text inside a Tertiary-colored light fill.
- **Lists:** Clean, horizontal dividers using 0.5px thickness in Tertiary color.
- **Quantity Pickers:** Minimalist +/- controls with no box, just text and icons separated by whitespace.
- **Product Badges:** Small, elegant circles or subtle "New" text in a serif font, never loud or neon.