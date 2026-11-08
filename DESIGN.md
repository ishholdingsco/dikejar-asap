# DIKEJAR ASAP: Dokumen Desain

> Endless runner satire gelap + horor atmosferik tentang sawit dan karhutla di Indonesia.
> Pemain mengendalikan **korban**. Dunia di sekitarnya berbicara dengan **suara korporat dan pejabat**.

Status: `✅` = sudah ada di prototipe v0.1 · `⏳` = belum · `❓` = belum diputuskan
Cara memberi masukan: tandai ID dengan ✅ pakai / ❌ buang / ✏️ ubah, atau tambah baris baru.

---

## 0. Keputusan inti

| Aspek | Keputusan |
|---|---|
| Judul | **Dikejar Asap** |
| Sudut pandang | Korban: petani kecil bercaping (v0.3; sebelumnya warga desa). Nanti: relawan pemadam, orangutan |
| Suara satire | Korporat dan pejabat lewat ticker, notifikasi, baliho, layar game over |
| Nada | Satire gelap + horor atmosferik. Horor penuh hanya di ISPU "Berbahaya" |
| Pengejar | Api, asap, bulldozer |
| Platform | Web (HTML + Canvas), mobile-first, swipe 4 arah, keyboard, haptic, Web Audio |
| Batasan | Tanpa gore. Tanpa nama perusahaan atau orang nyata. Perusahaan fiktif: **PT Sawit Juga Pohon (SJP)** |
| Fakta nyata di game over | **Ya**, dengan sumber (wajib diverifikasi ulang sebelum rilis) |
| Ditunda | Mode Pelaku ("Direktur"), versi 2 |
| Arah visual | **Kabut** (v0.2): siluet datar berlapis, asap abu-kuning, satu warna merah. Moodboard di `design/` |

---

## A. Premis & Identitas
| ID | Elemen | Status |
|---|---|---|
| A1 | Pemain = petani kecil bercaping (anyaman bambu), kaus lusuh, sarung kotak-kotak di pinggang, ambung rotan di punggung; bertekstur dan disorot api dari belakang | ✅ |
| A2 | PT Sawit Juga Pohon: nama yang membela sawit sebagai "pohon" | ✅ |
| A3 | Judul *Dikejar Asap* | ✅ |
| A4 | Slogan perusahaan: *"Sawit untuk masa depan yang ~~cerah~~ gelap berasap"* | ✅ |
| A5 | Logo daun hijau yang ujungnya terbakar | ⏳ |

## B. Mekanik Inti
| ID | Elemen | Status |
|---|---|---|
| B1 | 3 jalur, swipe kiri/kanan/atas/bawah + keyboard | ✅ |
| B2 | Meteran ISPU naik terus. Di 500, pemain meninggal karena ISPA | ✅ |
| B3 | Endless, tidak bisa dimenangkan | ✅ |
| B4 | Kiri-kanan jalur = sawit monoton dan tunggul terbakar | ✅ |
| B5 | Tersandung dua kali dalam 6 detik = disusul api | ✅ |
| B6 | Hujan sebagai jeda singkat, lalu kemarau tahun berikutnya | ✅ |
| B7 | Kecepatan bertambah seiring waktu | ✅ |

## C. Collectible & Power-up (versi korban)
| ID | Elemen | Status |
|---|---|---|
| C1 | 💧 Botol air: ISPU −2 per botol. Tiap 10 botol muncul satir air bersih (BPBD, kanal SJP, air mineral SJP) | ✅ |
| C2 | 😷 Masker bantuan (langka): ISPU −35. Teks: "1 lembar untuk 1 keluarga. Tidak menyaring PM2.5." | ✅ |
| C3 | 📄 Dokumen tanah adat: koleksi langka, tidak berguna di hadapan hukum | ⏳ |
| C4 | 🏥 Posko darurat: power-up yang tutup saat didatangi | ⏳ |
| C5 | Satwa yang berlari bersamamu dan bisa diselamatkan | ⏳ |

