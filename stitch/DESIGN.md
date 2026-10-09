---
name: Belgian Artisan Plumbing
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
  on-surface-variant: '#434653'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#737784'
  outline-variant: '#c3c6d5'
  surface-tint: '#2559bd'
  primary: '#00327d'
  on-primary: '#ffffff'
  primary-container: '#0047ab'
  on-primary-container: '#a5bdff'
  inverse-primary: '#b1c5ff'
  secondary: '#705d00'
  on-secondary: '#ffffff'
  secondary-container: '#fcd400'
  on-secondary-container: '#6e5c00'
  tertiary: '#283653'
  on-tertiary: '#ffffff'
  tertiary-container: '#3f4d6b'
  on-tertiary-container: '#b0bee1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#b1c5ff'
  on-primary-fixed: '#001946'
  on-primary-fixed-variant: '#00419e'
  secondary-fixed: '#ffe16d'
  secondary-fixed-dim: '#e9c400'
  on-secondary-fixed: '#221b00'
  on-secondary-fixed-variant: '#544600'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#b8c6ea'
  on-tertiary-fixed: '#0b1b36'
  on-tertiary-fixed-variant: '#384764'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '800'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '700'
    lineHeight: 24px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses high-end Belgian trade mastery: precise, reliable, punctually professional, and engineered to inspire instant trust. Designed specifically for high-conversion emergency and scheduled residential/commercial plumbing in Belgium (Flanders, Brussels, Wallonia), the visual language bridges architectural refinement with immediate, decisive action.

The emotional tone balances calm authority during household crises with transparent, institutional-grade craftsmanship. The visual execution blends **Corporate / Modern** precision with crisp tactile ergonomics: crisp micro-borders, clean atmospheric field depth, generous breathing room, and purposeful high-contrast callouts that command immediate conversion without cheapening the aesthetic.

## Colors

The palette establishes an unmistakable hierarchy of trust, calm, and actionable urgency:

- **Primary (`#0047AB` - Royal Blue):** The dominant brand foundation. Conveys clinical mastery, water purity, and European institutional dependability. Used for primary interactive triggers, key icons, active navigation tabs, and confident display anchors.
- **Secondary (`#FFD700` - Golden Yellow):** The decisive conversion accelerator. Reserved strictly for primary emergency dispatch triggers ("Dépannage 24/7", "Bel Nu Direct"), instant price quotes, and high-priority action badges. Must always pair with `#0B1B36` text for WCAG AAA compliance.
- **Dark Navy (`#0B1B36`) & Dark Slate (`#14243E`):** Structural anchors. Used for headers, high-emphasis typographic elements, dark-mode emergency bars, and deep contrasting footers.
- **Surfaces & Tints:**
  - Page Background: `#F4F8FD` (Light Blue Tinted Canvas)
  - Surface Card / Raised Containers: `#FFFFFF` (Pure White)
  - Interactive / Accent Backgrounds: `#EAF2FF` (Soft Blue Tint)
  - Structural Hairlines: `#E0E8F2` (Low-contrast slate border)
- **Muted Slate (`#64748B`):** Body subtitles, technical specifications, legal disclosures, and inactive controls. Meets strict WCAG AA contrast against `#FFFFFF` and `#F4F8FD`.

## Typography

The typographic system leverages **Plus Jakarta Sans** for headlines and interactive elements, providing geometric authority with humanist warmth. Body prose and data tables rely on **Inter** for maximum legibility under rapid scan scenarios (such as an emergency water leak).

Numerical pricing, ETA estimates, and contact numbers use tabular numerals with semi-bold weights to ensure instant visual processing on mobile viewports.

## Layout & Spacing

A strictly managed 12-column grid anchors desktop views with a max-width container of `1280px`. Breakpoints step down cleanly:
- **Desktop (≥ 1024px):** 12 columns, 24px gutters, 32px canvas margins.
- **Tablet (768px – 1023px):** 8 columns, 20px gutters, 24px canvas margins.
- **Mobile (< 768px):** 4 columns, 16px gutters, 16px canvas margins.

