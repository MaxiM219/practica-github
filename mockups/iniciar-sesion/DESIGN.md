---
name: Tevian Multiverse
colors:
  surface: '#181119'
  surface-dim: '#181119'
  surface-bright: '#3f3740'
  surface-container-lowest: '#120c14'
  surface-container-low: '#201922'
  surface-container: '#241d26'
  surface-container-high: '#2f2830'
  surface-container-highest: '#3a323b'
  on-surface: '#ecdfeb'
  on-surface-variant: '#d9c0cc'
  inverse-surface: '#ecdfeb'
  inverse-on-surface: '#352e37'
  outline: '#a18a96'
  outline-variant: '#54414c'
  surface-tint: '#91da44'
  primary: '#91da44'
  on-primary: '#1c3700'
  primary-container: '#66aa11'
  on-primary-container: '#1d3800'
  inverse-primary: '#3c6a00'
  secondary: '#eab2ff'
  on-secondary: '#510072'
  secondary-container: '#8806bb'
  on-secondary-container: '#ecb7ff'
  tertiary: '#ffafd4'
  on-tertiary: '#620041'
  tertiary-container: '#ff58b8'
  on-tertiary-container: '#630042'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#acf75e'
  primary-fixed-dim: '#91da44'
  on-primary-fixed: '#0e2000'
  on-primary-fixed-variant: '#2c5000'
  secondary-fixed: '#f7d8ff'
  secondary-fixed-dim: '#eab2ff'
  on-secondary-fixed: '#320047'
  on-secondary-fixed-variant: '#7400a0'
  tertiary-fixed: '#ffd8e7'
  tertiary-fixed-dim: '#ffafd4'
  on-tertiary-fixed: '#3d0027'
  on-tertiary-fixed-variant: '#8a005d'
  background: '#181119'
  on-background: '#ecdfeb'
  surface-variant: '#3a323b'
typography:
  headline-lg:
    fontFamily: Rubik
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Rubik
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.5px
  serif-italic:
    fontFamily: Noto Serif
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 440px
  stack-sm: 12px
  stack-md: 16px
  stack-lg: 24px
  section-gap: 40px
  gutter: 24px
---

## Brand & Style
Tevian Multiverse embodies a "Techno-Mystic" aesthetic, blending the precision of high-tech software with the atmospheric depth of science fiction. The brand is positioned at the intersection of gaming, web3, and digital evolution.

The design style is a hybrid of **Minimalism** and **Cyber-Atmospheric**. It utilizes a deep foundation to create a sense of infinite space, punctuated by high-vibrancy accents. Visual interest is generated through high-contrast typography, subtle neon glows (the "Neon-Glow" effect), and a strict geometric grid that feels both utilitarian and futuristic.

## Colors
The palette is built on a "Deep Space" foundation, utilizing a "Bio-Digital" Acid Lime primary and a muted, tactical neutral. The color strategy emphasizes functional vibrance against a desaturated, industrial base.

- **Primary (Acid Lime):** The lead color for critical actions, branding icons, and focus states. It provides a radioactive, synthetic contrast against the dark base.
- **Secondary (Void Purple):** A deep, cosmic purple used for supportive roles, secondary accents, and tactical highlights.
- **Tertiary (Neon Pink):** Reserved for softer multiverse-themed categorizations and tertiary interactions, providing a synthetic pop of color.
- **Neutral (Obsidian Ash):** This neutral (`#5c535d`) replaces the previous high-visibility sulfur with a more grounded, metallic tone. It serves as the primary source for outlines and structural definition, providing a sophisticated, hardware-like feel to the UI.
- **Backgrounds:** Deep dark surfaces provide the base, while the new muted neutral is leveraged for subtle, professional borders.
- **Status:** Errors use a high-contrast coral-red (`#ffb4ab`) with very low-opacity tinted backgrounds.

## Typography
The system uses a tri-font strategy to balance technical utility with narrative flair.

1.  **Rubik (Headlines):** A low-contrast sans-serif with slightly rounded corners that feels modern and approachable yet sturdy.
2.  **Inter (UI/Body):** The workhorse for all functional elements, inputs, and dense information, ensuring maximum legibility.
3.  **Noto Serif (Narrative):** Used sparingly for "flavor text" or quotes to add a sense of history and "lore" to the multiverse experience.

On mobile devices, `headline-lg` scales down to `28px/36px` to maintain comfortable reading proportions.

## Layout & Spacing
The layout employs a **Split-Column System** for wide screens:
- **Left Column:** Branding and immersive imagery, fixed or centered content.
- **Right Column:** Functional forms and interactive content, strictly centered with a maximum content width of `440px`.

Spacing follows a strict vertical rhythm based on 8px increments. Form groups are separated by 16px, while logical sections (Header to Form, Form to Divider) use 32px or 40px gaps. Horizontal padding of 24px is maintained on mobile to prevent content from touching the screen edges.

## Elevation & Depth
Depth is created through **Tonal Layering** and high-contrast outlines rather than heavy shadows.

- **Level 0 (Base):** The primary dark background.
- **Level 1 (Inputs/Containers):** Slightly lighter surfaces with a 1px border in the `neutral` Obsidian Ash color for a sharp, technical look.
- **Active State:** Focus is indicated by a 1px border of `primary` Acid Lime and a subtle, high-spread outer glow (e.g., `0 0 0 2px rgba(145, 218, 68, 0.2)`).
- **Interactive Elements:** Buttons and cards use a "lifting" micro-interaction (`translateY(-2px)`) on hover rather than changing elevation shadows.

## Shapes
The shape language is consistently "Soft-Geometric." 

Standard components (inputs, cards) use a **0.5rem (8px)** radius (based on `roundedness: 2`). Larger branding elements or iconic containers can scale up to **1rem (16px)**. Interactive "social" buttons or specific chips utilize a **Full (Pill)** radius to distinguish them from standard form inputs. Borders should remain thin (1px) to maintain a precise, technical feel.

## Components
- **Input Fields:** Dark background, 1px border using the `neutral` Obsidian Ash. Text is `body-md`. Placeholder text uses a muted tone. On focus, background shifts with a `primary` Acid Lime border.
- **Social Buttons:** Transparent background with Obsidian Ash neutral border. Pill-shaped. On hover, background fills to a darker surface tone.
- **Requirement Box:** Border-left (3px) using `error-red`. Background is a 5% opacity tint of the error color.
- **Dividers:** 1px solid lines using the `neutral` Obsidian Ash color, with centered text in `label-md` or `body-md`.
- **Icons:** Material Symbols Outlined. Use a `FILL: 1` setting for branding icons (often in `primary` Acid Lime) and `FILL: 0` for functional UI icons to create a clear visual hierarchy.