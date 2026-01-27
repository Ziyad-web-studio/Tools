# ⚛️ Vector Forge - React Edition (Final)

**Powerful. Lightweight. Safe.**

Vector Forge adalah tool generator prompt Adobe Stock yang dioptimalkan untuk kecepatan dan kemudahan. Versi final ini menggunakan engine **React 18** untuk performa UI yang mulus, dengan tampilan *glassmorphism* yang elegan dan background abstrak keren yang diminta user.

---

## 🔥 Fitur Utama & Pembaruan

### 1. React Core Engine & Safe Branding ⚛️
Kita menggunakan library **React 18** via CDN agar aplikasi tetap ringan (single file HTML) namun sangat responsif.
- **State Management:** UI terupdate otomatis saat ada perubahan data (misal: status API key).
- **Branding Aman:** Ikon Apple telah dihapus dan diganti dengan **Logo React** yang berputar elegan saat aplikasi *idle* (menunggu perintah).

### 2. Smart Notification System 🔔
Sistem notifikasi gaya "Dynamic Island" di bagian atas layar.
- **Auto-Dismiss:** Notifikasi akan **otomatis menghilang sendiri dalam 5 detik** jika tidak diklik.
- **Smooth Animation:** Animasi masuk (*pop-in*) dan keluar (*pop-out*) yang sangat halus.
- **Tap to Scroll:** Klik notifikasi untuk langsung menuju ke hasil prompt.

### 3. Three-Level Intelligence 🧠
Sistem pemilihan model AI otomatis berdasarkan kebutuhan detail:
- **LVL 1 (FAST):** Menggunakan model ringan (Llama 8B) untuk hasil instan, fokus pada bentuk simpel.
- **LVL 2 (PRO):** Menggunakan model standar (Llama 70B) untuk detail komersial yang seimbang.
- **LVL 3 (ULTRA):** Menggunakan model Llama 70B dengan instruksi khusus ("God Mode") untuk detail, pencahayaan, dan tekstur tingkat tinggi.

### 4. Premium UI/UX 💎
- **Background Keren:** Kembali menggunakan wallpaper abstrak warna-warni yang diminta user.
- **Glassmorphism:** Panel transparan dengan efek blur, sudut membulat yang besar, dan border tipis.
- **Responsif:** Layout otomatis menyesuaikan, 1 kolom di HP, 2 kolom di Desktop.
- **Indikator Status Real-time:** Panel status berwarna Merah/Hijau yang langsung berubah saat API Key dimasukkan.

---

## 🛠️ Teknologi yang Dipakai

* **Bahasa:** HTML5 + JavaScript (ES6+).
* **Framework:** React 18 (via CDN).
* **Styling:** Tailwind CSS (via CDN) dengan kustomisasi animasi dan warna.
* **Compiler:** Babel Standalone (untuk memproses JSX di browser).
* **API:** Groq Cloud API (Model Llama 3.1 & 3.3).

---

## 🚀 Cara Penggunaan

Sangat mudah, tidak perlu install apa-apa, cukup browser.

1.  **Buka File:**
    Klik ganda file `index.html`. Aplikasi akan terbuka di browser default Anda dengan background abstrak yang keren.

2.  **Masukkan API Key:**
    * Paste **Groq API Key** Anda (berawalan `gsk_...`) di kolom kiri.
    * Perhatikan indikator status: Jika berubah menjadi **HIJAU (SISTEM ONLINE)**, berarti aplikasi siap digunakan. Key akan tersimpan otomatis di browser Anda.

3.  **Pilih Konfigurasi:**
    * **Power Level:** Pilih tingkat detail yang diinginkan (1, 2, atau 3).
    * **Kategori:** Pilih jenis vektor (Icon, Social Media, Pattern, dll).
    * **Jumlah:** Tentukan berapa banyak prompt yang ingin dibuat sekaligus (1-5).

4.  **Generate:**
    Klik tombol **Generate**. Tombol akan menunjukkan status loading.

5.  **Ambil Hasil:**
    * Setelah selesai, notifikasi akan muncul di bagian atas layar.
    * Klik notifikasi tersebut untuk *scroll* otomatis ke hasil prompt di panel kanan.
    * Klik tombol **Copy Prompt** pada kartu hasil untuk menyalin teks ke clipboard.

---

## 📱 Kompatibilitas & Performa

* **Sangat Ringan:** Hanya satu file HTML, tidak ada proses build atau instalasi server.
* **Cross-Platform:** Berjalan mulus di Chrome, Safari, Edge, dan Firefox baik di Desktop maupun Mobile (Android/iOS).

---

*Enjoy the forge, Bro!* 🚀
