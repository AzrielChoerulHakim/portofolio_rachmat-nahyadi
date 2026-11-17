# RACHMAT NAHYADI — TYPE SPEC

## Reading brief
Recruiter or professional reviewer should recognize **name, actual current role, degree, recent experience and contact** immediately. Source: CV RACHMAT NAHYADI.pdf (1 page). Intended language Bahasa Indonesia with selectively technical bilingual descriptors, no invented personal quotations.

## Three monochrome same-copy specimens
See [`docs/type-specimens.html`](docs/type-specimens.html). Each variation uses this **exact** verified sample:

> RACHMAT NAHYADI — S1 Ilmu Hukum UIN Syarif Hidayatullah Jakarta. IPK 3.88/4.00. Legal Assistant (Secretary), BAKRI. April 2026 — Sekarang.

- **A, index:** dense professional list, optimized comparison; rejected for limited visual character.
- **B, expressive dossier (chosen):** large condensed name plus conventional detail lines; balances scan speed and energy.
- **C, running note:** reading-first introduction; rejected because recruiter must search harder for the current role.

## Type roles
| Role | Face and fallback | Visual role | Responsive safeguard |
| --- | --- | --- | --- |
| Name and chapter heads | Barlow Condensed 800–900 / Impact / Arial Narrow | Scale and recognizability | Smaller tracking/font sizes at 320/390; no JS-replaced text |
| Human-readable narrative | IBM Plex Sans 400–600 / Arial | Main reading content | 15–18px, 1.5–1.8 leading, width-limited prose |
| Dates and metadata | IBM Plex Mono / monospace | Comparability, explicit provenance | Short labels; avoid depending on 9px captions for essential data |
| Buttons and nav | IBM Plex Mono / monospace | Usable affordances | Keyboard focus visible; mobile menu at <=850 |

Google Fonts stylesheet loads webfonts externally; no font binary is redistributed. Their foundry licensing must be kept under review. Fallbacks are built into CSS. Captions use responsive scaling; actual CV facts must stay in body text as well.

## QA observations
At 320, 390, 640, 768, 1024, 1440px, initial overflow was identified in the large chapters and corrected through specific breakpoint rules. Fallback font testing was performed because remote fonts are blocked in the automated Chromium environment. **200% text-only enlargement, spacing override and independent legibility review remain not verified**, so no full Typography QA approval is claimed.
