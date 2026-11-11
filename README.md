<div align="center">
  <img src="APIW.png" alt="Apiw Icon" width="96" />
  <h1>Apiw — Living Notch untuk Windows</h1>
  <p>
    Notch interaktif di bagian atas layar Windows 10 &amp; 11 dengan maskot beruang berjaket merah, kontrol musik + lirik sinkron, TodoList + OCR, File Shelf, jadwal sholat, dan asisten dokumen AI.
  </p>
  <p>
    <a href="https://justnaaa.github.io/Apiw/">🌐 Halaman Web (Landing Page)</a> ·
    <a href="https://github.com/justnaaa/Apiw/releases/latest/download/ApiwSetup.zip">⬇️ Download ApiwSetup.zip</a> ·
    <a href="https://github.com/justnaaa/Apiw/releases">📦 Releases</a>
  </p>
</div>

---

## Fitur Utama

- **Living Notch & Maskot Apiw:** Kapsul pintar di atas layar yang melebar saat disentuh kursor, bisa sembunyi otomatis di aplikasi layar penuh, dan menampilkan maskot beruang berjaket merah saat idle, ada notifikasi, waktu sholat (halo malaikat + kedip 3×), serta peringatan baterai lemah (≤ 20%).
- **Musik & Lirik Sinkron (LRCLIB):** Mendeteksi lagu dari Spotify, Chrome, Edge, VLC, dll. via Windows GSMTC lengkap dengan lirik sinkron dari [LRCLIB](https://lrclib.net).
- **TodoList Modern + Scan OCR:**
  - Klik **`+ Add Task`** untuk langsung mengetik task baru di daftar tanpa kolom tambahan.
  - Klik bagian teks tugas untuk menandai selesai, plus tombol **`Clear`** untuk menghapus semua task yang sudah selesai.
  - **Import / Scan File & Gambar (OCR):** Pilih atau seret gambar (`.png`/`.jpg`), `.pdf`, `.docx`, `.xlsx`, atau `.txt` agar daftar tugas langsung terbaca satu per satu secara rapi.
- **Apiw Document Studio & Voice AI (Opsional):**
  - Membaca halaman aktif Word, Excel, Notepad, dan file PDF/PDF Scan/DOCX/XLSX.
  - Jendela **Document Studio** untuk analisa lengkap, perbandingan revisi (*Before → After*), **Undo**, dan **Export `.DOCX`**, plus ngobrol suara (`Alt+Space`).
- **Today Widgets, Sholat, Air & Pomodoro:** Kalender mini bulan berjalan, animasi tipis saat mengecas, jadwal sholat offline, pengingat minum air, dan timer Pomodoro.
- **File Shelf & Auto Screenshot:** Drop file/folder dengan animasi masuk ke Shelf, pratinjau otomatis hingga 4 screenshot terbaru, dan tombol **Copy All** untuk menyalin semuanya sekaligus.

---

## Cara Instalasi

1. Unduh file [**`ApiwSetup.zip`**](https://github.com/justnaaa/Apiw/releases/latest/download/ApiwSetup.zip) dari halaman Releases.
2. **Ekstrak** `ApiwSetup.zip` (klik kanan → *Extract All...*). Di dalamnya terdapat 1 file **`ApiwSetup.exe`**.
3. Klik dua kali **`ApiwSetup.exe`** lalu ikuti langkah pemasangan sampai selesai.
   - Jika muncul jendela *Windows protected your PC* (SmartScreen), klik **More info → Run anyway**.
4. Apiw akan langsung muncul di bagian atas layar dan ikonnya ada di **System Tray** (pojok kanan bawah).
5. *(Opsional)* Untuk fitur AI Gemini/OpenAI, klik kanan ikon Apiw di System Tray → **Settings → AI & Voice**, lalu masukkan API key Anda sendiri.
   - Semua fitur inti (Musik, Lirik, TodoList, OCR lokal, Shelf, Pomodoro, Sholat, Maskot) **tetap berjalan tanpa API key**.

---

## Cara Uninstall (Menghapus Apiw)

1. Klik kanan ikon **Apiw** di **System Tray** (pojok kanan bawah taskbar), lalu pilih **Quit**.
2. Buka **Windows Settings → Apps → Installed apps** (di Windows 10: *Apps & features*).
3. Cari **Apiw**, klik menu titik tiga (`...`), lalu pilih **Uninstall**.
4. *(Opsional — jika ingin menghapus seluruh pengaturan, To-Do, dan dokumen yang dipelajari)* Tekan `Win + R`, ketik `%APPDATA%`, tekan Enter, lalu hapus folder **`apiw`**.

---

## Privasi & API Key

- Paket instalasi resmi tidak menyimpan API key apa pun (`""`).
- API key dan pengaturan yang Anda masukkan hanya tersimpan lokal di PC Anda sendiri (`%APPDATA%\apiw\apiw-config.json`).
