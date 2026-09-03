---
name: Satirical Telemetry HUD
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353943'
  surface-container-lowest: '#0a0e17'
  surface-container-low: '#181b25'
  surface-container: '#1c1f29'
  surface-container-high: '#262a34'
  surface-container-highest: '#31353f'
  on-surface: '#dfe2ef'
  on-surface-variant: '#cbc3d7'
  inverse-surface: '#dfe2ef'
  inverse-on-surface: '#2c303a'
  outline: '#958ea0'
  outline-variant: '#494454'
  surface-tint: '#d0bcff'
  primary: '#d0bcff'
  on-primary: '#3c0091'
  primary-container: '#a078ff'
  on-primary-container: '#340080'
  inverse-primary: '#6d3bd7'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#2fd9f4'
  on-tertiary: '#00363e'
  tertiary-container: '#009fb4'
  on-tertiary-container: '#002f36'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#d0bcff'
  on-primary-fixed: '#23005c'
  on-primary-fixed-variant: '#5516be'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#a2eeff'
  tertiary-fixed-dim: '#2fd9f4'
  on-tertiary-fixed: '#001f25'
  on-tertiary-fixed-variant: '#004e5a'
  background: '#0f131c'
  on-background: '#dfe2ef'
  surface-variant: '#31353f'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 24px
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  telemetry-metric:
    fontFamily: JetBrains Mono
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.04em
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.12em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  space-xxs: 0.125rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-base: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  gutter-mobile: 0.75rem
  gutter-desktop: 1.25rem
  canvas-sidebar-w: 18rem
  telemetry-rail-w: 4.5rem
---

## Brand & Style

This design system establishes an atmospheric, hyper-focused "surveillance-grade" productivity environment balanced with biting satire. It visualizes the irony of quantified self-optimization, algorithmic micro-management, and modern burnout culture through the lens of a sleek, high-end mission control dashboard. 

The aesthetic fuses cyber-minimalism, tactical terminal telemetry, and high-contrast dark visual structures. The interface rejects sterile corporate monotony in favor of razor-sharp data density, glowing neon precision, and atmospheric depth. Subtle edge glows and cold slate tones project absolute technological authority, while playful diagnostics, hyperbolic progress loops, and crisp typography create a subversive, deeply engaging canvas.

## Colors

The color palette operates strictly in a calibrated dark mode to evoke tactical console telemetry.

- **Canvas & Backdrops:** Base deep canvas is set to `#090D16`, shifting to layered void slate `#0F172A` for page foundations.
- **Surface Elevation:** Intermediate modules utilize dark navy-slate tiers: `#161F30` for recessed canvases and cards, rising to `#1E293B` for elevated active panels, modals, and tooltips.
- **Structural Outlines:** Sleek, low-contrast ghost borders leverage `#334155` to define panel boundaries without visual clutter.
- **Accents & Telemetry:**
  - `Primary (#8B5CF6)`: Radiant violet used for cognitive states, satirical milestones, command actions, and primary interactive focus.
  - `Secondary (#06B6D4)` and `Tertiary (#22D3EE)`: Neon cyan and electric ice for metric gauges, active signals, terminal cursors, and cybernetic telemetry feedback.
- **Text & Content Hierarchy:**
  - High-contrast crisp white (`#F8FAFC`) for essential stats, headers, and immediate feedback.
  - Subdued slate (`#94A3B8`) for contextual metrics, labels, and secondary readouts.
  - Deep muted graphite (`#64748B`) for disabled metadata, minor grid ticks, and timestamp watermarks.

## Typography

The typographic hierarchy implements three distinct roles:

1. **Space Grotesk (Headlines & Narrative):** Delivers a technical, geometric edge for sarcastic prompts, satirical diagnostics, and modular headers.
2. **Geist (Body & Microcopy):** Ensures surgical clarity, neutral legibility, and modern density across reading streams and long-form companions.
3. **JetBrains Mono (Telemetry & Badges):** Establishes the terminal aesthetic, driving data widgets, status metrics, timestamped logs, and uppercase HUD trackers.

All uppercase tags using JetBrains Mono must incorporate deliberate positive tracking (`letterSpacing: 0.05em` to `0.12em`) to maintain crisp legibility against dark slate surfaces.

## Layout & Spacing

The canvas architecture is built on a high-density, multi-pane fluid workspace anchored by dynamic modular grids.

- **Grid Systems:**
  - **Desktop (1280px+):** Collapsible command rail (`4.5rem`), primary workflow canvas (8-column flexible grid), and context inspector (`18rem`). Gutters are locked to `1.25rem` (`20px`).
  - **Tablet (768px - 1279px):** 6-column fluid canvas with persistent icon telemetry rails and collapsible overlays.
  - **Mobile (<768px):** Single-column stacked stream with horizontal sliding telemetry bars and sticky quick-action modules.
