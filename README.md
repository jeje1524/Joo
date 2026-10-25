# Chess Overlay Prototype (Android)

Starter project Android untuk menguji izin dan tampilan overlay.

## Yang tersedia
- Tombol untuk meminta izin "display over other apps".
- Contoh label overlay: `NEXT MOVE — BISHOP f8 → e7`.
- Tombol tampil/sembunyikan overlay.
- Workflow GitHub Actions di `.github/workflows/build-apk.yml` untuk membangun APK debug di cloud.

## Yang belum tersedia
- Belum menangkap layar Discord.
- Belum mengenali kotak atau bidak catur.
- Belum menjalankan mesin catur.
- Belum menggambar highlight kotak pada papan.

## Build
Lihat `BUILD_APK_ID.md` untuk langkah membangun APK debug melalui GitHub Actions. APK tidak dikompilasi langsung di lingkungan ini karena Android SDK/Gradle tidak tersedia dan unduhan internet diblokir.
