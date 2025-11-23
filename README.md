# Radio.on

Aplikasi radio sederhana yang memungkinkan Anda mendengarkan stasiun radio favorit dari seluruh dunia langsung dari desktop atau perangkat Anda. Proyek ini bertujuan untuk menyediakan pengalaman mendengarkan radio yang minimalis dan efisien.

---

## 📻 Fitur Utama

* **Streaming Stasiun Radio:** Mendukung pemutaran *stream* audio dari berbagai format (misalnya, MP3, AAC).
* **Antarmuka Pengguna Sederhana:** Desain yang intuitif dan mudah dinavigasi.
* **Daftar Stasiun *Hardcoded* atau Dapat Dikonfigurasi:** Kemampuan untuk mengelola daftar stasiun radio favorit Anda.
* **Kontrol Pemutaran:** Fungsi dasar Putar (*Play*), Jeda (*Pause*), dan Hentikan (*Stop*).

---

## 🛠️ Teknologi yang Digunakan

Proyek ini dibuat dengan mempertimbangkan portabilitas dan kinerja. Berikut adalah teknologi utama yang diasumsikan digunakan:

| Kategori | Teknologi | Deskripsi |
| :--- | :--- | :--- |
| **Bahasa Pemrograman** | Python 3.x | Bahasa inti untuk logika aplikasi. |
| **Kerangka Kerja GUI** | Kivy / Tkinter (Asumsi) | Digunakan untuk membangun antarmuka pengguna grafis (GUI) yang kompatibel lintas platform. |
| **Jaringan & Data** | `requests` | Untuk menangani permintaan HTTP/HTTPS, seperti mengambil URL *stream* atau data stasiun. |
| **Pemutaran Audio** | PyAudio / Pydub (Asumsi) | Pustaka untuk menangani pemutaran *stream* audio secara real-time. |

---

## ⚙️ Prasyarat Instalasi

Sebelum memulai, pastikan Anda telah menginstal perangkat lunak berikut:

1.  **Python 3.x** (Versi 3.6 atau lebih tinggi direkomendasikan).
2.  **`pip`** (Manajer paket Python).
3.  **Dependensi Sistem (Opsional):** Beberapa pustaka audio mungkin memerlukan dependensi sistem seperti PortAudio (untuk PyAudio).

## 💻 Instalasi dan Penyiapan

Ikuti langkah-langkah di bawah ini untuk menjalankan aplikasi di mesin lokal Anda.

### 1. Kloning Repositori

Gunakan `git` untuk mengkloning proyek ini ke komputer Anda:

```bash
git clone [https://github.com/pashya166/Radio.on.git](https://github.com/pashya166/Radio.on.git)
cd Radio.on
