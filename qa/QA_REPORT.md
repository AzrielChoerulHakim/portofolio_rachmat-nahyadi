# QA REVIEW — Rachmat Nahyadi / Thunderline

**Source basis:** one-page CV and three supplied user photographs. **Visual direction:** High Voltage Neon.

## Executed checks

- Chromium / Playwright, fullpage render at **320, 390, 640, 768, 1024, 1440 CSS px**, plus 844×390 short landscape. **PASS:** no page-level horizontal overflow at these sizes.
- Hero video: **PASS** at 1440 and 390. WebM decoded, readyState = 4, playback time advanced to ~1.26s, duration = **3.000s**.
- Energy control: **PASS** at 1440 and 390. Click pauses playback and updates `aria-pressed=false`.
- Mobile menu: **PASS** at 390. Button expands four links, Escape collapses the menu.
- HTML links: **PASS** no unresolved internal anchors. Local `src`/`href`/poster assets exist. All `img` tags have `alt` attributes.
- JavaScript runtime: **PASS** no observed uncaught page errors after correcting a test-harness mistake that executed `defer` script in `<head>` prematurely.
- Reduced-motion mode: reduced-motion stylesheet renders a static plasma poster and content remains visible in captures.

## Render observations and fixes

The first proof at 320px exposed a wide BAKRI proof strip; the first 768px/1440px proofs exposed large word overflow in `BERTUMBUH` / `TERHUBUNG`. These were fixed with section-specific typography, `minmax(0, 1fr)` grids and mobile recomposition. Reruns show document scroll width equal to viewport width at every checked size.

This review used **inline asset data URLs** for testing because Chromium navigation to local HTTP and `file://` is blocked in this container. Source files are unchanged by that test transformation. Rendering used browser fallback typefaces because the Google Fonts endpoint was inaccessible.

## NOT VERIFIED / RELEASE LIMITATIONS

- Deployed GitHub Pages network behavior: pending GitHub publishing.
- WCAG audit and real-device mobile performance.
- 200% text-only zoom, 320-equivalent 400% reflow and custom text-spacing override.
- External Google Drive/LinkedIn endpoint responses and independently reviewed font rendering.
- Client approval of editorial copy (third-person text is not direct quotation).

This is a QA evidence record, not a guarantee of originality, accessibility certification, or proof of a production deployment.
