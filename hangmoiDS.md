---
name: Sơn Thủy Modern
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
  on-surface-variant: '#444653'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f3'
  outline: '#757684'
  outline-variant: '#c4c5d5'
  surface-tint: '#3755c3'
  primary: '#00288e'
  on-primary: '#ffffff'
  primary-container: '#1e40af'
  on-primary-container: '#a8b8ff'
  inverse-primary: '#b8c4ff'
  secondary: '#1f6c3a'
  on-secondary: '#ffffff'
  secondary-container: '#a4f1b2'
  on-secondary-container: '#24703e'
  tertiary: '#002e81'
  on-tertiary: '#ffffff'
  tertiary-container: '#0042b2'
  on-tertiary-container: '#a4b9ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b8c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#173bab'
  secondary-fixed: '#a6f4b5'
  secondary-fixed-dim: '#8bd79b'
  on-secondary-fixed: '#00210b'
  on-secondary-fixed-variant: '#005226'
  tertiary-fixed: '#dbe1ff'
  tertiary-fixed-dim: '#b4c5ff'
  on-tertiary-fixed: '#00174b'
  on-tertiary-fixed-variant: '#003ea8'
  background: '#f8f9fb'
  on-background: '#191c1e'
  surface-variant: '#e1e2e4'
typography:
  display-xl:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-xl-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Montserrat
    fontSize: 30px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
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
    lineHeight: '1.6'
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-padding: 120px
---

## Brand & Style

The design system is built on a "Sơn Thủy" (Mountain and Water) philosophy, blending the rugged endurance of premium footwear with the fluid, organic beauty of the Vietnamese landscape. It targets a sophisticated, eco-conscious consumer who values both heritage and technical performance.

The visual style is **Minimalist with Tactile Glassmorphism**. It utilizes generous whitespace to mimic the openness of a highland vista, while incorporating soft, organic container shapes that feel like polished river stones. The interface should feel serene yet high-tech, evoking a sense of grounded luxury. High-resolution photography of mist-covered mountains and emerald rice terraces serves as a structural backdrop, rather than mere decoration.

## Colors

The palette is derived from the natural elements of Vietnam:
- **Deep Water Blue (#1e40af):** Used for primary actions and foundational brand elements.
- **Forest Green (#166534):** Used for accents, secondary buttons, and environmental highlights.
- **Earthy Neutral (#f3f4f6):** The primary surface color for layout sections, providing a clean, "limestone" base.
- **Vibrant Sky (#2563eb):** Used sparingly for interactive hover states and focal text.

Maintain a high ratio of white space to color to ensure a premium, breathable aesthetic. Glassmorphism effects should use a 70% opacity white fill with a 20px background blur to create depth without clutter.

## Typography

This design system uses a dual-font approach to balance character with utility. 

**Montserrat** is the display typeface, chosen for its geometric purity and modern authority. Use it for all headlines and impactful product names. **Inter** is the functional workhorse, utilized for body copy, product descriptions, and navigational elements due to its exceptional legibility and neutral tone.

For mobile layouts, reduce display sizes significantly to maintain a comfortable reading hierarchy. Large headings should always have tight letter spacing (-0.02em) to appear more cohesive and premium.

## Layout & Spacing

The system follows a **12-column fluid grid** for desktop, transitioning to a **4-column grid** for mobile. 

- **Desktop:** 12 columns, 24px gutters, and 64px outside margins.
- **Tablet:** 8 columns, 20px gutters, and 40px outside margins.
- **Mobile:** 4 columns, 16px gutters, and 20px outside margins.

The "Generous Whitespace" directive is enforced through a strict 8px base unit. Primary sections must be separated by at least 120px on desktop to allow the brand imagery and products to "breathe." Content should be centered within a 1280px max-width container to ensure readability on ultra-wide monitors.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Ambient Diffusion**:

1.  **Level 0 (Canvas):** Pure white or `#f3f4f6` neutral.
2.  **Level 1 (Subtle Cards):** White surfaces with a very soft, large-radius shadow: `0px 10px 30px rgba(0, 0, 0, 0.04)`.
3.  **Level 2 (Glass Overlays):** Semi-transparent white layers (70% opacity) with `backdrop-filter: blur(20px)`. Used for search bars, navigation headers, and info-chips on images.
4.  **Level 3 (Active Elements):** Floating buttons or modal components with a more pronounced shadow: `0px 20px 40px rgba(30, 64, 175, 0.1)`.

Avoid harsh black shadows; always tint shadows with the primary blue color at very low opacity to maintain the organic feel.

## Shapes

The shape language is defined by the **24px organic corner radius**. This applies to all major containers including product cards, hero banners, and image frames.

- **Primary Radius:** 24px (used for cards, sections, and large buttons).
- **Secondary Radius:** 12px (used for small input fields and tags).
- **Interactive Radius:** Full pill (used for search bars and specific action chips).

Shapes should feel "found in nature," avoiding sharp edges entirely to reflect the soft curves of the Vietnamese landscape.

## Components

### Buttons
- **Primary:** Solid `#1e40af` with white text. 24px corner radius. High horizontal padding (32px).
- **Secondary:** Ghost style with `#1e40af` border (1.5px) or Forest Green solid for environmental callouts.
- **Glass:** Translucent white with backdrop blur for use over hero photography.

### Product Cards
- Cards feature a 24px radius, subtle Level 1 shadow, and a "hover lift" effect. Images should have a light grey background (`#f9fafb`) or be completely isolated (PNG) to appear 3D.
- Typography within cards uses `label-bold` for price and `headline-md` for product names.

### Input Fields
- Search bars are pill-shaped with a glassmorphism background. Iconography is thin-stroke (1.5pt) to match the Inter typography.

### Chips & Badges
- Used for "New Arrival" or "Limited Edition." These should be small, pill-shaped, and use the Forest Green color for a "natural" endorsement.

### Navigation
- A sticky header using a Glassmorphism background. The logo is anchored left, with nav links centered and utility icons (cart, profile) anchored right.