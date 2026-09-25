# Panduan Kaprodi

[← Semua panduan](../)

Panduan ini untuk dosen yang memimpin satu program studi. **Kaprodi menjalankan prodinya**: mengisi kurikulum, mencentang dosen pengampu, menyusun dan menerbitkan kalender, menunjuk pengajar tiap kelas, serta memantau laporan prodi. Pekerjaan mengajar (materi, kuis, tugas, penilaian) ada di [Panduan Dosen](../dosen/); kaprodi punya semua hak pengajar di kelas prodinya.

Kaprodi ditetapkan admin. Syaratnya: terdaftar sebagai dosen aktif dan sudah mengisi email kampus.

**Daftar isi:** [Pindah peran](#pindah-peran) · [Menu](#menu) · [Urutan kerja](#urutan-kerja-awal-semester) · [Beranda](#beranda) · [Kurikulum](#kurikulum-program-studi) · [Dosen pengampu](#dosen-pengampu-prodi) · [Kelola kelas](#kelola-kelas) · [Daftarkan dosen](#mendaftarkan-nomor-dosen-lewat-whatsapp) · [Kalender](#kalender-akademik) · [Pengguna prodi](#pengguna-prodi) · [Laporan prodi](#laporan-prodi) · [Kendala](#kendala-umum)

## Pindah peran

Dosen yang memegang jabatan melihat **pemilih peran** berisi peran yang benar-benar ia pegang: **admin**, **kaprodi &lt;PRODI&gt;**, dan **dosen**. Bawaannya peran tertinggi.

* **Layar lebar:** kotak pilihan di pojok kanan bilah atas (menggantikan label peran).
* **HP:** ketuk tombol akun (lingkaran inisial) → lembar **Akun** → bagian **Peran aktif**.

Pilihan langsung berlaku tanpa keluar-masuk dan disimpan di peramban itu saja. Pemilih peran **hanya mengubah menu yang tampil** — hak akses tetap mengikuti jabatan yang tercatat di sistem.

Membuka halaman milik peran lain menampilkan kartu dengan tombol **Pakai peran …**. Di grup **Lainnya** juga ada tombol **Pakai peran dosen** untuk pindah ke menu mengajar.

**Baru ditetapkan atau diganti sebagai kaprodi?** Akses laporan berubah seketika, tetapi label peran dan isi pemilih peran baru berubah setelah Anda **keluar lalu masuk lagi**.

## Menu

| Tempat | Isi |
|---|---|
| Bilah atas (layar lebar) | Beranda · Kelas · Kurikulum · Pengampu · Kalender · Pengguna · **Lainnya** |
| Bilah bawah HP | Beranda · Kelas · Kurikulum · Kalender · **Lainnya** |
| **Lainnya** | Dosen pengampu prodi dan Pengguna prodi (di HP), Pantau proyek kerja, Laporan kepatuhan, Rekap rapor angkatan, Rekap rekaman |

## Urutan kerja awal semester

1. **[Kurikulum](#kurikulum-program-studi)** — lengkapi data prodi, rumpun (blok 2–3 mata kuliah yang diikat satu proyek) beserta mata kuliahnya, CPL (capaian pembelajaran lulusan), dan ritme mingguan (pola satu minggu yang diulang menjadi kalender).
2. **[Dosen pengampu](#dosen-pengampu-prodi)** — centang dosen yang mengajar di prodi Anda; mereka menjadi daftar pilihan pengajar kelas.
3. **[Kalender](#kalender-akademik)** — buat draf dari ritme mingguan, periksa sesinya, lalu terbitkan. Sebelum kalender terbit, mahasiswa dan dosen belum melihat jadwal, agenda, materi mingguan, kuis, maupun rekaman. Kelas semester itu dibuat otomatis saat kalender terbit.
4. **[Kelas](#kelola-kelas)** — tunjuk pengajar tiap kelas dan sesuaikan pesertanya bila perlu. Tanpa pengajar, materi, kuis, tugas, dan nilai kelas itu hanya bisa diisi Anda.
5. **[Laporan](#laporan-prodi)** — pantau berkala selama semester.

## Beranda

Judulnya **Beranda kaprodi &lt;PRODI&gt;**.

* **Mulai di sini** — lima langkah di atas, dengan status dari data prodi Anda, mis. *belum ada CPL*, *SKS rumpun 30 dari 144*, *2 rumpun masih draf*, *N draf kalender menunggu diterbitkan*, *N kelas PRODI belum punya pengajar*.
* **Perlu dikerjakan** — mis. proyek kerja yang telat tinjauan tengah (**Mendesak**).
* **Jadwal minggu ini** — kalender terbit prodi Anda.
* **Layanan** — Kurikulum dan pengajar, Laporan prodi.

## Kurikulum Program Studi

Menu **Kurikulum**. Anda hanya bisa mengubah kurikulum **prodi yang Anda pimpin**. Urutan pengisian: **prodi → rumpun (beserta mata kuliah) → CPL**, lalu **ritme mingguan** untuk kalender. Istilah bertanda **?** bisa diketuk untuk melihat artinya.

Format baku tiap isian beserta contoh terisi (termasuk contoh kalender semester 16 minggu, Markdown dan CSV): **[Format Baku Isian Kaprodi](format/)**.

### 1. Program Studi

Formulir **Perbarui prodi Anda** sudah terisi data prodi Anda. Ubah **Nama**, **Jenjang**, **Total SKS**, **Jumlah semester** (1–14), atau **Proyek kerja mulai semester** (isi 0 untuk bawaan semester 4), lalu **Simpan Prodi**. Program studi baru dibuat admin.

### 2. Rumpun Mata Kuliah

1. Pilih **Prodi**. Daftar rumpun tampil dengan jumlah SKS terhadap total SKS prodi dan status **draf**/**disahkan**. Tekan **Sunting** untuk memuat rumpun ke formulir.
2. Isi **Kode rumpun** (mis. R1), **Nama rumpun**, **Semester**, **SKS**, **Proyek pengikat**, dan **Moda** (*Ritme mingguan* atau *Tempat kerja*).
3. Isi **Mata kuliah — satu per baris, SKS dalam kurung di akhir**, contoh:
   ```
   Fikih Muamalah (3)
   Akuntansi Syariah (3)
   ```
4. Isi **Kode CPL yang disentuh** (pisahkan koma, boleh kosong) dan **Catatan status**.
5. Tekan **Simpan Rumpun**.

Aturan:

* **Jumlah SKS mata kuliah harus sama dengan SKS rumpun** — penghitung di bawah isian memberi tahu sebelum menyimpan; kalau beda, penyimpanan ditolak.
* Mata kuliah tidak diketik terpisah; ia diturunkan otomatis dari daftar di rumpun.
* Rumpun yang punya **Catatan status** tampil sebagai **draf**. Kosongkan catatan untuk mengesahkannya.
* Mata kuliah yang sudah punya nilai mahasiswa tidak bisa dihapus atau diganti nama.
* Menyimpan dengan kode rumpun yang sama memperbarui rumpun itu.

### 3. Capaian Pembelajaran (CPL)

Pilih **Prodi**, lalu isi **Kode** (mis. CPL01), **Domain** (Sikap / Pengetahuan / Keterampilan umum / Keterampilan khusus), **Deskripsi**, dan **Rumpun penyentuh** (pisahkan koma). Tekan **Simpan CPL**.

Salin teks CPL dari dokumen kurikulum prodi, jangan dikarang. Daftar CPL dipakai dasbor mahasiswa dan laporan kepatuhan.

### 4. Ritme Mingguan

Ritme adalah pola satu minggu yang diulang menjadi kalender semester. **Kalender belum bisa disusun sebelum ada ritme.**

1. Di **Muat ritme**, pilih *(ritme baru)* atau ritme yang sudah ada.
2. Isi **Nama ritme** (mis. *Ritme PAI — Semester 1-6*).
3. Isi tiap baris: **Hari**, **Moda** (*Belajar mandiri (asinkron)* / *Kelas daring bersama dosen* / *Praktik & proyek (luring atau daring)* / *Tanpa kegiatan akademik*), **Jam mulai**, **Jam selesai**, **Menit**, **Catatan**. **+ Tambah Baris** untuk menambah, **×** untuk menghapus.
4. Periksa ringkasan *Total N menit/minggu · kapasitas X SKS per semester* (kapasitas = menit ÷ 85).
5. Tekan **Simpan Ritme**.

**Menit** diisi menit instruksional — jam kotor dikurangi ibadah, makan, dan jeda. **Ritme yang dipakai kalender prodi lain tidak bisa diubah**; simpan pola prodi Anda dengan nama ritme baru.

### 5. Data Bawaan (Seed)

Hanya tampil untuk prodi yang punya data bawaan. Memuat data bawaan **menimpa** rumpun dan CPL berkode sama yang sudah diketik (ritme tidak ikut). Centang pernyataan persetujuan, lalu tekan **Muat Data Bawaan**.

## Dosen Pengampu Prodi

Menu **Pengampu** (di HP: **Lainnya → Dosen pengampu prodi**). Dosen yang dicentang menjadi **daftar pilihan pengajar** kelas prodi Anda. Sejak 25 September 2026 centang ini saja belum memberi hak menyusun materi, kuis, tugas, atau rekaman — hak itu ikut kelas yang diajar ([Kelola kelas](#kelola-kelas)).

1. Centang atau hapus centang dosen di daftar. Dosen yang sudah menjadi pengampu ada di urutan atas; baris Anda bertanda **Anda**.
2. Tekan **Simpan perubahan (N dosen)**.
3. Tampil *Tersimpan: … Berlaku seketika.*

Catatan:

* **Dosen yang belum mengisi email kampus tidak bisa dicentang.** Mereka dirangkum di lipatan *N dosen aktif belum mengisi email kampus*. Minta mereka mengisinya di halaman **Roster & Email Dosen** (lihat [Panduan Dosen](../dosen/#email-kampus-anda)).
* Centang prodi lain milik dosen yang sama diatur kaprodi prodi itu dan tidak berubah.

## Kelola Kelas

Satu kelas untuk satu **rumpun** yang punya proyek pengikat, atau satu **mata kuliah** untuk rumpun tanpa proyek pengikat (wadah mata kuliah lepas, mis. Jalur Kontinu), pada satu kalender semester. Tidak ada kelas paralel. Kelas dibuat otomatis saat Anda menerbitkan kalender; pesertanya otomatis mahasiswa aktif roster dengan prodi, angkatan, dan semester kalender itu.

Menu **Kelas** menampilkan seluruh kelas prodi Anda per periode. Tekan **Kelola kelas PRODI** di atas daftar untuk membuka **Kelola Kelas**, yang dikelompokkan per kalender (angkatan · semester · periode).

**Menunjuk pengajar dan mengatur peserta** — tiap baris kelas:

1. **Nama** kelas boleh diganti (bawaannya kode + nama rumpun, atau nama mata kuliah).
2. Centang **pengajar** dari daftar dosen pengampu prodi Anda (dosen harus sudah mengisi email kampus). Satu kelas boleh punya lebih dari satu pengajar.
3. **Peserta tambahan (NIM, pisahkan koma)** — mis. mahasiswa mengulang dari angkatan lain. **Dikeluarkan dari kelas (NIM)** — peserta otomatis yang tidak ikut kelas ini.
4. Tekan **Simpan**. Pengajar langsung bisa menyusun isi kelas itu.

Tombol lain:

* **Buat kelas yang belum ada** (per kalender) — membuat lagi kelas otomatis yang belum ada, mis. setelah rumpun ditambahkan ke kurikulum.
* **Tambah Kelas** — pilih **Kalender**, **Rumpun**, **Mata kuliah** (hanya untuk rumpun mata kuliah lepas; rumpun berproyek biarkan *(seluruh rumpun)*), dan **Nama (opsional)**, lalu tekan **Tambah Kelas**.
* **Hapus** — kelas yang sudah punya tugas atau nilai meminta konfirmasi kedua; tugas, kiriman, dan nilainya tetap tersimpan. Kelas yang dihapus tidak muncul lagi dengan sendirinya.

Mahasiswa yang naik semester, cuti, atau lulus tetap tercatat di kelas yang pernah ia ikuti (sumber *tambahan* di tab **Anggota**) supaya nilainya tidak hilang dari rapor.

Membuka kelas dari daftar menampilkan tab yang sama dengan pengajar ([Panduan Dosen › Kelas yang Anda ajar](../dosen/#kelas-yang-anda-ajar)); Anda bisa membuat tugas, mengatur bobot, dan mengisi nilai di kelas prodi Anda.

## Mendaftarkan Nomor Dosen lewat WhatsApp

Dosen yang **sudah menjadi anggota grup WhatsApp dosen** dapat mendaftar sendiri. Untuk dosen di luar grup itu, Anda bisa mendaftarkannya lewat chat pribadi ke nomor bot:

```
daftarkan dosen | nomor WhatsApp | nama lengkap
```

Contoh: `daftarkan dosen | 081234567890 | Budi Santoso, M.Kom.` Nomor boleh ditulis `08…`, `62…`, atau `+62…`. Tautan siap-pakai: **[Daftarkan dosen lewat WhatsApp](https://wa.me/6282258512828?text=daftarkan%20dosen%20%7C%20%28ganti%20dengan%20nomor%20WhatsApp%20dosen%29%20%7C%20%28ganti%20dengan%20nama%20lengkapnya%29)** — ganti kedua isian dalam kurung, lalu tekan Kirim.

Setelah tersimpan, bot mengirim langkah berikutnya ke nomor dosen itu: masuk di aplikasi, isi email kampus, lalu minta dicentang di **Pengampu**. Setelah itu tunjuk ia sebagai pengajar di [Kelola kelas](#kelola-kelas). Email tidak diisi di sini — dosen yang bersangkutan mengisinya sendiri.

Yang ditolak bot: nomor yang sudah terdaftar sebagai dosen aktif, nomor yang ada di roster mahasiswa, dan **nomor yang pernah dinonaktifkan** (hanya admin yang dapat mengaktifkannya kembali).

Calon dosen juga bisa meminta sendiri: bila ia mengirim `daftar dosen | email` padahal belum anggota grup dosen, bot membalasnya dengan teks siap-teruskan berisi tautan pendaftaran untuk Anda — Anda cukup mengetuk tautannya lalu menekan Kirim.

## Kalender Akademik

Menu **Kalender**. Menyusun, menerbitkan, dan menghapus kalender hanya bisa selagi peran aktif **kaprodi**, dan hanya untuk prodi Anda. Kalender prodi lain hanya bisa dibaca.

### Membuat draf

1. Di kartu **Buat Draft Kalender**, pilih **Program studi**, isi **Angkatan (tahun masuk)**, **Semester**, **Tanggal mulai**, **Jumlah minggu** (bawaan 16), dan pilih **Ritme mingguan**.
2. Tekan **Buat Draft**. Sesi dibuat otomatis dari ritme.

Satu prodi, angkatan, dan semester hanya boleh punya satu kalender. Draf hanya terlihat oleh Anda.

### Memeriksa dan menerbitkan

Pada kartu kalender berstatus **draft**:

* **Sunting Sesi** — ubah **Tanggal** (hari ikut berubah), **Moda**, **Mulai**, **Selesai**, dan **Keterangan** per minggu (mis. hari libur), lalu **Simpan Sesi**. Jam mulai dan selesai diisi berpasangan.
* **Terbitkan Kalender Ini** — langsung terbit, **tanpa dialog konfirmasi**. Periksa sesinya dulu.
* **Hapus Draft**.

**Setelah terbit, sesi tidak bisa disunting lagi.** Kalender terbit hanya bisa dihapus (**Hapus Kalender Terbit**) — umumkan pembatalannya ke mahasiswa dan dosen sesudahnya.

## Pengguna Prodi

Menu **Pengguna** (di HP: **Lainnya → Pengguna prodi**). Hanya untuk prodi yang Anda pimpin.

* **Tab Mahasiswa** — daftar mahasiswa prodi Anda tampil otomatis beserta status **Kata sandi** (*kata sandi awal* atau *sudah diganti*). **Ubah** memperbarui data mahasiswa; **Reset kata sandi** mengembalikannya ke kata sandi awal (bagian email sebelum @ + `ADB`, atau NIM + `ADB` bila emailnya kosong). **Tambah Mahasiswa** dan **Impor dari Excel** bekerja seperti di [Panduan Admin › Kelola Pengguna](../admin/#kelola-pengguna); program studinya hanya prodi Anda, dan baris impor untuk prodi lain ditandai sebelum disimpan.
* **Tab Dosen** — dosen yang mengajar di prodi Anda (sudah dicentang di **Pengampu**). **Tambah Dosen** mendaftarkan nomor WhatsApp baru sebagai dosen; ia baru tampil di daftar ini setelah Anda mencentangnya di **Pengampu**. **Reset kata sandi** tersedia untuk dosen pengampu biasa — kata sandi admin dan kaprodi hanya bisa direset admin. Mengubah nomor, menonaktifkan, dan jabatan admin dikerjakan admin.

Kata sandi Anda sendiri diganti lewat **Kata sandi** di pojok kanan atas.

## Laporan Prodi

Menu **Laporan**. Semua laporan otomatis dibatasi ke prodi yang Anda pimpin.

### Pantau Proyek Kerja

Isi **Program studi**, **Angkatan**, dan **Semester**, lalu **Tampilkan**. Ringkasan menampilkan proyek aktif, total pengajuan, dan tabel **Telat Tinjauan Tengah Semester** (NIM, pekerjaan, siapa yang belum menilai, hari telat, pembimbing).

Keterlambatan hanya dihitung kalau prodi, angkatan, **dan** semester diisi serta kalendernya sudah terbit. Semester 0 = hanya jumlah proyek.

### Laporan Kepatuhan

Menit asinkron, daring, dan luring per mata kuliah terhadap tuntutan SKS — untuk akreditasi.

1. Pilih **Kalender terbit**, lalu **Tampilkan Laporan**.
2. Periksa status **memenuhi**/**belum memenuhi** per mata kuliah. Target = SKS × 85 menit terjadwal per minggu.
3. Ketuk nama mata kuliah untuk rekap lintas angkatan.
4. **Cetak / Simpan PDF** untuk berkas akreditasi.

### Rekap Rapor Angkatan

Di kartu **Rekap Nilai Semester**, pilih **Prodi**, isi **Angkatan** dan **Semester**, lalu **Tampilkan Rekap**. Satu baris per mahasiswa: huruf per mata kuliah, SKS dinilai, SKS lulus, IP. Klik NIM untuk membuka rapornya. Tanda **–** berarti belum dinilai, bukan E.

### Rekap Rekaman

Kartu **Rekap Keterlambatan Rekaman** menampilkan per kalender: jatuh tempo, tepat, terlambat, belum ada, menunggu, dan daftar *Perlu perhatian*. Sebagai pengajar prodinya, kaprodi juga bisa menerbitkan rekaman — lihat [Panduan Dosen](../dosen/#rekaman-sesi-sinkron).

## Kendala Umum

| Keadaan | Yang dilakukan |
|---|---|
| Pemilih peran belum menampilkan *kaprodi* | Keluar lalu masuk lagi setelah admin menetapkan Anda. |
| *Prodi yang Anda pimpin tidak ditemukan* | Keluar lalu masuk lagi; kalau tetap, minta admin memeriksa Kelola Kaprodi. |
| Tombol **Buat Draft** nonaktif | Belum ada ritme mingguan. Isi di Kurikulum › 4. Ritme Mingguan. |
| Rumpun ditolak karena SKS | Samakan SKS rumpun dengan jumlah SKS mata kuliahnya. |
| Ritme tidak bisa disimpan | Ritme dipakai kalender prodi lain — simpan dengan nama ritme baru. |
| Dosen tidak muncul untuk dicentang | Dosen belum mengisi email kampus, atau belum terdaftar sebagai dosen aktif (hubungi pengelola). |
| Dosen sudah dicentang pengampu tetapi ditolak saat menyusun materi, kuis, atau tugas | Sejak 25 September 2026 hak itu ikut kelas. Tunjuk dosennya sebagai pengajar di [Kelola kelas](#kelola-kelas). |
| Dosen tidak muncul di pilihan pengajar kelas | Centang dulu di **Pengampu** (dosennya harus sudah mengisi email kampus). |
| Kelas semester ini belum ada | Kalender semester itu belum terbit, atau kelasnya dihapus — terbitkan kalender, atau tekan **Buat kelas yang belum ada** di Kelola Kelas. |
| Menu materi/kuis/tugas tidak ada | Menu mengajar ada di peran **dosen** — pindah peran. |
| Mahasiswa atau dosen pengampu lupa kata sandi | **Pengguna** → cari orangnya → **Reset kata sandi**. Kata sandi admin dan kaprodi hanya bisa direset admin. |
