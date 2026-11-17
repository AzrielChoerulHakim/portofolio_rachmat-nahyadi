# Lazarus release review — Rachmat Nahyadi

Build: static HTML, CSS, JS, local MP4, original supplied photographs. No dependencies or build step required. Source basis: uploaded CV and photographs.

## Verified from implementation
- HTML title/description and structured semantic headings exist.
- All CV-derived claims present in source have been compared with the uploaded CV (degree, IPK, dates, institutional names, roles and contact details).
- Email, phone, LinkedIn, external CV-listed portfolio, and downloadable PDF use real destinations.
- Three-second self-generated plasma video exists locally in MP4; no audio; poster fallback exists.
- Pause/resume button and `prefers-reduced-motion` behavior implemented.
- JS syntax check passed with Node.

## Not yet verified / release conditions
- Browser screenshot review for 320, 390, 640, 768, 1024, 1440, short landscape.
- Device performance, 200% text resize, reflow, contrast measurement, text spacing overrides and missing font fallback.
- Deployed GitHub Pages URL: pending publication/configuration.

Passing static checks is not proof of originality, accessibility, performance or browser reliability.