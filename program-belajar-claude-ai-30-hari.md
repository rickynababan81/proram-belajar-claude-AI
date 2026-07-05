# Program Belajar Menjadi Ahli Claude AI — 30 Hari × 2 Jam/Hari

**Total investasi waktu:** ±60 jam
**Target akhir:** Menguasai Claude dari pengguna dasar hingga level "power user / praktisi ahli" — mampu merancang prompt tingkat lanjut, membangun workflow otomatis, menggunakan Claude Code, dan memahami API + MCP.
**Biaya:** Bisa 100% gratis (semua sumber utama gratis). Opsional: Claude Pro ($20/bulan) sangat disarankan mulai Minggu ke-2.

---

## Peta Kompetensi "Ahli Claude AI"

Seorang ahli Claude AI menguasai 6 pilar berikut. Program 4 minggu ini dibangun di atas peta ini:

1. **Fondasi & AI Fluency** — memahami cara kerja LLM, kemampuan & batasan Claude, model-model Claude (Sonnet, Opus, Haiku, Fable), kapan pakai yang mana, dan framework 4D (Delegation, Description, Discernment, Diligence).
2. **Prompt Engineering** — instruksi yang jelas, pemberian contoh (few-shot), chain-of-thought, role prompting, XML tags, prompt template yang reusable, dan evaluasi kualitas output.
3. **Fitur Produk claude.ai** — Projects, Artifacts, Styles, Memory, Deep Research, web search, analisis file (CSV/PDF/gambar), pembuatan dokumen (Word/Excel/PowerPoint), dan Connectors.
4. **Workflow Profesional** — menerapkan Claude ke pekerjaan nyata: menulis, riset, analisis data, presentasi, email, dan otomasi tugas berulang.
5. **Claude Code & Agentic AI** — coding agent di terminal/desktop, Skills (SKILL.md), subagents, dan Claude Cowork.
6. **Claude API & MCP** — dasar API, tool use, dan Model Context Protocol untuk menghubungkan Claude ke tools eksternal.

---

## Sumber Belajar Utama (Simpan Semua Link Ini)

### Resmi & Gratis dari Anthropic
| Sumber | Link | Keterangan |
|---|---|---|
| **Anthropic Academy** | https://anthropic.skilljar.com | Platform belajar resmi. 14+ kursus gratis, self-paced, video + quiz + **sertifikat resmi** yang bisa dipasang di LinkedIn. Cukup daftar dengan email. Ini tulang punggung program ini. |
| Anthropic Learn Hub | https://www.anthropic.com/learn | Panduan, tutorial, dan best practices |
| Kumpulan kursus di situs Claude | https://claude.com/resources/courses | Learning path dengan video & assessment |
| Dokumentasi Claude API/Platform | https://docs.claude.com | Referensi teknis lengkap |
| Dokumentasi versi Bahasa Indonesia | https://platform.claude.com/docs/id/intro | Docs resmi berbahasa Indonesia |
| Panduan Prompt Engineering resmi | https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview | Wajib dibaca tuntas di Minggu 2 |
| Pusat Bantuan claude.ai | https://support.claude.com | Fitur, limit, dan cara pakai claude.ai |
| Tutorial Interaktif Prompt Engineering (GitHub) | https://github.com/anthropics/prompt-eng-interactive-tutorial | 9 bab latihan langsung, gratis |
| Anthropic Cookbook (GitHub) | https://github.com/anthropics/anthropic-cookbook | Notebook contoh kode API |
| Dokumentasi Claude Code | https://docs.claude.com/en/docs/claude-code/overview | Untuk Minggu 4 |
| YouTube resmi Anthropic | https://www.youtube.com/@anthropic-ai | Demo fitur, tutorial, dan keynote |
| Berita produk | https://www.anthropic.com/news | Untuk update fitur terbaru |

