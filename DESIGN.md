---
name: Clinical Excellence
colors:
  surface: '#f6faff'
  surface-dim: '#c8ddee'
  surface-bright: '#f6faff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eaf5ff'
  surface-container: '#dff0ff'
  surface-container-high: '#d6ebfc'
  surface-container-highest: '#d0e5f7'
  on-surface: '#081e2a'
  on-surface-variant: '#42474c'
  inverse-surface: '#1f3340'
  inverse-on-surface: '#e5f3ff'
  outline: '#72787d'
  outline-variant: '#c2c7cd'
  surface-tint: '#436278'
  primary: '#001927'
  on-primary: '#ffffff'
  primary-container: '#0a2e42'
  on-primary-container: '#7796ae'
  inverse-primary: '#abcae4'
  secondary: '#755b00'
  on-secondary: '#ffffff'
  secondary-container: '#fed977'
  on-secondary-container: '#785d00'
  tertiary: '#181712'
  on-tertiary: '#ffffff'
  tertiary-container: '#2c2b26'
  on-tertiary-container: '#95928b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c8e6ff'
  primary-fixed-dim: '#abcae4'
  on-primary-fixed: '#001e2f'
  on-primary-fixed-variant: '#2b4a5f'
  secondary-fixed: '#ffe08f'
  secondary-fixed-dim: '#e6c364'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#584400'
  tertiary-fixed: '#e7e2da'
  tertiary-fixed-dim: '#cac6be'
  on-tertiary-fixed: '#1d1c17'
  on-tertiary-fixed-variant: '#494741'
  background: '#f6faff'
  on-background: '#081e2a'
  surface-variant: '#d0e5f7'
  ocean-light: '#0d3a52'
  gold-light: '#e2c47a'
  gold-muted: rgba(201,168,76,0.15)
  off-white: '#faf7f2'
  text-muted: '#4a6070'
  border-gold: rgba(201,168,76,0.3)
typography:
  display-hero:
    fontFamily: Cormorant Garamond
    fontSize: 80px
    fontWeight: '300'
    lineHeight: '1.1'
    letterSpacing: 0.02em
  display-hero-mobile:
    fontFamily: Cormorant Garamond
    fontSize: 48px
    fontWeight: '300'
    lineHeight: '1.1'
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Cormorant Garamond
    fontSize: 48px
    fontWeight: '400'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Cormorant Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Cormorant Garamond
    fontSize: 22px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Montserrat
    fontSize: 18px
    fontWeight: '300'
    lineHeight: '1.8'
  body-md:
    fontFamily: Montserrat
    fontSize: 16px
    fontWeight: '300'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Montserrat
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.15em
  nav-link:
    fontFamily: Montserrat
    fontSize: 13px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  section-padding: 120px
  section-padding-mobile: 64px
  grid-gutter: 24px
  content-max-width: 1100px
  text-max-width: 750px
---

## Brand & Style

This design system embodies the intersection of elite clinical professionalism and serene, high-end hospitality. It is designed for an audience seeking a psychological practice that is as authoritative and sophisticated as it is welcoming and restorative. 

The aesthetic is **Modern Luxury**, drawing heavily from the refined precision of premium medical clinics and the calming atmosphere of luxury wellness retreats. The UI relies on expansive whitespace, a disciplined color palette, and subtle organic motifs—such as wave patterns—to evoke emotional safety and intellectual trust. Every interaction should feel intentional, quiet, and deeply considered.

## Colors

The palette is anchored by **Deep Ocean**, providing a foundation of stability, depth, and professional authority. This is contrasted by **Gold**, which serves as a beacon for action and premium quality.

- **Primary (Deep Ocean):** Used for immersive backgrounds, navigation bars, and footer surfaces to create a sense of safe, enclosed space.
- **Secondary (Gold):** Reserved for critical interactive elements, borders of distinction, and sophisticated iconography. 
- **Tertiary (Cream):** The primary surface color for high-readability content sections, providing warmth that balances the coolness of the deep blues.
- **Neutral:** A range of blues and off-whites that ensure soft transitions and sophisticated text hierarchies.

