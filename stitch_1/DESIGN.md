---
name: Berri Identity System
colors:
  surface: '#fef9f1'
  surface-dim: '#ded9d2'
  surface-bright: '#fef9f1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f3eb'
  surface-container: '#f2ede5'
  surface-container-high: '#ece8e0'
  surface-container-highest: '#e7e2da'
  on-surface: '#1d1c17'
  on-surface-variant: '#474552'
  inverse-surface: '#32302b'
  inverse-on-surface: '#f5f0e8'
  outline: '#787583'
  outline-variant: '#c8c4d4'
  surface-tint: '#5951b4'
  primary: '#574eb1'
  on-primary: '#ffffff'
  primary-container: '#7067cc'
  on-primary-container: '#fffbff'
  inverse-primary: '#c5c0ff'
  secondary: '#006c4e'
  on-secondary: '#ffffff'
  secondary-container: '#83f5c6'
  on-secondary-container: '#007151'
  tertiary: '#5a5a71'
  on-tertiary: '#ffffff'
  tertiary-container: '#73728b'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e4dfff'
  primary-fixed-dim: '#c5c0ff'
  on-primary-fixed: '#140067'
  on-primary-fixed-variant: '#41379b'
  secondary-fixed: '#86f8c9'
  secondary-fixed-dim: '#68dbae'
  on-secondary-fixed: '#002115'
  on-secondary-fixed-variant: '#00513a'
  tertiary-fixed: '#e2e0fc'
  tertiary-fixed-dim: '#c6c4df'
  on-tertiary-fixed: '#1a1a2e'
  on-tertiary-fixed-variant: '#45455b'
  background: '#fef9f1'
  on-background: '#1d1c17'
  surface-variant: '#e7e2da'
typography:
  display-xl:
    fontFamily: Inter
    fontSize: 72px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
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
  unit: 8px
  container-max: 1280px
  gutter: 32px
  margin-edge: 64px
  section-gap: 128px
---

## Brand & Style

The visual identity of this design system is rooted in the concept of "Nuevo amanecer del sureste." It bridges the gap between the sophisticated digital landscape and the organic warmth of the Mexican southeast. The style is **Minimalist-Modern**, prioritizing high-end editorial layouts and technical precision.

The emotional goal is to evoke a sense of calm authority and innovative growth. By contrasting the deep, nocturnal stability of *Azul noche* with the optimistic warmth of *Arena*, the interface creates a premium, tactile experience that feels both grounded and forward-thinking.

## Colors

This design system utilizes a sophisticated four-tone palette. *Arena* serves as the canvas for most layouts, providing a warmer, more human alternative to pure white. *Azul noche* is reserved for high-contrast sections (such as footers or hero overlays) and primary typography to ensure maximum legibility and a sense of luxury.

*Berri violet* is the technical heartbeat of the system, used for interactive elements and brand markers. *Verde maya* acts as a precision accent, signifying growth and the agency's regional roots without overpowering the minimalist aesthetic.

## Typography

The typography relies exclusively on **Inter** to maintain a systematic and utilitarian feel. Hierarchy is established through aggressive scale and weight shifts rather than font mixing. Large display headings use tighter letter spacing and semi-bold weights to command attention, while body text remains airy and light to ensure readability against the *Arena* background. A specialized "label-caps" style is used for eyebrows and metadata to add a touch of professional discipline.

## Layout & Spacing

This design system employs a **Fixed Grid** model. The standard layout is a 12-column grid with generous 32px gutters to prevent visual clutter. 

Whitespace (or "Arena space") is used as a structural element rather than a void. Section transitions should feel expansive, utilizing the 128px gap to give the content room to breathe. High-end agency feel is achieved by avoiding "density" in favor of "clarity." Elements should align to the grid but feel floating within the generous margins.

## Elevation & Depth

To maintain a minimalist and professional aesthetic, this design system avoids heavy shadows. Depth is primarily communicated through **Tonal Layers** and **Low-Contrast Outlines**.

1.  **Level 0 (Floor):** The *Arena* background.
2.  **Level 1 (Cards):** Surfaces use a subtle 1px border of #1A1A2E at 10% opacity.
3.  **Level 2 (Modals/Popovers):** Ultra-diffused shadows are used sparingly, using a tint of *Azul noche* (#1A1A2E) at 5% opacity with a 20px blur to simulate ambient light.
4.  **Glassmorphism:** For navigation bars, a backdrop blur of 12px with 80% opacity on *Arena* creates a premium, layered feel.

## Shapes

The shape language is disciplined and geometric. Corner radii are kept **Soft (0.25rem)** to provide a hint of approachability without losing the professional, architectural feel of the brand.

Large containers and images should follow the `rounded-lg` (0.5rem) standard, while small interactive elements like checkboxes or tag components use the base `rounded` (0.25rem) setting. This subtle rounding prevents the interface from feeling "sharp" or "hostile" while maintaining its high-end tech DNA.

## Components

### Buttons
Primary buttons use the *Berri violet* background with white text. Secondary buttons utilize a "ghost" style: a 1.5px border of *Azul noche* with no fill. Interaction states involve a subtle scale-down effect (0.98) rather than dramatic color shifts.

### Input Fields
Inputs are minimalist, consisting of a bottom border (2px) of *Azul noche* at 20% opacity. Upon focus, the border becomes the full *Berri violet* color. This maintains the clean, editorial feel of the page.

### Cards
Cards are defined by their lack of heavy containers. Use generous padding (40px+) and a light border. Portfolio cards should utilize large imagery where the *Verde maya* accent can appear on hover as an overlay icon or tag.

### Chips & Tags
Used for service categories. These should be small, uppercase (label-caps), using *Arena* as the background with an *Azul noche* border, switching to a *Verde maya* fill when indicating "active" or "success" states.

### Navigation
The navigation bar is a minimalist horizontal strip with a significant height (80px), utilizing the backdrop blur effect to signify it is on a higher z-index than the scrollable content.