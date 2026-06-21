---
name: High-Performance Fitness System
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#cfc6ab'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#989177'
  outline-variant: '#4c4732'
  surface-tint: '#e3c600'
  primary: '#fffaf8'
  on-primary: '#393000'
  primary-container: '#ffde00'
  on-primary-container: '#716200'
  inverse-primary: '#6d5e00'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#fbfbfb'
  on-tertiary: '#2f3131'
  tertiary-container: '#dedfdf'
  on-tertiary-container: '#616263'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe24a'
  primary-fixed-dim: '#e3c600'
  on-primary-fixed: '#211b00'
  on-primary-fixed-variant: '#524600'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Anton
    fontSize: 80px
    fontWeight: '400'
    lineHeight: '1.0'
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Anton
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.1'
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 36px
    fontWeight: '400'
    lineHeight: '1.1'
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  section-gap-desktop: 128px
  section-gap-mobile: 64px
  container-max-width: 1280px
  gutter: 24px
---

## Brand & Style

The brand personality is high-octane, disciplined, and results-oriented. It targets individuals who view fitness as a serious pursuit of self-mastery. The emotional response should be a surge of adrenaline followed by the confidence of professional guidance.

The design style is **High-Contrast / Bold**. It utilizes a dark-mode foundation to create a focused, "theatrical" environment where content and calls-to-action (CTAs) pop with maximum intensity. Large-scale typography, aggressive directional lines, and raw, high-quality photography are used to convey movement and power.

## Colors

The palette is designed for extreme legibility and visual punch. 

- **Primary (Electric Volt):** A high-saturation yellow (#FFDE00) used exclusively for CTAs, highlights, and critical progress indicators. It represents energy and the "warning" of high intensity.
- **Surface / Neutral:** A deep "Obsidian" black (#0A0A0A) serves as the primary background to eliminate distractions. Secondary surfaces use "Carbon" gray (#1A1A1A) to create subtle depth.
- **Content:** Pure white is reserved for primary body text and headlines to maintain a stark contrast ratio against the dark background.

## Typography

This design system uses a dual-font strategy to balance raw impact with professional clarity.

- **Headlines:** `Anton` provides a condensed, powerful, and monumental feel. It should almost always be used in uppercase with tight line-height to create dense "blocks" of text that command attention.
- **Body & UI:** `Hanken Grotesk` offers a sharp, contemporary geometric feel that ensures readability for training programs and technical details.
- **System Logic:** Use `display-lg` for hero sections. Use `label-bold` for small accents like category tags or "kicker" text above headlines.

## Layout & Spacing

The layout follows a **Fluid Grid** model built on an 8px base unit. 

- **Desktop:** A 12-column grid with wide 24px gutters. Use generous vertical "Section Gaps" (128px) to allow the high-impact photography room to breathe.
- **Mobile:** A 4-column grid with 16px margins. Headlines should scale aggressively to maintain their "edge-to-edge" impact.
- **Alignment:** Consistent use of "optical heavy" alignment—elements should feel grounded. Use asymmetric layouts (e.g., text on the left, an athlete's limb breaking the container on the right) to suggest motion.

## Elevation & Depth

In this dark-themed system, depth is conveyed through **Tonal Layers** rather than heavy shadows.

- **Level 0 (Background):** Obsidian Black (#0A0A0A).
- **Level 1 (Cards/Sections):** Carbon Gray (#1A1A1A).
- **Level 2 (Popovers/Tooltips):** Lighter Carbon (#2A2A2A) with a very subtle, sharp 1px border in a semi-transparent white (10% opacity).
- **Interactive Depth:** When a card is hovered, it should not lift with a shadow; instead, it should trigger a subtle scale-up (1.02x) or the primary color border should illuminate to show focus.

## Shapes

The shape language is **Soft (0.25rem)**. While the brand is aggressive, sharp 90-degree corners feel dated; a slight radius (4px to 8px) adds a modern, "engineered" touch similar to high-end gym equipment.

- Use `rounded-sm` (4px) for buttons and input fields.
- Use `rounded-lg` (8px) for large content cards and image containers.
- Use hard edges for decorative background elements or full-width section dividers to maintain the "brutalist" undertone.

## Components

### Buttons
- **Primary:** Background in Primary Yellow, text in Obsidian Black, Bold Uppercase. High-speed hover effect: background shifts to white.
- **Secondary:** Transparent background with a 2px Primary Yellow border. 
- **Size:** Large and "tactile" (minimum 56px height for primary CTAs).

### Cards
- Background is always Carbon Gray (#1A1A1A).
- Imagery within cards should use a "Darken" blend mode or a subtle black gradient overlay at the bottom to ensure text legibility.

### Inputs
- Dark backgrounds (#1A1A1A) with bottom-only borders for a sleek, modern look. The border glows Primary Yellow when focused.

### Chips/Tags
- Small, uppercase, high-contrast badges used for "New Class" or "Elite Trainer" labels. Use the `label-bold` typographic style.

### Data Displays
- For workout stats or gym capacity, use the `Anton` font for the numbers to make them look like professional scoreboard digits.