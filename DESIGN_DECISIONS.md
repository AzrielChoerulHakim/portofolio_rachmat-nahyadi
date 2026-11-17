# DESIGN DECISIONS — RACHMAT NAHYADI

**Design OS:** Lazarus Design OS v4 · **Selected direction:** Thunderline / High Voltage Neon (user-approved)

## Evidence thesis
Site ini adalah editorial dossier pekerjaan hukum: bukti pendidikan, praktik riset/administrasi, dan pengalaman pelayanan publik dibaca terlebih dahulu. Plasma adalah komponen atmosfer, **bukan bukti profesi, kasus nyata, atau simbol lisensi advokat**.

## Seven client-specific structures evaluated

### A — Curriculum index
Reading grammar: Index-scanning: data terurut seperti direktori; keterangan singkat dulu
Order: identitas → ringkasan → pengalaman → pendidikan → kontak
Media: Portrait sebagai metadata visual
Interaction: Penanda section dan pencarian anchor
Tradeoff: Terlalu administratif; kehilangan ekspresi fotografi

### B — Electric editorial dossier
Reading grammar: Editorial headline-led, bukti aktual berurutan, dua kontras tekstur visual
Order: identitas → kompetensi → pengalaman → sisi personal → organisasi → dokumen → kontak
Media: Tiga foto autentik; video plasma sebagai atmosfer non-evidence
Interaction: Nav berjangkar, energy toggle, scroll progress
Tradeoff: Kepadatan visual dapat mengganggu scan bila skala huruf tak dikendalikan

### C — Evidence-first legal ledger
Reading grammar: Kronik bukti, uraian kerja di atas identitas, typographic evidence ledger
Order: pengalaman → dokumen → kompetensi → profil → pendidikan → kontak
Media: Foto kecil berlabel, komposisi dominan teks
Interaction: Expand per pengalaman; tautan sumber nyata
Tradeoff: Keterjangkauan cepat tetapi kurang human touch

### D — Academic trajectory
Reading grammar: Tata baca kronologis dari pendidikan ke kontribusi; numerik dominan
Order: pendidikan → organisasi → pengalaman → kompetensi → kontak
Media: Toga sebagai hero, gambar pendukung kecil
Interaction: Timeline bertahap non-blocking
Tradeoff: Tidak mengutamakan pengalaman kerja paling baru

### E — Public service case notes
Reading grammar: Bacaan problem-solution dalam modul sumber yang tidak diada-adakan
Order: pelayanan hukum → riset hukum → karya/dokumen → profil → kontak
Media: Fotografi publik hanya jika ada; bergantung teks CV
Interaction: Anchor penjelasan area pelayanan dan dokumen
Tradeoff: Tidak ada case studies konkret yang boleh dipublikasikan

### F — Profile as personal photo essay
Reading grammar: Caption-led longform; foto pribadi mendahului kronologi
Order: fotografi → profil → pendidikan → organisasi → pengalaman → kontak
Media: Foto malam / buku / wisuda masing-masing satu chapter
Interaction: Scroll photographic transitions
Tradeoff: Profesionalitas hukum bisa kurang cepat terbaca

### G — Compact hiring brief
Reading grammar: Skim 10-second recruiter flow, informasi tinggi kepadatan
Order: ringkasan keterampilan → pengalaman → pendidikan → organisasi → CV → kontak
Media: Satu portrait, sisa halaman hampir tanpa gambar
Interaction: Sticky contact rail, CV download
Tradeoff: Tidak memanfaatkan brief Thunderline yang eksplisit

## Chosen: B — Electric editorial dossier

Identity thesis: struktur yang menggabungkan headline tegas, bukti terverifikasi, dan blok fotografi yang manusiawi, karena Rachmat mempunyai pengalaman pelayanan dan dokumentasi hukum yang layak dipindai cepat oleh pembaca profesional.

### Specific decisions and limitations
- Open with actual name, current internship status, and law graduate — do not fabricate legal license or case studies.
- Place verified IPK, graduation year and current BAKRI experience in an evidence strip.
- Use original night portrait for hero; graduation and bookshop photos form later chapters. No invented job-photo composites.
- Loop footage precisely 3 seconds. Muted autoplay + WebM/MP4 fallback, pause control and reduced-motion poster.
- Organize experience chronologically; preserve CV for granular details.
- Tone is third-person editorial and still subject to client approval.
- Avoid copy-pasted SaaS cards or tiny mono labels as primary reading content.

## Provenance
All educational, role, date, contact and capability claims originate from the user-provided one-page CV. Photos originate from the three user-supplied photographs. Plasma generated from an original image-generation sequence for this experimental website.
