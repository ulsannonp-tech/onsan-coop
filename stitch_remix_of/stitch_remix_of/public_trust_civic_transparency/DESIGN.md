---
name: Public Trust & Civic Transparency
colors:
  surface: '#faf8ff'
  surface-dim: '#d2d9f4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3ff'
  surface-container: '#eaedff'
  surface-container-high: '#e2e7ff'
  surface-container-highest: '#dae2fd'
  on-surface: '#131b2e'
  on-surface-variant: '#444651'
  inverse-surface: '#283044'
  inverse-on-surface: '#eef0ff'
  outline: '#757682'
  outline-variant: '#c5c5d3'
  surface-tint: '#4059aa'
  primary: '#00236f'
  on-primary: '#ffffff'
  primary-container: '#1e3a8a'
  on-primary-container: '#90a8ff'
  inverse-primary: '#b6c4ff'
  secondary: '#1d4ed8'
  on-secondary: '#ffffff'
  secondary-container: '#4069f2'
  on-secondary-container: '#fffbff'
  tertiary: '#4a1d00'
  on-tertiary: '#ffffff'
  tertiary-container: '#6c2e00'
  on-tertiary-container: '#ff8e49'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#00164e'
  on-primary-fixed-variant: '#264191'
  secondary-fixed: '#dce1ff'
  secondary-fixed-dim: '#b7c4ff'
  on-secondary-fixed: '#001551'
  on-secondary-fixed-variant: '#0039b5'
  tertiary-fixed: '#ffdbca'
  tertiary-fixed-dim: '#ffb68e'
  on-tertiary-fixed: '#331200'
  on-tertiary-fixed-variant: '#763300'
  background: '#faf8ff'
  on-background: '#131b2e'
  surface-variant: '#dae2fd'
typography:
  display-lg:
    fontFamily: Noto Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 52px
  display-lg-mobile:
    fontFamily: Noto Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 38px
  headline-lg:
    fontFamily: Noto Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Noto Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Noto Sans
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  headline-sm:
    fontFamily: Noto Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  body-lg:
    fontFamily: Noto Sans
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Noto Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Noto Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Noto Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Noto Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Noto Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
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
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system delivers an authoritative, clear, and unassailable digital presence for a public interest non-profit corporation (공익법인 / 비영리법인). The aesthetic communicates institutional integrity, strict statutory compliance, fiscal transparency, and civic service. 

Key principles:
- **Institutional Weight without Clutter:** Clear lines, deliberate structural rhythm, and structured content modules replace decorative gimmicks.
- **Radical Transparency:** Information architecture emphasizes open data disclosure, audit certifications, public notice tables, and real-time governance metrics.
- **Accessible Civic Dignity:** High legibility, dignified contrasts, and balanced negative space establish immediate authority for government regulators, donors, and the general public.
- **Design Movement:** Modern Institutional Minimalism combined with precision editorial tabular design.

## Colors

The palette is engineered to meet WCAG AAA standards on key structural interfaces, conveying institutional stability and verified audit transparency.

- **Primary (`#1E3A8A` - Deep Trust Navy):** Anchors headers, official crests, major structural actions, and dominant brand elements.
- **Secondary (`#1D4ED8` - Royal Civic Blue):** Interactive elements, active tab states, primary links, and focused input indicators.
- **Tertiary (`#B45309` - Archival Amber / Statutory Gold):** Reserved for statutory disclosure badges, fiscal audit tags, certification stamps, and regulatory notice states. Soft variant `#FEF3C7` serves as badge fills.
- **Neutral Core (`#0F172A` - Slate Ink):** Deep, legible text tone avoiding harsh pure black.
- **Surface Foundations:**
  - Base canvas: `#F8FAFC` (Slate 50)
  - Secondary containers & table striping: `#F1F5F9` (Slate 100)
  - Card & sheet interiors: `#FFFFFF` (Pure White)
  - Precision dividers: `#E2E8F0` (Slate 200) and `#CBD5E1` (Slate 300)

## Typography

The type system relies on `Noto Sans` (with system-fallback mapping to Noto Sans KR and Pretendard for Hangul script rendering). It is tuned for bilingual legal declarations, balance sheets, and administrative public notices.

- **Hangul Rhythm & Tracking:** Negative letter-spacing of `-0.02em` is applied to all Korean headlines and `-0.01em` to body copy to prevent the wide optical sprawl natural to CJK glyphs.
- **Tabular Numerals:** All financial sheets, budget disclosures, and date records must employ `font-variant-numeric: tabular-nums` to ensure exact column alignment.
- **Line Heights:** Body leading is set at a generous 1.6–1.65 ratio to maintain comfortable tracking across dense bilingual civic manifestos.

## Layout & Spacing

The architecture operates on an 8pt spatial baseline using a bounded 12-column responsive grid with a maximum content container width of 1280px.

