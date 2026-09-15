# Format Baku Isian Kaprodi

[← Panduan Kaprodi](../)

Kolom = label isian di layar. Urutan isi: **1 Prodi → 2 Rumpun → 3 CPL → 4 Ritme mingguan → 5 Kalender semester**. Versi CSV tiap tabel: [prodi.csv](prodi.csv) · [rumpun.csv](rumpun.csv) · [cpl.csv](cpl.csv) · [ritme-mingguan.csv](ritme-mingguan.csv) · [kalender-semester.csv](kalender-semester.csv).

## 1. Program Studi

Kurikulum › 1. Program Studi › **Simpan Prodi**

| Nama | Jenjang | Total SKS | Jumlah semester | Proyek kerja mulai semester |
|---|---|---|---|---|
| Teknologi Rekayasa Perangkat Lunak | Sarjana Terapan · KKNI Level 6 | 145 | 8 | 5 |

## 2. Rumpun Mata Kuliah

Kurikulum › 2. Rumpun Mata Kuliah › **Simpan Rumpun** — satu baris per rumpun. Jumlah SKS mata kuliah = SKS rumpun.

Contoh rumpun ritme mingguan:

* **Kode rumpun:** R1
* **Nama rumpun:** Literasi & Wirausaha Digital
* **Semester:** 1 · **SKS:** 6 · **Moda:** Ritme mingguan
* **Proyek pengikat:** Portofolio digital profesional + rencana usaha berbasis teknologi
* **Mata kuliah** (satu per baris, SKS dalam kurung):
  ```
  Literasi Digital (3)
  Kewirausahaan (3)
  ```
* **Kode CPL yang disentuh:** CPL02, CPL03, CPL04, CPL08, CPL11
* **Catatan status:** *(kosong = disahkan)*

Contoh rumpun tempat kerja:

* **Kode rumpun:** R11
* **Nama rumpun:** Produk & Mutu
* **Semester:** 5 · **SKS:** 10 · **Moda:** Tempat kerja
* **Proyek pengikat:** Produk perangkat lunak utuh di tempat kerja mahasiswa + suite pengujian
* **Mata kuliah:**
  ```
  Proyek Perangkat Lunak 1 (4)
  Pemrograman Web (3)
  Pengujian PL (3)
  ```
* **Kode CPL yang disentuh:** CPL05, CPL06, CPL07, CPL09, CPL10
* **Catatan status:** *(kosong)*

Bentuk tabelnya (satu baris per rumpun) ada di [rumpun.csv](rumpun.csv). Moda: `Ritme mingguan` / `Tempat kerja`. Catatan status terisi = rumpun berstatus draf.

## 3. Capaian Pembelajaran (CPL)

Kurikulum › 3. Capaian Pembelajaran › **Simpan CPL** — satu baris per CPL. Deskripsi disalin dari dokumen kurikulum prodi.

| Kode | Domain | Deskripsi | Rumpun penyentuh |
|---|---|---|---|
| CPL01 | Sikap | *(rumusan CPL)* | |
| CPL02 | Pengetahuan | *(rumusan CPL)* | R1, R2, R3 |
| CPL05 | Keterampilan khusus | *(rumusan CPL)* | R5, R6 |
| CPL09 | Keterampilan umum | *(rumusan CPL)* | R11, R12 |

Domain: `Sikap` / `Pengetahuan` / `Keterampilan umum` / `Keterampilan khusus`.

## 4. Ritme Mingguan

Kurikulum › 4. Ritme Mingguan › **Simpan Ritme** — tujuh baris, satu per hari. Menit = menit instruksional (jam kotor dikurangi ibadah, makan, jeda).

**Nama ritme:** Ritme TRPL — Semester 1-6

| Hari | Moda | Jam mulai | Jam selesai | Menit | Catatan |
|---|---|---|---|---|---|
| Senin | Belajar mandiri (asinkron) | 17:00 | 21:00 | 210 | |
| Selasa | Belajar mandiri (asinkron) | 17:00 | 21:00 | 210 | |
| Rabu | Belajar mandiri (asinkron) | 17:00 | 21:00 | 210 | |
| Kamis | Kelas daring bersama dosen | 17:00 | 22:00 | 270 | |
| Jumat | Praktik & proyek (luring atau daring) | 08:00 | 20:00 | 540 | Jeda Jumatan & makan 11:30-13:00 tidak dihitung |
| Sabtu | Tanpa kegiatan akademik | | | 0 | |
| Minggu | Tanpa kegiatan akademik | | | 0 | |

Total 1440 menit/minggu · kapasitas 16,9 SKS per semester (menit ÷ 85).

## 5. Kalender Semester

Kalender › **Buat Draft Kalender** › **Buat Draft**, lalu **Sunting Sesi** bila perlu, lalu **Terbitkan Kalender Ini**.

| Program studi | Angkatan (tahun masuk) | Semester | Tanggal mulai | Jumlah minggu | Ritme mingguan |
|---|---|---|---|---|---|
| TRPL | 2026 | 1 | 2026-09-21 | 16 | Ritme TRPL — Semester 1-6 |

Hasilnya: 16 minggu × 7 hari = 112 sesi, tanggal/moda/jam dari ritme, minggu 1 dimulai hari Senin pada pekan tanggal mulai. Contoh lengkap 112 baris: [kalender-semester.csv](kalender-semester.csv). Minggu pertama (minggu berikutnya sama, tanggalnya bergeser tujuh hari):

| Tanggal | Hari | Moda | Jam |
|---|---|---|---|
| 2026-09-21 | Senin | Belajar mandiri (asinkron) | 17:00–21:00 |
| 2026-09-22 | Selasa | Belajar mandiri (asinkron) | 17:00–21:00 |
| 2026-09-23 | Rabu | Belajar mandiri (asinkron) | 17:00–21:00 |
| 2026-09-24 | Kamis | Kelas daring bersama dosen | 17:00–22:00 |
| 2026-09-25 | Jumat | Praktik & proyek (luring atau daring) | 08:00–20:00, keterangan *Jeda Jumatan & makan 11:30-13:00 tidak dihitung* |
| 2026-09-26 | Sabtu | Tanpa kegiatan akademik | — |
| 2026-09-27 | Minggu | Tanpa kegiatan akademik | — |

Yang bisa diubah per sesi selagi draf: Tanggal, Moda, Mulai, Selesai, Keterangan (maks. 300 karakter). Satu prodi + angkatan + semester = satu kalender.
