# Cara build APK tanpa Android Studio di HP

Project ini sudah memiliki workflow GitHub Actions untuk membangun APK debug di cloud. Lingkungan ChatGPT saat ini tidak dapat mengunduh Android SDK/Gradle dari internet, jadi APK tidak bisa dikompilasi langsung di sini.

1. Unduh ZIP project dan ekstrak.
2. Masuk ke GitHub dan buat repository baru (misalnya `chess-overlay-prototype`).
3. Upload semua isi folder project ke repository, termasuk folder `.github/workflows`.
4. Buka tab **Actions** pada repository.
5. Pilih workflow **Build Android APK**, lalu tekan **Run workflow** (atau push ke branch `main`).
6. Saat job selesai dengan tanda hijau, buka hasil run dan bagian **Artifacts**.
7. Unduh `chess-overlay-debug-apk`, ekstrak ZIP hasil artifact, lalu pindahkan `app-debug.apk` ke HP Android dan instal. Android mungkin meminta izin instal aplikasi dari sumber tersebut.

## Batasan fitur

APK ini hanya prototipe tampilan overlay dengan contoh teks tetap. Ia belum membaca layar Discord, mengenali bidak, atau menghitung langkah otomatis. Jangan gunakan sebagai APK analisis otomatis; fitur tersebut belum dibuat.
