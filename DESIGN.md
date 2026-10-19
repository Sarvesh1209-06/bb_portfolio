---
name: Big Buddy Fitness Studio
colors:
  surface: '#11150a'
  surface-dim: '#11150a'
  surface-bright: '#373b2e'
  surface-container-lowest: '#0c0f06'
  surface-container-low: '#191d12'
  surface-container: '#1d2116'
  surface-container-high: '#282b20'
  surface-container-highest: '#32362a'
  on-surface: '#e1e4d2'
  on-surface-variant: '#c3c9b0'
  inverse-surface: '#e1e4d2'
  inverse-on-surface: '#2e3226'
  outline: '#8d937d'
  outline-variant: '#434936'
  surface-tint: '#9ed830'
  primary: '#fbffeb'
  on-primary: '#233600'
  primary-container: '#b7f34a'
  on-primary-container: '#4b6d00'
  inverse-primary: '#476800'
  secondary: '#aed373'
  on-secondary: '#223600'
  secondary-container: '#395600'
  on-secondary-container: '#a6cb6d'
  tertiary: '#fcfef5'
  on-tertiary: '#2e312c'
  tertiary-container: '#dfe1d9'
  on-tertiary-container: '#61645d'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#b9f54c'
  primary-fixed-dim: '#9ed830'
  on-primary-fixed: '#131f00'
  on-primary-fixed-variant: '#354e00'
  secondary-fixed: '#c9ef8c'
  secondary-fixed-dim: '#aed373'
  on-secondary-fixed: '#121f00'
  on-secondary-fixed-variant: '#334f00'
  tertiary-fixed: '#e2e3db'
  tertiary-fixed-dim: '#c5c7bf'
  on-tertiary-fixed: '#191c17'
  on-tertiary-fixed-variant: '#454842'
  background: '#11150a'
  on-background: '#e1e4d2'
  surface-variant: '#32362a'
typography:
  headline-xl:
    fontFamily: Outfit
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 60px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Outfit
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Outfit
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Outfit
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '500'
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
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.05em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system channels high-octane fitness energy, combining the pulse-pounding aesthetic of Cult.fit with ultra-clean rounded geometry and sophisticated high-contrast framing. The brand personality is bold, electric, uncompromising, and deeply motivating. 

The visual style leans into a **High-Contrast / Bold** design movement integrated with modern athletic minimalism. It uses piercing neon accents against deep obsidian and charcoal backdrops to create a high-octane visual rhythm that commands attention and drives action.

## Colors

The color palette is built for maximum visual impact in a dark environment. The primary neon green (`#B7F34A`) acts as the core electrical current, driving interactive states and primary call-to-actions. The secondary tone (`#D8FF9A`) provides softer gradient highlights and active states. Deep black (`#10110F`) and charcoal (`#1B1E19`) construct the spatial foundation, while pure white (`#FFFFFF`) ensures razor-sharp legibility for high-priority statistics and headlines.

## Typography

Typography fuses athletic punch with supreme readability. **Outfit** is deployed for headlines to deliver wide, geometric, commanding statements that scale effectively from mobile viewports to massive studio displays. **Plus Jakarta Sans** provides a soft, rounded, highly legible body font that keeps workout logs, schedules, and metrics crystal clear under any lighting condition.

## Layout & Spacing

The layout utilizes a robust **Fluid Grid** model optimized for high-energy mobile apps and desktop booking dashboards. Spacing relies on an 8pt-derived rhythm to maintain structural alignment across dynamic workout cards, live class grids, and schedule matrices. Margins scale dynamically: 16px on compact mobile screens, expanding to 32px on tablets and 64px on desktop environments to maintain generous breathing room.

## Elevation & Depth

Depth is established primarily through **Low-contrast outlines and tonal layering** backed by subtle, neon-tinted ambient glows. Rather than heavy drop shadows, surfaces rely on crisp tonal shifts between deep black (`#10110F`) and charcoal (`#1B1E19`), framed by razor-thin, high-contrast borders or soft 5% opacity primary color highlights to emphasize interactive states.

## Shapes

The design system enforces a **Pill-shaped (3)** roundedness strategy. Buttons, badges, avatar containers, and primary input fields utilize fully rounded pill geometries, communicating an ultra-clean, modern, and approachable athletic identity. Cards and large structural containers adopt large corner radii (`2rem` to `3rem`) to balance the high-contrast aesthetic with soft, inviting ergonomics.

## Components

### Buttons
Primary action buttons are fully rounded pill shapes filled with the neon primary color (`#B7F34A`), featuring bold black text for maximum contrast. Secondary actions utilize transparent backgrounds with high-contrast white or charcoal borders and clean hover states.

### Chips & Badges
Compact status indicators and filter tags use pill geometries with dark charcoal surfaces, subtle borders, and bright neon typography to denote active states, workout intensities, or category tags.

### Lists
Class schedules and instructor lists are structured with clean horizontal dividers, generous vertical padding, and distinct typographic hierarchy separating time slots, class titles, and remaining capacity counts.

### Checkboxes & Radio Buttons
Custom controls feature thick, high-contrast borders with solid neon fill states upon selection, incorporating smooth micro-animations for an energetic tactile response.

### Input Fields
Form inputs for booking and profile creation feature pill-shaped containers with charcoal background fills, subtle focus rings in primary neon, and floating labels in Plus Jakarta Sans.

### Cards
Workout and instructor cards are built with smooth, heavily rounded corners, dark surface fills, and optional high-contrast image overlays with gradient scrims to ensure text legibility over action photography.