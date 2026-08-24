---
name: Technical Precision Light
colors:
  surface: '#f8fafb'
  surface-dim: '#d8dadb'
  surface-bright: '#f8fafb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f5'
  surface-container: '#eceeef'
  surface-container-high: '#e6e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#404750'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#eff1f2'
  outline: '#707881'
  outline-variant: '#c0c7d2'
  surface-tint: '#00639c'
  primary: '#00598e'
  on-primary: '#ffffff'
  primary-container: '#0072b4'
  on-primary-container: '#e8f1ff'
  inverse-primary: '#98cbff'
  secondary: '#536600'
  on-secondary: '#ffffff'
  secondary-container: '#d2ea7b'
  on-secondary-container: '#576a00'
  tertiary: '#844400'
  on-tertiary: '#ffffff'
  tertiary-container: '#a75904'
  on-tertiary-container: '#ffede3'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cfe5ff'
  primary-fixed-dim: '#98cbff'
  on-primary-fixed: '#001d33'
  on-primary-fixed-variant: '#004a77'
  secondary-fixed: '#d5ed7d'
  secondary-fixed-dim: '#b9d164'
  on-secondary-fixed: '#171e00'
  on-secondary-fixed-variant: '#3e4c00'
  tertiary-fixed: '#ffdcc4'
  tertiary-fixed-dim: '#ffb77f'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6f3800'
  background: '#f8fafb'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
  surface-panel: '#FFFFFF'
  border-quiet: '#E3E8EF'
  text-main: '#101418'
  text-muted: '#64748B'
  active-indicator: '#D8EAF6'
typography:
  display-lg:
    fontFamily: beVietnamPro
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: beVietnamPro
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: beVietnamPro
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: beVietnamPro
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  technical-label:
    fontFamily: jetbrainsMono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
  code-block:
    fontFamily: jetbrainsMono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 32px
  container-max: 1440px
---

## Brand & Style

This design system is a high-performance **Corporate / Modern** framework tailored for B2B SaaS environments. It prioritizes clarity, systematic organization, and professional reliability. By shifting to a light-themed aesthetic, the system maximizes readability for complex data sets and administrative workflows.

The visual narrative is "Organized Intelligence"—a clean, airy interface that reduces cognitive load through generous whitespace and a disciplined color application. It avoids the heaviness of traditional enterprise software, favoring a crisp, developer-friendly look that remains approachable for executive stakeholders. The emotional response should be one of control, efficiency, and transparency.

## Colors

The palette is anchored by **Integrity Blue** (#0072B4) for primary actions and semantic indicators of progress. **June Bud** (#C5DD6F) is used as a functional accent for success states and positive data trends, providing a fresh contrast to the professional blue.

The background hierarchy is critical for spatial orientation:
- **Primary Canvas:** A soft grey-white (#F8FAFB) serves as the main application background.
- **Surface Panels:** Sidebars, navigation headers, and content cards use pure white (#FFFFFF) to pop against the canvas.
- **Borders:** Structural definition is achieved through 1px strokes of #E3E8EF, replacing heavy shadows for a cleaner, flatter aesthetic.
- **Active States:** Subtle tints like #D8EAF6 are used for background highlights in navigation or selected list items.

## Typography

The typography system uses **Be Vietnam Pro** for headlines to provide a friendly yet modern geometric feel. **Inter** is the primary typeface for UI elements and body text, ensuring maximum legibility at small sizes and high-density data views. 

**JetBrains Mono** is reserved for technical identifiers, status codes, and telemetry data, maintaining the system's engineering DNA. 

High contrast is maintained by using a near-black (#101418) for primary headings and a slate-grey (#64748B) for secondary body text to establish a clear information hierarchy.

## Layout & Spacing

The design system utilizes a **Fluid Grid** for internal dashboard content and a **Fixed Sidebar** for global navigation. 

- **Grid:** 12-column system on desktop with 24px gutters.
- **Rhythm:** A 4px baseline grid ensures vertical consistency across all components.
- **Density:** High-density components (data tables, sidebars) use 8px - 12px padding, while container groups and layout sections use 24px - 32px to provide visual breathing room.
- **Adaptivity:** On mobile, margins shrink to 16px and the grid collapses to a single column, with the sidebar transitioning to a hidden drawer menu.

## Elevation & Depth

Hierarchy is established primarily through **Tonal Layers** and **Low-Contrast Outlines**. 

- **Level 0 (Canvas):** #F8FAFB background.
- **Level 1 (Panels/Cards):** #FFFFFF surfaces with a 1px #E3E8EF border.
- **Level 2 (Interactive Elements):** Dropdowns and popovers use a very soft ambient shadow (0px 4px 12px rgba(0,0,0,0.05)) to separate from the Level 1 surface.

Borders are the primary tool for separation. Avoid using heavy shadows or blurs. The goal is a flat, architectural feel where depth is implied by structural containment.

## Shapes

The shape language is balanced and professional. 
- **Standard UI Elements:** (Buttons, Inputs, Cards) use 0.5rem (8px) roundedness to soften the technical nature of the interface.
- **Status Pills:** Use a full pill-shape (9999px) to distinguish status indicators from clickable buttons.
- **Selection States:** Navigation active indicators use a 0.25rem (4px) radius on one side (bar style) or fully rounded corners for block highlights.

## Components

### Buttons
Primary buttons are solid **Integrity Blue** with white text. Ghost buttons use a 1px border of #E3E8EF with primary blue text. Roundedness is strictly 8px.

### Cards
Cards are pure white (#FFFFFF) with a 1px #E3E8EF border. Headers within cards should have a subtle bottom border to separate titles from content.

### Navigation Sidebar
The sidebar uses a white background with a light grey border on the right. Active items use the **Active Indicator** color (#D8EAF6) for the background and a thick 4px vertical bar of **Integrity Blue** on the left edge.

### Status Chips
Success states use **June Bud** with dark green text. Information states use light blue backgrounds with Integrity Blue text. Backgrounds should be at 15-20% opacity of the main color to ensure text remains legible.

### Form Inputs
Inputs use a white background with a 1px #E3E8EF border. On focus, the border shifts to Integrity Blue with a subtle 2px glow.

### Data Tables
Tables use high-density rows (32px-40px height) with #F8FAFB zebra-striping or simple horizontal separators in #E3E8EF. Column headers use `body-sm` in all-caps or bold weights for clarity.