- **Desktop (1024px+):** 12 columns, 24px gutters (`gutter`), 32px margins (`margin`). Sidebars consume 3 or 4 columns; content bodies consume 8 or 9 columns.
- **Tablet (640px - 1023px):** 8 columns, 16px gutters, 24px margins. Tabular disclosure data shifts to horizontally scrollable viewports with sticky first columns.
- **Mobile (under 640px):** 4 columns, 16px gutters (`gutter-sm`), 16px margins (`margin-sm`). Stack all multi-column statistical cards into single vertical tracks.
- **Rhythm:** Internal component paddings utilize `space-md` (16px) for compact table cells and `space-lg` (24px) for official disclosure cards and form blocks.

## Elevation & Depth

To maintain civic sobriety and regulatory authority, this design system rejects dramatized floating drop-shadows and neomorphic surfaces. Visual hierarchy is built through **tonal layering and crisp 1px structural outlines**.

- **Level 0 (Base Canvas):** `#F8FAFC` background.
- **Level 1 (Card & Content Blocks):** Solid `#FFFFFF` fill bounded by a 1px border of `#E2E8F0`. Soft ambient shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.05)`.
- **Level 2 (Hovered Cards & Interactive Disclosure Tiles):** Border transitions to `#CBD5E1` with subtle ambient elevation: `0 4px 6px -1px rgba(15, 23, 42, 0.07), 0 2px 4px -2px rgba(15, 23, 42, 0.05)`.
- **Level 3 (Modal Dialogs & Compliance Overlays):** `#FFFFFF` surface with a crisp 1px `#CBD5E1` border and structured grounding shadow: `0 20px 25px -5px rgba(15, 23, 42, 0.12), 0 8px 10px -6px rgba(15, 23, 42, 0.08)`.
- **Level 4 (Sticky Statutory Navigation & Top Bar):** Background `#FFFFFF` with 95% opacity (`rgba(255, 255, 255, 0.95)`) accompanied by `backdrop-filter: blur(8px)` and a definitive 1px border-bottom in `#E2E8F0`.

## Shapes

The design system enforces a **Soft (`1`)** shape scale (0.25rem / 4px base radius) to project legal rigor, stability, and structure. Excessive rounding is prohibited as it degrades the gravitas expected of a public interest entity.

- **Base Controls (Buttons, Inputs, Selects):** 4px (`0.25rem`).
- **Cards, Panels, & Disclosure Containers:** 6px–8px (`0.375rem` to `0.5rem`).
- **Status Tags, Compliance Badges, & Law Reference Chips:** 3px–4px (`0.1875rem` to `0.25rem`). Strictly no circular pill shapes for data tags.
- **Interactive Toggles & Avatars:** Only elements strictly demanding circular semantics may exceed this restriction.

## Components

### Buttons
- **Primary Institutional:** Background `#1E3A8A`, text `#FFFFFF`, 4px radius, 0.5px subtle inner highlight. Focus ring: 2px offset with `#1D4ED8`.
- **Secondary Civic:** Border 1px solid `#CBD5E1`, background `#FFFFFF`, text `#0F172A`. Hover: background `#F1F5F9`.
- **Administrative Lock Utility:** Low-contrast minimal button. Text `#64748B`, leading lock icon (14px), text-sm. Hover: text `#1E3A8A`, background transparent.

### Statutory Badges & Status Chips
- **Fiscal / Compliance Verified:** Background `#FEF3C7`, text `#92400E`, border 1px solid `#FDE68A`. Preceded by an official seal or check mark.
- **Public Disclosure Tag (경영공시):** Background `#EFF6FF`, text `#1E40AF`, border 1px solid `#DBEAFE`.
- **Category Chips:** Background `#F1F5F9`, text `#475569`, border 1px solid `#E2E8F0`, 3px radius.

### Disclosure Tables (공시 자료표)
- Table headers utilize `#F8FAFC` background, text `#475569`, font size `label-sm`, letter spacing `0.05em`, upper border 2px solid `#1E3A8A`, and bottom border 1px solid `#CBD5E1`.
- Rows feature 1px `#E2E8F0` dividers, hover state `#F8FAFC`, and strict vertical alignment. Number fields align right with tabular figures.

### Official Banner & Announcement Header
- High-contrast banner with `#1E3A8A` background, white heading typography, subtle watermark seal opacity (5%), and breadcrumb chain in `#93C5FD`.

### Card Grids (Business & Project Reports)
- Contained in 1px `#E2E8F0` border, white surface, 6px radius.
- Includes clear header metadata: Project ID, Year, Responsible Department, and a downloadable PDF action link at bottom right.

### Accessible Forms & Field Inputs
- Border 1px solid `#CBD5E1`, background `#FFFFFF`, height 42px, radius 4px, font size 15px.
- Focus state: border `#1D4ED8`, box-shadow `0 0 0 3px rgba(29, 78, 216, 0.15)`. Labels are explicitly paired with distinct asterisks (`#DC2626`) for mandatory regulatory filings.