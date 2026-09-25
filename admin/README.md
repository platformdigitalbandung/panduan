# Panduan Admin

[← Semua panduan](../)

Panduan ini untuk super admin platform. **Admin hanya menyiapkan**: membuat program studi baru, menetapkan kaprodinya, dan mengelola pengguna, lalu boleh membuka laporan semua prodi. Kurikulum, kalender, kelas (termasuk menunjuk pengajarnya), kuis, dan materi prodi dijalankan kaprodi masing-masing ([Panduan Kaprodi](../kaprodi/)). Persiapan semester tiap prodi (kalender, kelas, pengajar, peserta) bisa Anda lihat tanpa mengubahnya: menu **Kelas** → pilih program studi (pilihan ini tampil selama Anda tidak mengajar kelas) → halaman **Siapkan Semester** prodi itu.

Admin juga harus terdaftar sebagai dosen aktif. **Tidak ada pemilih peran** (sejak 26 September 2026): menu admin tampil sebagai bagian **Admin** di samping menu dosen (dan bagian **Prodi** bila Anda juga kaprodi).

**Daftar isi:** [Menu](#menu) · [Beranda](#beranda) · [Kelola pengguna](#kelola-pengguna) · [Menyiapkan prodi baru](#menyiapkan-prodi-baru) · [Kelola kaprodi](#kelola-kaprodi) · [Laporan semua prodi](#laporan-semua-prodi) · [Daftarkan dosen](#mendaftarkan-nomor-dosen-lewat-whatsapp) · [Di luar aplikasi](#yang-dikerjakan-di-luar-aplikasi) · [Kendala](#kendala-umum)

## Menu

| Tempat | Isi |
|---|---|
| Bilah atas (layar lebar) | Beranda · Kelas · Jadwal · **Admin** · **Lainnya** |
| Bilah bawah (HP) | Beranda · Kelas · Jadwal · **Menu** (lembar berisi bagian Admin dan Lainnya) |
| **Admin** | Pengguna, Kelola kaprodi, Program studi baru, Pantau proyek kerja, Laporan kepatuhan, Rekap rapor angkatan, Rekap rekaman |

## Beranda

Judulnya **Hari ini**.

* **Langkah yang belum selesai → Penyiapan platform**
  1. **Tetapkan kaprodi tiap prodi** → *Kelola kaprodi*
  2. **Pastikan dosen mengisi email kampus** → *Lihat daftar dosen*
* **Perlu dikerjakan** — prodi yang belum punya kaprodi (**Mendesak**), prodi yang masih memakai data kaprodi lama, dan jumlah dosen aktif yang belum mengisi email kampus.
* **Penyiapan program studi** (kolom samping) — semua prodi beserta kaprodinya, atau tanda **Belum ada kaprodi**.

## Kelola Pengguna

Menu **Pengguna**. Dua tab: **Mahasiswa** dan **Dosen**. Admin mengelola semua prodi.

### Tab Mahasiswa

* **Cari Mahasiswa** — pilih **Program studi** (atau *(semua)*), isi **Angkatan** dan/atau **NIM atau nama**, lalu **Tampilkan**. Kolom **Kata sandi** menunjukkan *kata sandi awal* (belum pernah diganti) atau *sudah diganti*.
* **Ubah** pada baris membuka formulir **Ubah Mahasiswa**; **Simpan Perubahan** memperbarui data (NIM tidak bisa diubah).
* **Reset kata sandi** mengembalikan kata sandi mahasiswa itu ke kata sandi awal (bagian email sebelum @ + `ADB`, atau NIM + `ADB` bila emailnya kosong).
* **Tambah Mahasiswa** — isi NIM, Nama, Nomor WhatsApp, Email, Program studi, Angkatan, Semester, Status, lalu **Tambah Mahasiswa**. Nomor boleh ditulis `08…`, `8…`, atau `62…`; tersimpan sebagai `62…`. Email menentukan kata sandi awal.
* **Impor dari Excel** — salin baris dari Excel/Google Sheets (kolom berurutan: NIM, Nama, Nomor WhatsApp, Email, Prodi, Angkatan, Semester), tempel di **Baris**, isi bawaan prodi/angkatan/semester, lalu tekan **Periksa**. Tabel pratinjau menampilkan nomor yang sudah dibakukan dan menandai baris bermasalah (mis. nomor tampil sebagai `6.28E+12` — format kolom nomor di Excel sebagai **teks** lalu salin ulang). Tekan **Simpan N Mahasiswa** untuk menyimpan baris yang siap.

### Tab Dosen

* **Tambah Dosen** — isi **Nomor WhatsApp** dan **Nama lengkap**, lalu **Tambah Dosen**. Dosen baru langsung aktif; email kampusnya diisi dosen sendiri. Nomor yang pernah dinonaktifkan diaktifkan kembali lewat formulir ini.
* **Semua Dosen** — cari dengan nama, email, atau nomor. Aksi per baris:
  * **Reset kata sandi** — kembali ke kata sandi awal (bagian email kampus sebelum @ + `ADB`). Tidak tampil untuk dosen yang belum mengisi email kampus.
  * **Ubah** — nama dan nomor WhatsApp (email tidak bisa diubah di sini; dosennya sendiri yang mengisi).
  * **Jadikan admin** / **Cabut admin** — hanya untuk dosen aktif. Admin aktif terakhir tidak bisa dicabut. Label perannya berubah setelah ia keluar lalu masuk lagi.
  * **Nonaktifkan** / **Aktifkan** — dosen nonaktif kehilangan semua perannya (dosen, kaprodi, admin) dan tidak bisa masuk dengan cara apa pun. Anda tidak bisa menonaktifkan diri sendiri, dan admin aktif terakhir tidak bisa dinonaktifkan.
* **Riwayat Jabatan Admin** — siapa menetapkan atau mencabut admin siapa, dan kapan.

## Menyiapkan prodi baru

### 1. Buat program studi

Menu **Admin → Program studi baru** (halaman Kurikulum Program Studi). Di halaman itu admin hanya melihat kartu **Program Studi**.

1. Periksa tabel prodi yang sudah ada supaya kodenya tidak kembar.
2. Di **Tambah program studi baru**, isi:
   * **Kode** — mis. `pai`: huruf kecil, angka, atau tanda hubung; 2–20 karakter; diawali huruf. **Kode menjadi kunci** di rumpun, CPL, mata kuliah, roster, dan kalender, jadi pilih dengan cermat dan jangan diubah sesudahnya.
   * **Nama**, **Jenjang** (bawaan S1), **Total SKS** (bawaan 144), **Jumlah semester** (1–14, bawaan 8), **Proyek kerja mulai semester** (0 = bawaan semester 4).
3. Tekan **Simpan Prodi**.

Admin tidak bisa mengubah prodi yang sudah ada (kecuali ia sendiri kaprodi prodi itu).

### 2. Tetapkan kaprodinya

Lanjutkan ke [Kelola Kaprodi](#kelola-kaprodi). Setelah itu rumpun, CPL, ritme, kalender, dan pengajar kelas diisi kaprodi tersebut.

## Kelola Kaprodi

Menu **Admin → Kelola kaprodi**.

### Menetapkan atau mengganti

1. Di tabel **Kaprodi per Program Studi**, cari baris prodinya.
2. Pilih dosen di kolom **Tetapkan kaprodi** (tampil sebagai *Nama · email*).
3. Tekan **Tetapkan** (prodi tanpa kaprodi) atau **Ganti**, lalu konfirmasi.
4. Tampil *Kaprodi &lt;prodi&gt; kini &lt;dosen&gt;*.

### Mengosongkan

Tekan **Kosongkan** pada baris prodi, lalu konfirmasi. Kaprodi itu kembali menjadi dosen biasa untuk prodi tersebut. Selama kosong, laporan prodi itu hanya bisa dibuka admin.

### Aturan

* **Dosen yang belum mengisi email kampus tidak bisa dipilih.** Mereka dirangkum di lipatan *N dosen aktif belum mengisi email kampus*. Minta mereka mengisinya di halaman **Roster & Email Dosen**.
* Satu prodi hanya punya satu kaprodi. Menetapkan kaprodi baru otomatis mengembalikan kaprodi lama menjadi dosen biasa untuk prodi itu.
* Satu dosen boleh sekaligus kaprodi dan admin.
* **Kapan berlaku:** akses laporan prodi berubah **seketika**. Bagian **Prodi** di menunya muncul saat halaman dimuat ulang; label perannya baru berubah setelah ia **keluar lalu masuk lagi** — sampaikan hal ini kepadanya.

## Laporan Semua Prodi

Menu **Laporan**. Halamannya sama dengan laporan kaprodi ([Panduan Kaprodi › Laporan prodi](../kaprodi/#laporan-prodi)), dengan cakupan semua prodi:

| Laporan | Perbedaan untuk admin |
|---|---|
| Pantau proyek kerja | Pilihan **Program studi** punya opsi *(semua)*. |
| Laporan kepatuhan | **Kalender terbit** berisi kalender semua prodi. |
| Rekap rapor angkatan | **Prodi** berisi semua prodi; saran NIM dari roster semua prodi. |
| Rekap rekaman | Rekap semua prodi. Admin melihat sesi tetapi tidak bisa menerbitkan atau menghapus rekaman. |

Untuk mengubah roster, atau pekerjaan mengajar lain, pindah ke peran **dosen**.

## Mendaftarkan Nomor Dosen lewat WhatsApp

Dosen yang **sudah menjadi anggota grup WhatsApp dosen** dapat mendaftar sendiri. Untuk dosen di luar grup itu, Anda (dan kaprodi) bisa mendaftarkannya lewat chat pribadi ke nomor bot:

```
daftarkan dosen | nomor WhatsApp | nama lengkap
```

Contoh: `daftarkan dosen | 081234567890 | Budi Santoso, M.Kom.` Nomor boleh ditulis `08…`, `62…`, atau `+62…`. Tautan siap-pakai: **[Daftarkan dosen lewat WhatsApp](https://wa.me/6282258512828?text=daftarkan%20dosen%20%7C%20%28ganti%20dengan%20nomor%20WhatsApp%20dosen%29%20%7C%20%28ganti%20dengan%20nama%20lengkapnya%29)** — ganti kedua isian dalam kurung, lalu tekan Kirim.

Setelah tersimpan, bot mengirim langkah berikutnya ke nomor dosen itu: masuk di aplikasi, isi email kampus, lalu minta kaprodi menunjuknya sebagai pengajar kelas. Email tidak diisi di sini — dosen yang bersangkutan mengisinya sendiri.

Yang ditolak bot: nomor yang sudah terdaftar sebagai dosen aktif, nomor yang ada di roster mahasiswa, dan **nomor yang pernah dinonaktifkan** (hanya admin yang dapat mengaktifkannya kembali).

Calon dosen juga bisa meminta sendiri: bila ia mengirim `daftar dosen | email` padahal belum anggota grup dosen, bot membalasnya dengan teks siap-teruskan berisi tautan pendaftaran untuk Anda — Anda cukup mengetuk tautannya lalu menekan Kirim.

## Yang dikerjakan di luar aplikasi

Hal berikut sengaja tidak punya tombol di aplikasi dan dikerjakan pengelola platform di sistem, bukan lewat aplikasi:

* **Menetapkan admin pertama** (sesudah itu admin menetapkan admin lain di [Kelola Pengguna](#kelola-pengguna)).
* Memindahkan data kaprodi lama yang masih memakai NIP ke email kampus (inilah butir *prodi yang masih memakai data kaprodi lama* di Beranda; sebagai admin Anda cukup menetapkan ulang kaprodinya lewat **Kelola Kaprodi** setelah dosen itu mengisi email kampus).

Hubungi pengelola platform untuk keperluan ini.

## Kendala Umum

| Keadaan | Yang dilakukan |
|---|---|
| Dosen tidak muncul di pilihan kaprodi | Dosen belum mengisi email kampus, atau belum terdaftar sebagai dosen aktif. |
| Pengguna lupa kata sandi | **Pengguna** → cari orangnya → **Reset kata sandi**. Kata sandinya kembali ke kata sandi awal. |
| *ini admin aktif terakhir* | Tetapkan admin lain dulu, baru cabut atau nonaktifkan admin itu. |
| Kaprodi baru belum melihat menu kaprodi | Minta ia keluar lalu masuk lagi. |
| *Buat program studinya dulu di halaman Kurikulum* | Belum ada prodi; buat lewat menu **Admin → Program studi baru**. |
| Prodi yang ada tidak bisa diubah | Perubahan data prodi dilakukan kaprodinya. |
| Muncul kartu *untuk kaprodi* | Halaman itu untuk kaprodi prodinya; admin hanya membaca. |
