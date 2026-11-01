---
name: Walang Gutom Kitchen Management System
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
  on-surface-variant: '#5b403d'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#906f6c'
  outline-variant: '#e4beb9'
  surface-tint: '#bb181e'
  primary: '#8c000e'
  on-primary: '#ffffff'
  primary-container: '#b5121b'
  on-primary-container: '#ffc5bf'
  inverse-primary: '#ffb3ac'
  secondary: '#ae2f2f'
  on-secondary: '#ffffff'
  secondary-container: '#fc6863'
  on-secondary-container: '#69000b'
  tertiary: '#004e1e'
  on-tertiary: '#ffffff'
  tertiary-container: '#00692b'
  on-tertiary-container: '#6eeb88'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb3ac'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#93000f'
  secondary-fixed: '#ffdad7'
  secondary-fixed-dim: '#ffb3ae'
  on-secondary-fixed: '#410004'
  on-secondary-fixed-variant: '#8d151b'
  tertiary-fixed: '#7ffc97'
  tertiary-fixed-dim: '#62df7d'
  on-tertiary-fixed: '#002109'
  on-tertiary-fixed-variant: '#005320'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
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
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
  data-mono:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 1.5rem
  margin-mobile: 1rem
  margin-desktop: 2.5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
---

## Brand & Style

This design system establishes a high-performance, dignified, and reliable administrative framework for the Walang Gutom Kitchen Management System (WGKMS). Designed for institutional use under the Department of Social Welfare and Development, the visual aesthetic merges modern GovPH digital standards with a clean, functional enterprise architecture. 

The aesthetic is grounded, authoritative, and deeply practical—balancing civic gravitas with the agile operational requirements of nationwide food security, centralized kitchen logistics, and inventory auditing. The interface evokes trust, accountability, and seamless clarity, reducing visual fatigue for kitchen coordinators, social workers, and regional auditors operating under high-throughput conditions.

## Colors

The color system prioritizes structural hierarchy and compliance with international accessibility standards (WCAG 2.1 AA/AAA contrast ratios).

### Primary & Functional Roles
- **Primary Red (`#B5121B`)**: Used for institutional identification, critical active states, primary actions, and top-tier navigation accents.
- **Secondary Dark Red (`#850E16`)**: Applied to pressed button states, prominent header fills, and high-emphasis institutional markers.
- **Background White (`#FFFFFF`)**: The root canvas for modal dialogs, data sheets, and primary cards.
- **Secondary Background Light Gray (`#F7F7F7`)**: Used for root page wrappers, workspace sidebars, alternating table rows, and secondary layout wells.
- **Text Dark Charcoal (`#292929`)**: High-contrast, neutral dark tone for body text, primary data points, and input labels.
- **Muted Text Gray (`#737373`)**: Reserved for secondary metadata, breadcrumbs, helper hints, and table column headers.
- **Border Light Gray (`#E8E8E8`)**: Defines subtle structural boundaries, table separators, and container edges without visual noise.

### Status Palette
- **Success Green (`#16A34A`)**: Inventory dispatches complete, meal allotments verified, stock balanced.
- **Warning Amber (`#D97706`)**: Low critical ingredient thresholds, delayed dispatch schedules, pending validations.
- **Danger Red (`#DC2626`)**: Critical shortages, spoiled batch flags, validation rejections.

## Typography

The design system relies entirely on **Inter** to ensure maximum legibility across dense data tables, rapid kitchen order fulfillment lists, and administrative dashboards.

- **Tabular Figures**: Numeric data in tables, inventory counts, and timestamps must use OpenType tabular numbers (`tnum`) to keep tracking aligned vertically.
- **Hierarchy Rules**: 
  - `headline-xl` is reserved for major dashboard view titles and regional portal headers.
  - `headline-md` and `headline-sm` designate modular cards, data widgets, and sub-section blocks.
  - `body-md` serves as the primary system workhorse for descriptions, standard inputs, and transactional data rows.
  - `label-md` and `label-sm` are strictly applied to UI controls, table headers (uppercase with tracking), and status indicators.

## Layout & Spacing

The layout model is built on an enterprise 12-column responsive grid engineered for dense information density and operational efficiency.

- **Desktop (1200px and up)**: 12 columns, 32px (`gutter-lg`) column spacing, 40px (`margin-desktop`) canvas margin. Layouts prioritize multi-pane operational workspaces (e.g., permanent navigation sidebar, main ledger, and contextual side-drawer).
- **Tablet (768px – 1199px)**: 8 columns, 24px (`gutter`) column spacing, 24px (`margin`) outer padding. Side navigation collapses into a persistent top app bar with flyout panels.
- **Mobile (Below 768px)**: 4 columns, 16px (`gutter-sm`) column spacing, 16px (`margin-mobile`) outer margins. Complex data sets collapse to stacked visual cards with tap-to-expand details.
- **Rhythm**: All vertical and horizontal component spacing adheres strictly to a 4px/8px incremental base, preventing irregular vertical offsets during high-volume screen switching.

