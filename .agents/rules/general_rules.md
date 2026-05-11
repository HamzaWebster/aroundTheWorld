# Project Rules & Guidelines

## General Principles
1. **Consistency**: Always use the defined theme constants in `.agents/theme/constants.md`. Never use hardcoded colors outside the palette.
2. **Aesthetics First**: Every new page or component must feel premium. Use gradients, smooth transitions, and high-quality imagery (Unsplash is the preferred source).
3. **Responsiveness**: All designs must be mobile-first. Test at 375px, 768px, and 1440px widths.
4. **Semantics**: Use proper HTML5 semantic tags (`<header>`, `<main>`, `<section>`, `<footer>`).

## Technical Guidelines
1. **Framework**: Bootstrap 5.3 is the foundation. Use its grid system and utility classes where appropriate, but override styles with custom CSS for the premium feel.
2. **Performance**: Use CSS transitions over JavaScript animations where possible.
3. **Images**: Use `object-fit: cover` for gallery and card images. Always include `alt` text for accessibility.
4. **SEO**: Every page must have a unique `<title>` and `<meta name="description">`. Use `<h1>` once per page.

## Visual Specifics
- **Buttons**: Use `.btn-primary-custom` for main actions. It should have the terracotta gradient and a glow shadow.
- **Sections**: Alternate between `var(--color-cream)` and `var(--color-sage)` backgrounds to create visual rhythm.
- **Cards**: All cards must have a `border-radius: 20px` and a hover effect (e.g., `transform: translateY(-10px)`).
- **Navigation**: The navbar should be transparent on top and transition to `var(--color-navy)` on scroll (or be solid Navy on subpages).
