# minpro_2_pab

Nama : Rizky Yunia 

Nim : 2409116089

Kelas : Sistem Informasi C

# Deskripsi Aplikasi 
Aplikasi Resep Masakan ini berbasis Flutter yang digunakan untuk menyimpan dan mengelola berbagai resep makanan. Aplikasi ini terhubung dengan Supabase sebagai backend database untuk menyimpan data resep secara online. Pengguna dapat melakukan registrasi akun terlebih dahulu jika tidak mempunyai akun, atau langsung login jika sudah mempunyai akun. Kemudian login ke dalam aplikasi untuk melihat daftar resep, menambahkan resep baru, serta menghapus resep yang sudah tidak diperlukan. Aplikasi ini dibuat untuk mempermudah pengguna dalam menyimpan dan mengelola resep masakan secara praktis.

# Fitur Aplikasi
1. Register: Pengguna dapat membuat akun baru menggunakan email dan password melalui Supabase Authentication.
2. Login: Pengguna dapat masuk ke dalam aplikasi menggunakan akun yang sudah terdaftar.
3. Menampilkan Daftar Resep: Aplikasi akan menampilkan daftar resep yang tersimpan pada database Supabase.
4. Menambahkan Resep
   Pengguna dapat menambahkan resep baru yang berisi:
   - Nama Masakan
   - Bahan-bahan
   - Langkah Memasak
5. Menghapus Resep: Pengguna dapat menghapus resep yang sudah tidak diperlukan dari database.

# Widget yang Digunakan
Widget Flutter yang digunakan dalam aplikasi ini antara lain:
1. MaterialApp → Struktur utama aplikasi Flutter
2. Scaffold → Layout dasar halaman
3. AppBar → Menampilkan judul halaman
4. TextField → Input data pengguna
5. ElevatedButton → Tombol aksi (Login / Register / Simpan)
6. ListView → Menampilkan daftar resep
7. ListTile → Menampilkan item resep
8. Card → Membuat tampilan daftar lebih rapi
9. CircleAvatar → Menampilkan ikon pada list
10. Icon → Menampilkan ikon pada aplikasi
11. FloatingActionButton → Tombol tambah resep
12. FutureBuilder → Mengambil data dari database Supabase
13. Padding & SizedBox → Mengatur jarak antar widget

