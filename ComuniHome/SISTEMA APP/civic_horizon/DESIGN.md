---
name: Civic Horizon
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
  on-surface-variant: '#444651'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#006591'
  on-secondary: '#ffffff'
  secondary-container: '#39b8fd'
  on-secondary-container: '#004666'
  tertiary: '#003120'
  on-tertiary: '#ffffff'
  tertiary-container: '#004a32'
  on-tertiary-container: '#4ac08f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#c9e6ff'
  secondary-fixed-dim: '#89ceff'
  on-secondary-fixed: '#001e2f'
  on-secondary-fixed-variant: '#004c6e'
  tertiary-fixed: '#85f8c4'
  tertiary-fixed-dim: '#68dba9'
  on-tertiary-fixed: '#002114'
  on-tertiary-fixed-variant: '#005137'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.005em
  title-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: 0em
  title-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
  title-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style
The design system establishes a balance between administrative precision and residential warmth. Built for property managers, administrative boards, and residents, the visual tone conveys institutional reliability, financial clarity, and civic order without feeling cold or bureaucratic. 

The aesthetic is **Modern Corporate with Tactile Grounding**:
- **Clarity and Order:** Layouts prioritize scannability, structural containment, and immediate legibility of critical metrics (e.g., fees, reserve funds, assembly voting, incident tickets).
- **Transparency & Trust:** Flat, crisp surfaces paired with deliberate, high-contrast semantic indicators eliminate ambiguity in financial and maintenance statuses.
- **Gestalt Principles:** Deep emphasis on closure and common region; residential dashboards utilize enclosed cards and clear grouping to separate community alerts, amenity bookings, and accounting ledgers.
- **Human-Centric Approachability:** Clean geometric typography and balanced white space make dense municipal and financial data accessible to all age demographics within a building community.

## Colors
The palette leverages deep maritime blues anchored by functional neutrals and high-contrast semantic indicators to establish trust, financial precision, and rapid spatial orientation.

- **Primary (`#1E3A8A`):** Corporate indigo. Anchors primary navigation, structural headers, high-importance actions, and master identity elements.
- **Secondary (`#0EA5E9`):** Cerulean sky. Utilized for secondary calls to action, focus rings, interactive chart series, and active state highlights.
- **Tertiary / Success (`#059669`):** Emerald green. Dedicated to positive operational milestones: approved budgets, paid maintenance fees, confirmed facility reservations, and active voting quorums. Pair with `#D1FAE5` for surface backgrounds.
- **Neutral (`#64748B`):** Balanced slate. Drives text hierarchy, inactive borders (`#E2E8F0`), and clean non-distracting canvases (`#F8FAFC` base canvas; `#FFFFFF` surface elevation).

### Semantic & Status Application
- **Pending / In Review:** Text/Icon `#D97706` over Background `#FEF3C7` (Ratio > 4.5:1).
- **In Progress:** Text/Icon `#2563EB` over Background `#DBEAFE`.
- **Urgent / Incident Alert:** Text/Icon `#DC2626` over Background `#FEE2E2`.
- **Text Primary:** `#0F172A` (Slate 900) on all light backgrounds for WCAG AAA conformance.

## Typography
The system employs a dual-typeface strategy engineered for scannability and structural authority:

- **Display & Section Headings (`Plus Jakarta Sans`):** Selected for its balanced geometric structure, subtle friendly apertures, and contemporary polish. It establishes an approachable atmosphere for resident-facing views while remaining organized and distinct in managerial dashboards.
- **Interface, Data & Body Copy (`Inter`):** Selected for industry-standard typographic performance, high x-height, and neutral character geometry. Essential for numerical scanning in financial statements, balance sheets, unit listings, and tabular documentation.
- **Tabular Numerals:** All financial, metric, and date displays must use `font-variant-numeric: tabular-nums` to maintain vertical alignment across balance tables and payment histories.

## Layout & Spacing
The layout follows a responsive 12-column fluid grid system anchored by strict common-region groupings.

### Form Factors & Adaptation
- **Desktop (1024px+):** 12 columns, 24px (`1.5rem`) gutters, 32px (`2rem`) outer margin. Maximum content bounding container of 1440px. Side navigation remains persistent at 280px fixed width.
- **Tablet (768px - 1023px):** 8 columns, 20px gutters, 24px outer margin. Side navigation collapses into an off-canvas drawer or a compact 72px icon rail. Complex data tables degrade to stacked metric cards.
- **Mobile (320px - 767px):** 4 columns, 16px (`1rem`) gutters, 16px (`1rem`) canvas margins. Navigation transforms into a fixed bottom navigation bar with a distinct center action for incident reports or quick payments.

### Spacing Cadence
Component internal layouts follow a strict 8pt rhythm using the defined tokens:
- **`space-xs` (4px):** Form micro-spacing (between label text and required indicator), icon-to-label gaps in badges.
- **`space-sm` (8px):** Internal element spacing inside list rows, chip gaps, and input-to-helptext spacing.
- **`space-md` (16px):** Standard card padding on mobile, spacing between related form fields, header-to-tab bar gaps.
- **`space-lg` (24px):** Standard card padding on desktop, spacing between disparate component groups.
- **`space-xl` (32px):** Macro section separation, modal dialog padding, major dashboard quadrant gaps.

