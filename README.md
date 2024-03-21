# hospital_apps

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

### Menu, Layar, dan Komponen Frontend untuk Superadmin:

| Menu                 | Deskripsi                                                | Layar                                                       | Komponen Frontend (Flutter)                                        |
| -------------------- | -------------------------------------------------------- | ----------------------------------------------------------- | ------------------------------------------------------------------ |
| Dashboard            | Halaman utama dengan ringkasan data dan statistik        | DashboardSuperadmin                                         | Grafik, Tabel, Grafik Pemetaan, dll.                               |
| Manajemen User       | Fitur untuk mengelola pengguna (tambah, edit, hapus)     | DaftarPengguna, TambahPengguna, EditPengguna, HapusPengguna | Tabel, Form (Input, Dropdown, dll.), Tombol Aksi                   |
| Manajemen Dokter     | Fitur untuk mengelola data dokter (tambah, edit, hapus)  | DaftarDokter, TambahDokter, EditDokter, HapusDokter         | Tabel, Form (Input, Dropdown, dll.), Tombol Aksi                   |
| Manajemen Perawat    | Fitur untuk mengelola data perawat (tambah, edit, hapus) | DaftarPerawat, TambahPerawat, EditPerawat, HapusPerawat     | Tabel, Form (Input, Dropdown, dll.), Tombol Aksi                   |
| Manajemen Pasien     | Fitur untuk mengelola data pasien (tambah, edit, hapus)  | DaftarPasien, TambahPasien, EditPasien, HapusPasien         | Tabel, Form (Input, Dropdown, dll.), Tombol Aksi                   |
| Manajemen Konsultasi | Fitur untuk melihat dan mengelola riwayat konsultasi     | RiwayatKonsultasi                                           | Tabel, Filter, Detail Konsultasi, Tombol Aksi                      |
| Pengaturan           | Pengaturan aplikasi dan akun superadmin                  | PengaturanAkunSuperadmin                                    | Form Pengaturan (Ubah Kata Sandi, Notifikasi, dll.), Tombol Simpan |
| Logout               | Keluar dari aplikasi                                     | -                                                           | Tombol "Logout"                                                    |

### Menu, Layar, dan Komponen Frontend untuk Dokter:

| Menu       | Deskripsi                                             | Layar                                 | Komponen Frontend (Flutter)                                             |
| ---------- | ----------------------------------------------------- | ------------------------------------- | ----------------------------------------------------------------------- |
| Dashboard  | Halaman utama dengan ringkasan data dan statistik     | DashboardDokter                       | Grafik, Tabel, Grafik Pemetaan, dll.                                    |
| Pasien     | Melihat daftar pasien dan riwayat konsultasi          | DaftarPasien, RiwayatKonsultasiPasien | Tabel, Filter, Detail Pasien, Riwayat Konsultasi, Tombol Aksi           |
| Konsultasi | Memulai atau bergabung dalam konsultasi dengan pasien | DaftarKonsultasi, KonsultasiDokter    | Ruang Obrolan, Form Input Pesan, Tombol Kirim, Tombol Akhiri Konsultasi |
| Profil     | Melihat dan mengedit informasi profil                 | ProfilDokter                          | Informasi Profil, Form Edit Profil, Tombol Simpan                       |
| Pengaturan | Pengaturan akun dokter                                | PengaturanAkunDokter                  | Form Pengaturan (Ubah Kata Sandi, Notifikasi, dll.), Tombol Simpan      |
| Logout     | Keluar dari aplikasi                                  | -                                     | Tombol "Logout"                                                         |

### Menu, Layar, dan Komponen Frontend untuk Perawat:

| Menu       | Deskripsi                                                | Layar                                 | Komponen Frontend (Flutter)                                             |
| ---------- | -------------------------------------------------------- | ------------------------------------- | ----------------------------------------------------------------------- |
| Dashboard  | Halaman utama dengan ringkasan data dan statistik        | DashboardPerawat                      | Grafik, Tabel, Grafik Pemetaan, dll.                                    |
| Pasien     | Melihat daftar pasien dan riwayat konsultasi             | DaftarPasien, RiwayatKonsultasiPasien | Tabel, Filter, Detail Pasien, Riwayat Konsultasi, Tombol Aksi           |
| Konsultasi | Menangani konsultasi pasien dan komunikasi dengan dokter | DaftarKonsultasi, KonsultasiPerawat   | Ruang Obrolan, Form Input Pesan, Tombol Kirim, Tombol Akhiri Konsultasi |
| Profil     | Melihat dan mengedit informasi profil                    | ProfilPerawat                         | Informasi Profil, Form Edit Profil, Tombol Simpan                       |
| Pengaturan | Pengaturan akun perawat                                  | PengaturanAkunPerawat                 | Form Pengaturan (Ubah Kata Sandi, Notifikasi, dll.), Tombol Simpan      |
| Logout     | Keluar dari aplikasi                                     | -                                     | Tombol "Logout"                                                         |

### Menu, Layar, dan Komponen Frontend untuk Pasien:

| Menu               | Deskripsi                                           | Layar                                        | Komponen Frontend (Flutter)                                        |
| ------------------ | --------------------------------------------------- | -------------------------------------------- | ------------------------------------------------------------------ |
| Dashboard          | Halaman utama dengan ringkasan data kesehatan       | DashboardPasien                              | Grafik, Tabel, dll.                                                |
| Konsultasi         | Memulai konsultasi dengan dokter                    | DaftarDokter, DetailDokter, KonsultasiPasien | DaftarDokter, Filter, DetailDokter, TombolMulaiKonsultasi          |
| Riwayat Konsultasi | Melihat riwayat konsultasi sebelumnya dengan dokter | RiwayatKonsultasiPasien                      | Tabel, Filter, DetailKonsultasi, TombolAksi                        |
| Profil             | Melihat dan mengedit informasi profil               | ProfilPasien                                 | Informasi Profil, Form Edit Profil, Tombol Simpan                  |
| Pengaturan         | Pengaturan akun pasien                              | PengaturanAkunPasien                         | Form Pengaturan (Ubah Kata Sandi, Notifikasi, dll.), Tombol Simpan |
| Logout             | Keluar dari aplikasi                                | -                                            | Tombol "Logout"                                                    |
