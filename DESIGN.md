---
name: Obsidian Terminal
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353942'
  surface-container-lowest: '#0a0e16'
  surface-container-low: '#181c24'
  surface-container: '#1c2028'
  surface-container-high: '#262a33'
  surface-container-highest: '#31353e'
  on-surface: '#dfe2ee'
  on-surface-variant: '#bbcabf'
  inverse-surface: '#dfe2ee'
  inverse-on-surface: '#2c3039'
  outline: '#86948a'
  outline-variant: '#3c4a42'
  surface-tint: '#4edea3'
  primary: '#4edea3'
  on-primary: '#003824'
  primary-container: '#10b981'
  on-primary-container: '#00422b'
  inverse-primary: '#006c49'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#7bd0ff'
  on-tertiary: '#00354a'
  tertiary-container: '#19aee8'
  on-tertiary-container: '#003e55'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#6ffbbe'
  primary-fixed-dim: '#4edea3'
  on-primary-fixed: '#002113'
  on-primary-fixed-variant: '#005236'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#c4e7ff'
  tertiary-fixed-dim: '#7bd0ff'
  on-tertiary-fixed: '#001e2c'
  on-tertiary-fixed-variant: '#004c69'
  background: '#0f131c'
  on-background: '#dfe2ee'
  surface-variant: '#31353e'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  code-lg:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 20px
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 16px
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
  metric-val:
    fontFamily: JetBrains Mono
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.04em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 0.75rem
  gutter-sm: 0.5rem
  margin: 1rem
  margin-compact: 0.75rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
  space-2xl: 2rem
---

## Brand & Style

This design system crafts an elite, high-precision engineering portfolio optimized strictly for high-density mobile viewports. The aesthetic merges technical minimalism with an architectural command-line ethos, using controlled cybernetic luminosity against ultra-deep black substrates.

- **Brand Personality**: High-caliber, precise, calculated, uncompromising. It signals mastery of modern systems engineering, infrastructure, and full-stack architecture.
- **Target Audience**: Technical recruiters, engineering directors, founders, and peer developers evaluating engineering depth and taste.
- **Emotional Response**: Immediate respect for technical rigor, clarity, and visual economy; feels like operating inside an elite developer utility rather than an amateur resume.
- **Visual Execution**: Sleek terminal-minimalism. Monoline technical borders, deep obsidian planes, subtle translucent blur surfaces, and focused phosphor-glow accents (electric emerald and hyper-cyan) that act strictly as functional indicators rather than decorative noise.

## Colors

The palette relies on a pitch-black canvas with layered slate tones and high-energy luminescent accents.

- **Substrates & Surfaces**:
  - `Canvas / Root`: `#0B0F17` (Obsidian void)
  - `Surface Container Low`: `#111827` (Card layers, terminal bodies)
  - `Surface Container Mid`: `#1E293B` (Interactive states, nested code blocks)
  - `Surface Container High`: `#334155` (Hover states, badge backings)
- **Functional Accents**:
  - `Primary / Emerald`: `#10B981` (Production health, online states, major CTAs, git commit high-activity)
  - `Secondary / Cyan`: `#06B6D4` (Active navigation states, repo metadata, branch tags)
  - `Tertiary / Sky`: `#38BDF8` (Syntax highlighting tokens, diff metrics, external links)
- **Text & Contrast Tokens**:
  - `Text High-Contrast`: `#F8FAFC` (Terminal output, headings, metrics)
  - `Text Medium-Contrast`: `#94A3B8` (Body copy, commit descriptions, path labels)
  - `Text Muted`: `#475569` (Line numbers, inactive git nodes, metadata keys)
- **Borders & Rules**:
  - `Border Subtle`: `rgba(255, 255, 255, 0.08)` (Structural cards)
  - `Border Accent`: `rgba(16, 185, 129, 0.3)` (Active interactive elements)

## Typography

The typographic hierarchy implements an asymmetric dual-engine system:

- **Primary Structure (Inter)**: Handles conversational interfaces, human-readable intros, project titles, and long-form impact descriptions. Tightly tracked at larger sizes for density and punch.
- **Technical Engine (JetBrains Mono)**: Elevates system metrics, branch details, inline CLI operations, badge labels, and code snippets.
- **Mobile Readability Rules**:
  - Maximum headline size on mobile viewport capped at `32px` to prevent awkward word splits on long engineering jargon.
  - All monospaced tags and metrics must render with tabular figures (`font-variant-numeric: tabular-nums`) to maintain alignment across animated commit counters and statistics.

## Layout & Spacing

A compact, high-density fluid mobile layout prioritizing immediate thumb access, vertical momentum, and minimal canvas waste.