## Elevation & Depth

To preserve an official, clean, and utilitarian aesthetic, elevation relies primarily on flat surfaces, crisp low-contrast outlines (`#E8E8E8`), and minimal ambient shadows. Deep or dramatic drops are omitted to keep interfaces light and fast.

- **Level 0 (Flat Canvas)**: `#F7F7F7` root surface. No elevation or border.
- **Level 1 (Structural Cards & Modules)**: `#FFFFFF` fill with a 1px solid `#E8E8E8` stroke. Used for data tables, kitchen detail cards, and static widgets. No shadow required under normal ambient states.
- **Level 2 (Interactive / Hovered Containers)**: `#FFFFFF` fill, 1px solid `#E8E8E8` border, subtle ambient drop shadow: `0px 2px 8px rgba(0, 0, 0, 0.05)`.
- **Level 3 (Dropdowns & Popovers)**: `#FFFFFF` fill, 1px solid `#E8E8E8`, defined shadow: `0px 4px 16px rgba(0, 0, 0, 0.08)`.
- **Level 4 (Modals & Action Drawers)**: `#FFFFFF` fill, bordered, supported by a translucent institutional scrim: `background: rgba(41, 41, 41, 0.48)`, elevation shadow `0px 12px 32px rgba(0, 0, 0, 0.12)`.

## Shapes

The design system enforces a restrained **Soft (`1`)** shape language. This subtly curved geometric rhythm reinforces the disciplined, official structure of government administrative portals.

- **Core Controls (Buttons, Text Inputs, Selectors)**: 4px border radius (`0.25rem`) provides clean, crisp borders suited for compact desktop screens.
- **Cards and Panels**: 8px border radius (`0.5rem`) balances structural division with modern elegance.
- **Badges and Status Pills**: Fully rounded pill shapes (`9999px`) are allowed only for categorical indicators and operational status markers to distinguish them instantly from actionable input fields.

## Components

### Buttons
- **Primary**: Background `#B5121B`, text `#FFFFFF`, border none, 4px border radius. Hover state transitions to `#850E16`. Active state uses `#660B11`.
- **Secondary (Outline)**: Background `#FFFFFF`, text `#292929`, 1px solid border `#E8E8E8`. Hover shifts background to `#F7F7F7` with text shifting to `#B5121B`.
- **Destructive**: Background `#DC2626`, text `#FFFFFF`. Hover transitions to `#B91C1C`.
- **Sizes**: Standard desktop height is 36px (compact) and 40px (default), padding `0 16px`, typography `label-md`.

### Status Badges & Chips
- Designed for immediate comprehension in logistics and meal distribution views.
- Composed of an 8px circular indicator dot, 12px text (`label-sm`), and a subtle tinted background:
  - **Success**: Text `#16A34A`, background `#F0FDF4`, border `1px solid #BBF7D0`.
  - **Warning**: Text `#D97706`, background `#FFFBEB`, border `1px solid #FDE68A`.
  - **Critical/Danger**: Text `#DC2626`, background `#FEF2F2`, border `1px solid #FECACA`.
  - **Neutral**: Text `#737373`, background `#F7F7F7`, border `1px solid #E8E8E8`.

### Input Fields & Controls
- **Text Inputs & Selects**: 1px solid border `#E8E8E8`, background `#FFFFFF`, text `#292929`, placeholder text `#737373`, height 40px, padding `0 12px`, radius 4px.
- **Focus State**: 1px solid `#B5121B` with a subtle outline ring `0 0 0 3px rgba(181, 18, 27, 0.12)`.
- **Checkboxes & Radios**: Checked fill `#B5121B`, unchecked border `#737373`. Sized to 16x16px for desktop tables, 20x20px on mobile touch targets.

### Structured Data Cards
- Container constructed with background `#FFFFFF`, border `1px solid #E8E8E8`, radius 8px, and internal padding of 16px to 24px (`space-md` to `space-lg`).
- Header includes a dedicated title block (`headline-sm`), an action menu or status badge, and an optional bottom divider in `#E8E8E8`.

### Tables (Kitchen Inventories & Beneficiary Allocations)
- **Header**: Background `#F7F7F7`, text `#737373`, uppercase 11px font (`label-sm`), 1px solid border bottom `#E8E8E8`.
- **Row**: Height 44px (condensed) or 52px (standard), background `#FFFFFF`, hover row highlight `#F7F7F7`, cell divider 1px solid `#E8E8E8`.

### Specialized GovPH Kitchen Components
- **Ingredient Threshold Meter**: Horizontal progress bar showing live depot levels; critical levels switch automatically from `#16A34A` to `#D97706` and `#DC2626`.
- **Official Seal Banner**: Structural top bar featuring the official agency header, station identifier, and user clearance tier in high-contrast neutral styling.