The default mode is light-themed for content-heavy sections to maintain a clinical, clean feel, transitioning to deep-themed sections for high-impact emotional resonance.

## Typography

The system utilizes a "High-Low" typographic pairing to signal both tradition and modernity. 

**Cormorant Garamond** is the voice of the practitioner: authoritative, elegant, and timeless. It is used exclusively for headlines and titles. For the hero section, the weight is kept light (300) to emphasize sophistication over mass.

**Montserrat** is the voice of the information: clean, geometric, and highly legible. It is used for body copy, navigation, and labels. Body text should maintain a light weight (300) with a generous line height (1.8) to ensure the layout feels airy and easy to process, reducing cognitive load for the user.

## Layout & Spacing

This design system uses a **Fixed Grid** philosophy to maintain the "editorial" feel of a premium publication. Content is centered within a maximum width of 1100px to prevent excessive line lengths and keep information focused.

- **Vertical Rhythm:** A generous 120px padding is used between major sections to provide visual "breathing room," signaling that the experience is not rushed.
- **Horizontal Constraints:** Long-form text blocks (About, Articles) are constrained to 750px to optimize readability.
- **Mobile Adaptations:** Vertical padding scales down to 64px on mobile devices. Grids collapse from 3 or 4 columns to a single column stack, maintaining the same gold-bordered separators to preserve brand continuity.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layers** and **Glassmorphism**, rather than heavy shadows.

- **Surface Tiers:** We use a "Light-on-Dark" and "Dark-on-Light" stacking method. For example, a slightly lighter `ocean-light` card sits on top of a `deep-ocean` background.
- **Soft Glows:** Instead of traditional grey shadows, we use a `shadow-gold`—a very diffused, low-opacity gold glow—to indicate interactivity on service cards.
- **Blur Effects:** The navigation bar utilizes a backdrop blur (20px) on scroll, maintaining a sense of the content underneath while providing a clear interactive layer.
- **Clinical Precision:** Form containers use a deep, heavy shadow (`shadow-deep`) only when they are the primary focal point of a section, such as the final Contact CTA.

## Shapes

The shape language is **Soft (0.25rem)**, leaning towards sharp corners. This choice reflects clinical precision and architectural structure. 

- **Primary Elements:** Buttons and service cards use a minimal 2px radius. This keeps the design feeling modern and high-end, avoiding the "bubbly" look of consumer-grade apps.
- **Separators:** 1px gold lines, both horizontal and vertical, are used to create structure. Vertical lines are particularly effective at suggesting "pillars" of service or support.
- **Imagery:** Photography should feature sharp edges or be contained within containers that respect the system's 2px radius.

## Components

### Buttons
- **Primary:** Solid `gold` background with `deep-ocean` text. 2px border radius. Hover state lightens the background to `gold-light`.
- **Secondary:** Transparent background with a 1px `gold` border. Text in `gold` or `cream` depending on the background.

### Cards (Service & Modality)
- **Service Cards:** Feature a 3px `gold` top-border accent. Background is either `off-white` (on light sections) or `ocean-light` (on dark sections).
- **Modality Cards:** Arranged in a tight grid with 2px gaps, creating a sophisticated "tiled" look.

### Input Fields
- Understated design with a 1px border (`rgba(10,46,66,0.2)`). On focus, the border transitions to solid `gold`. Labels use `label-caps` typography.

### Iconography
- Custom SVG icons with a 1.5pt stroke weight. Icons should never be filled; they rely on clear, open paths to match the "airy" feel of the typography.

### Waves
- Use animated SVG wave paths at the transition between hero and content sections. The movement should be slow (6s-10s duration) to provide a calming, organic background rhythm.