---
name: Industrial Ledger
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#44474d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#75777e'
  outline-variant: '#c5c6ce'
  surface-tint: '#4f5e7e'
  primary: '#041632'
  on-primary: '#ffffff'
  primary-container: '#1b2b48'
  on-primary-container: '#8393b5'
  inverse-primary: '#b7c7eb'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#380002'
  on-tertiary: '#ffffff'
  tertiary-container: '#5f0004'
  on-tertiary-container: '#ff594e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#b7c7eb'
  on-primary-fixed: '#091b37'
  on-primary-fixed-variant: '#374765'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffdad6'
  tertiary-fixed-dim: '#ffb4ab'
  on-tertiary-fixed: '#410002'
  on-tertiary-fixed-variant: '#93000b'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
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
    lineHeight: 24px
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
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  data-mono:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-bold:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
  container-max: 1440px
---

## Brand & Style
The design system is engineered for high-stakes financial environments within industrial logistics. It prioritizes **accuracy, reliability, and systemic efficiency**. The brand personality is authoritative yet unobtrusive, functioning as a precise instrument for accounting professionals.

The design style is **Corporate / Modern** with a focus on **Data Density**. It utilizes a systematic approach to information architecture, ensuring that complex ledger data is scannable and unambiguous. The aesthetic is clean and structured, borrowing the utilitarian rigor of industrial ERP systems while maintaining a sophisticated, modern professional interface. The goal is to evoke a sense of absolute financial control and institutional trust.

## Colors
The palette is rooted in financial clarity and logical categorization:

- **Primary (Deep Navy):** Used for structural navigation, headers, and primary actions. It establishes the "Institutional" foundation of the tool.
- **Secondary (Emerald Green):** Reserved exclusively for positive cash flow, receipts, "Cleared" statuses, and growth indicators.
- **Tertiary (Muted Crimson):** Applied to expenses, "Overdue" alerts, and negative variances.
- **Neutral (Slate):** Used for secondary text, borders, and background layering to maintain a calm, balanced workspace.

Backgrounds utilize a high-white surface (`#FFFFFF`) with subtle cool-gray offsets (`#F8FAFC`) to differentiate between the workspace and the container.

## Typography
**Inter** is utilized across all levels to ensure maximum legibility and a neutral, professional tone. 

- **Numeric Data:** For tabular data and ledger entries, use `data-mono` (Medium weight) to ensure vertical alignment of digits, facilitating quick mental math and auditing.
- **Hierarchy:** Use `label-bold` for table headers and metadata descriptors to provide a clear anchor for the eye.
- **Responsiveness:** On mobile devices, `headline-lg` should scale down to 24px to preserve vertical space for data rows.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for desktop to prevent data lines from becoming excessively long and unreadable. 

- **Grid:** A 12-column grid with a 16px gutter.
- **Density:** This design system utilizes a "Compact" spacing model. Vertical padding in tables and lists is kept to a minimum (8px - 12px) to maximize the amount of financial information visible on a single screen.
- **Alignment:** Financial values are always right-aligned in columns. Labels and descriptors are left-aligned. 
- **Reflow:** On mobile, complex tables transition into structured "Transaction Cards" that stack vertically, maintaining the primary data point (the amount) in the top-right corner of the card.

## Elevation & Depth
To maintain a professional and sturdy feel, this design system uses **Tonal Layers** and **Low-Contrast Outlines** rather than heavy shadows.

- **Surface Levels:** The base background is light gray. Primary content areas (ledgers, forms) are housed in pure white containers.
- **Outlines:** Use 1px solid borders (`#E2E8F0`) for all card and input containers. 
- **Active State:** Elements with focus or in an active state receive a subtle 2px primary-colored bottom border or a very soft, low-opacity ambient shadow (0px 4px 6px rgba(27, 43, 72, 0.05)).
- **Separation:** Use horizontal rules sparingly to separate ledger entries, opting for subtle row-striping (Zebra striping) in large datasets.

## Shapes
The shape language is **Soft (0.25rem)**. This slight rounding provides a modern touch while maintaining the "industrial" and "structured" feel of an ERP system. Sharp corners are avoided to reduce visual fatigue, but high-radius "pill" shapes are restricted strictly to status badges (e.g., 'Cleared', 'Pending') to make them stand out from the rectangular data grid.

## Components
- **Transaction Cards:** Use a white background, 1px slate border, and a 4px left-border accent colored by status (Secondary for cleared, Tertiary for expenses).
- **Status Indicators:** 
    - *Cleared:* Secondary-color text on a 10% opacity secondary-color background.
    - *Pending:* Neutral-color text on a 10% opacity neutral-color background.
- **Financial Summary Cards:** Large-format `headline-md` values. Include a small trend indicator (percentage increase/decrease) positioned below the main value.
- **Input Fields:** Squared corners (4px radius), 1px border. On focus, the border thickens to 2px in the Primary color.
- **Buttons:** 
    - *Primary:* Solid Deep Navy with white text.
    - *Secondary:* Outline (1px) in Deep Navy for administrative actions.
- **Data Grids:** Use "Sticky" headers and "Sticky" first columns (Date/ID) to ensure context is never lost during horizontal or vertical scrolling.