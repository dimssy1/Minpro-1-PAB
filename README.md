# Minpro-1-PAB

# 🛍️ Butik Stylish - Aplikasi Penjualan Baju

Aplikasi Flutter untuk manajemen toko pakaian (butik) dengan fitur kasir dan data penjualan.

---

## 📱 Deskripsi Aplikasi

**Butik Stylish** adalah aplikasi kasir dan manajemen penjualan baju berbasis Flutter. Aplikasi ini dirancang untuk membantu pemilik toko baju dalam mengelola produk dan mencatat transaksi penjualan. Aplikasi ini memiliki dua fitur utama yaitu halaman kasir untuk menampilkan katalog produk dan checkout, serta halaman data penjualan untuk melihat, menambah, mengedit, dan menghapus transaksi.

Aplikasi ini cocok digunakan untuk:
- Toko baju / butik retail
- Kasir toko pakaian
- Inventory management pakaian

---

## ✨ Fitur Aplikasi

### 1. Halaman Kasir (Produk)

1. Katalog Produk
Menampilkan produk dalam grid 2 kolom dengan gambar, nama, brand, dan harga

2. Tambah Produk Baru
Admin dapat menambah produk baru ke katalog melalui form input

3. Checkout
Memilih produk dan jumlah, lalu mencatat penjualan

4. Filter Kategori
Pilihan kategori pakaian (semua, kaos, hoodie, kemeja, dll)

5. Banner Promo
Tampilan promo menarik di bagian atas

### 2. Halaman Penjualan (CRUD)

1. Create.
Menambah data penjualan baru secara manual

2. Read.
Melihat daftar semua transaksi penjualan

3. Update.
Mengedit data penjualan yang sudah ada

4. Delete.
Menghapus data penjualan (dengan swipe atau tombol)

5. Ringkasan.
Menampilkan total transaksi, total items, dan total pendapatan

6. Auto Save.
Saat checkout di kasir, data otomatis masuk ke halaman penjualan

### 3. Navigasi
Bottom Navigation Bar untuk berpindah antara halaman Kasir dan Penjualan

## 🧩 Widget yang Digunakan

Widget Dasar Flutter

1. MaterialApp.
Root aplikasi Flutter

2. Scaffold.
Struktur dasar halaman

3. AppBar.
Header/tittle bar di setiap halaman

4. BottomNavigationBar.
Navigasi utama aplikasi

5. FloatingActionButton.
Tombol tambah data

6. GridView.builder.
Menampilkan produk dalam grid

7. ListView.builder.
Menampilkan daftar penjualan

8. Card.
Kontainer untuk item produk

9. Column / Row.
Layouting elemen UI

10. Expanded.
Mengisi ruang kosong dalam flex

11. Container.
Box styling dan decoration

12. Padding / Margin.
Spacing

13. Stack.
Overlay widget

Widget Input

1. TextField / TextFormField. Input teks dan form

2. ElevatedButton. Tombol submit

3. TextButton. Tombol alternatif

4. IconButton. Tombol dengan ikon

5. InkWell. Tombol dengan efek ripple

6. ChoiceChip. Filter kategori

Widget Display

1. Image.network. Menampilkan gambar produk

2. Text. Menampilkan teks

3. Icon. Menampilkan ikon
   
4. ClipRRect. Membuat gambar dengan border radius

5. LinearGradient. Background gradient

6. SnackBar. Notifikasi pop-up

Widget Dialog & Pop-Up

1. AlertDialog. Dialog konfirmasi

2. showModalBottomSheet. Form input dari bawah

3. Dismissible. Hapus data dengan swipe

Widget Lainnya

1. Form. Wrapper untuk validasi form

2. GlobalKey Kunci untuk validasi

3. TextEditingController. Mengambil nilai input

4. setState. Update UI saat data berubah


## 🛠️ Teknologi yang Digunakan
- Framework: Flutter
- Bahasa: Dart
- Target Platform: Android, iOS, Web
- State Management: StatefulWidget (setState)

## 📂 Struktur Folder

<img width="482" height="361" alt="image" src="https://github.com/user-attachments/assets/8e1132d6-a0b3-4df1-afaa-0b8c81a0d911" />


