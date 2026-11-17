# Mobile composition / planned review

Reading sequence: header identity → hero name/role/profile line → education/IPK/professional evidence → practice capabilities → verified timeline → reading photo → organization record → external portfolio document → contacts.

Actual section IDs: `top`, `profil`, `kompetensi`, `pengalaman`, `interlude-title` (interlude section), `beyond-title` (beyond section), `portfolio-title` (portfolio section), `kontak`.

Risk areas: very long name/degree titles at 320, photo crossing hero text, plasma behind metadata, fixed header covering anchor targets, timeline employer names wrapping, external links becoming too narrow, footer email wrapping, image focal crop at 390 and below.

Mitigations: viewport-specific font sizing, dark overlay behind copy, single-column recomposition for most content below 650px, natural employer-name wrapping, two-column contact grid becoming single column below 380px; pause control and reduced-motion poster fallback. Mobile photograph crops prioritise recognizable subject and do not conceal essential text. Test every real section at 320/390 before release.

Current status: implementation prepared; visual browser verification not yet complete.