## D. Rintangan
| ID | Elemen | Aksi | Status |
|---|---|---|---|
| D1 | Kayu tebangan | Lompat (kalau tertabrak, tersandung) | ✅ |
| D2 | Spanduk "ZERO BURNING ✓" melintang | Merunduk | ✅ |
| D3 | Bulldozer PT SJP | Pindah jalur (mematikan) | ✅ |
| D3b | Excavator PT SJP yang sedang menggali | Pindah jalur (mematikan) | ✅ |
| D3c | Truk pengangkut sawit PT SJP (bak penuh tandan). Game over: “Batang pohon” hancur terlindas ~~truk~~ sistem | Pindah jalur (mematikan) | ✅ |
| D4 | Gambut terbakar dari dalam (retakan menyala, berasap) | Lompat (mematikan) | ✅ |
| D5 | Kanal pengering yang dibuat perusahaan | Lompat | ⏳ |
| D6 | Pagar konsesi baru di atas tanah adat | ⏳ | ⏳ |
| D7 | Api loncat yang muncul tiba-tiba di depan | ⏳ | ⏳ |

## E. Momen Gelap
| ID | Elemen | Status |
|---|---|---|
| E1 | Satwa panik di pinggir jalur, suaranya berhenti tiba-tiba | ⏳ |
| E2 | Sekolah dengan anak bermasker, menghilang tertutup asap | ⏳ |
| E3 | Rumah panggung yang "tiba-tiba" jadi area konsesi | ⏳ |
| E4 | Burung jatuh dari langit di level Berbahaya | ⏳ |

## F. Teks, UI & Suara Korporat
| ID | Elemen | Status |
|---|---|---|
| F1 | Ticker berita dengan nada makin absurd per level ISPU | ✅ |
| F2 | Notifikasi ala HP: "Saham SJP naik 3%" | ✅ |
| F3 | Kutipan pejabat fiktif di loading screen | ⏳ |
| F4 | Penghitung hotspot satelit yang tidak pernah turun | ✅ |
| F5 | Tombol "Lari Lagi", tanpa tombol berhenti | ✅ |
| F6 | Laporan CSR: "Kami menanam 12 pohon" | ⏳ |
| F7 | Achievement ironis | ⏳ |

## G. Game Over
| ID | Elemen | Status |
|---|---|---|
| G1 | Teks penyebab kematian (ISPA, bulldozer, gambut, spanduk, api) | ✅ |
| G2 | "PT SJP menyampaikan duka cita mendalam dan berkomitmen pada zero burning." | ✅ |
| G3 | Statistik: Jarak · Liter air · Masker · **0 tersangka dari PT SJP · 1 tersangka: “oknum warga” (kamu)** | ✅ |
| G4 | Satu fakta nyata + sumber | ✅ (verifikasi ulang) |
| G5 | Kamera berbalik ke siluet yang tersisa di asap | ⏳ |

## I. Pengejar
| ID | Elemen | Status |
|---|---|---|
| I1 | Api di belakang pemain, naik saat tersandung | ✅ |
| I2 | Bulldozer yang ikut mengejar | ⏳ |
| I3 | Warga & satwa lain yang ikut berlari, satu per satu tumbang dalam asap | ⏳ |

## J. Karhutla
| ID | Elemen | Status |
|---|---|---|
| J1 | Garis api menjalar di samping jalur | ⏳ |
| J2 | Api gambut bawah tanah (= D4) | ✅ |
| J3 | Api loncat (= D7) | ⏳ |
| J4 | Hotspot counter (= F4) | ✅ |
| J5 | Kanal pengering (= D5) | ⏳ |
| J6 | Lapisan warna langit dan kabut per level ISPU | ✅ |
| J7 | Jarak pandang menyusut | ✅ |
| J8 | Matahari jingga lalu merah | ✅ |
| J9 | Nota protes negara tetangga | ✅ (notifikasi) |
| J10 | Pesawat water bombing yang terlambat | ✅ (melintas + notifikasi) |
| J11 | Petugas pemadam dengan alat seadanya | ⏳ |
| J12 | Hujan buatan (TMC): gerimis 2 detik | ⏳ |
| J13 | "Rakor dijadwalkan minggu depan" | ✅ |
| J14 | "Sumber api tidak diketahui" | ✅ |
| J15 | "Lahan terbakar dengan sendirinya" / "oknum warga" | ✅ |
| J16 | Siklus kemarau → hujan → kemarau tahun berikutnya | ✅ |
| J17 | Sekolah diliburkan, penerbangan dibatalkan, saham naik | ✅ |

