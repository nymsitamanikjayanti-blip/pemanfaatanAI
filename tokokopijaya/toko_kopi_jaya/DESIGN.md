---
name: Toko Kopi Jaya
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#504442'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#827472'
  outline-variant: '#d3c3c0'
  surface-tint: '#745853'
  primary: '#271310'
  on-primary: '#ffffff'
  primary-container: '#3e2723'
  on-primary-container: '#ae8d87'
  inverse-primary: '#e3beb8'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed65b'
  on-secondary-container: '#745c00'
  tertiary: '#300d00'
  on-tertiary: '#ffffff'
  tertiary-container: '#521b00'
  on-tertiary-container: '#d67d54'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#e3beb8'
  on-primary-fixed: '#2b1613'
  on-primary-fixed-variant: '#5b403c'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb596'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#76320f'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-lg:
    fontFamily: ebGaramond
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: ebGaramond
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: ebGaramond
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.2'
  title-md:
    fontFamily: plusJakartaSans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: plusJakartaSans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  body-sm:
    fontFamily: plusJakartaSans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: plusJakartaSans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max-width: 1200px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style

The brand identity revolves around the concept of "Kehangatan yang Elegan" (Elegant Warmth). This design system balances the rustic charm of traditional coffee culture with modern, premium sensibilities. It targets a diverse Indonesian demographic—from students seeking a focused workspace to families enjoying a weekend treat—by maintaining a tone that is both professional and deeply welcoming.

The visual style is a blend of **Minimalism** and **Tactile** design. We utilize heavy whitespace and a refined grid to ensure clarity, while incorporating "physical" cues like soft ambient shadows and metallic accents to evoke the premium feel of a physical boutique cafe. The aesthetic should feel like a sun-drenched afternoon in a high-end Jakarta coffee house: bright, airy, but grounded by deep, earthy tones.

## Colors

The palette is rooted in organic, coffee-inspired tones to reinforce the "Jaya" (Success/Glory) aspect of the brand through premium accents.

- **Primary (Espresso):** A deep, rich brown used for primary text, navigation, and core branding elements. It provides the "weight" and professional grounding for the UI.
- **Secondary (Gold Leaf):** Used sparingly for interactive accents, subtle borders, and highlights. This signifies the premium quality of the product.
- **Tertiary (Terracotta):** A warm, clay-like accent used for "human" elements like notifications, specific call-to-actions, or active states to add a cozy, local feel.
- **Surface (Cream & White):** We use a warm off-white (#FDFBF7) as the primary canvas to avoid the clinical feel of pure white, paired with pure white for card surfaces to create subtle layered depth.
- **Black:** Reserved for high-contrast utility text and heavy iconography.

## Typography

This design system uses a sophisticated typographic pairing to signal both heritage and modernity.

- **Headings (EB Garamond):** Used for storytelling, product names, and section titles. The serif nature conveys authority and a "premium boutique" feel. It should be typeset with slightly tighter letter-spacing for large displays.
- **Body & Interface (Plus Jakarta Sans):** Chosen specifically for its modern, friendly, and highly legible geometric forms. It handles the "functional" side of the UI—menus, descriptions, and buttons—ensuring the app feels contemporary and accessible to tech-savvy users in Indonesia.
- **Localization Note:** Ensure line heights are generous (1.5+) for Indonesian body text, as the language often uses longer words that require more breathing room for comfortable scanning.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** approach for desktop to maintain a controlled, editorial feel, transitioning to a **Fluid Grid** for mobile devices.

- **The 8px Rhythm:** All padding, margins, and component heights must be multiples of 8px.
- **Card-Based Architecture:** Information is encapsulated in cards to mimic the look of a physical cafe menu or coasters. This allows for clean categorization of coffee types, food, and promo banners.
- **White Space:** Use generous "breathing room" around photography. We prioritize an uncluttered view over information density.
- **Breakpoints:**
  - Mobile: < 600px (1-column layout, 16px margins).
  - Tablet: 600px - 1024px (2-column layout, 24px margins).
  - Desktop: > 1024px (12-column grid, max-width 1200px).

## Elevation & Depth

To achieve the "warm lighting vibes," elevation in this design system is conveyed through soft, tinted shadows rather than harsh greys.

- **Shadow Profile:** Use a "Coffee Glow" shadow—a low-opacity espresso tint (#3E2723 at 8-12%) with a high blur radius (16px to 32px). This mimics the soft dispersion of warm indoor lighting.
- **Layering:** 
  - **Level 0 (Background):** Cream (#FDFBF7).
  - **Level 1 (Cards/Surface):** Pure White with a subtle 1px golden border (#D4AF37 at 20% opacity).
  - **Level 2 (Interactive/Hover):** Increased shadow spread and a more pronounced golden border.
- **Glassmorphism:** Use subtle backdrop blurs (10px) on navigation bars to allow the warm tones of photography to bleed through as the user scrolls.

## Shapes

The shape language is purposefully **Rounded** to evoke comfort and friendliness. 

- **Primary Radius:** 0.5rem (8px) for standard buttons and input fields.
- **Large Radius:** 1rem (16px) for cards and featured image containers.
- **Pill Shapes:** Used exclusively for tags/chips (e.g., "Promo," "Tersedia," "Baru") to distinguish them from actionable buttons.
- **Golden Borders:** Use a subtle, thin (1px) border on primary cards to give them a "framed" appearance, reminiscent of high-end packaging.

## Components

- **Buttons:**
  - *Primary:* Solid Espresso (#3E2723) with white text. High-contrast and authoritative.
  - *Secondary:* Outlined with Gold (#D4AF37) and Espresso text.
  - *Tertiary:* Text-only with a Terracotta underline for "batal" or "kembali" actions.
- **Cards:**
  - Must include a `16px` inner padding.
  - Featured cards should use high-quality lifestyle photography as the background with a 40% espresso overlay for text legibility.
- **Input Fields:**
  - Minimalist design. Use a simple bottom-border that transforms into a full golden outline upon focus. 
  - Label text should use `label-caps` typography.
- **Chips/Badges:**
  - Soft Terracotta backgrounds with dark brown text for labels like "Best Seller" or "Seasonal."
- **Photography:** 
  - Use a consistent "Warm/Gold" filter. Avoid cold blues or high-saturation neon colors. Focus on steam, textures (wood, ceramic), and candid human interactions.
- **Product Lists:**
  - Use a clean list with "Price" right-aligned in `title-md` (Plus Jakarta Sans) to emphasize the premium value.