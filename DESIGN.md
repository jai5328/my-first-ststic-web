---
name: Obsidian Kinetic
colors:
  surface: '#10141a'
  surface-dim: '#10141a'
  surface-bright: '#353940'
  surface-container-lowest: '#0a0e14'
  surface-container-low: '#181c22'
  surface-container: '#1c2026'
  surface-container-high: '#262a31'
  surface-container-highest: '#31353c'
  on-surface: '#dfe2eb'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dfe2eb'
  inverse-on-surface: '#2d3137'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#d0bcff'
  on-secondary: '#3c0091'
  secondary-container: '#571bc1'
  on-secondary-container: '#c4abff'
  tertiary: '#4edea3'
  on-tertiary: '#003824'
  tertiary-container: '#00885d'
  on-tertiary-container: '#000703'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#10141a'
  on-background: '#dfe2eb'
  surface-variant: '#31353c'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
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
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  mono-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  mono-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: -0.01em
  mono-xs:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
  label-caps:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
---

## Brand & Style
The brand targets fast-moving engineering teams, technical leads, and distributed software organizations who value speed, spatial efficiency, and extreme signal-to-noise ratio. The emotional response is centered on high-agency control, precision, and frictionless workflow—evoking the focused calm of late-night terminal sessions and high-throughput deployment consoles.

The visual style merges technical minimalism with high-precision structural boundaries. It draws heavily from keyboard-first development environments and developer command palettes: deep near-black backgrounds, micro-metric surfaces, razor-sharp 1px structural dividing lines, and subtle frosted overlays. Vibrant indigo/violet energy accents drive user focus directly to actionable primitives, while disciplined semantic status indicators give instant situational awareness without cognitive fatigue.

## Colors
The system is built ground-up for dark mode, using subtle stepped luminescence rather than high-contrast glare to denote surface hierarchy.

- **Canvas & Surface Tiering:**
  - Base canvas: `#0D1117`
  - Elevated card/widget surface: `#161B22`
  - Active hover / dropdown / floating layer: `#21262D`
  - Subtle structural border: `#30363D` (or `rgba(255, 255, 255, 0.08)`)

- **Primary & Accent Tokens:**
  - Primary Indigo (`#6366F1`): Primary actions, active navigation items, progress highlights.
  - Secondary Violet (`#8B5CF6`): Secondary tags, command palette accents, selection rings.
  - Interactive Hover (`#4F46E5`): Button press states and focused toggles.

- **Semantic Status Signals:**
  - Success / Merged / On Track: Emerald (`#10B981`) paired with faint badge tint `rgba(16, 185, 129, 0.12)`.
  - Warning / At Risk / Queue: Amber (`#F59E0B`) with badge tint `rgba(245, 158, 11, 0.12)`.
  - Critical / Failing CI / Conflicts: Rose (`#EF4444`) with badge tint `rgba(239, 68, 68, 0.12)`.
  - Neutral / Inactive: Slate (`#94A3B8`) with badge tint `rgba(148, 163, 184, 0.10)`.

Text tokens strictly respect accessibility on `#0D1117`: Primary text at `#F0F6FC` (high contrast), secondary text at `#8B949E` (subdued metadata), and muted text at `#6E7681` (placeholders and inactive icons).

## Typography
The typographic hierarchy utilizes two distinct font disciplines:
1. **Inter**: Powers the user interface, navigational hierarchy, card titles, and contextual body copy. It provides neutral geometric clarity with tight letter-spacing on headline scales to prevent awkward wrapping in dense sidebars.
2. **JetBrains Mono**: Used intentionally for high-signal developer data primitives, including commit hashes (`a9c2f81`), Git branch tags (`feat/linear-sync`), pull request reference IDs (`#1402`), diff delta statistics (`+42 -8`), and timestamp logs.

All tabular numbers in tables and metrics cards must render using tabular lining figures (`font-variant-numeric: tabular-nums`) to ensure vertical visual alignment across streaming data points.

## Layout & Spacing
The layout follows a fluid 12-column responsive grid built for maximum data density while maintaining structural legibility:

- **Desktop (1280px and above):** 12-column layout with a fixed or collapsible 260px navigation sidebar. Canvas margin is `margin-desktop` (32px), with `gutter-desktop` (24px) separating card widgets. Complex widgets span 4, 6, 8, or 12 columns.
- **Tablet (768px – 1279px):** 6-column reflow. The sidebar collapses into an icon-rail or off-canvas drawer. Gutters scale to `gutter` (16px), and card widgets expand to fill minimum 3 or 6 columns.
- **Mobile (< 768px):** Single-column stacked stream with `margin` (16px) outer safe area. Multi-metric dashboards collapse to horizontal scrolling carousels or stacked status lists.

Internal component rhythm enforces a compact 4px baseline system (`0.25rem`, `0.5rem`, `0.75rem`, `1rem`, `1.5rem`). Information-dense table rows and chip groups prioritize `space-xs` and `space-sm` gaps, while widget padding sits at a strict 16px to 20px boundary.