## K. Tense & Horror
| ID | Elemen | Status |
|---|---|---|
| K1 | Rintangan baru terlihat dari kabut di detik-detik terakhir | ✅ |
| K2 | Siluet manusia di pinggir jalur (hanya ISPU ≥ 300) | ✅ |
| K3 | Langit biru → jingga → merah → gelap | ✅ |
| K4 | Vignette makin pekat, berdenyut dengan detak jantung | ✅ |
| K5 | Bara melayang | ✅ |
| K6 | Retakan merah di tanah gambut | ✅ |
| K7 | Napas makin berat dan cepat | ✅ |
| K8 | Batuk dari arah acak tanpa sumber terlihat | ✅ |
| K9 | Derak api dari belakang | ✅ |
| K10 | Detak jantung di level Berbahaya | ✅ |
| K11 | Pengumuman toa: "warga diimbau tetap di dalam rumah" | ⏳ |
| K12 | Melodi memudar, tinggal dengung | ✅ |
| K13 | Suara burung panik yang berhenti | ✅ (sederhana) |
| K14 | Tokoh menoleh ke belakang ke arah api (kamera belum) | ✅ (sebagian) |
| K16 | Getaran HP saat tersandung / mati | ✅ |
| K18 | Momen sunyi palsu sebelum api loncat | ⏳ |
| K19 | Ticker tetap ceria saat layar paling mengerikan | ✅ |
| K20 | Baliho korporat tersenyum, objek paling jelas dalam kabut | ✅ |
| K21 | Jingle iklan terdistorsi | ⏳ |
| K22 | "Status siaga darurat" muncul setelah game over | ✅ |

---

## Fakta untuk layar game over (G4)

> Dicek ulang 8 November 2026 terhadap artikel sumber. Angka antarsumber dan antartanggal bisa berbeda; sebutkan periode/tanggal bersama angkanya.

1. Sepanjang 2026, 202.010 ha terbakar (SiPongi Kemenhut via GoodStats, 8 Sep 2026). Januari–Juli 2026 naik 69% dari periode sama 2025 (SiPongi via Kompas.com, 3 Okt 2026).
2. 288.540 kasus ISPA di 63 kab/kota per 14 Okt 2026, termasuk 64.913 balita. (Kemenkes via Kumparan)
3. 10,67 juta warga terdampak asap per 27 Agustus 2026. (Kemenkes via Kumparan)
4. Kerugian Januari–Agustus 2026 diperkirakan Rp123,1 triliun. (CELIOS via Betahita, 4 Sep 2026)
5. 2.775 penerbangan domestik terdampak sejak 11 Agustus, per 21 Okt 2026. (Kemenhub via Citra Sumsel) — sumber ini tidak menyebut Malaysia.
6. Hingga akhir Oktober 2026: 20 korporasi (diumumkan 29 Okt) dan 245 orang tersangka. (Bareskrim via Garuda TV)
7. Kalimantan Barat terluas: 38.310 ha; Papua Selatan 25.838 ha. (SiPongi via GoodStats)
8. Pembanding: karhutla 2015 menghanguskan sekitar 2,6 juta ha. (Bank Dunia via BenarNews, 15 Des 2015)
9. Ticker: 21 Agu 2026, 1.842 titik panas di Kalimantan (BNPB via NU Online). Juli 2026 hampir 95 ribu ha dalam sebulan (Katadata). KLIA berasap, rute KL–Singapura (Firefly) ditangguhkan (CNBC Indonesia/Reuters).
