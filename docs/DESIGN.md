---
name: Hampter Core
colors:
  surface: '#fff8f6'
  surface-dim: '#f9d1c8'
  surface-bright: '#fff8f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0ed'
  surface-container: '#ffe9e4'
  surface-container-high: '#ffe2db'
  surface-container-highest: '#ffdad2'
  on-surface: '#2b1611'
  on-surface-variant: '#524533'
  inverse-surface: '#432a25'
  inverse-on-surface: '#ffede9'
  outline: '#847560'
  outline-variant: '#d7c4ac'
  surface-tint: '#805600'
  primary: '#805600'
  on-primary: '#ffffff'
  primary-container: '#ffb000'
  on-primary-container: '#6a4700'
  inverse-primary: '#ffba43'
  secondary: '#785a0f'
  on-secondary: '#ffffff'
  secondary-container: '#fed480'
  on-secondary-container: '#795a10'
  tertiary: '#00677f'
  on-tertiary: '#ffffff'
  tertiary-container: '#00d0fe'
  on-tertiary-container: '#00556a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffddaf'
  primary-fixed-dim: '#ffba43'
  on-primary-fixed: '#281800'
  on-primary-fixed-variant: '#614000'
  secondary-fixed: '#ffdea1'
  secondary-fixed-dim: '#e9c16e'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5c4300'
  tertiary-fixed: '#b7eaff'
  tertiary-fixed-dim: '#4cd6ff'
  on-tertiary-fixed: '#001f28'
  on-tertiary-fixed-variant: '#004e60'
  background: '#fff8f6'
  on-background: '#2b1611'
  surface-variant: '#ffdad2'
typography:
  display-lg:
    fontFamily: Quicksand
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Quicksand
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Quicksand
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Quicksand
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: Quicksand
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Quicksand
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Quicksand
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  headline-lg-mobile:
    fontFamily: Quicksand
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  unit: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 40px
  container-margin: 32px
  gutter: 20px
---

## Brand & Style

The design system is built on a "Cute-Professional" hybrid aesthetic. It targets users who value productivity within a cozy, low-stress environment. The UI evokes the feeling of a well-organized burrow: safe, warm, and highly functional. 

The visual style is a blend of **Soft Minimalism** and **Tactile UI**. It utilizes high-quality whitespace, rounded geometry, and a layered "paper-on-wood" metaphor to provide focus. The emotional response is one of calm delight—professional enough for serious tasks, but friendly enough to reduce cognitive load and anxiety.

## Colors

The palette is derived from natural, warm tones associated with hamster habitats and soft fur. 

- **Primary & Secondary**: Used for call-to-actions, progress indicators, and active states. Sunflower yellow provides the "pop" for high-priority items, while fur-orange handles softer accents.
- **Background & Canvas**: The light cream (#FFF8E1) acts as the primary canvas color, reducing the harshness of pure white and providing a "paper" feel.
- **Deep Contrast**: Walnut brown (#4E342E) is reserved for structural elements like sidebars, headers, or heavy margins. This creates a "frame" effect that pushes the user's attention toward the warm, light content area in the center.
- **Semantic Accents**: Soft pink and mint green are used sparingly for destructive and constructive actions respectively, maintaining the soft-saturation theme.

## Typography

This design system uses **Quicksand** exclusively to maintain a cohesive, friendly personality across all touchpoints. 

- **Headlines**: Use Bold (700) or Semi-Bold (600) weights. The rounded terminals of Quicksand prevent large text from feeling aggressive.
- **Body**: Medium (500) weight is preferred for body-lg to ensure legibility against the cream background. Regular (400) is used for dense information.
- **Labels**: Always Semi-Bold or Bold to provide clear hierarchy even at small sizes.
- **Line Height**: Generous line heights are applied to maintain the "airy" and "uncluttered" feel of the design narrative.

## Layout & Spacing

The layout follows a **Fixed-Width Centered** approach for desktop apps to mimic a focused workspace, while transitioning to a fluid grid for mobile.

- **The "Burrow" Framework**: Content is usually housed in a central container with a max-width of 1200px. The sidebar (Walnut Brown) is fixed, providing a sturdy anchor.
- **Spacing Rhythm**: An 8px-based grid is used, but internal padding for cards and containers should lean towards "lg" (24px) or "xl" (40px) to enhance the sense of comfort and prevent crowding.
- **Mobile Adaptation**: On mobile, the walnut brown frame disappears or moves to a bottom navigation bar, and margins shrink to 16px to maximize the utility of the smaller screen.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Soft Ambient Shadows**.

- **Surfaces**: The base layer is the Cream (#FFF8E1). Elevated elements (cards, modals) use pure White (#FFFFFF) to pop forward.
- **Shadows**: Use very large blur radii (20px+) with low opacity (8-12%). The shadow color should be slightly tinted with the Walnut Brown (#4E342E) rather than pure black to keep the warmth of the palette.
- **Depth Levels**:
  - *Level 0*: Background cream.
  - *Level 1*: Interactive cards, subtle depth.
  - *Level 2*: Hover states and dropdowns.
  - *Level 3*: Modals and floating action buttons.

## Shapes

The shape language is defined by extreme roundedness, reflecting the "soft" and "friendly" brand traits.

- **Base Radius**: 1rem (16px) for standard components like input fields and small buttons.
- **Large Radius (2xl/3xl)**: 2rem to 3rem for main content containers and cards.
- **Pill Shapes**: Used for tags, chips, and primary action buttons to emphasize their interactability.
- **Icons**: Icons should always feature rounded caps and corners to match the typography. Hard angles are strictly avoided.

## Components

- **Buttons**: Primary buttons are pill-shaped, using Sunflower Yellow with Walnut Brown text for maximum contrast. Secondary buttons use a fur-orange border with no fill.
- **Cards**: Pure white backgrounds with a 32px corner radius and soft brown-tinted shadows. Internal padding is generous (24px).
- **Input Fields**: Soft cream-tinted backgrounds (#FFFDE7) with a subtle 1px border in soft orange. On focus, the border thickens and glows with the Primary Yellow.
- **Chips**: Used for categories, these are fully rounded (pill) with fur-orange backgrounds and walnut text.
- **Success/Error States**: Submit buttons transition to Mint Green (#81C784) with white text. Reset/Delete buttons use Soft Pink (#FF8A80).
- **Specialty Component - "The Pouch"**: A specific container style for grouping small tools or actions, using a slightly darker peach shade with an inset shadow to look "tucked in" to the interface.