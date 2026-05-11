# UI Component Skills

## 1. Creating a Hero Section
To create a high-impact Hero section:
- Use a `.hero` container with `min-height: 100vh`.
- Add a `.hero-bg` with a CSS animation (`heroZoom`) for subtle movement.
- Apply a `.hero-overlay` with a gradient from `rgba(30, 58, 95, 0.85)` to `rgba(199, 91, 57, 0.3)`.
- Use `.hero-title` with `clamp()` for responsive font sizes and `fadeInUp` animation.

## 2. Implementing a Lightbox Gallery
To implement the project's signature lightbox:
- Structure: A grid of `.col` containing `.gallery-item`.
- Inside `.gallery-item`, include an `<img>` and a `.zoom-overlay` with a 🔍 icon.
- Use the shared JavaScript in `cairo.html` to handle the `active` class on the `#lightbox` container.
- Ensure the lightbox has `backdrop-filter: blur(10px)` and supports keyboard navigation (ESC, Arrows).

## 3. Designing Story Cards
Story sections should follow an alternating pattern:
- Use `.story-section` with `.row.align-items-center.g-5`.
- Use `.story-image-wrapper` for images to ensure consistent `border-radius` and hover scaling.
- Alternate the order of the image and content columns using Bootstrap's `order-lg-2` and `order-lg-1` classes.

## 4. Crafting Mission Cards
Mission cards are for high-level value propositions:
- Use a `.mission-card` with a centered `.mission-icon`.
- Icons should be large emojis inside a circular gradient background (`var(--color-primary-light)` to `var(--color-primary)`).
- Include a subtle hover lift effect (`transform: translateY(-10px)`).

## 5. Global Footer
The footer must include:
- A brand section with the globe emoji.
- Quick links to all main destinations.
- A "Connect" section for meta-information.
- A copyright notice in a `.footer-bottom` with a top border.
