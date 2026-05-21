---
name: Cinematic Kineticism
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#38393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c5c9ac'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#8f9378'
  outline-variant: '#444932'
  surface-tint: '#b0d500'
  primary: '#ffffff'
  on-primary: '#2a3400'
  primary-container: '#caf300'
  on-primary-container: '#596c00'
  inverse-primary: '#536600'
  secondary: '#c9c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#ffffff'
  on-tertiary: '#313030'
  tertiary-container: '#e5e2e1'
  on-tertiary-container: '#656464'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#caf300'
  primary-fixed-dim: '#b0d500'
  on-primary-fixed: '#171e00'
  on-primary-fixed-variant: '#3e4c00'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c9c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-xl:
    fontFamily: Space Grotesk
    fontSize: 80px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin: 40px
---

## Brand & Style

The design system is engineered to evoke the high-octane energy of a premium motion studio while maintaining the rigorous precision of a top-tier digital agency. It centers on a "High-Performance Tech" aesthetic—where speed meets luxury. The brand personality is authoritative, cutting-edge, and unapologetically bold. 

The visual style leverages **High-Contrast Minimalism**. By stripping away decorative clutter and focusing on aggressive typography and vibrant accents against a void-like background, the design system creates a sense of focused power. It avoids soft aesthetics in favor of architectural rigidity and digital clarity, ensuring every interface feels like a high-end professional tool.

## Colors

The palette is built on a foundation of absolute blacks and deep charcoal grays to provide maximum depth and minimize visual noise. The primary accent is an "Electric Lime"—a high-energy neon yellow/green that cuts through the dark interface with surgical precision.

- **Primary:** Electric Lime (#D4FF00) used for critical calls to action, active states, and brand-defining highlights.
- **Surface Tiers:** A hierarchy of grays from Charcoal (#0A0A0A) to Steel (#2D2D2D) defines layers without breaking the dark-mode immersion.
- **Data/Feedback:** Use the primary accent for success or "go" states; maintain high-contrast white for information density.

## Typography

Typography in the design system is split between "Cinematic Impact" and "Technical Clarity." 

**Space Grotesk** is used for headlines and labels. Its geometric, slightly futuristic construction provides the technical edge required for a premium agency. Headlines should be set with tight letter-spacing to feel dense and impactful.

**Inter** handles all body and long-form text. It was selected for its exceptional legibility in dark mode and its neutral character, which allows the headlines to command attention. Small labels and "meta" information should be set in Space Grotesk Bold, Uppercase, to reinforce the high-performance aesthetic.

## Layout & Spacing

The design system utilizes a **12-column fluid grid** for web layouts, emphasizing generous outer margins to frame content like a cinematic wide-shot. The internal rhythm is governed by a strict 8px linear scale.

Spacing is used to create "clumping"—where related technical data is tightly grouped (8px–12px) while major content sections are separated by massive vertical voids (80px+). This contrast in density creates a sophisticated, editorial rhythm that guides the eye through complex information.

## Elevation & Depth

This design system rejects traditional shadows and soft blurs. Depth is achieved through **Tonal Layering** and **Sharp Gradients**. 

- **Surface Levels:** Elements closer to the user are rendered in slightly lighter shades of charcoal (#1A1A1A or #242424) rather than using drop shadows.
- **Gradients:** Use subtle, linear gradients (45-degree angle) on cards to simulate a metallic or glass sheen, but keep the edges perfectly sharp.
- **Accents:** Depth is also communicated through "Glow Borders"—1px solid strokes of the primary accent color or a low-opacity version of it to define the silhouette of an element against the black background.

## Shapes

The shape language is defined by **Absolute Precision**. To maintain the "High-Performance" and "Tech-Forward" narrative, the design system utilizes a 0px border radius across all components. 

Sharp corners evoke a sense of professional-grade hardware and architectural blueprints. This rigidity must be consistent; from buttons to massive image containers, every corner must be a perfect 90-degree angle. This lack of softness differentiates the product from more consumer-leaning, "friendly" SaaS platforms.

## Components

### Buttons
Primary buttons are solid blocks of the accent color (#D4FF00) with black Space Grotesk text. They feature no rounding and a subtle 1px inset border for a technical finish. Secondary buttons use a 1px white or accent-colored stroke with no fill.

### Input Fields
Inputs are minimal: a bottom-border only or a 1px charcoal outline. Upon focus, the border transitions to the primary accent color with a sharp, non-blurred outer glow effect.

### Cards
Cards are defined by a background color slightly lighter than the page foundation (#1A1A1A). They should not have shadows. Instead, use a 1px border (#2D2D2D) that highlights on hover.

### Progress Indicators
Reflecting the "Motion" aspect of the agency, progress bars and loaders should use the primary accent color with high-speed, linear animations. 

### Navigation
The navigation should be sparse and high-contrast, utilizing the uppercase label style for menu items to create a utilitarian, dashboard-like feel.