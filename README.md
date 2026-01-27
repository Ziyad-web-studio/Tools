# ⚛️ Vector Forge - React Edition

**Powerful. Lightweight. Safe.**

Vector Forge adalah tool generator prompt untuk Adobe Stock yang dioptimalkan untuk kecepatan dan kemudahan penggunaan. Versi ini dibangun ulang sepenuhnya menggunakan **React** untuk performa maksimal di mobile maupun desktop.

---

## 🔥 Fitur Terbaru (Update Log)

### 1. React Core Engine ⚛️
Kita migrasi dari Vanilla JS ke **React 18**.
- **Kenapa?** Lebih responsif, manajemen state lebih rapi, dan rendering UI jauh lebih mulus (tanpa reload halaman).
- **Logo:** Ikon Apple dihapus (biar aman dari copyright), diganti dengan **Logo React** yang berputar elegan saat *idle*.

### 2. Smart Notification System 🔔
Gak perlu klik "close" manual.
- Notifikasi muncul di atas layar (gaya pil/kapsul).
- **Auto-Dismiss:** Notifikasi akan otomatis menghilang sendiri setelah **5 detik**.
- Animasi masuk dan keluar yang halus (*smooth transition*).

### 3. Three-Level Intelligence 🧠
Sistem pemilihan model otomatis berdasarkan kebutuhan:
- **LVL 1 (FAST):** Menggunakan model ringan untuk hasil instan.
- **LVL 2 (PRO):** Menggunakan model Llama 70B untuk detail komersial standar.
- **LVL 3 (ULTRA):** Menggunakan model Llama 70B dengan instruksi "God Mode" untuk detail, pencahayaan, dan tekstur tingkat tinggi.

### 4. Glassmorphism UI (Updated) 💎
Tampilan modern dengan efek kaca buram (*blur*), sudut membulat, dan layout responsif yang menyesuaikan layar HP atau Laptop secara otomatis.

---

## 🛠️ Teknologi yang Dipakai

* **Bahasa:** HTML5 + JavaScript (ES6+).
* **Framework:** React 18 (via CDN, tanpa build step).
* **Styling:** Tailwind CSS (via CDN).
* **Compiler:** Babel Standalone (untuk compile JSX di browser).
* **API:** Groq Cloud API (Llama 3.1 & 3.3).

---

## 🚀 Cara Penggunaan

Sangat mudah, tidak perlu install apa-apa.

1.  **Buka File:**
    Klik ganda file `index.html`. Bisa dibuka di Chrome, Edge, Safari, atau Firefox.
    *Ringan banget, bisa jalan di HP kentang sekalipun.*

2.  **Masukkan API Key:**
    * Paste **Groq API Key** (awalan `gsk_...`) di kolom kiri.
    * Cek status indikator: Jika berubah jadi **HIJAU (SISTEM ONLINE)**, berarti siap dipakai.

3.  **Pilih Konfigurasi:**
    * **Power Level:** Pilih level detail (1, 2, atau 3).
    * **Kategori:** Pilih jenis vektor yang mau dibuat (Icon, Pattern, Character, dll).
    * **Jumlah:** Geser slider untuk menentukan berapa prompt yang mau dibuat sekaligus.

4.  **Generate:**
    Klik tombol **Generate**. Tunggu sebentar (biasanya < 3 detik).

5.  **Ambil Hasil:**
    Notifikasi akan muncul di atas. Klik notifikasi untuk scroll otomatis ke hasil, atau scroll manual. Klik **Copy Prompt** untuk menyalin.

---

## 📱 Kompatibilitas

* **Desktop:** Windows, Mac, Linux (Tampilan Grid 2 Kolom).
* **Mobile:** Android, iOS (Tampilan Stack 1 Kolom yang responsif).

---

*Dibuat untuk mempercepat workflow desain vektor lu. Sikat, Bro!* 🚀