- **Rhythm:** Driven by a base-4 grid system (`0.25rem`, `0.5rem`, `0.75rem`, `1rem`, `1.5rem`, `2rem`). Telemetry metrics align strictly to compact spacing units (`space-xs` through `space-md`) to ensure dense, command-center information presentation.

## Elevation & Depth

Visual depth is achieved primarily through layered tonal tiers, crisp border delineations, and localized neon luminous blooms:

- **Level 0 (Base Void):** Background at `#090D16`. Zero elevation, subtle matrix grid dots or scanlines in `#1E293B` at 20% opacity.
- **Level 1 (Card & Module Foundation):** `#161F30` bordered with `1px solid #334155`. Flat appearance, no shadow.
- **Level 2 (Active Panels & Draggables):** `#1E293B` with border `#475569`. Diffused ambient shadow: `0 8px 24px -4px rgba(0, 0, 0, 0.6), 0 0 1px 1px rgba(255, 255, 255, 0.05)`.
- **Level 3 (Focused & Floating Telemetry):** Backing backdrop-filter blur (`16px`) with semi-translucent background `rgba(22, 31, 48, 0.85)` and an electric outline glow: `0 0 16px -2px rgba(139, 92, 246, 0.35)`.
- **Accent Radiance:** Neon indicators and high-priority action alerts emit a tight `0 0 10px rgba(6, 182, 212, 0.45)` aura.

## Shapes

The design uses a sharp, tactical corner profile (`roundedness: 1`):

- **Base Radius (0.25rem / 4px):** Standard for buttons, code tags, metric modules, and status pills. Reflects tactical engineering hardware.
- **Container Radius (0.5rem / 8px):** Utilized for dashboard cards, terminal windows, canvas panels, and modal flyouts.
- **Inner Elements (0.125rem / 2px):** Applied to progress meter segments, telemetry bar indicators, and inline monospace code chips.
- **Pills/Circles:** Reserved exclusively for live status blips, ping beacons, and avatar badges.

## Components

### Buttons
- **Primary Cyber:** Solid `#8B5CF6` background with `#F8FAFC` text, `border-radius: 4px`, uppercase tracking. On hover: background shifts to `#7C3AED` with an electric outer glow (`box-shadow: 0 0 14px rgba(139, 92, 246, 0.5)`).
- **Secondary Telemetry:** Background `#161F30`, border `1px solid #334155`, text `#22D3EE`. On hover: border transitions to `#22D3EE`, text brightens to `#F8FAFC`.
- **Ghost/Destructive:** Transparent background, text `#64748B`, hover text `#EF4444` with subtle red ambient tint.

### Cards & Modules
- Structured panels built with `#161F30`, `1px solid #334155` border, and `8px` corner radius.
- Includes a dedicated header strip featuring monospace meta-labels (`label-caps`) in `#64748B`, a status beacon (green `#10B981` or violet `#8B5CF6`), and an optional right-aligned tracking metric.

### Chips & Telemetry Badges
- Compact `20px` height container with `4px` radius. Monospace font (`JetBrains Mono`, `10px`).
- Tone varieties:
  - *Sarcastic Warning:* Border `rgba(234, 179, 8, 0.4)`, background `rgba(234, 179, 8, 0.1)`, text `#FDE047`.
  - *Active Sync:* Border `rgba(6, 182, 212, 0.4)`, background `rgba(6, 182, 212, 0.1)`, text `#22D3EE`.

### Inputs & Terminal Fields
- Dark inset backgrounds (`#0F172A`) with recessed inner shadow.
- Default border `1px solid #334155`, resting text `#F8FAFC`, placeholder `#64748B`.
- Focused state highlights border with `#06B6D4` and casts a subtle cyan drop-shadow blur (`0 0 8px rgba(6, 182, 212, 0.3)`). Input caret is colored neon cyan `#22D3EE`.

### Checkboxes & Radios
- Box size `16px x 16px`, `2px` corner radius (`radio: full`). Border `1px solid #475569`, background `#0F172A`.
- Checked state: `#8B5CF6` background with crisp checkmark or dot in `#FFFFFF`. Radiates subtle violet glow.

### Specialized Canvas Components
- **Satirical Diagnostic HUD:** Split-segmented horizontal meter tracks cognitive load and productivity delusions with neon cyan steps.
- **Console Log Stream:** Monospaced terminal list with `#090D16` backdrop, alternating scanlines, cyan timestamp brackets (`[00:42:19]`), and satirical event messages.