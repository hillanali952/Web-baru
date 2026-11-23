# PES Face Generator (web)

Foto -> wajah PES 2021 PC. Jalan di browser HP/PC, tanpa server. Foto tidak diunggah.

## Pasang di GitHub Pages (bisa dari HP)
1. Buat repo baru di github.com (publik), mis. `pes-face`.
2. Add file -> Upload files -> pilih SEMUA file di folder ini (bukan zip-nya) -> Commit.
3. Settings -> Pages -> Source: "Deploy from a branch", Branch: main, folder: / (root) -> Save.
4. Tunggu 1-2 menit, buka https://NAMA-ANDA.github.io/pes-face/
5. Di Chrome: menu -> "Tambahkan ke layar utama" supaya seperti aplikasi.

## Pakai
1. Pilih zip template wajah PES 2021 (berisi face.fpk). Cukup sekali.
2. Pilih foto depan. Geser titik hijau bila perlu.
3. Isi ID wajah dan nama folder, tekan "Buat wajah", unduh ZIP.

## Opsional: model landmark lokal
Taruh `face_landmarker.task` di root repo agar tidak diunduh dari internet tiap kali.
