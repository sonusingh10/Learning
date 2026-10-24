# Responsive and Mobile-Friendly Web App Design

A practical guide to designing web applications that work well on phones, tablets, and larger screens.

## What “responsive” means

A responsive web app adjusts its layout and controls to the available screen space. A mobile-friendly design does more than shrink a desktop page: it keeps the main tasks easy to find and use, avoids unnecessary horizontal scrolling, and remains usable with touch, keyboard, zoom, and assistive technology.

There is no single setting that makes every app automatically fit a phone. Use flexible layouts and responsive assets, then test the real pages and workflows at different sizes.

## Mobile-first design checklist

1. **Start with the narrow layout.** Put the most important content and actions first. Add columns or secondary panels when the content has room, rather than forcing a desktop layout onto a small screen.
2. **Use flexible layout rules.** Build with CSS Grid or Flexbox, relative units, and sensible maximum widths. Avoid fixed page widths that can cause content to overflow. Add breakpoints where the content needs them.
3. **Keep navigation and actions usable.** Make primary actions easy to reach. If navigation collapses into a menu, ensure it works with keyboard and touch and has a clear accessible name.
4. **Make forms and controls comfortable.** Use clear labels, appropriate input types, visible focus, and adequately sized, spaced touch targets. WCAG 2.2's minimum target-size criterion is 24 by 24 CSS pixels, with defined exceptions; larger targets are often easier to tap.
5. **Make content reflow.** Text should wrap and remain readable when users zoom. Avoid requiring two-dimensional scrolling for ordinary page content; wide tables or maps may need a contained scrolling region.
6. **Serve appropriately sized images.** Use responsive image options so a phone does not have to download unnecessarily large desktop images.
7. **Check the whole experience.** Test key pages at narrow and wide widths, portrait and landscape, with browser zoom, keyboard navigation, touch input, and slower network conditions. Emulation is useful, but check important flows on a real phone too.

## Testing references

- [Chrome DevTools device mode](https://developer.chrome.com/docs/devtools/device-mode) — Preview a page at different viewport sizes and simulate some mobile conditions. It is an approximation of a real device.
- [WCAG 2.1: Reflow](https://www.w3.org/WAI/WCAG21/Understanding/reflow) — Guidance on keeping content usable at narrow widths and high zoom.
- [WCAG 2.2: Target Size (Minimum)](https://www.w3.org/WAI/WCAG22/Understanding/target-size-minimum) — Minimum target-size guidance for pointer inputs.

## Learn more

- [web.dev: Learn Responsive Design](https://web.dev/learn/design/?hl=en) — Course covering responsive layouts, media queries, typography, images, accessibility, and interaction.
- [MDN: Responsive web design](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Responsive_Design) — Concepts and practical responsive-layout guidance.
- [MDN: Media query fundamentals](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Media_queries) — How media queries adapt styles to viewport and device conditions.

## Related saved resources

- [Designer Websites and Tools](Designer%20Websites%20and%20Tools.md) — UI inspiration, component libraries, icons, and design tools.