### Kursus Gratis di Platform Lain
- **Coursera** — beberapa kursus Anthropic Academy juga tersedia di Coursera (cari "Anthropic"). Bisa di-audit gratis. Namun rekomendasinya: ambil langsung di anthropic.skilljar.com karena kontennya lebih lengkap, sertifikat gratis, dan lebih cepat di-update.
- **DeepLearning.AI** (https://www.deeplearning.ai/short-courses/) — cari short course bertema Anthropic/MCP/Claude, gratis untuk diikuti.

### Sumber Bahasa Indonesia
- **BuildWithAngga** — "Panduan Lengkap Menggunakan Claude AI untuk Pemula": https://buildwithangga.com/tips/panduan-lengkap-menggunakan-claude-ai-untuk-pemula-dari-nol-sampai-produktif-dalam-1-hari (gratis, sangat bagus untuk Hari 1–3)
- **KelasClaude.com** (https://www.kelasclaude.com) — kursus berbayar berbahasa Indonesia, per profesi (developer, marketing, finance, dll), dilengkapi prompt siap pakai & template. Opsional jika ingin materi lokal terstruktur.
- **FounderPlus** — artikel praktik analisa data dengan Claude Desktop: https://founderplus.id/blog/cara-analisa-data-dengan-claude-desktop/
- **NobleProg Indonesia** (https://www.nobleprog.id/claude-ai-training) — pelatihan live instructor-led (berbayar), opsional untuk perusahaan.

### Catatan tentang Ebook di Tokopedia
Saat ini **belum ada ebook berkualitas berbahasa Indonesia yang khusus membahas Claude secara mendalam** di Tokopedia/Gramedia — sebagian besar hasil pencarian "Claude AI" di Tokopedia adalah **jualan akun premium sharing/"lifetime"**, yang melanggar ketentuan layanan Anthropic dan berisiko akun diblokir. **Hindari membeli akun seperti ini.** Alternatif yang lebih aman:
- Buku umum AI/prompt engineering di Gramedia/Tokopedia (cari kata kunci "prompt engineering" atau "produktif dengan AI") sebagai pelengkap konsep.
- Ebook/kursus digital dari kreator lokal seperti KelasClaude di atas.
- Materi resmi Anthropic Academy — gratis dan jauh lebih dalam daripada ebook mana pun saat ini.

---

# MINGGU 1 — Fondasi & Menguasai claude.ai (Hari 1–7)

**Tujuan:** paham cara kerja Claude, semua fitur claude.ai, dan mulai membiasakan diri memakainya setiap hari.

### Hari 1 — Kenalan Menyeluruh
- **Jam 1:** Daftar akun di https://anthropic.skilljar.com. Mulai kursus **"Claude 101"** (modul 1–2).
- **Jam 2:** Baca artikel BuildWithAngga (link di atas) sampai selesai. Atur akun claude.ai Anda: aktifkan Artifacts, coba dark mode, jelajahi Settings.
- **Tugas:** Tulis 5 hal yang ingin Anda otomatisasi/percepat dengan Claude dalam pekerjaan Anda. Ini akan jadi "proyek pribadi" sepanjang program.

### Hari 2 — Claude 101 & Model-Model Claude
- **Jam 1:** Lanjutkan **Claude 101** (modul 3–4) + kerjakan quiz bawaannya.
- **Jam 2:** Baca perbedaan model di https://docs.claude.com (Models overview) — pahami kapan pakai Sonnet vs Opus vs Haiku. Praktik: berikan 1 pertanyaan yang sama ke model berbeda dan bandingkan hasilnya.
- **Tugas:** Buat tabel perbandingan model versi Anda sendiri (kecepatan, kedalaman, use case).

### Hari 3 — AI Fluency: Framework 4D
- **Jam 1–2:** Mulai kursus **"AI Fluency: Framework & Foundations"** di Anthropic Academy. Fokus pada framework 4D: *Delegation* (tugas apa yang didelegasikan), *Description* (cara mendeskripsikan tugas), *Discernment* (menilai output), *Diligence* (tanggung jawab & etika).
- **Tugas:** Ambil 1 tugas nyata dari pekerjaan Anda, tuliskan analisis 4D-nya sebelum menyerahkannya ke Claude.

### Hari 4 — Selesaikan AI Fluency + Kemampuan & Batasan AI
- **Jam 1:** Selesaikan AI Fluency + quiz → dapatkan **sertifikat pertama Anda**.
- **Jam 2:** Ambil kursus singkat **"AI Capabilities and Limitations"** di Academy. Pahami halusinasi, knowledge cutoff, dan kapan TIDAK memakai AI.
- **Tugas/Quiz mandiri:** Tulis 3 contoh tugas yang sebaiknya tidak didelegasikan penuh ke AI, dan alasannya.

### Hari 5 — Fitur claude.ai: Projects, Styles, Memory
- **Jam 1:** Baca di https://support.claude.com tentang Projects, custom instructions, Styles, dan Memory. Buat **Project pertama** untuk pekerjaan Anda, isi dengan dokumen konteks (profil perusahaan, contoh tulisan Anda, dll).
- **Jam 2:** Praktik: buat 1 custom Style yang meniru gaya menulis Anda. Uji dengan 3 permintaan berbeda.
- **Tugas:** Project Anda harus punya minimal 3 file konteks dan 1 set instruksi kustom.

### Hari 6 — Artifacts & Pembuatan Dokumen
- **Jam 1:** Pelajari Artifacts: minta Claude membuat (a) dokumen laporan, (b) halaman web interaktif sederhana, (c) diagram/visualisasi. Coba edit iteratif ("ubah bagian X").
- **Jam 2:** Coba fitur pembuatan file: minta Claude membuat file Word, Excel, dan PowerPoint dari data/topik pekerjaan Anda, lalu unduh hasilnya.
- **Tugas:** Hasilkan 1 slide deck PowerPoint utuh tentang topik pekerjaan Anda hanya dengan Claude.

### Hari 7 — Review Minggu 1 + Analisis File
- **Jam 1:** Praktik upload & analisis: PDF panjang (minta rangkuman + Q&A), file CSV/Excel (minta insight + chart), dan gambar/screenshot (minta transkripsi/analisis). Ikuti panduan FounderPlus untuk analisa data.
- **Jam 2:** **Quiz mandiri Minggu 1** (kerjakan tanpa melihat catatan, lalu minta Claude menilai jawaban Anda):
  1. Apa perbedaan utama Sonnet, Opus, dan Haiku?
  2. Jelaskan framework 4D dengan contoh nyata.
  3. Kapan sebaiknya memakai Project vs chat biasa?
  4. Apa itu halusinasi dan 2 cara memitigasinya?
  5. Sebutkan 5 fitur claude.ai selain chat teks.
- **Checkpoint:** ✅ 2 sertifikat Academy, ✅ 1 Project aktif, ✅ terbiasa pakai Claude harian.

---

# MINGGU 2 — Prompt Engineering Tingkat Ahli (Hari 8–14)

**Tujuan:** menguasai seni & sains merancang prompt — pembeda terbesar antara pengguna biasa dan ahli.

### Hari 8 — Dasar Prompt yang Efektif
- **Jam 1:** Baca dokumentasi resmi: https://docs.claude.com/en/docs/build-with-claude/prompt-engineering/overview — bagian *Be clear and direct* dan *Use examples (multishot)*.
- **Jam 2:** Latihan: ambil 5 prompt lama Anda yang hasilnya kurang bagus, tulis ulang dengan prinsip "clear & direct + contoh", bandingkan hasilnya.
- **Tugas:** Dokumentasikan before/after di catatan belajar Anda.

### Hari 9 — Tutorial Interaktif Anthropic (Bab 1–4)
- **Jam 1–2:** Kerjakan https://github.com/anthropics/prompt-eng-interactive-tutorial bab 1–4 (struktur prompt, being direct, role prompting, memisahkan data dari instruksi). Tutorial ini punya **exercise + answer key** — kerjakan semua latihannya.

### Hari 10 — Tutorial Interaktif (Bab 5–9)
- **Jam 1–2:** Lanjutkan bab 5–9: output formatting, chain-of-thought ("think step by step"), few-shot examples, menghindari halusinasi, dan complex prompt building.
- **Tugas:** Selesaikan seluruh exercise. Ini setara "ujian tengah program".

### Hari 11 — Teknik Lanjutan: XML Tags, Prefill, Chaining
- **Jam 1:** Baca bagian lanjutan docs prompt engineering: XML tags, system prompts, prefilling, dan prompt chaining (memecah tugas kompleks jadi beberapa langkah).
- **Jam 2:** Praktik: buat 1 prompt kompleks untuk pekerjaan Anda dengan struktur XML (<context>, <instructions>, <examples>, <output_format>).
- **Tugas:** Prompt tersebut harus menghasilkan output konsisten saat dijalankan 3 kali.

### Hari 12 — Membangun Prompt Library Pribadi
- **Jam 1–2:** Buat **library 10 prompt template** untuk tugas rutin Anda (email, laporan, analisis, rangkuman meeting, riset kompetitor, dll). Simpan di Project claude.ai atau dokumen terpisah. Gunakan placeholder seperti [TOPIK], [DATA].
- **Tugas:** Uji minimal 5 template dengan kasus nyata.

### Hari 13 — Riset & Deep Research
- **Jam 1:** Pelajari web search & Deep Research di claude.ai (cek support.claude.com untuk cara pakai & limit). Jalankan 1 Deep Research tentang topik industri Anda.
- **Jam 2:** Latih *discernment*: verifikasi 5 klaim dari hasil riset ke sumber aslinya. Belajar membaca sitasi.
- **Tugas:** Buat laporan riset 1 halaman lengkap dengan sumber.

### Hari 14 — Review Minggu 2
- **Jam 1:** Kerjakan ulang 2 exercise tersulit dari tutorial interaktif tanpa melihat jawaban.
- **Jam 2:** **Quiz mandiri Minggu 2:**
  1. Kapan few-shot examples lebih efektif daripada instruksi panjang?
  2. Apa fungsi XML tags dalam prompt?
  3. Jelaskan chain-of-thought dan kapan memakainya.
  4. Bagaimana cara mengurangi halusinasi lewat prompt? (min. 3 teknik)
  5. Tulis 1 prompt lengkap terstruktur untuk kasus nyata, dan jelaskan setiap komponennya.
- **Checkpoint:** ✅ Tutorial interaktif selesai, ✅ prompt library berisi 10+ template teruji.

---

# MINGGU 3 — Workflow Profesional & Ekosistem Claude (Hari 15–21)

**Tujuan:** mengubah skill menjadi sistem kerja: Connectors, Claude Desktop/Cowork, otomasi, dan use case per profesi.

### Hari 15 — Claude Desktop & Connectors (MCP dari Sisi Pengguna)
- **Jam 1:** Install Claude Desktop. Pelajari Connectors di support.claude.com — hubungkan tool yang Anda pakai (Google Drive, Gmail, dll sesuai kebutuhan).
- **Jam 2:** Praktik: minta Claude mencari & merangkum dokumen dari Drive Anda, atau triase email.
- **Tugas:** Selesaikan 1 tugas kerja nyata end-to-end menggunakan connector.

### Hari 16 — Kursus "Introduction to Claude Cowork"
- **Jam 1–2:** Ambil kursus **Introduction to Claude Cowork** di Anthropic Academy — agen desktop untuk pekerjaan non-coding (mengelola file, riset multi-langkah, membuat deliverable).
- **Tugas:** Delegasikan 1 tugas multi-langkah (misal: "rapikan folder laporan bulanan dan buat rangkuman") dan evaluasi hasilnya.

### Hari 17 — Kursus "Introduction to MCP" (Konseptual)
- **Jam 1–2:** Ambil kursus **Introduction to MCP** di Academy. Fokus memahami konsep: apa itu MCP, tools/resources/prompts, dan kenapa ini penting untuk masa depan AI. (Praktik teknisnya di Minggu 4 — hari ini cukup paham konsep dan bisa memakai MCP server yang sudah jadi.)
- **Tugas:** Tambahkan 1 MCP server/connector baru dan uji kegunaannya.

### Hari 18 — Use Case Mendalam Sesuai Profesi Anda
- **Jam 1–2:** Pilih jalur sesuai pekerjaan Anda dan dalami:
  - *Penulis/Marketing:* content pipeline (riset → outline → draft → edit → repurpose ke berbagai platform).
  - *Analis/Finance:* analisis data CSV → insight → laporan Excel otomatis.
  - *Manajer/Bisnis:* meeting notes → action items → email follow-up → laporan mingguan.
  - *Developer:* langsung mulai materi Claude Code Hari 22 lebih awal.
- **Tugas:** Bangun 1 workflow lengkap (minimal 3 langkah berantai) dan dokumentasikan.

### Hari 19 — Otomasi Tugas Berulang dengan Projects + Template
- **Jam 1:** Gabungkan semuanya: buat 1 Project khusus per workflow (misal "Laporan Mingguan") dengan instruksi kustom + file konteks + prompt template.
- **Jam 2:** Simulasikan pemakaian seminggu: jalankan workflow 3 kali dengan input berbeda, ukur konsistensinya, perbaiki instruksinya.
- **Tugas:** Workflow harus bisa dijalankan orang lain hanya dengan mengikuti dokumentasi Anda.

### Hari 20 — Evaluasi Output & Iterasi (Skill Pembeda Ahli)
- **Jam 1:** Pelajari cara mengevaluasi output secara sistematis: buat rubrik penilaian (akurasi, kelengkapan, tone, format). Minta Claude mengkritik outputnya sendiri dengan rubrik itu.
- **Jam 2:** Teknik iterasi: pelajari pola "draft → critique → revise" dan multi-persona review (minta Claude meninjau dari sudut pandang berbeda).
- **Tugas:** Terapkan siklus ini pada 1 deliverable penting Anda.

### Hari 21 — Review Minggu 3
- **Jam 1:** Rapikan semua workflow & dokumentasi.
- **Jam 2:** **Quiz mandiri Minggu 3:**
  1. Apa perbedaan Claude di web, Desktop, Cowork, dan Code?
  2. Jelaskan konsep MCP dengan analogi sederhana.
  3. Bagaimana struktur Project yang baik untuk workflow berulang?
  4. Sebutkan rubrik evaluasi output yang Anda pakai.
  5. Demonstrasikan 1 workflow Anda dari awal sampai akhir.
- **Checkpoint:** ✅ 2+ sertifikat baru (Cowork, MCP), ✅ 2 workflow terdokumentasi, ✅ connector aktif.

---

# MINGGU 4 — Claude Code, API, & Proyek Akhir (Hari 22–30)

**Tujuan:** menyentuh sisi teknis (bahkan untuk non-programmer, level pemahaman ini yang membedakan "ahli") dan menutup dengan proyek nyata.

### Hari 22 — Claude Code 101
- **Jam 1–2:** Ambil kursus **"Claude Code 101"** di Anthropic Academy (dirancang untuk yang belum pernah pakai coding agent). Install Claude Code: https://docs.claude.com/en/docs/claude-code/overview
- **Tugas:** Jalankan Claude Code pada 1 folder/proyek sederhana, minta ia menjelaskan isi folder dan membuat file baru.

### Hari 23 — Claude Code in Action
- **Jam 1–2:** Lanjutkan kursus **"Claude Code in Action"** di Academy: workflow Explore → Plan → Code, thinking mode vs planning mode, dan CLAUDE.md.
- **Tugas:** Buat proyek kecil (contoh: script otomasi rename file, kalkulator web sederhana, atau generator laporan) sepenuhnya via Claude Code.

### Hari 24 — Agent Skills & Subagents
- **Jam 1:** Kursus **Agent Skills** di Academy: cara menulis SKILL.md, trigger description, dan membagikannya ke tim.
- **Jam 2:** Kursus **Introduction to Subagents**: delegasi tugas ke sub-agen untuk mengelola konteks.
- **Tugas:** Tulis 1 SKILL.md sederhana untuk tugas rutin Anda.

### Hari 25 — Dasar Claude API
- **Jam 1–2:** Mulai kursus **"Building with the Claude API"** di Academy (bagian awal). Buat akun di https://platform.claude.com, pahami: API key, struktur messages, system prompt, max_tokens, dan model string. Non-programmer: cukup pahami konsep + jalankan contoh dari https://github.com/anthropics/anthropic-cookbook
- **Tugas:** Kirim 1 request API pertama Anda (bisa dibimbing Claude langkah demi langkah).

### Hari 26 — API Lanjutan: Tool Use & Vision
- **Jam 1–2:** Lanjutkan kursus API: tool use / function calling, mengirim gambar/PDF via API, dan streaming. Gunakan cookbook sebagai bahan praktik.
- **Tugas:** Buat 1 script sederhana yang memakai tool use (boleh dibuatkan Claude Code — yang penting Anda paham alurnya).

### Hari 27–29 — PROYEK AKHIR (Capstone)
Pilih salah satu (atau sesuai kebutuhan Anda), kerjakan 2 jam/hari selama 3 hari:
- **Jalur Profesional:** Bangun "sistem operasi kerja pribadi" — 3 Project claude.ai lengkap dengan instruksi, prompt library, workflow terdokumentasi, dan 1 SOP yang bisa dipakai tim Anda.
- **Jalur Builder:** Bangun 1 aplikasi/tool fungsional dengan Claude Code (misal dashboard analisis penjualan, chatbot FAQ internal, atau otomasi laporan) + dokumentasinya.
- **Jalur Edukator/Kreator:** Buat mini-course atau panduan "Claude untuk [profesi Anda]" dalam Bahasa Indonesia — ini sekaligus portofolio dan bisa dijual/dibagikan.

Struktur 3 hari: Hari 27 = rancang & mulai bangun; Hari 28 = selesaikan & uji; Hari 29 = poles, dokumentasikan, dan minta Claude melakukan review kritis.

### Hari 30 — Ujian Akhir & Rencana Lanjutan
- **Jam 1:** **Ujian akhir mandiri** — minta Claude membuatkan ujian 20 soal yang mencakup seluruh materi 4 minggu (berdasarkan catatan belajar Anda), kerjakan, lalu minta Claude menilai dan memberi feedback area lemah.
- **Jam 2:** Susun rencana 90 hari berikutnya: sertifikat Academy yang belum diambil, ikuti https://www.anthropic.com/news untuk fitur baru, dan tetapkan 1 target penerapan nyata per bulan.

---

## Checklist Sertifikat Gratis yang Bisa Anda Kumpulkan (Semua dari Anthropic Academy)

- [ ] Claude 101
- [ ] AI Fluency: Framework & Foundations
- [ ] AI Capabilities and Limitations
- [ ] Introduction to Claude Cowork
- [ ] Introduction to MCP
- [ ] Claude Code 101
- [ ] Claude Code in Action
- [ ] Agent Skills
- [ ] Introduction to Subagents
- [ ] Building with the Claude API
- [ ] (Lanjutan) MCP: Advanced Topics

Semua gratis, self-paced, bersertifikat resmi Anthropic yang bisa dipajang di LinkedIn.

---

## Tips Sukses Menjalankan Program Ini

1. **Konsistensi > intensitas.** 2 jam setiap hari jauh lebih efektif daripada 14 jam di akhir pekan.
2. **Belajar sambil mengerjakan pekerjaan nyata.** Setiap latihan di program ini sengaja diarahkan ke tugas Anda sendiri — itulah yang membuat skill menempel.
3. **Buat "learning journal".** Satu dokumen berisi catatan harian, prompt terbaik, dan pelajaran. Di akhir bulan, ini jadi aset berharga.
4. **Materi Academy berbahasa Inggris.** Jika kesulitan, gunakan subtitle otomatis, atau tempel transkrip/materinya ke Claude dan minta dijelaskan dalam Bahasa Indonesia — sekaligus latihan.
5. **Jadikan Claude tutor Anda.** Setiap selesai materi, minta Claude menguji pemahaman Anda dengan pertanyaan. Ini menggandakan retensi.
6. **Hindari akun premium sharing dari marketplace.** Berisiko diblokir dan melanggar ketentuan. Mulai dari akun gratis resmi, upgrade ke Pro jika kebutuhan meningkat.
