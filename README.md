# css-carousel

This project demonstrates a horizontal carousel built entirely with modern CSS, without any JavaScript.  
See [`index.html`](css-carousel/index.html) for the implementation.

**Live version:** [https://grzegorzly.github.io/css-carousel/](https://grzegorzly.github.io/css-carousel/)

## Features

- **Pure CSS carousel**: No JavaScript required.
- **Modern CSS features**:
  - `scroll-snap-type` for smooth, snap-to-card scrolling ([MDN Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-snap-type))
  - `scroll-behavior: smooth` for animated scrolling ([MDN Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-behavior))
  - CSS custom properties (variables) for easy theming ([MDN Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/--*))
  - Experimental features:
    - `anchor-name` and `position-anchor` ([CSS Anchor Positioning Spec](https://drafts.csswg.org/css-anchor-position/))
    - `scroll-marker-group`, `scroll-marker`, and `scroll-button` ([CSS Scroll-driven Animations Spec](https://drafts.csswg.org/css-scroll-animations-1/))

## References

- [CSS Scroll Snap](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Scroll_Snap)
- [CSS Anchor Positioning (Draft)](https://drafts.csswg.org/css-anchor-position/)
- [CSS Scroll-driven Animations (Draft)](https://drafts.csswg.org/css-scroll-animations-1/)

> **Note:** Some features used in this project are experimental and may not be supported in all browsers. Please check browser compatibility before using