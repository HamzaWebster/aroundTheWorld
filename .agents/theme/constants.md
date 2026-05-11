# Visual Identity & Theme Constants

## Color Palette
| Name | Hex | Usage |
|------|-----|-------|
| Primary | `#C75B39` | CTA Buttons, Links, Accents (Terracotta) |
| Primary Dark | `#A84829` | Button Hovers, Darker Accents |
| Primary Light | `#E07B5A` | Lighter Accents, Gradients |
| Secondary | `#2D5A27` | Success states, Nature-themed icons (Forest Green) |
| Secondary Dark | `#1E3D19` | Deep Forest Green |
| Secondary Light | `#4A8A42` | Bright Forest Green |
| Navy | `#1E3A5F` | Footer, Navbar Scroll, Deep Backgrounds |
| Navy Dark | `#152A45` | Deep Navy |
| Navy Light | `#2E4F7A` | Subtle Navy Accents |
| Sand | `#D4A574` | Earthy Accents, Decorative Lines |
| Cream | `#FDF8F3` | Primary Background (Light) |
| Sage | `#F4F7F4` | Secondary Background (Subtle Green) |
| Charcoal | `#2D2D2D` | Main Text |
| Stone | `#6B6B6B` | Subtitles, Secondary Text |

## Typography
- **Headings**: `'Playfair Display', Georgia, serif`
  - Weights: 400, 500, 600, 700
- **Body**: `'Inter', -apple-system, sans-serif`
  - Weights: 300, 400, 500, 600

## Design Tokens
- **Shadows**:
  - `sm`: `0 2px 8px rgba(0, 0, 0, 0.08)`
  - `md`: `0 4px 20px rgba(0, 0, 0, 0.12)`
  - `lg`: `0 8px 40px rgba(0, 0, 0, 0.16)`
  - `glow`: `0 4px 20px rgba(199, 91, 57, 0.3)`
- **Glassmorphism**: `backdrop-filter: blur(10px); -webkit-backdrop-filter: blur(10px);`
- **Border Radius**: 20px for cards, 50px for buttons.

## Bootstrap Overrides
- `--bs-primary`: `var(--color-primary)`
- `--bs-secondary`: `var(--color-secondary)`
- `--bs-info`: `var(--color-navy)`
- `--bs-warning`: `var(--color-sand)`