## Elevation & Depth
Depth is constructed through subtle luminance layering, ghost borders, and precision backdrops rather than muddy diffuse drop shadows:

- **Level 0 (Base Canvas):** Pure background tone `#0D1117`. Flat with no shadow.
- **Level 1 (Card & Dashboard Widgets):** Fill `#161B22` enclosed with a 1px border `rgba(255, 255, 255, 0.08)`. Subtle grounding shadow: `0 1px 3px rgba(0, 0, 0, 0.40)`.
- **Level 2 (Hovered & Active Drag Targets):** Fill `#1C2128` with dynamic border `rgba(99, 102, 241, 0.35)`. Shadow: `0 8px 24px -4px rgba(0, 0, 0, 0.60), 0 0 0 1px rgba(99, 102, 241, 0.20)`.
- **Level 3 (Command Palettes, Popovers & Tooltips):** Frosted glass surface using backdrop blur (`backdrop-filter: blur(12px)`), surface tone `rgba(22, 27, 34, 0.85)`, and a crisp perimeter border `rgba(255, 255, 255, 0.12)`. Shadow: `0 16px 36px rgba(0, 0, 0, 0.70)`.

Never use saturated colored drop shadows outside of micro active focus states.

## Shapes
The system relies on a consistent 12px (`rounded-lg` / 0.75rem) corner radius for primary modules, delivering the engineered feel of contemporary developer tools:

- **Standard Cards & Drag Widgets:** Formed with precisely 12px corners (`0.75rem`), balancing modern softness with high-density tabular edges.
- **Buttons, Inputs & Selectors:** Styled with 6px to 8px radius for crisp interaction points.
- **Chips, Badges & Avatars:** Micro pill shapes (`9999px`) for semantic status indicators and small metadata tags; standard 6px radius for commit tags and monospaced hashes.
- **Inner Nested Elements:** When an element sits within a 12px container with an 8px inset padding, its inner border-radius decreases to 6px or 8px to preserve concentric visual balance.

## Components

### Buttons
- **Primary:** Background `#6366F1`, hover `#4F46E5`, active `#4338CA`. Text `#FFFFFF`, font-weight 500, radius 6px. Focused state displays a 2px offset ring in `#8B5CF6`.
- **Secondary / Ghost:** Transparent background with border `rgba(255, 255, 255, 0.10)`. Hover background `rgba(255, 255, 255, 0.05)`, text `#F0F6FC`.
- **Destructive:** Background `rgba(239, 68, 68, 0.10)`, border `rgba(239, 68, 68, 0.25)`, text `#EF4444`. Hover background `rgba(239, 68, 68, 0.20)`.

### Chips & Semantic Status Badges
- Built with a height of 22px, padding `2px 8px`, and 9999px pill corners.
- **On Track / Merged:** Background `rgba(16, 185, 129, 0.12)`, text `#34D399`, border `rgba(16, 185, 129, 0.25)`. Preceded by an icon or 6px solid emerald dot.
- **At Risk / Waiting:** Background `rgba(245, 158, 11, 0.12)`, text `#FBBF24`, border `rgba(245, 158, 11, 0.25)`.
- **Failing CI / Conflicts:** Background `rgba(239, 68, 68, 0.12)`, text `#F87171`, border `rgba(239, 68, 68, 0.25)`.

### Widget Cards (Draggable & Modular)
- Background `#161B22`, border 1px solid `#30363D`, corner radius 12px.
- **Header:** Height 48px with flex layout. Includes a subtle 6-dot grab handle icon (`#6E7681`, hovering to `#F0F6FC`) indicating drag-and-drop affordance, followed by widget title and contextual action menus.
- **Active Drag State:** Opacity 0.85, slight scale transform (1.01x), elevated with shadow `0 20px 30px rgba(0, 0, 0, 0.65)` and primary indigo border highlight.

### Developer Data Tables
- Monospaced metadata columns (hashes, lines added/removed, durations).
- Header row height 36px, background `#0D1117`, typography `label-caps` in `#8B949E`.
- Body row height 44px, alternating hover highlight `rgba(255, 255, 255, 0.02)`, bottom border 1px solid `rgba(255, 255, 255, 0.05)`.
- Status, author avatar, branch badge, and PR status icons vertically centered with tabular numeric alignment.

### Inputs & Filter Bars
- Background `#0D1117`, border 1px solid `#30363D`, text `#F0F6FC`, placeholder `#6E7681`.
- Focused state transitions border to `#6366F1` with an ambient glow `0 0 0 1px #6366F1`.
- Integrated keyboard shortcut hint pills (e.g., `⌘K`) rendered in JetBrains Mono (`mono-xs`) with subtle border `rgba(255, 255, 255, 0.12)`.

### Interactive Tabs & Progress Bars
- **Tabs:** Underline style with a 2px active indicator in `#6366F1`. Inactive text `#8B949E`, active text `#F0F6FC`. Optional counter pill beside tab title.
- **Progress Bars:** 4px or 6px height track `#21262D` with rounded ends. Active fill transitions between `#6366F1` and `#8B5CF6`, or maps directly to semantic green/amber/red when rendering sprint completion and CI health.