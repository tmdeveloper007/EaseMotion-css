# Float

This submission demonstrates the CSS `float` property with practical examples using the EaseMotion CSS design system tokens.

## Features

- Multiple size variants (sm, md, lg, xl)
- Color variants using `--ease-color-*` design tokens
- Interactive state demonstrations (hover, focus, active, disabled)
- Fully responsive grid layout
- Dark mode support via `prefers-color-scheme: dark`
- Reduced motion support via `prefers-reduced-motion: reduce`
- Uses `--ease-*` CSS custom properties from `core/variables.css`

## Usage

```html
<!-- Size variant -->
<div class="float-card variant-md color-primary">Content</div>

<!-- Color variants -->
<div class="float-card color-success">Success</div>
<div class="float-card color-danger">Danger</div>

<!-- Interactive states -->
<div class="float-card state-hover state-focus">Hover me</div>
<div class="float-card state-active">Click me</div>
<div class="float-card state-disabled">Disabled</div>
```

## Why is it useful?

The `float` property is a fundamental CSS tool for building consistent UI components. By using EaseMotion's `--ease-*` design tokens, these demonstrations integrate seamlessly with the broader design system, ensuring visual consistency across all submissions in the repository.
