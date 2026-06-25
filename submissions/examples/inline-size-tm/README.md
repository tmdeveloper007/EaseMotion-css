# Inline Size

This submission demonstrates **Inline Size** CSS utilities using the EaseMotion design system tokens and CSS custom properties.

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
<div class="inline-size">Small variant</div>
<div class="inline-size-md">Medium variant</div>
<div class="inline-size-lg">Large variant</div>
<div class="inline-size-xl">Extra Large variant</div>
<div class="inline-size-success">Success color variant</div>
<div class="inline-size-danger">Danger color variant</div>
<div class="inline-size-warning">Warning color variant</div>
<div class="inline-size-info">Info color variant</div>
<div class="inline-size-gradient">Gradient effect variant</div>
<div class="inline-size-glow">Glow effect variant</div>
<div class="inline-size-bordered">Bordered variant</div>
<div class="inline-size-pill">Pill variant</div>
<div class="inline-size-inset">Inset shadow variant</div>
<div class="inline-size-hover">Hover interactive variant</div>
<div class="inline-size-focus">Focus interactive variant</div>
<div class="inline-size-active">Active interactive variant</div>
<div class="inline-size-disabled" disabled>Disabled state variant</div>
```

## Why is it useful?

The Inline Size utilities integrate seamlessly with EaseMotion's design token system, using `--ease-*` CSS custom properties for consistent spacing, colors, typography, shadows, and transitions across all variants. This ensures visual coherence with the rest of the framework while providing a comprehensive set of ready-to-use CSS utilities for production websites and applications. All submissions follow the same design language, making them consistent with the existing EaseMotion ecosystem.
