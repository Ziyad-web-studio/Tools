# ⚡ Vector Forge - Ultimate Edition

**Developed by ZIYAD (for YOU).**

Yoo, selamat datang di **Vector Forge**. Ini adalah *tools* andalan gue (dan sekarang punya lu juga) buat *generate* prompt Adobe Stock tanpa pusing mikirin teknis yang ribet.

Gue sadar kita sering ada di dua posisi: kadang jadi **Developer** yang ngoding, kadang jadi **User** yang cuma pengen hasil cepet. Makanya tools ini gue desain buat memuaskan kedua sisi itu.

---

## 🔥 Fitur Utama (Yang Lu Minta Banget)

### 1. Smart Status Indicator 🔴🟢
Gak usah nebak-nebak API Key lu jalan apa enggak.
- **MERAH (Offline):** Lu belum masukin API Key, atau Key lu salah. Tombol generate bakal mati biar lu gak buang waktu ngeklik.
- **HIJAU (Online/Aktif):** Begitu lu paste key `gsk_...`, sistem langsung nyala. *Ready to go!*

### 2. Three-Level Power System 🎚️
Gue udah hapus daftar model yang bikin pusing. Gue ganti jadi logika **3 Level Kecerdasan**:
- **Level 1 (FAST):** Pake model ringan (*Llama 8B*). Cocok buat *draft* cepet atau nyari ide kasar. Prompt-nya simpel.
- **Level 2 (PRO):** *Recommended.* Pake model *Llama 70B* standar. Detailnya pas buat Vector Stock pada umumnya.
- **Level 3 (GOD MODE):** Ini monster-nya. Pake model *Llama 70B* tapi gue paksa dia "mikir" lebih keras (tokens lebih banyak, system prompt artistik). Hasilnya super detail, ada *lighting*, tekstur, dll.

### 3. Auto-Scroll Notification ⬇️
Pernah gak lu klik generate, terus bingung "mana hasilnya?" karena ada di bawah layar?
Sekarang, begitu AI selesai mikir, bakal muncul notifikasi **Pop-up Hijau** di atas layar. Klik itu, layar bakal otomatis *scroll* mulus ke hasil.

---

## 🚀 Cara Pakai (Gampang Banget)

1.  **Buka File:** Cukup buka `index.html` di browser (Chrome/Edge). Gak perlu install Node.js atau ribet-ribet.
2.  **Paste Key:** Masukin **Groq API Key** lu di kolom kiri. Liat indikator berubah jadi **HIJAU**. (Key lu aman, cuma disimpen di browser lu sendiri/LocalStorage).
3.  **Pilih Level:**
    - Mau ngebut? Pilih **LVL 1**.
    - Mau jualan serius? Pilih **LVL 2**.
    - Mau pamer karya masterpiece? Pilih **LVL 3**.
4.  **Tentukan Topik:** Pilih kategori atau konsep vector yang lu mau.
5.  **Generate:** Klik tombol. Tunggu sebentar.
6.  **Ambil Hasil:** Klik notifikasi yang muncul di atas, lalu copy prompt-nya.

---

## 🛠️ Catatan Teknis (Buat Sisi Developer Lu)

-   **Stack:** React 18 (Standalone via CDN) + Tailwind CSS. Sengaja dibikin *single file* biar gampang dipindah-pindah.
-   **State Management:** Pake `useState` dan `useEffect` buat mantau API Key secara *real-time*.
-   **Mapping Model:**
    -   Level 1 -> `llama-3.1-8b-instant`
    -   Level 2 & 3 -> `llama-3.3-70b-versatile` (dengan *System Prompt* yang beda).
-   **Prompt Engineering:** Gue udah inject parameter `--no text watermark realistic shading` dan `--v 6.0` secara otomatis di belakang layar.

---

*Enjoy, Bro. Semoga laku keras di Adobe Stock!* 💸
