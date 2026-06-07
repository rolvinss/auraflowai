---
name: Synthesized Intelligence Dashboard
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#464554'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#767586'
  outline-variant: '#c7c4d7'
  surface-tint: '#494bd6'
  primary: '#4648d4'
  on-primary: '#ffffff'
  primary-container: '#6063ee'
  on-primary-container: '#fffbff'
  inverse-primary: '#c0c1ff'
  secondary: '#565e74'
  on-secondary: '#ffffff'
  secondary-container: '#dae2fd'
  on-secondary-container: '#5c647a'
  tertiary: '#4f5f76'
  on-tertiary: '#ffffff'
  tertiary-container: '#68788f'
  on-tertiary-container: '#000510'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#dae2fd'
  secondary-fixed-dim: '#bec6e0'
  on-secondary-fixed: '#131b2e'
  on-secondary-fixed-variant: '#3f465c'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 28px
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
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  container-padding-desktop: 32px
  container-padding-mobile: 16px
  gutter: 24px
  card-gap: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
---

## Brand & Style
The design system is engineered for a high-performance B2B SaaS environment specializing in AI-driven content orchestration. The brand personality is **authoritative, precise, and technologically advanced**, aiming to evoke a sense of "quiet intelligence." 

The visual style follows a **Modern Minimalist** approach with a **Developer-Friendly** edge. It prioritizes high functional density without sacrificing clarity. We utilize a structured "Card-on-Canvas" architecture, where the background remains neutral and utilitarian, allowing vibrant primary actions and semantic status indicators to drive the user's focus. The interface relies on crisp borders and logical grouping rather than heavy shadows to define its hierarchy.

## Colors
The palette is rooted in a professional "Slate & Navy" foundation to ensure longevity and visual comfort during extended use. 

- **Primary Action (AI Violet):** `#6366F1` (Indigo 500) is reserved for core AI interactions, primary buttons, and active states. 
- **Surface & Navigation:** The deep Navy (`#0F172A`) is used for sidebar navigation and high-level headers to provide a strong structural frame.
- **Backgrounds:** We use a tiered neutral system. The main app canvas is `#F8FAFC`, while card surfaces are pure white (`#FFFFFF`) to create subtle but clear separation.
- **Semantic Feedback:** Success, error, and pending states use vibrant, high-contrast tones to ensure that status updates in the content scheduler are immediately scannable.

## Typography
This design system utilizes **Inter** for all primary UI and editorial content due to its exceptional legibility and systematic rhythm. To emphasize the "AI/Developer" nature of the product, **JetBrains Mono** is introduced for labels, status chips, and metadata.

- **Scale:** We use a tight typographic scale to maintain high information density.
- **Letter Spacing:** Headlines utilize slight negative tracking for a more "locked-in" professional look, while mono-spaced labels use increased tracking for readability at small sizes.
- **Hierarchy:** Bold weights are used sparingly for section headers; medium weights are preferred for interactive elements to maintain a clean, balanced aesthetic.

## Layout & Spacing
The layout follows a **Fixed-Fluid Hybrid** model. The sidebar remains at a fixed 260px width, while the main content area utilizes a fluid 12-column grid.

- **The 4px Rule:** All spacing and sizing must be multiples of 4px to ensure mathematical harmony.
- **Card-Based Architecture:** Data and content are encapsulated in cards. On desktop, these cards follow a gutter-based grid; on mobile, they stack vertically with 100% width.
- **Density:** The design system favors "Compact" spacing for data-heavy views (e.g., the scheduler timeline) and "Default" spacing for configuration pages.

## Elevation & Depth
In alignment with a minimalist B2B aesthetic, this design system rejects heavy shadows in favor of **Tonal Layers and Low-Contrast Outlines**.

- **Level 0 (Canvas):** `#F8FAFC` — The lowest layer.
- **Level 1 (Cards/Surface):** White background with a 1px border of `#E2E8F0`. This is the standard state for all dashboard widgets.
- **Level 2 (Hover/Active):** A very soft, diffused shadow (`0px 4px 12px rgba(15, 23, 42, 0.05)`) is applied only when a card is interactive or being dragged.
- **Modals:** Use a Backdrop Blur (12px) to dim the background, ensuring the focus remains on the action without adding heavy visual weight.

## Shapes
The shape language is **Soft and Precise**. 

We use a 0.25rem (4px) base radius for small components like checkboxes and input fields. For cards and larger containers, we scale up to `rounded-lg` (8px). This creates a UI that feels modern and approachable but retains a professional "engineered" sharpness. Buttons use a consistent 6px radius to distinguish them from standard input fields.

## Components
- **Buttons:** Primary buttons use the AI Violet background with white text. Secondary buttons use a slate outline. All buttons include a subtle 1px "inner-shine" top border to suggest a tactile feel without being skeuomorphic.
- **Input Fields:** Use a 1px border (`#CBD5E1`). On focus, the border changes to Primary Indigo with a 2px outer glow of 10% opacity.
- **Status Chips:** Utilize the JetBrains Mono font. They feature a light background tint (10% opacity) of the semantic color with high-contrast text.
- **Cards:** Pure white background, 8px corner radius, and a 1px Slate-200 border. Headers within cards should have a subtle bottom divider.
- **Scheduler Timeline:** Uses a vertical "Time-line" motif with rounded nodes. Successful posts feature a green check; failed posts feature a red "X" with a "Retry" secondary button action.
- **AI Assist Tooltip:** A specific component with a gradient border (Indigo to Violet) to signify an AI-powered suggestion or insight.