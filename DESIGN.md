---
name: Academic Focus
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#434655'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#0058be'
  on-secondary: '#ffffff'
  secondary-container: '#2170e4'
  on-secondary-container: '#fefcff'
  tertiary: '#006242'
  on-tertiary: '#ffffff'
  tertiary-container: '#007d55'
  on-tertiary-container: '#bdffdb'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#d8e2ff'
  secondary-fixed-dim: '#adc6ff'
  on-secondary-fixed: '#001a42'
  on-secondary-fixed-variant: '#004395'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-xl:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

The brand personality is disciplined, encouraging, and intellectually organized. Designed for students and researchers, the UI prioritizes cognitive ease, minimizing distractions to foster "deep work" states.

The design style is **Corporate / Modern** with a lean toward **Minimalism**. It utilizes expansive whitespace to prevent information overload, paired with high-quality typography to ensure long-form task lists remain legible. The emotional response should be one of "controlled productivity"—the feeling that one's schedule is manageable and structured.

## Colors

The palette is rooted in professional "Academic Blues" to evoke trust and stability. 

- **Primary (#2563eb):** Used for main actions, active states, and brand-heavy elements.
- **Secondary (#3b82f6):** Used for supporting UI elements, such as category tags or secondary buttons.
- **Tertiary (#10b981):** Reserved strictly for success states, completed tasks, and positive progress indicators.
- **Neutral (#f8fafc):** The primary canvas color, providing a soft, low-strain background for extended study sessions. 

Surface colors for cards and containers should remain pure white (#ffffff) to pop against the neutral background.

## Typography

This design system utilizes **Inter** across all levels to maintain a systematic and utilitarian feel. The hierarchy is strictly enforced to help students distinguish between course titles, task descriptions, and meta-data.

- **Headlines:** Use tighter letter-spacing and heavier weights to anchor pages.
- **Body:** Generous line-heights are employed to ensure that dense task lists do not feel cramped.
- **Labels:** Small caps or bold weights are used for data points like "Due Date" or "Credit Hours" to provide quick scannability.

## Layout & Spacing

The design system uses a **Fixed Grid** for desktop to maintain focus, centering the content to prevent eye strain on ultra-wide monitors. 

- **Desktop:** 12-column grid with a 1280px max-width.
- **Tablet:** 8-column fluid grid.
- **Mobile:** 4-column fluid grid with 16px side margins.

A strict 8px spacing scale (base unit) governs all padding and margins. Tasks within a list should use a 12px vertical gap to feel distinct but connected. Large layout sections (e.g., Sidebar vs. Main Content) are separated by 32px or 48px to clearly define functional zones.

## Elevation & Depth

Depth is communicated through **Tonal Layers** and **Ambient Shadows**. 

- **Level 0 (Background):** #f8fafc (Neutral).
- **Level 1 (Cards/Containers):** Pure white with a 1px border (#e2e8f0) and a very soft, diffused shadow (0px 4px 6px rgba(0,0,0,0.05)).
- **Level 2 (Interactive/Hover):** Increased shadow spread and slight lift to indicate clickability.
- **Level 3 (Modals/Overlays):** High-diffusion shadows with a backdrop blur (8px) on the obscured content to maintain focus on the task at hand.

## Shapes

The shape language is modern and approachable, utilizing `rounded-xl` as the standard for primary containers.

- **Small Components:** 8px (Buttons, Input Fields).
- **Medium Components:** 16px (Task Cards, Popovers).
- **Large Components:** 24px (Main Content Areas, Dashboard Sections).

This significant roundedness softens the "institutional" feel of academic software, making the app feel more like a personal assistant and less like a formal database.

## Components

### Buttons
Primary buttons use a solid #2563eb fill with white text. Secondary buttons use a subtle gray ghost style with a 1px border. All buttons must have a 0.2s transition on hover.

### Checkboxes
Task checkboxes are oversized (20px x 20px) to provide a satisfying "tap target." When checked, they should transition from an outline to a solid Tertiary (#10b981) fill with a checkmark icon.

### Progress Bars
The progress bar is a signature element. It uses a thick 12px height with a light gray track and a Primary-to-Secondary gradient fill. Animation should be "springy" to reward task completion.

### Cards
Cards are the primary container for tasks. They include a subtle left-border accent color to categorize tasks by subject (e.g., Math = Blue, History = Red).

### Input Fields
Inputs use a white background with a soft #e2e8f0 border. On focus, the border transitions to Primary Blue with a 2px outer glow (ring). Labels always sit above the input, never as placeholders only.