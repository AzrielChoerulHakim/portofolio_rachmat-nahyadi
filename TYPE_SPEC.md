# Typography Direction / Rachmat Nahyadi

## Reading needs
A recruiter or professional reader should recognize Rachmat's name, legal degree, real experience, and contact actions rapidly. Dense CV descriptions need clear paragraph widths; dates and positions must not be buried in atmospheric styling. Bahasa Indonesia is the primary language, with selective English art-direction labels that do not conceal facts.

## Three same-copy monochrome specimens
Visual comparison source: `type-specimens.html` (same verified text in three structural compositions; no imagery or neon colors).

- **A / Formal dossier**: small sober display, section labels, evenly spaced annotations. Advantage: restrained and trustworthy. Risk: generic institutional CV and weak character.
- **B / Name-led editorial (selected)**: high contrast large condensed display, source-backed metadata below, short reading columns. Advantage: memorable first encounter without losing facts. Risk: must reflow for long names on narrow widths.
- **C / Experience-led index**: places BAKRI internship first and name second, chronological accents. Advantage: fast experience discovery. Risk: obscures personal identity as a portfolio landing.

## Type system selected
- Display: Barlow Condensed 800–900 (Google Fonts, open-source SIL OFL), fallback Impact / Arial Narrow / sans-serif. For identity and evidence headings, not body paragraphs.
- Reading: IBM Plex Sans 400–700 (IBM Plex, open-source SIL OFL), fallback Arial / sans-serif. Body around 15–18 CSS px with 1.6–1.8 line-height and controlled widths of roughly 50–65 characters where practical.
- Technical labels: IBM Plex Mono 500 (IBM Plex, SIL OFL), fallback monospace; labels are secondary and never the sole carriers of critical information.
- Use proportional figures in narrative, tabular numerals where aligned data appears. IPK `3.88/4.00` retained exactly from CV.
- Display tracking approximately −0.035 to −0.057em and narrow width are confined to large contexts; body uses normal tracking. Verify fallback metrics.
- For mobile, display font uses viewport-aware sizing and section-specific recomposition. Long employer names wrap naturally, not clipped or replaced with ellipses.
- Every meaningful word remains semantic HTML, selectable and indexable.

## Pending browser release checks
Inspect 320/390/640/768/1024/1440, short landscape, 200% text, 320px-equivalent reflow, text-spacing override, contrast states, missing font and keyboard focus. No browser QA pass should be claimed without real screenshots and notes.