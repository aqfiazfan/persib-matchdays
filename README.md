# Persib Bandung — Matchday Dashboard

**Satu abad data pertandingan Persib Bandung dalam satu halaman interaktif.**

🔗 **Live:** [aqfiazfan.github.io/persib-matchdays](https://aqfiazfan.github.io/persib-matchdays/)

---

## Tentang Proyek

Dashboard ini mengompilasi **1.277+ pertandingan resmi** Persib Bandung dari tahun 1933 hingga 2026, mencakup era Stedenwedstrijden kolonial, Perserikatan amatir, Liga Indonesia profesional, hingga era Liga 1 modern.

Tujuan proyek ini adalah menyajikan sejarah panjang klub sepak bola tertua dan tersukses di Indonesia dalam format visual yang mudah dipahami siapapun — bukan hanya para penggemar data.

---

## Isi Database

| Kategori | Detail |
|---|---|
| **Total Pertandingan** | 1.277+ laga resmi |
| **Rentang Waktu** | 1933 – 2026 (92+ tahun) |
| **Total Gol Dicetak** | 1.944+ |
| **Total Gol Kebobolan** | 1.283+ |
| **Win Rate** | ~48% |
| **Era Tercakup** | Stedenwedstrijden, Perserikatan, Liga Indonesia, ISL, Liga 1 |

### Era Kompetisi

| Era | Tahun | Keterangan |
|---|---|---|
| Stedenwedstrijden | 1933–1939 | Liga antar kota era kolonial Belanda |
| Kejurnas PSSI (Perserikatan) | 1951–1978 | Kompetisi amatir nasional PSSI |
| Divisi Utama PSSI | 1979–1994 | Transisi ke era semi-profesional |
| Liga Indonesia (Profesional) | 1994–2008 | Era profesional pertama |
| Liga Super Indonesia (ISL) | 2008–2015 | Indonesian Super League |
| Torabika Soccer Championship | 2016 | Kompetisi transisi |
| Liga 1 | 2017–sekarang | Liga profesional modern |
| AFC Champions League | Berbagai tahun | Kompetisi kontinental |

---

## Fitur Dashboard

### 📊 Visualisasi Interaktif
- **Hero Monument** — Angka utama 1.277 pertandingan dalam tampilan dramatis
- **Peta Performa Dekade** — Bubble chart serangan × pertahanan × hasil per dekade
- **Menang/Seri/Kalah per Dekade** — Stacked bar chart historis
- **Gol Dicetak vs Kebobolan** — Line chart per dekade
- **Pertandingan per Tahun Kalender** — Line chart distribusi waktu

### 🏠 Analisis Bermain
- **Kandang vs Tandang** — Perbandingan win rate, gol, dan clean sheet
- **Distribusi Skor** — Grid interaktif skor terpopuler dengan filter W/D/L

### 🏆 Rival & Pemain
- **15 Rival Terbesar** — Kartu rivalitas dengan H2H record
- **Top Scorer** — Daftar pencetak gol terbanyak era profesional
- **Spotlight David da Silva** — Profil top scorer Liga 1

### 🔍 Database Lengkap
- Tabel 1.277+ pertandingan yang bisa dicari dan difilter
- Filter berdasarkan tahun, kompetisi, hasil (W/D/L), kandang/tandang
- Tampilan musim yang benar (2025/2026 bukan hanya "2026")

---

## Sumber Data

| Sumber | Coverage | Keterangan |
|---|---|---|
| **RSSSF** (rsssf.org) | 1933–2024 | Sumber primer — arsip statistik sepak bola dunia |
| **Soccerway** | 2009–2026 | Verifikasi dan data musim modern |
| **persibhistory.wordpress.com** | Berbagai era | Arsip sejarah komunitas |
| **museumpersib.blogspot.com** | Berbagai era | Dokumen historis |
| **arsipsepakbolaindonesia.com** | Era 1990-an | Data Liga Indonesia awal |
| **liga 90-an.txt** (manual) | 1994–2000 | Data Liga Indonesia dikumpulkan manual |
| **Soccerway squad stats** | 2025/26 | Data top scorer dan assist musim terkini |

### ⚠️ Catatan Akurasi
- Data **pencetak gol** hanya tersedia untuk era modern (∼2000-an ke atas)
- Data **era Perserikatan** (1951–1994) hanya mencakup babak final nasional, bukan semua ronde regional
- Tahun **1996**, **1997**, **1998** belum lengkap karena keterbatasan sumber
- Pertandingan **1969-71** (Persib ikut turnamen) tidak memiliki data hasil individual

---

## Teknologi

| Komponen | Detail |
|---|---|
| **Frontend** | Vanilla HTML, CSS, JavaScript — tanpa framework |
| **Charts** | Chart.js (inlined, no CDN) |
| **Data** | JSON embedded dalam HTML (`<script id="dashboard-data">`) |
| **Hosting** | GitHub Pages (static) |
| **Fonts** | Playfair Display (Google Fonts) |

---

## Struktur File

```
persib-matchdays/
├── index.html              # Dashboard utama (semua-dalam-satu)
├── persib_matches.json     # Raw match database (RSSSF format)
├── persib_players_curated.json  # Data pemain dan top scorer
├── *.png / *.svg / *.jpeg  # Logo-logo rival
├── persib_header.png       # Header banner
├── Logo persib.png         # Logo utama Persib
└── David Da Silva.png      # Foto spotlight
```

---

## Statistik Menarik

- **Kemenangan terbesar:** Persib 8-0 Perssi Sukabumi (1957)
- **Kekalahan terbesar:** Sriwijaya 6-0 Persib (2011)
- **Skor agregat tertinggi:** 9 gol dalam 1 laga (7-2 vs Persit Tjiamis 1951 & 8-1 vs PSMS 1957)
- **Tahun tersibuk:** 2016 — 46 pertandingan
- **Win rate kandang:** 66% | **Win rate tandang:** 29%
- **Gelar nasional:** 10 trofi (5 Perserikatan + 1 Liga Indonesia + 1 ISL + 3 Liga 1)
- **Hattrick juara Liga 1:** 2023/24, 2024/25, 2025/26

---

## Lisensi

Data RSSSF digunakan sesuai ketentuan mereka untuk keperluan non-komersial.
Proyek ini dibuat untuk tujuan edukasi dan dokumentasi sejarah sepak bola Indonesia.

---

*Dibuat dengan ❤️ untuk komunitas Bobotoh dan pencinta sejarah sepak bola Indonesia.*
*Last updated: Mei 2026*
