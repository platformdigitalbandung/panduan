# Panduan Admin

[← Semua panduan](../)

Panduan ini untuk super admin platform. **Admin hanya menyiapkan**: membuat program studi baru dan menetapkan kaprodinya, lalu boleh membuka laporan semua prodi. Kurikulum, dosen pengampu, kalender, kuis, dan materi prodi dijalankan kaprodi masing-masing ([Panduan Kaprodi](../kaprodi/)).

Admin juga harus terdaftar sebagai dosen aktif. Pemilih peran dan cara pindah peran dijelaskan di [Panduan Kaprodi › Pindah peran](../kaprodi/#pindah-peran); menu mengajar ada di peran **dosen**.

**Daftar isi:** [Menu](#menu) · [Beranda](#beranda) · [Menyiapkan prodi baru](#menyiapkan-prodi-baru) · [Kelola kaprodi](#kelola-kaprodi) · [Laporan semua prodi](#laporan-semua-prodi) · [Di luar aplikasi](#yang-dikerjakan-di-luar-aplikasi) · [Kendala](#kendala-umum)

## Menu

| Tempat | Isi |
|---|---|
| Bilah atas / bilah bawah HP | Beranda · Kaprodi · Prodi baru · **Laporan** |
| **Laporan** | Pantau proyek kerja, Laporan kepatuhan, Rekap rapor angkatan, SLA forum (pertanyaan yang lewat target jawaban dosen 1×24 jam), Rekap rekaman |

## Beranda

Judulnya **Beranda admin**.

* **Mulai di sini**
  1. **Tetapkan kaprodi tiap prodi** → *Kelola kaprodi*
  2. **Pastikan dosen mengisi email kampus** → *Lihat daftar dosen*
* **Perlu dikerjakan** — prodi yang belum punya kaprodi (**Mendesak**), prodi yang masih memakai data kaprodi lama, dan jumlah dosen aktif yang belum mengisi email kampus.
* **Penyiapan program studi** (kolom samping) — semua prodi beserta kaprodinya, atau tanda **Belum ada kaprodi**.

## Menyiapkan prodi baru

### 1. Buat program studi

Menu **Prodi baru** (halaman Kurikulum Program Studi). Admin hanya melihat kartu **Program Studi**.

1. Periksa tabel prodi yang sudah ada supaya kodenya tidak kembar.
2. Di **Tambah program studi baru**, isi:
   * **Kode** — mis. `pai`: huruf kecil, angka, atau tanda hubung; 2–20 karakter; diawali huruf. **Kode menjadi kunci** di rumpun, CPL, mata kuliah, roster, dan kalender, jadi pilih dengan cermat dan jangan diubah sesudahnya.
   * **Nama**, **Jenjang** (bawaan S1), **Total SKS** (bawaan 144), **Jumlah semester** (1–14, bawaan 8), **Proyek kerja mulai semester** (0 = bawaan semester 4).
3. Tekan **Simpan Prodi**.

Admin tidak bisa mengubah prodi yang sudah ada (kecuali ia sendiri kaprodi prodi itu).

### 2. Tetapkan kaprodinya

Lanjutkan ke [Kelola Kaprodi](#kelola-kaprodi). Setelah itu rumpun, CPL, ritme, dosen pengampu, dan kalender diisi kaprodi tersebut.

## Kelola Kaprodi

Menu **Kaprodi**. Hanya tampil selagi peran aktif **admin**.

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
* **Kapan berlaku:** akses laporan prodi berubah **seketika**. Label peran dan pemilih peran orang itu baru berubah setelah ia **keluar lalu masuk lagi** — sampaikan hal ini kepadanya.

## Laporan Semua Prodi

Menu **Laporan**. Halamannya sama dengan laporan kaprodi ([Panduan Kaprodi › Laporan prodi](../kaprodi/#laporan-prodi)), dengan cakupan semua prodi:

| Laporan | Perbedaan untuk admin |
|---|---|
| Pantau proyek kerja | Pilihan **Program studi** punya opsi *(semua)*. |
| Laporan kepatuhan | **Kalender terbit** berisi kalender semua prodi. |
| Rekap rapor angkatan | **Prodi** berisi semua prodi; saran NIM dari roster semua prodi. |
| SLA forum | **Prodi** bawaannya *Semua prodi*. Admin **hanya membaca** — tidak bisa membalas atau menutup pertanyaan. |
| Rekap rekaman | Rekap semua prodi. Admin melihat sesi tetapi tidak bisa menerbitkan atau menghapus rekaman. |

Untuk membalas forum, mengubah roster, atau pekerjaan mengajar lain, pindah ke peran **dosen**.

## Yang dikerjakan di luar aplikasi

Hal berikut sengaja tidak punya tombol di aplikasi dan dikerjakan pengelola platform di sistem, bukan lewat aplikasi:

* **Menjadikan atau mencabut admin.**
* **Mendaftarkan dosen baru** atau **menonaktifkan dosen**. Dosen yang dinonaktifkan kehilangan semua perannya — dosen, kaprodi, dan admin.
* Memindahkan data kaprodi lama yang masih memakai NIP ke email kampus (inilah butir *prodi yang masih memakai data kaprodi lama* di Beranda; sebagai admin Anda cukup menetapkan ulang kaprodinya lewat **Kelola Kaprodi** setelah dosen itu mengisi email kampus).

Hubungi pengelola platform untuk keperluan ini.

## Kendala Umum

| Keadaan | Yang dilakukan |
|---|---|
| Dosen tidak muncul di pilihan kaprodi | Dosen belum mengisi email kampus, atau belum terdaftar sebagai dosen aktif. |
| Kaprodi baru belum melihat menu kaprodi | Minta ia keluar lalu masuk lagi. |
| *Buat program studinya dulu di halaman Kurikulum* | Belum ada prodi; buat lewat menu **Prodi baru**. |
| Prodi yang ada tidak bisa diubah | Perubahan data prodi dilakukan kaprodinya. |
| Muncul kartu *untuk dosen atau kaprodi* | Halaman itu bukan untuk peran admin. Tekan **Pakai peran …** bila Anda juga dosen. |
