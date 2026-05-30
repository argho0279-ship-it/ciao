---
name: Modern Trattoria
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#44483b'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#75796a'
  outline-variant: '#c5c8b7'
  surface-tint: '#4d661d'
  primary: '#293d00'
  on-primary: '#ffffff'
  primary-container: '#3d550c'
  on-primary-container: '#acc974'
  inverse-primary: '#b3d17b'
  secondary: '#954742'
  on-secondary: '#ffffff'
  secondary-container: '#fe9b94'
  on-secondary-container: '#78302d'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cca730'
  on-tertiary-container: '#4f3e00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ceee94'
  primary-fixed-dim: '#b3d17b'
  on-primary-fixed: '#131f00'
  on-primary-fixed-variant: '#364e04'
  secondary-fixed: '#ffdad7'
  secondary-fixed-dim: '#ffb3ad'
  on-secondary-fixed: '#3d0506'
  on-secondary-fixed-variant: '#77302d'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: DM Sans
    fontSize: 14px
    fontWeight: '500'
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
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  section-padding-desktop: 80px
  section-padding-mobile: 48px
---

## Brand & Style

The design system is anchored in the "Modern Trattoria" aesthetic—a sophisticated intersection of rustic Italian heritage and contemporary urban elegance. It targets a discerning audience that values authenticity, culinary craftsmanship, and a refined atmosphere. 

The visual language balances **Minimalism** with **Tactile** elements. It utilizes generous whitespace to evoke a sense of high-end dining, while incorporating subtle organic textures and fine-line illustrations to ground the experience in the warmth of a traditional kitchen. The emotional response should be one of welcoming luxury: "Old World" soul met with "New World" precision.

## Colors

The palette is inspired by the essential ingredients of the Italian table. The primary **Olive Green** provides a grounded, organic foundation, while the secondary **Balsamic Red** is used for deep accents and emotional resonance. **Golden Honey** serves as the primary action color, drawing the eye to calls-to-action with a sun-drenched, premium glow. 

The background is strictly **Warm Parchment**, moving away from clinical whites to provide a tactile, paper-like feel. Typography uses **Charcoal** instead of pure black to maintain a softer, more organic contrast that remains highly readable.

## Typography

This design system employs a classic high-contrast pairing. **Playfair Display** provides the editorial authority required for a premium brand, used for all major headings and display moments. Its delicate serifs evoke the artisanal quality of hand-rolled pasta and vintage wine labels.

**DM Sans** provides a functional, modern counterpoint. It is used for body copy, menus, and descriptions to ensure maximum legibility across all digital touchpoints. Label styles utilize a slight letter-spacing and uppercase treatment to create a sense of organized, professional hierarchy.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop, centering content within a 1200px container to simulate the focused experience of a printed menu. A 12-column system provides the structure, but content is often intentionally "broken" by fine-line illustrations or overlapping food photography to create a dynamic, editorial feel.

Spacing is generous. High-end dining requires room to breathe; therefore, section vertical padding is intentionally large to prevent the UI from feeling cluttered. On mobile, the grid shifts to a single-column flow with 16px side margins, maintaining the sense of luxury through vertical rhythm rather than horizontal complexity.

## Elevation & Depth

Depth in this design system is achieved through **Tonal Layers** and **Low-Contrast Outlines** rather than aggressive shadows. 

1.  **Surfaces:** Use subtle shifts in parchment tones or very light olive washes to define different content areas.
2.  **Borders:** Use 1px solid lines in Balsamic Red (at low opacity) or Olive Green to frame content. These "Sophisticated Borders" act as a nod to traditional ledger books and classic menu design.
3.  **Shadows:** When necessary (e.g., for elevated modals), use "Ambient Shadows"—extremely soft, blurred shadows with a slight warm tint (#2D2D2D at 5% opacity) to mimic the soft glow of candlelight in a restaurant.
4.  **Glassmorphism:** Use sparingly for navigation overlays to maintain a modern edge, with a high-intensity backdrop blur and a parchment-tinted fill.

## Shapes

The shape language is **Soft (0.25rem)**. While a contemporary restaurant could use sharp corners, the slight rounding introduces a "human" element that mirrors the organic nature of food and ingredients. 

- **Standard Elements:** (Buttons, Input fields) use a 4px radius.
- **Large Elements:** (Featured Cards, Image containers) use 8px to feel more approachable.
- **Iconography:** Should be thin-stroke, monolinear illustrations with slightly rounded terminals to match the component corners.

## Components

### Buttons
Primary actions are styled in **Golden Honey** with **Charcoal** text, using the `label-md` typographic style. They should feel like a "gold leaf" accent on a parchment page. Secondary buttons use a fine 1px **Olive Green** border with no fill.

### Cards
Cards for menu items or blog posts should feature no shadow. Instead, use a thin **Balsamic Red** border (10% opacity) and a slight background color shift. Content within cards must have generous internal padding (min 24px).

### Input Fields
Inputs are minimalist, utilizing a single bottom border in **Charcoal** rather than a full box, evoking the feel of a signature line on a receipt. Labels sit above in the `label-md` style.

### Lists & Menus
Menu lists are the heart of the design system. Use the **Playfair Display** for item names and **DM Sans** for descriptions. Prices should be highlighted in **Olive Green** and positioned with a "dot leader" or significant whitespace between the item and the price.

### Textures & Imagery
Incorporate a subtle "Grain" or "Paper" overlay on all Parchment backgrounds. Food photography should always be warm-toned, shot with a shallow depth of field, and framed with significant padding to maintain the minimalist luxury.