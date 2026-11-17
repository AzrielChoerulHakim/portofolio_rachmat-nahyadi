# RACHMAT NAHYADI — MOBILE VISUAL QA PLAN

**Target:** 320 / 390 CSS px sections plus full-page 640 / 768 / 1024 / 1440 and short landscape.

Reading order: Hero → profile → expertise → experience → photo essay → organizations → external portfolio → contact.

Risk zones: very long upper-case BERTUMBUH/TERHUBUNG headings, proof strip at 320, hero portrait overlap, fixed menu, plasma under live text, source-linked resume and contact links.

Method: Headless Chromium via Playwright `set_content()` with local CSS/JS/media converted to data URLs because this environment blocks localhost/file navigation. This exercises the full DOM, assets, responsive CSS, and actual media playback, but **not network loading on a deployed GitHub Pages URL**. Video playback checked at 1440 and 390: readyState 4, playback time advanced from zero.

Fallbacks: poster image for plasma, reduced motion shows static image; energy toggle stops video; link navigation remains available even if JavaScript fails on desktop. Mobile menu uses JS and keyboard Escape; default no-JS mobile navigation should be enhanced when possible.

### Required final checks
Actual screenshots and per-section observations go in `qa/QA_REPORT.md`. Independent reading/real-device testing and browser deployment network checks remain open until performed.
