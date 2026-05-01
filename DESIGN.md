---
name: Orange Glass UI
colors:
  surface: '#1c110b'
  surface-dim: '#1c110b'
  surface-bright: '#45362f'
  surface-container-lowest: '#160c06'
  surface-container-low: '#251912'
  surface-container: '#291d16'
  surface-container-high: '#342720'
  surface-container-highest: '#40322a'
  on-surface: '#f5ded3'
  on-surface-variant: '#e0c0b1'
  inverse-surface: '#f5ded3'
  inverse-on-surface: '#3b2d26'
  outline: '#a78b7d'
  outline-variant: '#584236'
  surface-tint: '#ffb68e'
  primary: '#ffb68e'
  on-primary: '#542200'
  primary-container: '#ff7a1a'
  on-primary-container: '#5e2700'
  inverse-primary: '#9c4500'
  secondary: '#ffb59a'
  on-secondary: '#5b1b00'
  secondary-container: '#fd5900'
  on-secondary-container: '#501600'
  tertiary: '#8aceff'
  on-tertiary: '#00344e'
  tertiary-container: '#00aaf2'
  on-tertiary-container: '#003b57'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbca'
  primary-fixed-dim: '#ffb68e'
  on-primary-fixed: '#331200'
  on-primary-fixed-variant: '#773300'
  secondary-fixed: '#ffdbcf'
  secondary-fixed-dim: '#ffb59a'
  on-secondary-fixed: '#380d00'
  on-secondary-fixed-variant: '#802900'
  tertiary-fixed: '#c9e6ff'
  tertiary-fixed-dim: '#8aceff'
  on-tertiary-fixed: '#001e2f'
  on-tertiary-fixed-variant: '#004c6e'
  background: '#1c110b'
  on-background: '#f5ded3'
  surface-variant: '#40322a'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: 0.05em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '500'
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
  unit: 4px
  gutter: 24px
  margin-page: 48px
  container-max: 1440px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

This design system is engineered for high-performance, immersive digital environments. It evokes the atmosphere of a premium command center—combining the raw energy of cybernetic aesthetics with the sophisticated polish of high-end glassmorphism. 

The aesthetic is anchored in "Tech-Noir" principles, utilizing deep, obsidian surfaces contrasted against vibrant, kinetic orange illumination. The target audience values precision, innovation, and an interface that feels like a physical manifestation of advanced software. The emotional response is one of focused intensity and futuristic luxury.

## Colors

The palette is dominated by a near-black, warm-toned base that provides the necessary depth for light-based effects to thrive. The primary and secondary oranges are used sparingly as "light sources" rather than flat fills, mimicking the behavior of neon or plasma within a dark space.

A subtle radial gradient is applied to the global background, transitioning from a core of vibrant orange into the deep base. A micro-grain noise overlay is required across all surfaces to prevent color banding and add a tactile, cinematic texture.

## Typography

Typography functions as a data-visualization layer. Headlines use a wide-tracked, geometric sans-serif to mirror futuristic display panels, enhanced by a soft orange outer glow (text-shadow) to simulate light emission. 

The body text shifts to a more breathable, human-centric sans-serif to ensure legibility during extended reading sessions. Use "Warm White" for high-priority information and the "Muted" variant for meta-data and decorative labeling to maintain a clear visual hierarchy.

## Layout & Spacing

The system utilizes a 12-column fluid grid designed for expansive dashboards. Spacing is governed by a 4px base unit, favoring generous margins and gutters to give the glass elements "room to breathe." 

Layouts should prioritize a "modular cockpit" feel, where information is grouped into distinct translucent pods. Whitespace is not empty; it is a dark canvas that highlights the luminescent interactive elements.

## Elevation & Depth

Depth is created through light refraction and layering rather than traditional shadows. 
- **Base Layer:** The obsidian background with radial light spill.
- **Glass Layer:** Elevated surfaces use a 5% white tint with a 20px backdrop blur. These layers are defined by a 1px semi-transparent white border that catches "specular highlights."
- **Active Layer:** Elements currently in use or hovered should exhibit an "inner glow" of orange and an increased backdrop blur to suggest they are moving closer to the user.

## Shapes

The shape language is precise and architectural. A soft corner radius (4px to 8px) is applied to maintain a technical, engineered appearance. While fully sharp corners are too aggressive, overly rounded "pill" shapes are avoided to keep the interface feeling like professional hardware rather than a consumer toy.

## Components

### Buttons
Primary buttons are transparent glass frames with a 1px border. On hover, they "power up," displaying a subtle orange outer glow and a semi-transparent orange fill. Transitions should be smooth (300ms) to mimic the warming up of a filament.

### Cards & Modules
Containers must use the glassmorphic style: high blur, low opacity fill, and a sharp, thin border highlight. Content within cards should have a clear vertical stack with labels in the technical headline font.

### Inputs
Input fields are minimalist, utilizing a bottom-border-only approach or a very faint glass background. When focused, the border should pulse with the Primary Accent color.

### Status Indicators
Use the secondary vibrant orange for active states, alerts, or data spikes. These should always be accompanied by a "glow" effect to distinguish them from static text labels.