- **Canvas Frame**: 1-column fluid stacking between `360px` and `430px` mobile screen widths. Outer screen padding fixed strictly to `16px` (`margin`).
- **Rhythm & Grid**: 
  - Standard spacing utilizes a 4px/8px incremental cadence.
  - Structural project cards use `space-lg` (16px) internal padding.
  - Compact tech badges and terminal pill elements adopt `space-xs` (4px) vertical and `space-sm` (8px) horizontal gaps.
- **Section Dividers**: Separated by `space-xl` (24px) vertical margins with an optional hair-line divider rule (`border-t border-white/5`).

## Elevation & Depth

Visual hierarchy rejects muddy, heavy drop-shadows in favor of razor-sharp surface contrast and faint luminescent ambient halos.

- **Tonal Planes**:
  - Base level: `#0B0F17` (viewport base).
  - Cards & Blocks: `#111827` overlaid with a continuous 1px perimeter border of `rgba(255, 255, 255, 0.08)`.
  - Floating Elements (Bottom Tab Bar, Dialogs): Frosted acrylic (`rgba(17, 24, 39, 0.8)`) backed by a high-intensity blur (`backdrop-blur-md`) and top border hairline (`rgba(255, 255, 255, 0.12)`).
- **Phosphor Accents & Glow**:
  - Active status indicators (e.g., "Available for Hire" or "Build Passing") use an ambient radial glow: `box-shadow: 0 0 12px rgba(16, 185, 129, 0.35)`.
  - Critical buttons feature a sharp edge glow: `box-shadow: 0 0 16px -4px rgba(6, 182, 212, 0.4)`.

## Shapes

The interface embraces a disciplined "Soft" technical geometry (Level 1) that feels engineered and structural:

- **Micro Components (Badges, Tags, Buttons)**: Formed with `0.25rem` (4px) corner radii, preserving a tight, chip-like chassis.
- **Cards & Terminal Surfaces**: Styled with `rounded-lg` (8px) corner radii.
- **Circular Indicators**: Status beacons and avatar enclosures remain strict circular elements (`rounded-full`).
- **Never Pill-Shaped**: Broad surfaces and standard action triggers never cross into organic circular pills; edges must retain architectural crispness.

## Components

### Buttons & Action Triggers
- **Primary CTA**: Emerald background (`#10B981`), pitch black text (`#0B0F17`), `font-weight: 600`, 4px radius, padded `12px 16px`. Active state triggers cyan focus hairline.
- **Secondary / Repo Link**: Surface `#111827`, border `1px solid rgba(255,255,255,0.1)`, cyan text (`#06B6D4`), monospaced label with an external link arrow (`->`).
- **Icon Actions**: 40x40px square hit area, centered SVG, subtle border, `#1E293B` background.

### Tech Stack Badges
- Container: Monospace `label-mono`, height 24px, padding `0 8px`, border `1px solid rgba(255, 255, 255, 0.06)`, background `rgba(30, 41, 59, 0.5)`.
- Left-side indicator: 5px solid color dot designating runtime or stack category (Emerald = Backend/Systems, Cyan = Frontend, Amber = Cloud/DevOps).

### Git Contribution & Activity Grid
- Mobile-optimized horizontal-scrolling SVG heat grid.
- Cells: 10x10px rounded squares with 2px gaps.
- Levels: Level 0 (`#1E293B`), Level 1 (`#064E3B`), Level 2 (`#047857`), Level 3 (`#10B981`), Level 4 (`#34D399` with faint glow).
- Header includes commit metrics (`metric-val`) and branch switch trigger in `code-md`.

### Project Cards
- Enclosure: `#111827` surface, 8px radius, `1px solid rgba(255,255,255,0.08)`.
- Header: Directory path format (`~/projects/decentralized-cache`) in `label-mono` muted text.
- Title: `headline-sm` in pure white with live production status dot.
- Body: 2-line condensed summary in `body-sm`.
- Footer: Horizontal scrollable badge array, paired with "Live Demo" and "GitHub" tap targets.

### Code Snippet Blocks
- Darkened shell (`#070A0F`) embedded directly into parent cards.
- Mac/Terminal title bar with simulated window dots (`#EF4444`, `#F59E0B`, `#10B981`) and file name label (`architecture.rs`).
- Line numbers in muted slate (`#475569`); code text in `code-md` using high-contrast syntax highlighting.
- Integrated one-tap "Copy" button in top-right corner.

### Metric Counters
- Minimal stat module: Value displayed in `metric-val` (`#10B981`), description below in uppercase `label-mono` (`#94A3B8`).

### Mobile Tab Bar Navigation
- Fixed to bottom viewport, thumb-safe zone (56px base height + safe area inset).
- Frosted black slate backing (`rgba(11, 15, 23, 0.85)` + blur).
- Top border: `1px solid rgba(255, 255, 255, 0.08)`.
- 4 primary tabs: `[// root]`, `[// projects]`, `[// stack]`, `[// contact]`.
- Active state: `#06B6D4` text color accompanied by a top 2px illuminated cyan pip.