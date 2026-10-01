---
name: Piepie Challenge
colors:
  surface: '#131026'
  surface-dim: '#131026'
  surface-bright: '#3a364d'
  surface-container-lowest: '#0e0b20'
  surface-container-low: '#1c192e'
  surface-container: '#201d32'
  surface-container-high: '#2a273d'
  surface-container-highest: '#353249'
  on-surface: '#e5dffd'
  on-surface-variant: '#bac9cc'
  inverse-surface: '#e5dffd'
  inverse-on-surface: '#312e44'
  outline: '#849396'
  outline-variant: '#3b494c'
  surface-tint: '#00daf3'
  primary: '#c3f5ff'
  on-primary: '#00363d'
  primary-container: '#00e5ff'
  on-primary-container: '#00626e'
  inverse-primary: '#006875'
  secondary: '#ffb2be'
  on-secondary: '#660025'
  secondary-container: '#d70357'
  on-secondary-container: '#ffeced'
  tertiary: '#ffe5fc'
  on-tertiary: '#570066'
  tertiary-container: '#fcbbff'
  on-tertiary-container: '#941da8'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#9cf0ff'
  primary-fixed-dim: '#00daf3'
  on-primary-fixed: '#001f24'
  on-primary-fixed-variant: '#004f58'
  secondary-fixed: '#ffd9de'
  secondary-fixed-dim: '#ffb2be'
  on-secondary-fixed: '#400014'
  on-secondary-fixed-variant: '#900038'
  tertiary-fixed: '#ffd6fe'
  tertiary-fixed-dim: '#f9abff'
  on-tertiary-fixed: '#35003f'
  on-tertiary-fixed-variant: '#7b008f'
  background: '#131026'
  on-background: '#e5dffd'
  surface-variant: '#353249'
typography:
  display-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.03em
  display-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  metric-xl:
    fontFamily: Space Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.03em
  metric-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.02em
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
---

## Brand & Style

This design system drives a high-intensity, visually immersive athletic tracking experience. The visual language bridges competitive sports motivation with sleek cyber-athletic digital craft.

### Brand Personality
- **Electrifying & Kinetic:** Dynamic color pops, clean luminescence, and high-energy contrasts mimic digital stadium scoreboards and race telemetry.
- **Precise & Goal-Oriented:** Metrics, progress gauges, and challenge tables prioritize uncompromised legibility and immediate feedback.
- **Modern & Premium:** Deep midnight violet surfaces layered with frosted luminescence replace generic dark grays, conveying an exclusive, next-generation fitness ecosystem.

### Target Audience & Emotional Response
Geared toward competitive runners, cyclists, and fitness enthusiasts who thrive on streak progression, social challenges, and data clarity. The interface instills a sense of momentum, adrenaline, personal mastery, and modern edge.

### Design Movement
**Vibrant Cyber-Athletic Glass:** Deep tinted backgrounds (`#0F0C20` to `#1A162B`), hyper-saturated neon performance accents (Electric Cyan, Hot Magenta, Neon Purple), crisp 1px borders, subtle frosted elevation layers, and structured numeric typography.

## Colors

The palette leverages an atmospheric midnight-purple substrate juxtaposed with high-velocity luminescence.

### Palette Architecture
- **Primary (`#00E5FF` - Electric Cyan):** The pulse of action. Utilized for primary interactive states, current active streaks, sprint times, live tracking paths, and primary CTA accents.
- **Secondary (`#E91E63` - Kinetic Magenta):** High-impact challenge driver. Denotes challenge milestones, calorie outputs, heart rate zones, and urgency indicators.
- **Tertiary (`#9C27B0` - Voltage Violet):** Deep energy bridge. Applied to badges, secondary telemetry tags, challenge ranks, and gradient overlays.
- **Neutral Substrate (`#0F0C20` to `#1A162B`):** Multi-tiered dark slate violet background hierarchy:
  - Base canvas: `#0F0C20`
  - Elevated surfaces: `#1A162B`
  - Floating overlays: `#241E3A`
  - Structural stroke/border: `#2D274A`
- **Text & Feedback Surfaces:**
  - High-contrast text: `#FFFFFF` (100% white for headline numbers and metrics)
  - Secondary text: `#A59EBA` (65% muted slate)
  - Disabled/Tertiary text: `#6C638A` (40% muted)
  - Success: `#00E676`
  - Warning: `#FFD600`
  - Critical/Stop: `#FF1744`

### Application Rules
- Avoid plain gray or pure `#000000` blacks; all surfaces must carry the deep violet undertone.
- Gradients must remain directional and purposeful: blend `#00E5FF` into `#9C27B0` for endurance bars, or `#E91E63` into `#9C27B0` for streak flame meters.
- Text must never blend directly into glowing borders; preserve high contrast by reserving cyan and magenta for small focal badges, numbers, icons, and primary buttons.

## Typography

The type system blends the technical, mechanical precision of **Space Grotesk** with the ergonomic legibility of **Plus Jakarta Sans**.

### Font Pairing Logic
- **Space Grotesk (Headlines, Metrics & Labels):** Provides an athletic, telemetry-dashboard aesthetic. The geometric numerals and tightened letter spacing communicate high performance and speed.
- **Plus Jakarta Sans (Body & Titles):** Balances technical flair with rounded human warmth, ensuring challenge descriptions, social feed posts, and rulebooks remain effortlessly readable on high-density mobile screens.

### Numerical & Data Conventions
- Numbers in leaderboard tables, split-times, and metric cards must use tabular figures (`font-variant-numeric: tabular-nums`) to prevent horizontal jitter during live telemetry updates.
- Metric subtext and status flags must use `label-md` or `label-sm` with uppercase transformation and tracking expansion (`0.06em` to `0.08em`).

