# 📱 Cara Setup Proyek di MIT App Inventor

Berikut ini adalah langkah-langkah dasar untuk membuat aplikasi pertama kamu menggunakan **MIT App Inventor**, lengkap dengan penjelasan fitur-fiturnya.

---

## 🔧 Langkah-langkah Membuat Aplikasi

1. **Buka MIT App Inventor**  
   Buka browser dan ketik di Google: `mit app inventor`, lalu klik link pertama atau langsung ke: [https://appinventor.mit.edu](https://appinventor.mit.edu)

2. **Klik Tombol "Create Apps!"**  
   Setelah masuk ke website MIT App Inventor, klik tombol **"Create Apps!"** di pojok kanan atas.

3. **Login dengan Akun Google**  
   MIT App Inventor akan meminta kamu login menggunakan akun Google.

4. **Klik "Start new project" / "New Project"**  
   Setelah login, klik tombol **"Start new project"** untuk memulai aplikasi baru.

5. **Masukkan Nama Proyek**  
   Masukkan nama aplikasi yang ingin kamu buat (misalnya: `MonitoringDuduk_IoT`). Biarkan pengaturan lainnya default, lalu klik **OK**.

6. **MIT App Inventor Siap Digunakan!**  
   Sekarang kamu sudah masuk ke antarmuka pengembangan aplikasi. Kamu bisa mulai drag & drop komponen untuk membangun aplikasi kamu.

---

## 🧩 Penjelasan Fitur MIT App Inventor

MIT App Inventor menggunakan dua tampilan utama:

### 1. **Designer View (Tampilan Desain)**  
Tempat kamu mendesain tampilan aplikasi (UI):

- **Palette**: Berisi komponen yang bisa kamu seret (drag) ke layar aplikasi (misal: Button, TextBox, Label, ListView, dsb)
- **Viewer**: Menampilkan preview aplikasi kamu (seperti canvas).
- **Components**: Daftar semua komponen yang sudah kamu tambahkan ke layar.
- **Properties**: Mengatur properti dari komponen yang dipilih (warna, ukuran, teks, dll).

### 2. **Blocks View (Tampilan Blok)**  
Tempat kamu membuat logika aplikasi dengan sistem blok visual (seperti puzzle). Contoh logika: ketika tombol ditekan → kirim data ke Firebase.

---

## 🔌 Integrasi IoT / Firebase

Untuk menghubungkan dengan Firebase dan IoT seperti ESP32, kamu akan memerlukan:
- Komponen **Web** (untuk komunikasi HTTP / REST API)
- Komponen **FirebaseDB** (untuk komunikasi langsung dengan Firebase Realtime Database)
- Komponen **Clock** (untuk pembacaan waktu atau refresh data)
- Komponen **Notifer** (untuk menampilkan popup atau peringatan)

---
