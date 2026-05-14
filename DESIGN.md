---
name: Heritage & Progress
colors:
  surface: '#f8f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f8f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f6'
  surface-container: '#edeef0'
  surface-container-high: '#e7e8ea'
  surface-container-highest: '#e1e2e4'
  on-surface: '#191c1e'
  on-surface-variant: '#5a413d'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f3'
  outline: '#8e706c'
  outline-variant: '#e2bfb9'
  surface-tint: '#b22b1d'
  primary: '#570000'
  on-primary: '#ffffff'
  primary-container: '#800000'
  on-primary-container: '#ff8371'
  inverse-primary: '#ffb4a8'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed01b'
  on-secondary-container: '#6f5900'
  tertiary: '#00137f'
  on-tertiary: '#ffffff'
  tertiary-container: '#0021b9'
  on-tertiary-container: '#94a0ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#ffb4a8'
  on-primary-fixed: '#410000'
  on-primary-fixed-variant: '#8f0f07'
  secondary-fixed: '#ffe083'
  secondary-fixed-dim: '#eec200'
  on-secondary-fixed: '#231b00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#dfe0ff'
  tertiary-fixed-dim: '#bcc2ff'
  on-tertiary-fixed: '#000c61'
  on-tertiary-fixed-variant: '#1830c2'
  background: '#f8f9fb'
  on-background: '#191c1e'
  surface-variant: '#e1e2e4'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 42px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-sm:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  section-gap: 80px
---

## Brand & Style

This design system establishes an authoritative, premium, and movement-oriented visual language. It is designed to evoke a sense of heritage, leadership, and structured progress. The aesthetic leans heavily into **Modern Editorial** and **High-Contrast Bold** styles, prioritizing clarity and impact over decorative trends.

The UI should feel like a high-end broadsheet or a prestigious institutional publication. It avoids the "disposable" feel of modern SaaS by using substantial weight, deliberate whitespace, and a restricted but powerful color palette. The emotional response is one of trust, stability, and collective purpose.

## Colors

The palette is rooted in the traditional and symbolic colors of leadership. 

- **Primary (Deep Maroon):** Used for key branding elements, primary navigation, and headers. It represents authority and the core identity of the movement.
- **Secondary (Golden Yellow):** Reserved exclusively for calls to action, high-priority highlights, and "Victory" states. It provides a sharp contrast against the maroon.
- **Neutral (Light Grey/Off-White):** Used for background layering and section separation to keep the interface feeling airy and editorial.
- **Text:** High-contrast charcoal and black for maximum legibility.

This system does not support dark mode; it relies on the purity of a white-based "paper" aesthetic to maintain its professional political character.

## Typography

The typography strategy focuses on a clear hierarchy between the "voice of leadership" and "information."

- **Montserrat (Headlines):** Used in Bold and ExtraBold weights. It provides a geometric, modern, and commanding presence for slogans, titles, and major movement statements.
- **Inter (Body & UI):** Used for long-form reading, data, and functional labels. Its neutrality ensures it doesn't compete with the headlines while maintaining perfect legibility at all sizes.

Vertical rhythm is critical. Use generous line-heights for body text to ensure an editorial, readable feel. Labels and small descriptors should frequently use uppercase with slight letter-spacing to denote a formal, institutional quality.

## Layout & Spacing

The design system utilizes a **Fixed Grid** model for desktop to maintain a structured, newspaper-like layout. On smaller screens, it transitions to a fluid model with defined safe margins.

- **Grid:** A 12-column grid is standard for desktop. Elements should snap to the grid to maintain a disciplined aesthetic.
- **Whitespace:** Emphasize "Macro-whitespace" between sections (using `section-gap`). This allows the high-contrast maroon elements to breathe and prevents the UI from feeling cluttered or "noisy."
- **Alignment:** Use left-alignment for most editorial content. Center-alignment is reserved for high-impact hero statements and movement manifestos.

## Elevation & Depth

To avoid a "SaaS" look, the design system rejects soft ambient shadows and blurred depth. Instead, it uses **Tonal Layers** and **Low-Contrast Outlines**.

- **Depth through Color:** Backgrounds alternate between White (`#FFFFFF`) and Light Grey (`#F3F4F6`) to distinguish sections.
- **Borders:** Use thin (1px) solid borders in a slightly darker grey (`#D1D5DB`) to define cards and containers.
- **No Shadows:** Shadows are omitted entirely to keep the design grounded and physical, like ink on paper. 
- **Z-Index:** Navigation bars should remain sticky but use a flat bottom-border for separation rather than a shadow.

## Shapes

The shape language is conservative and disciplined. 

The design system uses **Soft** corners (`roundedness: 1`). This 4px base radius is enough to take the edge off the "brutalism" without making the UI look playful or "app-like." It strikes a balance between professional rigidity and modern accessibility. 

Interactive elements like buttons and input fields should strictly follow this corner radius. Circular/Pill shapes are only permitted for status badges or numeric notifications.

## Components

### Buttons
- **Primary:** Solid Maroon (`#800000`) with White text. Bold weight. Rectangular with 4px radius.
- **Action/Accent:** Solid Golden Yellow (`#FACC15`) with Black or Maroon text. Used for "Join" or "Donate."
- **Ghost:** Transparent background with a Maroon 2px border.

### Cards
Cards are flat containers with a White background and a 1px Grey border. Header areas within cards can use a Light Grey background to create a clear "Information Header." No shadows are allowed.

### Input Fields
Inputs should have a White background, a 1px border, and a slight "Inset" feel. Labels should be placed above the field in `label-bold` style.

### Lists & Navigation
Navigation is clean, using `label-bold` typography. Active states are indicated by a 3px Maroon underline rather than a background change.

### Movement Timeline
A custom vertical line component (Maroon) with circular nodes to represent the history or future roadmap of the movement.

### Information Banners
Full-width Maroon strips with White or Golden Yellow text for urgent movement announcements or proclamations.