# CSL DSI UNDIP

**Citation Style Language (CSL)** tidak resmi untuk Program Doktor Sistem Informasi (DSI) Universitas Diponegoro. Modifikasi APA 7th Edition berbahasa Indonesia. Dapat digunakan dengan **Zotero** dan **Mendeley**.

---

## Fungsi

Style ini dirancang untuk:

- **Format sitasi dan daftar pustaka** disertasi DSI UNDIP sesuai standar APA 7th yang dimodifikasi untuk Bahasa Indonesia
- **Otomatisasi sitasi** saat menulis di Microsoft Word, LibreOffice, atau Google Docs dengan Zotero/Mendeley
- **Konsistensi format** penulisan referensi (buku, jurnal, prosiding, tesis, dll.) dalam satu dokumen

---

## Fasilitas

### Sitasi In-Text

| Fitur | Keterangan |
|------|------------|
| **Format kurung (parenthetical)** | `(Penulis, Tahun)` — sitasi di dalam kurung |
| **Format naratif (narrative)** | `Penulis (Tahun)` — nama penulis di awal kalimat |
| **Disambiguasi tahun** | Penulis sama + tahun sama → suffix a, b, c (urut alfabet judul) |
| **Disambiguasi nama** | Nama belakang sama, orang beda → tambah inisial (J. Ma vs S. Ma) |
| **Multi-sitasi** | Beberapa referensi dalam satu kurung diurutkan otomatis |

### Daftar Pustaka

| Tipe dokumen | Format |
|--------------|--------|
| Buku | Penulis (Tahun). *Judul*. Edisi. Penerbit. |
| Artikel jurnal | Penulis (Tahun). Judul artikel. *Nama Jurnal*. Vol. X (N), halaman. |
| Bab buku / Prosiding | Penulis (Tahun). Judul bab. Dalam Editor (Ed.), *Judul Buku* (hlm. X–Y). Penerbit. |
| Tesis / Disertasi | Penulis (Tahun). Judul. Tesis/Disertasi. Universitas. |

### Istilah Bahasa Indonesia

- **dkk.** (dan kawan-kawan) — untuk 3+ penulis
- **dan** — untuk 2 penulis
- **hlm.** — halaman
- **Vol.** — volume (dicetak miring)
- **ed.** / **eds.** — editor
- **dalam** — in (untuk bab dalam buku)

---

## Cara Penggunaan

### 1. Instalasi

1. Unduh file `dsi-undip-v1.csl`
2. **Zotero:** Buka Zotero → Edit → Preferences → Cite → Get Additional Styles → + (tambah) → pilih file `.csl`
3. **Mendeley:** Buka Mendeley → View → Citation Settings → Get More Styles → import file `.csl`

### 2. Memilih Style

- **Zotero:** Di Word/Google Docs, pilih style "DISERTASI DSI UNDIP v1 (Unofficial)" dari dropdown style
- **Mendeley:** Pilih "DISERTASI DSI UNDIP v1 (Unofficial)" di Citation Settings

### 3. Menyisipkan Sitasi (Format Kurung)

1. Letakkan kursor di tempat sitasi
2. Klik **Add/Edit Citation** (Zotero) atau **Insert Citation** (Mendeley)
3. Cari dan pilih referensi
4. Hasil: `(Penulis, 2025)` atau `(Penulis dkk., 2025)`

### 4. Format Naratif dengan Omit Author

Untuk sitasi di **awal kalimat** (format naratif: *Penulis (Tahun) menyatakan...*):

1. **Ketik nama penulis** di awal kalimat (misalnya: `Yamsa-ard dkk.` atau `Ma dan Pu`)
2. Letakkan kursor setelah nama
3. Sisipkan sitasi seperti biasa
4. **Edit sitasi** → centang **"Omit Author"** (atau "Suppress Author")
5. Klik OK

**Lokasi Omit Author:**

- **Word (Zotero):** Klik sitasi → klik kanan → **Edit Citation** → centang **Omit Author**
- **Google Docs:** Klik sitasi → ikon pensil (Edit) → centang **Omit Author**
- **LibreOffice:** Klik sitasi → klik kanan → **Edit Citation** → centang **Omit Author**

Hasil: `Yamsa-ard dkk. (2025) menyatakan...`

### 5. Membuat Daftar Pustaka

- **Zotero:** Insert Bibliography (biasanya otomatis muncul di akhir dokumen)
- **Mendeley:** Insert Bibliography

---

## Contoh Hasil Sitasi

### Format Kurung (Parenthetical)

| Jumlah penulis | Contoh |
|----------------|--------|
| 1 penulis | (Yamsa-ard, 2025) |
| 2 penulis | (Yamsa-ard dan Masri, 2025) |
| 3+ penulis | (Yamsa-ard dkk., 2025) |
| Disambiguasi tahun | (Ma, 2024a); (Ma, 2024b) |
| Disambiguasi nama | (J. Ma dkk., 2025) vs (S. Ma dkk., 2025) |
| Multi-sitasi | (Ma, 2024; Pu dan Fu, 2023; Yamsa-ard dkk., 2025) |

### Format Naratif (Narrative)

| Jumlah penulis | Contoh |
|----------------|--------|
| 1 penulis | Yamsa-ard (2025) menyatakan... |
| 2 penulis | Yamsa-ard dan Masri (2025) menyatakan... |
| 3+ penulis | Yamsa-ard dkk. (2025) menyatakan... |

---

## Contoh Daftar Pustaka

### Buku

> Ma, J., Pu, H., dan Fu, L. (2025). *Sistem informasi manajemen*. Ed. ke-3. Penerbit Undip.

### Artikel Jurnal

> Mnih, V., Kavukcuoglu, K., Silver, D., Rusu, A. A., Veness, J., Bellemare, M. G., Graves, A., Riedmiller, M., Fidjeland, A. K., Ostrovski, G., Petersen, S., Beattie, C., Sadik, A., Antonoglou, I., King, H., Kumaran, D., Wierstra, D., Legg, S., dan Hassabis, D. (2015). Human-level control through deep reinforcement learning. *Nature*. Vol. 518 (7540), 529–533.

### Bab dalam Buku / Prosiding

> Smith, J. (2024). Metode penelitian kualitatif. Dalam A. Brown dan C. Davis (Eds.), *Handbook of research methods* (hlm. 45–67). Academic Press.

### Tesis / Disertasi

> Wijaya, A. (2024). Analisis penerapan blockchain dalam supply chain. Disertasi. Universitas Diponegoro.

---

## Kredit

- **Dikembangkan oleh:** Moch Saiful Umam  
- **Sumber:** https://github.com/vpslabs/csl-dsi-undip  
- **Lisensi:** CC BY-SA 3.0
