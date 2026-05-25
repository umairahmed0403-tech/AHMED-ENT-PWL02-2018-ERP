---
name: Industrial Logistics Framework
colors:
  surface: '#f6fafe'
  surface-dim: '#d6dade'
  surface-bright: '#f6fafe'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f4f8'
  surface-container: '#eaeef2'
  surface-container-high: '#e4e9ed'
  surface-container-highest: '#dfe3e7'
  on-surface: '#171c1f'
  on-surface-variant: '#44474d'
  inverse-surface: '#2c3134'
  inverse-on-surface: '#edf1f5'
  outline: '#75777e'
  outline-variant: '#c5c6ce'
  surface-tint: '#4f5e7e'
  primary: '#041632'
  on-primary: '#ffffff'
  primary-container: '#1b2b48'
  on-primary-container: '#8393b5'
  inverse-primary: '#b7c7eb'
  secondary: '#505f76'
  on-secondary: '#ffffff'
  secondary-container: '#d0e1fb'
  on-secondary-container: '#54647a'
  tertiary: '#241300'
  on-tertiary: '#ffffff'
  tertiary-container: '#3f2500'
  on-tertiary-container: '#cc8200'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e2ff'
  primary-fixed-dim: '#b7c7eb'
  on-primary-fixed: '#091b37'
  on-primary-fixed-variant: '#374765'
  secondary-fixed: '#d3e4fe'
  secondary-fixed-dim: '#b7c8e1'
  on-secondary-fixed: '#0b1c30'
  on-secondary-fixed-variant: '#38485d'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f6fafe'
  on-background: '#171c1f'
  surface-variant: '#dfe3e7'
typography:
  headline-lg:
    fontFamily: Inter
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 20px
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
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
  mono-data:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
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
  margin-desktop: 32px
  margin-mobile: 16px
  container-max: 1440px
  stack-xs: 4px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
---

## Brand & Style

This design system is engineered for high-stakes logistics and customs environments where clarity, speed, and precision are paramount. The aesthetic follows a **Corporate/Modern** movement with an **Industrial** focus, prioritizing information density without sacrificing visual ergonomics.

The visual language communicates security and institutional reliability. It employs a structured, grid-based approach that feels architectural and grounded. By utilizing a "data-first" philosophy, the design system minimizes decorative elements in favor of functional indicators, ensuring that customs agents and warehouse managers can process complex shipping manifests and regulatory data with minimal cognitive load.

**Key Principles:**
- **Functional Density:** Maximizing screen real estate for data tables while maintaining rhythmic white space.
- **Regulatory Authority:** Using a heavy-weight primary palette to evoke trust and compliance.
- **Operational Clarity:** High-contrast status indicators to highlight urgent logistics bottlenecks.

## Colors

The palette is anchored by **Deep Navy (#1B2B48)**, representing the stability of a customs-bonded institution. **Slate Gray (#64748B)** serves as the secondary functional color for supporting UI elements and icons, providing a neutral backdrop that reduces eye strain during long shifts.

**Industrial Amber (#F59E0B)** is used exclusively as a high-visibility accent for "In-Review," "Pending Customs," or "Warning" states. 

- **Primary:** Navigation, primary actions, and branding.
- **Secondary:** Secondary actions, inactive states, and structural borders.
- **Accent:** Status badges, highlights, and critical call-to-outs.
- **Neutrals:** Used for surface layering to create a clear "paper-on-desk" hierarchy against the background.

## Typography

The design system utilizes **Inter** for all standard UI elements due to its exceptional legibility in data-dense forms and high x-height. For specific tracking numbers, container IDs, and customs codes, a secondary monospaced font (**JetBrains Mono**) is introduced to prevent character confusion (e.g., distinguishing '0' from 'O').

**Hierarchy Rules:**
- **Headlines:** Use Semi-Bold weight with slight negative letter-spacing for a compact, professional look.
- **Body:** The standard size is 14px to allow for high information density while remaining accessible.
- **Labels:** Small, uppercase labels are used for table headers and section descriptors to create a clear "form-like" structure.
- **Mobile:** Scale headlines down by 15% on mobile devices, keeping body text at 14px for tap-target integrity.

## Layout & Spacing

This design system uses a **Fluid Grid** model within a maximum container width of 1440px. The layout is based on a 4px baseline grid to ensure mathematical consistency across all components.

**Layout Model:**
- **Desktop:** 12-column grid with 16px gutters. Sidebars are fixed at 280px to maximize the central data workspace.
- **Tablet:** 8-column grid. Sidebars collapse into a rail or hamburger menu.
- **Mobile:** 4-column grid. All data tables transition into "card stacks" or horizontally scrollable containers with pinned ID columns.

**Spacing Rhythm:**
Tight vertical spacing (`stack-sm`) is used between related form fields to maintain the "one-view" dashboard feel. Larger gaps (`stack-lg`) are reserved for separating major logical sections like "Consignee Information" from "Shipping Line Details."

## Elevation & Depth

To maintain a professional and efficient appearance, the design system avoids heavy shadows and skeuomorphism. Instead, it utilizes **Tonal Layers** and **Low-Contrast Outlines** to define hierarchy.

**Layering Logic:**
1. **Level 0 (Background):** Slate-tinted neutral (`#F8FAFC`) representing the warehouse floor/base.
2. **Level 1 (Cards/Containers):** Pure white surfaces with a 1px border in `#E2E8F0`. This is the primary workspace for data.
3. **Level 2 (Modals/Dropdowns):** Elevated surfaces using a very soft, diffused shadow (0px 4px 12px rgba(27, 43, 72, 0.08)) to indicate temporary interaction.

**Visual Separation:**
Vertical separators (1px wide) in the primary Navy or Slate color are used within tables to clearly divide data categories, mimicking the look of physical cargo manifests.

## Shapes

The shape language is **Soft (0.25rem)**. This subtle rounding provides a modern touch while maintaining the serious, "boxy" feel expected of an industrial ERP system.

- **Standard Elements:** Input fields, buttons, and cards use a 4px (`rounded`) radius.
- **Data Badges:** Use a 4px radius rather than a pill shape to maintain the industrial, structured aesthetic.
- **Large Components:** Layout containers or main dashboard modules use 8px (`rounded-lg`) to provide a clear containerized look.

## Components

### Data Tables
Tables are the heart of the system. They use a zebra-stripe pattern with high-contrast headers (`primary_color_hex`). Row heights are compact (40px) to maximize data visibility. Hover states on rows should use a light slate tint.

### Buttons
- **Primary:** Solid Navy with white text. High-contrast and authoritative.
- **Secondary:** Outlined Navy or Slate. Used for "Cancel" or "Export" actions.
- **Ghost:** Used for inline table actions to reduce visual noise.

### Status Badges
Badges are used to denote the progress of goods. 
- **Amber:** Pending Customs / Inspection.
- **Navy:** In Transit / Registered.
- **Green:** Cleared / Released.
- **Red:** Discrepancy / Hold.
Badges use a "tinted background + dark text" approach (e.g., Amber background at 20% opacity with 100% opacity Amber text).

### Form Fields
Inputs use a white background with a 1px Slate border. On focus, the border thickens and changes to Navy. Labels are always persistent (not floating) and placed above the field in `label-md` style for clarity during rapid data entry.

### Shipping Cards
Summary cards for individual shipments or containers. They feature a bold header with the Container ID in `mono-data` and use the 4px rounded corner profile to group related logistics data.