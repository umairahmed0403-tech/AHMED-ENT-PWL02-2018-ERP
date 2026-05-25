---
name: Industrial Logistics Framework
colors:
  surface: '#fff8f7'
  surface-dim: '#e3d7d8'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fdf1f2'
  surface-container: '#f7ebec'
  surface-container-high: '#f1e5e6'
  surface-container-highest: '#ece0e1'
  on-surface: '#201a1b'
  on-surface-variant: '#514346'
  inverse-surface: '#352f30'
  inverse-on-surface: '#faeeef'
  outline: '#837376'
  outline-variant: '#d5c2c5'
  surface-tint: '#864e5c'
  primary: '#2d0613'
  on-primary: '#ffffff'
  primary-container: '#471a28'
  on-primary-container: '#be7e8e'
  inverse-primary: '#fab3c4'
  secondary: '#74575d'
  on-secondary: '#ffffff'
  secondary-container: '#fcd6de'
  on-secondary-container: '#785b62'
  tertiary: '#001a07'
  on-tertiary: '#ffffff'
  tertiary-container: '#033114'
  on-tertiary-container: '#6e9b75'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e0'
  primary-fixed-dim: '#fab3c4'
  on-primary-fixed: '#360c1a'
  on-primary-fixed-variant: '#6a3745'
  secondary-fixed: '#ffd9e1'
  secondary-fixed-dim: '#e2bdc5'
  on-secondary-fixed: '#2a151b'
  on-secondary-fixed-variant: '#5a4046'
  tertiary-fixed: '#beeec2'
  tertiary-fixed-dim: '#a3d2a8'
  on-tertiary-fixed: '#00210b'
  on-tertiary-fixed-variant: '#254f2f'
  background: '#fff8f7'
  on-background: '#201a1b'
  surface-variant: '#ece0e1'
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

The visual language communicates security and institutional reliability. By transitioning to a palette of muted earth tones and deep forest accents, the system provides a more sophisticated, "executive-industrial" feel. It employs a structured, grid-based approach that feels architectural and grounded. By utilizing a "data-first" philosophy, the design system minimizes decorative elements in favor of functional indicators, ensuring that customs agents and warehouse managers can process complex shipping manifests and regulatory data with minimal cognitive load.

**Key Principles:**
- **Functional Density:** Maximizing screen real estate for data tables while maintaining rhythmic white space.
- **Regulatory Authority:** Using a sophisticated, muted primary palette to evoke trust and established permanence.
- **Operational Clarity:** Using deep, high-contrast status indicators to highlight logistics states without visual fatigue.

## Colors

The palette is anchored by **Muted Rose (#a26675)**, representing the modern face of a customs-bonded institution. **Warm Taupe (#8e6f76)** serves as the secondary functional color for supporting UI elements and icons, providing a grounded, neutral backdrop that reduces eye strain during long shifts.

**Deep Forest Green (#033114)** is used as a high-visibility, authoritative accent for "Cleared," "Security Verified," or "Standard" states. 

- **Primary:** Navigation, primary actions, and branding.
- **Secondary:** Secondary actions, inactive states, and structural borders.
- **Tertiary:** High-contrast status badges and specific success indicators.
- **Neutrals:** Used for surface layering to create a clear "paper-on-desk" hierarchy against the background using stone-toned grays.

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
1. **Level 0 (Background):** Stone-tinted neutral background representing the base environment.
2. **Level 1 (Cards/Containers):** Pure white surfaces with a 1px border. This is the primary workspace for data.
3. **Level 2 (Modals/Dropdowns):** Elevated surfaces using a very soft, diffused shadow (0px 4px 12px rgba(71, 26, 40, 0.08)) to indicate temporary interaction.

**Visual Separation:**
Vertical separators (1px wide) in the Primary Rose or Taupe color are used within tables to clearly divide data categories, mimicking the look of physical cargo manifests.

## Shapes

The shape language is **Soft (0.25rem)**. This subtle rounding provides a modern touch while maintaining the serious, "boxy" feel expected of an industrial ERP system.

- **Standard Elements:** Input fields, buttons, and cards use a 4px (`rounded`) radius.
- **Data Badges:** Use a 4px radius rather than a pill shape to maintain the industrial, structured aesthetic.
- **Large Components:** Layout containers or main dashboard modules use 8px (`rounded-lg`) to provide a clear containerized look.

## Components

### Data Tables
Tables are the heart of the system. They use a zebra-stripe pattern with high-contrast headers utilizing the `primary_color_hex` (Muted Rose). Row heights are compact (40px) to maximize data visibility. Hover states on rows should use a light stone tint.

### Buttons
- **Primary:** Solid Muted Rose with white text. High-contrast and authoritative.
- **Secondary:** Outlined Taupe. Used for "Cancel" or "Export" actions.
- **Ghost:** Used for inline table actions to reduce visual noise.

### Status Badges
Badges are used to denote the progress of goods. 
- **Forest Green:** Cleared / Released / Success.
- **Rose:** Critical Hold / Discrepancy.
- **Taupe:** Registered / Pending / In Transit.
Badges use a "tinted background + dark text" approach (e.g., Forest Green background at 20% opacity with 100% opacity text).

### Form Fields
Inputs use a white background with a 1px Taupe border. On focus, the border thickens and changes to the Primary Rose. Labels are always persistent (not floating) and placed above the field in `label-md` style for clarity during rapid data entry.

### Shipping Cards
Summary cards for individual shipments or containers. They feature a bold header with the Container ID in `mono-data` and use the 4px rounded corner profile to group related logistics data.