## Elevation & Depth
Depth conveys physical hierarchy and transactional security through low-contrast structural borders combined with ambient, diffused light.

### Elevation Hierarchy
- **Level 0 (Canvas Base):** Plain `#F8FAFC`. Zero elevation, zero outline. Used for the application background shell.
- **Level 1 (Card & Module Resting):** Surface `#FFFFFF`, bounded by a 1px solid border in `#E2E8F0`, accompanied by a subtle ambient shadow: `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.05), 0 1px 2px -1px rgba(15, 23, 42, 0.03)`.
- **Level 2 (Interactive Hover & Flyout Panels):** Surface `#FFFFFF`, border `#CBD5E1`, with enhanced elevation: `box-shadow: 0 4px 6px -1px rgba(15, 23, 42, 0.07), 0 2px 4px -2px rgba(15, 23, 42, 0.05)`.
- **Level 3 (Modals, Overlays & Confirmations):** Floating `#FFFFFF` surface with a crisp `#E2E8F0` edge, cast above a 40% opacity Slate backdrop blur (`backdrop-filter: blur(4px); background-color: rgba(15, 23, 42, 0.45)`). Shadow: `box-shadow: 0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.06)`.

Avoid high-contrast drop shadows or hard, retro borders. All shadows must be tinted with neutral Slate (`rgba(15, 23, 42, ...)`) rather than pure black to preserve atmospheric clarity.

## Shapes
The shape language uses moderate roundedness (`0.5rem` / `8px` baseline) to maintain structural order while feeling welcoming for residents.

- **Standard Elements (Buttons, Inputs, Table Cells, Badges):** `rounded-md` (`0.5rem` / `8px`). Keeps controls ergonomic and recognizable without appearing playful.
- **Card Containers & Modules:** `rounded-lg` (`1rem` / `16px`). Provides clear Gestalt containment for invoices, service orders, and amenities cards.
- **Modals & Bottom Sheets:** `rounded-xl` (`1.5rem` / `24px`) on desktop modals; bottom sheets on mobile receive top-left and top-right radii of `1.5rem` with a flat bottom.
- **Status Pills & Avatar Elements:** Fully rounded / pill (`9999px`) to immediately distinguish informational status markers from actionable rectangular buttons.

## Components

### 1. Buttons
- **Primary:** Background `#1E3A8A`, text `#FFFFFF`, radius `0.5rem`, height `40px` (desktop) / `48px` (touch). Hover state deepens to `#172554`. Focus visible triggers a `2px` offset outline in `#0EA5E9`.
- **Secondary:** Background `#FFFFFF`, 1px solid border `#CBD5E1`, text `#0F172A`. Hover transitions to `#F1F5F9`.
- **Tertiary / Destructive:** For irreversible actions (e.g., rejecting expense claims, issuing eviction warnings), background `#DC2626`, text `#FFFFFF`, hover `#B91C1C`.

### 2. Status Chips & Badges
- Strict pill architecture (`border-radius: 9999px`) with 1px calibrated tone-on-tone border.
- **Pending:** `#D97706` text, `#FEF3C7` background, `#FDE68A` border.
- **In Process:** `#2563EB` text, `#DBEAFE` background, `#BFDBFE` border.
- **Approved / Paid:** `#059669` text, `#D1FAE5` background, `#A7F3D0` border.
- **Urgent:** `#DC2626` text, `#FEE2E2` background, `#FECACA` border. Includes a 6px solid circular pulse indicator to aid quick scannability.

### 3. Cards & Gestalt Containers
- All cards utilize `#FFFFFF` resting on `#F8FAFC`.
- Border is locked to `1px solid #E2E8F0` with `1rem` corner rounding.
- Internal layout must respect a clear separation: Title area (with contextual status badge top-right), body metrics, and a distinguished footer surface (`#F8FAFC` background, bordered top edge) for secondary actions or audit timestamps.

### 4. Input Fields & Form Controls
- **Text Inputs:** Height `42px`, background `#FFFFFF`, border `1px solid #CBD5E1`, padding `0 12px`. Labels are always visible top-aligned (`title-sm`, `#334155`).
- **Focus State:** 2px focus ring `#0EA5E9` with 0px outline offset.
- **Error State:** Border `#DC2626`, accompanied by an inline error icon and descriptive message in `#DC2626` (`body-sm`). Never rely solely on color; include descriptive text.

### 5. Selection Controls (Checkboxes & Radios)
- Fixed at `18px × 18px`. Unchecked state uses a 1.5px border in `#94A3B8`.
- Checked state uses `#1E3A8A` fill with a white checkmark or center pip. Target touch hit-area is padded to `40px × 40px` for mobile accessibility.

### 6. Destructive & Financial Confirmation Modals
- Strictly centered dialog layout. Header features a 48px circle badge containing the status icon (e.g., amber warning triangle for dues alterations, red shield for security access revocation).
- Action buttons are side-by-side: primary confirm action right-aligned; full-width cancel button left-aligned to prevent accidental taps (Nielsen Heuristic: Error Prevention).

### 7. Unit / Resident Data Tables
- Header cells: `#F8FAFC` background, text `#475569`, uppercase `label-sm`, letter spacing `0.05em`.
- Alternating row zebra banding is omitted in favor of thin `1px solid #F1F5F9` dividers and an active hover state of `#F8FAFC` across the entire row to preserve scan lines across large apartment lists.