## Layout & Spacing

A compact, density-optimized layout designed primarily for one-handed mobile navigation and responsive web tablet scaling.

### Layout Model
- **Mobile (< 768px):** Single-column fluid architecture. 16px (`1rem`) outer screen margins, 12px (`0.75rem`) internal grid gutters. Top priority goes to metric summaries and stacked challenge tiles.
- **Tablet (768px - 1024px):** 6-column fluid grid. 24px (`1.5rem`) outer canvas margins, 16px (`1rem`) gutters. Metric tiles sit in 2 or 3-column rows.
- **Desktop (> 1024px):** 12-column max-width container (1200px cap) centered with dynamic auto margins, keeping the sports feed focused and dashboard-oriented.

### Rhythm Principles
- Space tokens drive internal component architecture: 8px (`space-sm`) separates icon from numeric metric; 16px (`space-md`) separates stacked modules inside a card; 24px (`space-lg`) marks the vertical cadence between major challenge zones.
- Data tables maintain compact 12px vertical cell padding to maximize visible leaderboard entries above the mobile fold.

## Elevation & Depth

Depth is established through translucent dark layers, luminous backdrops, and crisp perimeter definition rather than muddy black drop shadows.

### Atmospheric Glassmorphism
- **Base Canvas:** Deep, non-uniform radial gradient transitioning from `#1A162B` (top-center spotlight) down to `#0F0C20` (ground darkness).
- **Cards & Containers:** `rgba(26, 22, 43, 0.72)` background fill with a `12px` to `16px` backdrop filter blur. This allows vivid background glows and map paths to bleed softly through.
- **Border Architecture:** Every card is framed with a razor-thin `1px` border using `#2D274A`. On interactive hover or active state, the border shifts to an electric gradient: `linear-gradient(135deg, rgba(0, 229, 255, 0.4), rgba(233, 30, 99, 0.2))`.

### Neon Luminescence & Shadow
- Standard components receive zero ambient black shadow.
- Elevated elements (floating action buttons, modal sheets, active streak badges) use colored neon halos:
  - **Electric Cyan Glow:** `0 0 24px rgba(0, 229, 255, 0.22), 0 4px 12px rgba(0, 0, 0, 0.5)`
  - **Kinetic Magenta Glow:** `0 0 24px rgba(233, 30, 99, 0.25), 0 4px 12px rgba(0, 0, 0, 0.5)`
- This creates an unmistakable arcade-stadium luminescence that defines critical focus points without cluttering the screen.

## Shapes

The design system adopts a consistent, confident corner radius profile centered on clean ergonomics and sleek modern hardware cues.

### Radius Hierarchy
- **Cards & Metric Tiles:** Uniform `16px` (`rounded-lg` under roundedness level 2). This delivers the signature friendly, modern silhouette while remaining sharp enough for dense data grids.
- **Interactive Buttons & Badges:** `8px` (`rounded`) for input fields, filter chips, and primary buttons.
- **Pill Tags & Progress Meters:** Complete capsules (`9999px`) reserved exclusively for live status chips (e.g., "LIVE NOW", "STREAK ACTIVE") and circular tracking progress bars.

## Components

### Buttons
- **Primary Athletic CTA:** High-voltage cyan fill (`#00E5FF`), bold Space Grotesk text in deep obsidian (`#0F0C20`), 12px 20px padding, 8px radius. Active tap triggers a subtle scale compression (0.97) and cyan halo bloom.
- **Secondary Action:** Glass container (`rgba(26, 22, 43, 0.8)`), 1px border `#2D274A`, white text. On hover/focus: border turns `#00E5FF` with white text.
- **Destructive/Urgent Action:** Magenta outline (`#E91E63`) with translucent magenta wash (`rgba(233, 30, 99, 0.1)`).

### Metric Tiles & Structured Data Tables
- **Metric Tiles:** Rounded 16px cards with frosted fill. Top row: uppercase `label-sm` in `#A59EBA` paired with a sharp neon icon. Center row: `metric-xl` headline in pure `#FFFFFF`. Bottom row: contextual delta pill (e.g., "+12.4% vs last week" in electric cyan or green).
- **Leaderboard & Challenge Tables:** Alternating rows using subtle violet glass tinting (`rgba(255, 255, 255, 0.02)` on even rows). Sticky headers with uppercase Space Grotesk tags. Numerical ranks 1-3 highlighted with Neon Cyan, Magenta, and Violet perimeter indicators.

### Cards & Challenge Modules
- Built with a `16px` border-radius, `backdrop-filter: blur(14px)`, and `1px` stroke `#2D274A`.
- Include a dynamic progress bar at the card footer: a 4px tall capsule track in `#241E3A` filled with a glowing gradient from `#E91E63` to `#00E5FF`.

### Chips & Filter Pills
- Compact capsule shapes (`rounded-full`), 6px 14px padding.
- Inactive state: `#1A162B` surface with `#2D274A` border and `#A59EBA` text.
- Active state: `#00E5FF` border and font color with `rgba(0, 229, 255, 0.12)` background tint.

### Inputs & Search Bars
- Dark recessed background (`#0F0C20`) to contrast with elevated `#1A162B` cards.
- 1px static border `#2D274A`, transitioning smoothly to `#00E5FF` upon focus.
- Placeholder text in `#6C638A`, with typed text in crisp `#FFFFFF`.

### Checkboxes & Segmented Toggles
- Custom square-rounded checkboxes (4px radius) with `#2D274A` border. Checked state transitions to solid `#00E5FF` with a deep `#0F0C20` checkmark.
- Segmented switches live inside a unified `#0F0C20` track with a floating `#1A162B` thumb highlighted by a 1px `#2D274A` border.