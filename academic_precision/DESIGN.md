---
name: Academic Precision
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daee'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edff'
  surface-container-high: '#e1e8fd'
  surface-container-highest: '#dce2f7'
  on-surface: '#141b2a'
  on-surface-variant: '#3e4947'
  inverse-surface: '#293040'
  inverse-on-surface: '#edf0ff'
  outline: '#6e7977'
  outline-variant: '#bdc9c6'
  surface-tint: '#006a63'
  primary: '#005c55'
  on-primary: '#ffffff'
  primary-container: '#0f766e'
  on-primary-container: '#a3faef'
  inverse-primary: '#80d5cb'
  secondary: '#755b00'
  on-secondary: '#ffffff'
  secondary-container: '#fed255'
  on-secondary-container: '#735a00'
  tertiary: '#005b56'
  on-tertiary: '#ffffff'
  tertiary-container: '#00766f'
  on-tertiary-container: '#91fcf1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#9cf2e8'
  primary-fixed-dim: '#80d5cb'
  on-primary-fixed: '#00201d'
  on-primary-fixed-variant: '#00504a'
  secondary-fixed: '#ffe08e'
  secondary-fixed-dim: '#ecc246'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#584400'
  tertiary-fixed: '#8af4ea'
  tertiary-fixed-dim: '#6dd8ce'
  on-tertiary-fixed: '#00201e'
  on-tertiary-fixed-variant: '#00504b'
  background: '#f9f9ff'
  on-background: '#141b2a'
  surface-variant: '#dce2f7'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Sora
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  data-label:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
  button-text:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: '1.0'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  section-gap-desktop: 80px
  section-gap-mobile: 48px
  card-padding: 24px
  grid-gutter: 24px
  container-max: 1200px
---

## Brand & Style
The design system is anchored in a philosophy of **Instructional Elegance**. It targets high-achieving students and early-career professionals who require a focused, distraction-free environment for placement preparation. The aesthetic sits at the intersection of Apple’s spaciousness and Stripe’s functional clarity.

The visual narrative is "Premium Academic," emphasizing stability, intelligence, and upward mobility. We avoid trendy visual gimmicks in favor of high-quality typography, precise alignment, and a sophisticated, grounded color palette. The UI should feel like a high-end physical textbook translated into a high-performance digital workspace.

## Colors
The palette is designed to reduce cognitive load while maintaining clear semantic hierarchies. 

- **Primary Background (#F6F7F4):** A warm, off-white that prevents screen fatigue during long study sessions.
- **Deep Emerald (#0F766E):** Used for primary actions and symbols of growth/intelligence.
- **Champagne Gold (#C9A227):** Reserved exclusively for moments of achievement, milestones, and premium "pro" features.
- **Soft Teal (#2FA39A):** Used for highlighting progress and secondary interactive states.
- **Grays:** We use a deep charcoal (#1D2433) for high-contrast legibility in headings, and a muted slate (#667085) for supporting metadata.

## Typography
Typography is the primary driver of the system's "Premium" feel. 

1. **Headings (Sora):** Utilize tight letter-spacing on larger sizes to create a modern, authoritative look.
2. **Body (Inter):** Set with generous line-heights to ensure readability during dense technical reading or interview prep instructions.
3. **Technical (JetBrains Mono):** Used for code snippets, performance metrics, and "time-to-complete" labels. This adds a layer of "engineering precision" to the student's data.

## Layout & Spacing
The system employs a **Fixed Grid** philosophy for desktop (12 columns) and a **Fluid Layout** for mobile. 

- **Whitespace as a Feature:** Do not pack elements. Every primary container should breathe with a minimum of 24px internal padding. 
- **Section Breaks:** Use large vertical gaps (80px+) between major content areas to maintain a "calm" interface.
- **Alignment:** Strictly align technical data labels (JetBrains Mono) to the right or center within their specific data cells to maintain a clean vertical rhythm.

## Elevation & Depth
This design system avoids heavy shadows and floating effects. 

- **Flat Layering:** Depth is communicated through color contrast (White surfaces on Off-white backgrounds).
- **Subtle Borders:** All "cards" and input fields must use a 1px solid border (#D8DEE4). No shadows should be used for default states.
- **Interaction Depth:** On hover, a card may transition to a 2px Deep Emerald bottom border or a very soft, diffused ambient shadow (0px 4px 20px rgba(0,0,0,0.04)) to indicate interactivity.

## Shapes
A "Rounded" approach (0.5rem base) is used to balance the professional navy/emerald tones with an approachable educational feel. 

- **Primary Elements:** Buttons and Input fields use the 8px (0.5rem) radius.
- **Large Containers:** Course cards and modal overlays use the 16px (1rem) radius.
- **Status Tags:** Use 100px (Pill) radius for labels like "Completed" or "In Progress" to differentiate them from interactive buttons.

## Components

- **Buttons:** Primary buttons are solid Deep Emerald (#0F766E) with White text. Secondary buttons use a White background with the #D8DEE4 border and Deep Navy text. All buttons have a subtle 200ms ease-in-out transition on hover.
- **Cards:** Must have a white background, 1px border (#D8DEE4), and 24px padding. No heavy drop shadows.
- **Input Fields:** Use Inter (Body-md). The border turns Deep Emerald on focus with a 2px outer "glow" of the same color at 10% opacity.
- **Progress Bars:** Use a dual-tone approach. The track is the Background color (#F6F7F4) and the filler is Soft Teal (#2FA39A).
- **Achievement Badges:** Circular or hex-shaped containers utilizing the Champagne Gold (#C9A227) as a stroke or icon color to denote prestige.
- **Technical Snippets:** Monospaced data blocks should have a slightly darker background (#F1F3F5) to distinguish them from standard content.