# NoahDroid

Aplikasi Android native sederhana berbasis Kotlin.

## Fitur
- Tampilan gelap sederhana
- Tombol penghitung dan reset
- Mendukung Android 6.0 (API 23) ke atas
- GitHub Actions membangun APK debug secara otomatis

## Cara mendapatkan APK di HP Android
1. Buka tab **Actions** di repo GitHub ini.
2. Pilih proses **Build Android APK** yang paling baru dan tunggu sampai statusnya hijau.
3. Di bagian **Artifacts**, unduh `NoahDroid-debug-apk`. File yang diunduh berupa ZIP.
4. Buka ZIP lewat aplikasi Files/File Manager, lalu ekstrak `app-debug.apk`.
5. Ketuk file APK. Jika Android meminta izin, izinkan pemasangan aplikasi dari sumber tersebut untuk aplikasi yang sedang digunakan, lalu pilih **Install**.

Jika Android menolak pemasangan, pastikan build terbaru berstatus sukses dan tidak ada versi NoahDroid lama dengan tanda tangan berbeda yang terpasang. APK debug ini untuk pengujian dan belum dipublikasikan di Play Store.

## Build APK
Workflow **Build Android APK** berjalan otomatis setiap ada push ke branch `main`. Bisa juga dijalankan manual melalui **Actions** → **Build Android APK** → **Run workflow**.
