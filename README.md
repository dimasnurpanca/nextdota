# Next Dota

**Next Dota** adalah asisten *gameplay* Dota 2 berbasis desktop yang dirancang untuk membantu Anda memenangkan fase draft dan memantau objektif penting di dalam game secara otomatis. Aplikasi ini berjalan secara cerdas di latar belakang (*background*) dan dapat diakses melalui *system tray* (mini taskbar) serta *in-game overlay*.

---

## 🚀 Fitur Utama

1. **Auto Hero Grid Sync**
   * Mengunduh konfigurasi grid hero kustom langsung berdasarkan meta dengan win rate tertinggi (auto update).
   * Secara otomatis menyinkronkan grid hero kustom ke semua profil Steam di PC Anda tanpa konfigurasi manual tambahan.

2. **Enemy Matchups & Counters Overlay**
   * Mendeteksi draft musuh secara otomatis saat fase *drafting* dimulai.
   * Menampilkan daftar *lane counter* terbaik/terburuk serta statistik kemenangan game terhadap draf lawan.
   * Otomatis muncul saat masuk *match* dan menutup sendiri ketika game selesai atau keluar.

3. **Pro Build Tracker**
   * Menampilkan panduan build item terlengkap dari pro player (item awal, timeline pembelian item, dan talents).
   * Panduan urutan menaikkan skill hero secara *real-time* yang disesuaikan dengan peran (POS 1 hingga POS 5) yang dipilih.

4. **Smart Voice Reminders (Notifikasi Suara)**
   * Pengingat suara yang memberitahukan objektif penting tepat waktu sebelum terjadi:
     * **Creep Camp Stacking** (detik ke-53)
     * **Bounty, Water, Power, dan Wisdom Runes**
     * **Healing Lotus** di kolam samping
     * **Stok Ward** di shop (Observer Ward penuh/stok 3)
   * Menyediakan 2 pilihan bahasa: **Bahasa Indonesia (Slang/Friendly)** dan **Bahasa Inggris**.

5. **Auto Agro Macro & Utility**
   * Macro pintasan untuk memicu agro creep secara instan (*Auto Agro*) guna mempermudah laning phase Anda (mendukung tombol keyboard dan tombol mouse samping seperti Mouse Button 4/5).
   * Pengaturan toggle visibilitas overlay secara manual melalui hotkey `Alt + O`.

6. **Interactive Overlay Settings**
   * Pengaturan volume suara, mengaktifkan/menonaktifkan jenis alert tertentu, mengubah bahasa suara, dan menyesuaikan hotkey langsung dari tab pengaturan overlay.

---

## 🎮 Cara Penggunaan In-Game (CTRL + TAB)

Aplikasi menggunakan mode overlay transparan canggih di dalam game:

* **Mode Interaktif (`Ctrl + Tab`)**:
  * Menekan `Ctrl + Tab` di dalam game Dota 2 akan masuk ke **Mode Interaktif**.
  * Di mode ini, kursor mouse Anda dapat berinteraksi dengan overlay untuk memilih bahasa, mengubah peran (POS), memencet tombol, mengubah pengaturan macro, dan menyesuaikan konfigurasi.
* **Mode Pasif/Gameplay (`Ctrl + Tab` kembali)**:
  * Menekan `Ctrl + Tab` sekali lagi akan mengembalikan overlay ke **Mode Pasif**.
  * Di mode ini, kursor/klik mouse Anda akan langsung menembus overlay (*click-through*) ke game Dota 2 Anda agar gameplay tidak terganggu.
  * Transparansi (Opacity) overlay akan berkurang secara otomatis sesuai dengan persentase yang Anda atur.
* **Pengaturan Transparansi (Overlay Opacity)**:
  * Anda dapat menyesuaikan transparansi overlay saat Mode Pasif melalui tab **Settings -> Overlay Settings**.
  * Dilengkapi dengan range slider (5% hingga 100%) dan live preview langsung tanpa perlu restart aplikasi.

---

## ⚙️ Petunjuk Penggunaan

Jalankan `Next Dota.bat` untuk memulai aplikasi.

> [!NOTE]
> File launcher `Next Dota.bat` secara otomatis akan memeriksa dan mematikan (*kill*) proses lama yang masih berjalan di latar belakang untuk mencegah konflik hotkey, kemudian memulai aplikasi secara bersih.

---
