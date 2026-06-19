---
name: Literary Modernist
colors:
  surface: '#fdf9f0'
  surface-dim: '#dedad1'
  surface-bright: '#fdf9f0'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ea'
  surface-container: '#f2ede4'
  surface-container-high: '#ece8df'
  surface-container-highest: '#e6e2d9'
  on-surface: '#1c1c16'
  on-surface-variant: '#444748'
  inverse-surface: '#32302a'
  inverse-on-surface: '#f5f0e7'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5e5e5b'
  on-secondary: '#ffffff'
  secondary-container: '#e1dfdb'
  on-secondary-container: '#63635f'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#191d0e'
  on-tertiary-container: '#818671'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#e4e2dd'
  secondary-fixed-dim: '#c8c6c2'
  on-secondary-fixed: '#1b1c19'
  on-secondary-fixed-variant: '#474744'
  tertiary-fixed: '#e0e5cc'
  tertiary-fixed-dim: '#c4c9b1'
  on-tertiary-fixed: '#191d0e'
  on-tertiary-fixed-variant: '#444937'
  background: '#fdf9f0'
  on-background: '#1c1c16'
  surface-variant: '#e6e2d9'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 30px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
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
  margin-mobile: 20px
  margin-desktop: 64px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

This design system is anchored in the concept of "The Digital Atelier"—a premium, quiet space that honors the tactile heritage of physical books while providing a modern, frictionless browsing experience. The brand personality is scholarly yet accessible, sophisticated, and deeply intentional.

The visual style is **Minimalist** with high-end editorial influences. It prioritizes vast white space to allow the vibrant, often intricate artwork of book covers to serve as the primary visual interest. By using a warm, paper-like background instead of a harsh pure white, the UI reduces eye strain and evokes the physical sensation of high-quality vellum or archival paper. 

Key attributes include:
- **Quiet Authority:** Premium through restraint rather than excess.
- **Curated Spacing:** Generous margins that mimic the "safe zones" of a well-designed book page.
- **Tactile Minimalism:** Subtle shadows and borders that suggest depth without breaking the flat, modern aesthetic.

## Colors

The palette is designed to be "the canvas, not the art." 

- **Primary (Charcoal):** Used for all core typography to ensure maximum legibility and a sharp, ink-on-paper feel.
- **Background (Warm Bone):** The foundational surface. It provides a softer, more premium experience than pure white and complements the organic colors found in traditional book printing.
- **Neutral (Sand/Grey):** Used for subtle borders and secondary UI elements like disabled states or dividers.
- **Accents (Muted Earth):** Sage, Terracotta, and Soft Blue are derived from the reference book covers. These should be used sparingly for specific categories, notifications, or call-to-action highlights to maintain the minimalist integrity.

Primary interaction states (buttons) should utilize the Charcoal color to maintain high contrast and a bold, authoritative presence.

## Typography

The typographic hierarchy establishes a clear dialogue between "The Story" (Serif) and "The Service" (Sans-serif).

- **Headlines:** Use high-contrast Serif settings. For hero sections and book titles, use the `display-lg` style with tighter letter spacing for a refined, editorial look.
- **Body:** Built for long-form reading. `body-lg` uses generous line-height (1.6x) and subtle tracking to ensure the digital reading experience feels as effortless as print.
- **Labels:** Small caps and increased tracking are used for meta-data (ISBN, Author Name, Category) to distinguish utility information from narrative content.

Avoid using Serif for any functional UI elements like buttons or input fields; these should remain in the clean, utilitarian Sans-serif to ensure clarity of action.

## Layout & Spacing

This design system employs a **Fixed Grid** model for desktop to maintain a controlled, gallery-like presentation. 

- **Desktop (12 columns):** 1280px max-width container. Gutters are intentionally wide (32px) to prevent the UI from feeling cluttered.
- **Mobile (4 columns):** Full-bleed with 20px side margins. 
- **Rhythm:** All spacing is based on an 8px base unit. Vertical rhythm is critical; use `stack-lg` (48px) to separate major sections to reinforce the feeling of "Luxury through Space."

Book grids should prioritize a "Comfortable" density—usually 4 items per row on desktop and 2 items on mobile—to ensure each cover art can be appreciated.

## Elevation & Depth

Visual hierarchy is achieved through a combination of **Tonal Layering** and **Ambient Shadows**.

- **Surface Levels:** The base level is the Warm Bone background. Interactive elements (cards) sit on an "Off-white" surface slightly brighter than the background.
- **Shadows:** Use extremely diffused, low-opacity shadows (e.g., `box-shadow: 0 10px 30px rgba(26, 26, 26, 0.04)`). Shadows should look like natural light hitting a thick piece of paper.
- **Borders:** Use 1px borders in a slightly darker neutral tone for input fields and secondary buttons. Avoid heavy borders; the goal is for elements to feel defined but light.
- **Hover States:** When hovering over book cards, the elevation should increase slightly with a more pronounced shadow and a subtle 2% scale-up to mimic the action of picking a book off a shelf.

## Shapes

The shape language is **Soft (Level 1)**. 

While the bookstore is high-end, pure sharp corners can feel too aggressive or "corporate." A subtle 4px (0.25rem) radius on buttons and cards provides a "finished" feel that mimics the slightly rounded corners of a book spine or cover.

- **Standard Elements:** 4px radius.
- **Large Components (Cards):** 8px (rounded-lg) for a more approachable feel.
- **Inputs:** 4px radius to maintain a structured, professional look.

## Components

### Buttons
- **Primary:** Solid Charcoal background with white text. High contrast, sharp, and authoritative.
- **Secondary:** Transparent background with a 1px Charcoal border.
- **Text Link:** Underlined Serif for an editorial "Read More" feel.

### Book Cards
- The core of the experience. No borders; use the light ambient shadow for definition. 
- Image aspect ratio should strictly follow a standard book format (approx 2:3).
- Titles are rendered in the Serif font.

### Input Fields
- Understated design. Bottom-border only or very light 1px stroke. 
- Focus state: Border color changes to Charcoal with a subtle 2px bottom weight.

### Chips/Tags
- Used for genres or topics. Pill-shaped with a 50% opacity version of the accent earth tones. 
- Text inside should use `label-md` (Inter, uppercase).

### Lists
- Clean vertical lists with generous padding (16px top/bottom). 
- Use the Sand/Neutral color for thin 1px separators.