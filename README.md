 - Praktikum #8
Aplikasi Android modern berbasis Jetpack Compose yang dirancang untuk mengelola berbagai fitur multimedia, mulai dari pengambilan gambar melalui kamera, pengelolaan galeri, hingga pemutaran audio dan video dengan fitur interaktif.
🎯 Tujuan Praktikum
 * Pengelolaan Multimedia: Memahami konsep dasar audio, video, dan gambar pada platform Android.
 * Integrasi Kamera & Galeri: Mengambil foto langsung atau memilih media yang sudah ada.
 * Gesture Interaktif: Menerapkan fitur pinch zoom dan pan (geser) pada gambar dan video.
 * Audio & Video Playback: Mengimplementasikan perekam suara (Audio Recorder) dan pemutar video berbasis ExoPlayer dengan mode fullscreen.
 * Scoped Storage: Menyimpan foto secara permanen ke galeri perangkat menggunakan MediaStore.
🛠️ Stack Teknologi & Library
 * Bahasa: Kotlin
 * UI Framework: Jetpack Compose dengan Material 3
 * Navigasi: Navigation Compose
 * Multimedia:
   * ExoPlayer (Media3): Pemutaran video
   * MediaRecorder: Perekaman audio
   * Coil: Memuat dan menampilkan gambar
 * Izin (Permissions): Kamera dan Mikrofon (RECORD_AUDIO).
📂 Struktur Proyek
Aplikasi ini menggunakan arsitektur UI yang terstruktur untuk memisahkan setiap fitur:
p8_multimedia_nimanda/
├── MainActivity.kt        # Entry point aplikasi
├── ui/
│   ├── gallery/          # Fitur Camera & Gallery Screen
│   ├── home/             # Tampilan Utama (Dashboard)
│   ├── player/           # Fitur Audio Player
│   ├── recorder/         # Fitur Audio Recorder
│   ├── video/            # Fitur Video Player
│   └── theme/            # Konfigurasi Tema & Warna
├── NavGraph.kt           # Pengaturan navigasi antar screen
└── util/                 # Utility file management

🚀 Fitur Utama
 * Dashboard Interaktif: Header gradient dengan menu kartu untuk akses cepat ke setiap fitur.
 * Camera & Gallery: Mengambil foto dan menampilkannya di Image Preview tanpa berpindah screen.
 * Advanced Player: Pemutar video dengan kontrol lengkap, dukungan rotasi layar, dan fitur zoom/pan.
 * File Manager: Mengambil daftar file rekaman, mengubah nama (rename), dan menghapus file secara aman.
📝 Langkah Instalasi
 * Clone atau Download proyek ini.
 * Pastikan menggunakan Android Studio versi terbaru.
 * Gunakan Minimum SDK 24 (Android 7.0).
 * Lakukan Gradle Sync untuk mengunduh semua dependensi.
 * Jalankan aplikasi pada Real Device atau emulator yang mendukung kamera dan audio.
📊 Rubrik Penilaian
 * Implementasi Camera & Gallery (15%)
 * Image Preview (Zoom, Geser, Orientasi) (15%)
 * Penyimpanan ke MediaStore (10%)
 * Audio Recorder & Player (15%)
 * Video Player & Fullscreen (15%)
 * Manajemen File (10%)
Dosen Pengampu: Muhayat, M.IT
