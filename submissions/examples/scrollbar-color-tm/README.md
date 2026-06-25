# Scrollbar Color

This submission demonstrates **Scrollbar Color** CSS utilities using the EaseMotion design system tokens and CSS custom properties.

## Features

- Multiple size variants (sm, md, lg, xl) for flexible usage across components
- Color variants using `--ease-color-*` design tokens: success, danger, warning, info
- Interactive state variants: hover, focus, active
- Special effect variants: gradient, glow, bordered, pill, inset
- Disabled state with reduced opacity and non-interactive cursor
- Full dark mode support via `prefers-color-scheme: dark`
- Reduced motion support via `prefers-reduced-motion: reduce`
- Responsive grid layout adapts to tablet (768px) and desktop (1024px)
- Hover transitions using `--ease-speed-medium` and `--ease-ease` easing curve

## Usage

```html
<div class="scrollbar-color">Small variant</div>
<div class="scrollbar-color-md">Medium variant</div>
<div class="scrollbar-color-lg">Large variant</div>
<div class="scrollbar-color-xl">Extra Large variant</div>
<div class="scrollbar-color-success">Success color variant</div>
<div class="scrollbar-color-danger">Danger color variant</div>
<div class="scrollbar-color-warning">Warning color variant</div>
<div class="scrollbar-color-info">Info color variant</div>
<div class="scrollbar-color-gradient">Gradient effect variant</div>
<div class="scrollbar-color-glow">Glow effect variant</div>
<div class="scrollbar-color-bordered">Bordered variant</div>
<div class="scrollbar-color-pill">Pill variant</div>
<div class="scrollbar-color-inset">Inset shadow variant</div>
<div class="scrollbar-color-hover">Hover interactive variant</div>
<div class="scrollbar-color-focus">Focus interactive variant</div>
<div class="scrollbar-color-active">Active interactive variant</div>
<div class="scrollbar-color-disabled" disabled>Disabled state variant</div>
```

## Why is it useful?

The Scrollbar Color utilities integrate seamlessly with EaseMotion's design token system, using `--ease-*` CSS custom properties for consistent spacing, colors, typography, shadows, and transitions across all variants. This ensures visual coherence with the rest of the framework while providing a comprehensive set of ready-to-use CSS utilities for production websites and applications. All submissions follow the same design language, making them consistent with the existing EaseMotion ecosystem.