The spacing rhythm adheres strictly to an 8px vertical baseline (`space-xs` = 4px, `space-sm` = 8px, `space-md` = 16px, `space-lg` = 24px, `space-xl` = 40px). Emergency banners and direct-call sticky bars dock seamlessly to mobile safe-bottom areas with full lateral bleed.

## Elevation & Depth

Visual depth is achieved through layered tonal surfaces complemented by soft, diffused, navy-tinted ambient shadows. Avoid pitch-black shadows; depth must feel luminous and architectural.

- **Level 0 (Flat / Canvas):** Surface color `#F4F8FD` with no shadow.
- **Level 1 (Card Default):** `#FFFFFF` surface enclosed by a 1px border of `#E0E8F2` with shadow `0 2px 8px -2px rgba(11, 27, 54, 0.04), 0 1px 4px -1px rgba(11, 27, 54, 0.02)`.
- **Level 2 (Hover / Elevated Cards / Quick-Select):** `#FFFFFF` surface with shadow `0 12px 24px -6px rgba(0, 71, 171, 0.08), 0 4px 12px -2px rgba(11, 27, 54, 0.04)` and border color shifting to `#CBD9EB`.
- **Level 3 (Sticky CTAs & Emergency Drawers):** Shadow `0 20px 32px -8px rgba(11, 27, 54, 0.16), 0 8px 16px -4px rgba(11, 27, 54, 0.08)`.

## Shapes

The system sets a refined base corner radius of `16px` for primary cards and modular containers, balancing architectural stability with modern consumer tactile friendliness.

- **Standard Containers & Cards:** `16px` (`rounded-lg`).
- **Interactive Inputs, Dropdowns, and Selectors:** `10px` to `12px` (`rounded-md`).
- **Tags, Notification Chips, and Floating Pills:** Fully rounded `9999px` (`pill-shaped`).
- **Standard Buttons:** `12px` for authoritative tap target solidity.

## Components

### Buttons & Quick CTAs
- **Primary Conversion CTA (Emergency / Direct Action):** Solid `#FFD700` fill, `#0B1B36` bold label, `12px` radius, minimum 48px height (54px on mobile). On hover: `#F5CE00` with subtle scale transition (`transform: translateY(-1px)`).
- **Secondary Corporate CTA:** Solid `#0047AB` fill, `#FFFFFF` label. On hover: `#003B8E`.
- **Ghost / Outlined:** `#FFFFFF` background, 1.5px solid `#E0E8F2`, text `#14243E`. Hover triggers background `#EAF2FF` with border `#0047AB`.

### Trust & Status Chips
- Certified Belgian Master Plumber / VCA / Cerga badges use a pill shape (`9999px`), `#EAF2FF` background, `#0047AB` text, with a 6px pulse dot in emerald or golden yellow.

### Cards & Service Modules
- Pure white (`#FFFFFF`) containers, fixed `16px` corner radius, encased in a 1px `#E0E8F2` hairline border.
- Headers inside cards utilize `#0B1B36` Plus Jakarta Sans with clear subtext in `#64748B`. Hover states elevate subtly via Level 2 elevation.

### Emergency Contact Floating Bar (Mobile)
- Docks to the viewport bottom with `padding: 12px 16px`. Dual split layout: Direct Click-to-Call button in `#FFD700` alongside an estimated response timer badge ("Arrivée 30-45 min") in `#0B1B36` and `#FFFFFF`.

### Input Fields & Booking Forms
- Base height: 48px. Background: `#FFFFFF`. Border: 1.5px solid `#E0E8F2`.
- Focus state: Border transitions to `#0047AB` with a 3px outer glow ring of `rgba(0, 71, 171, 0.15)`. Labels sit top-aligned in Plus Jakarta Sans 14px SemiBold (`#0B1B36`).

### Checkboxes & Radio Selectors
- Sizing: 20x20px with `6px` radius for checkboxes, full circle for radios. Active state fills with `#0047AB` featuring a crisp white SVG glyph checkmark. Inactive state features `#E0E8F2` border on `#FFFFFF`.