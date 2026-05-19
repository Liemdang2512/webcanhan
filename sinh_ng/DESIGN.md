---
name: Sinh Động
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#c6c6c6'
  on-secondary: '#303030'
  secondary-container: '#474747'
  on-secondary-container: '#b5b5b5'
  tertiary: '#f2cc00'
  on-tertiary: '#3a3000'
  tertiary-container: '#d2b100'
  on-tertiary-container: '#534400'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#ffe16d'
  tertiary-fixed-dim: '#e9c400'
  on-tertiary-fixed: '#221b00'
  on-tertiary-fixed-variant: '#544600'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Montserrat
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max-width: 1200px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style

The design system is engineered for an elite demographic within high-traffic luxury environments, specifically airport lounges and premium OOH (Out-of-Home) advertising spaces. It strikes a balance between **Minimalism** and **High-Contrast Boldness**, evoking a sense of "tech-forward power" and exclusive hospitality.

The visual narrative centers on the contrast between the deep, silent void of matte black and the energetic, luminous quality of gold. It communicates reliability and high-speed energy through a "High-Voltage Luxury" aesthetic—where physical power (the ecosystem) meets digital sophistication. The UI should feel like a premium concierge: invisible until needed, then striking and authoritative when active.

## Colors

The palette is strictly nocturnal, utilizing depth and luminance to guide the eye.

- **Primary & Tertiary:** A duo of Gold (#D4AF37) and Bright Gold (#FFD700). These are reserved for high-priority actions, critical information, and the "power flow" indicators.
- **Backgrounds:** A layered approach using Piano Black (#000000) for base surfaces and Matte Black (#121212) for elevated containers or cards.
- **Typography:** Off-white (#F5F5F5) for primary readability and Silver-Gray (#E0E0E0) for metadata, ensuring high contrast without the harshness of pure white.

Interactive states should utilize a gold-tinted glow (outer-glow) rather than traditional drop shadows.

## Typography

This design system employs a high-contrast typographic pairing to signal both heritage and innovation.

- **Headlines:** `Bodoni Moda` provides an editorial, high-fashion feel. Use this for titles, value propositions, and large numeric displays (like battery percentages).
- **Body & Labels:** `Montserrat` offers a clean, geometric counterpoint that ensures legibility in low-light environments and at high speeds (OOH). 
- **Styling:** Labels should frequently use uppercase styling with increased letter spacing to enhance the "luxury brand" feel. Headlines should use tight tracking to emphasize their architectural weight.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model for desktop and large-scale OOH displays to maintain intentional, generous whitespace—a key indicator of luxury.

- **Grid:** A 12-column system with wide gutters (24px) to allow elements room to breathe.
- **Rhythm:** All spacing is derived from an 8px base unit. 
- **OOH Considerations:** For large-scale digital signage, increase the margins significantly (up to 120px) to ensure content is not cut off by physical bezels or architectural obstructions.
- **Mobile:** Content should reflow into a single column with 20px side margins, emphasizing vertical scrolling and thumb-friendly interaction zones at the bottom 40% of the screen.

## Elevation & Depth

In this dark-mode-first system, depth is communicated through **Glassmorphism** and **Luminous Accents** rather than traditional shadows.

- **Surface Strategy:** 
  - Level 0: Piano Black (#000000) base.
  - Level 1: Matte Black (#121212) cards with a 1px Gold (#D4AF37) border at 20% opacity.
  - Level 2: Translucent "Glass" layers (Background blur 20px) for overlays, drawers, and modal components.
- **Glow Effects:** Interactive elements (like active power banks or "Charge Now" buttons) should feature a subtle radial gradient glow behind them to simulate a physical LED light source.
- **Outlines:** Use ultra-thin (1px) strokes for all containers to maintain a sharp, technical precision.

## Shapes

The design system utilizes **Soft** geometry (Level 1). This choice ensures the UI feels modern and engineered rather than "organic" or "bubbly."

- **Standard Elements:** 4px (0.25rem) corner radius for buttons and input fields.
- **Large Containers:** 8px (0.5rem) for cards and modals.
- **Interactive Triggers:** Small elements like chips or toggles may use a pill-shape to distinguish them as tactile controls.

## Components

### Buttons
Primary CTAs feature a linear gradient from Gold (#D4AF37) to Bright Gold (#FFD700). On hover, the button should emit a 15px gold outer glow. Text should be Black (#000000) for maximum legibility against the gold background. Secondary buttons use a transparent background with a 1px gold stroke.

### Input Fields
Sleek, dark-filled fields (#121212) with a bottom-only 1px border. Upon focus, the border transitions to a full-box gold stroke with a subtle inner gold glow. Placeholders are set in Montserrat Light at 50% opacity.

### Cards & Containers
Cards utilize a "Glass-Dark" style: a black background at 80% opacity with a 20px backdrop blur. Borders are 1px thick, using a top-to-bottom gold-to-transparent gradient to suggest a "rim-light" effect.

### Shared Power Bank Status
Specific components for battery health and availability should use the primary gold color to represent "Active/Energy." Empty slots or unavailable units should be rendered in a desaturated, low-opacity gray to recede into the background.

### Lists
List items are separated by thin, 1px lines in Matte Black (#121212). Leading icons should be rendered in Gold to act as bullet points of high importance.