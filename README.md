# Peony Point — Berkas Rilis

Repo ini **hanya berisi berkas rilis** aplikasi Peony Point (installer Windows), bukan kode
sumber. Kode sumber disimpan di repo privat terpisah.

Setiap rilis menerbitkan:

- `Peony-Point-Setup-<versi>.exe` — installer untuk mesin toko
- `Peony-Point-Setup-<versi>.exe.blockmap` — metadata unduhan sebagian (delta)
- `Peony-Point-<versi>-Portable.exe` — versi tanpa instalasi, untuk mencoba
- `latest.yml` — hanya mulai versi yang sudah punya fitur periksa pembaruan

## Memasang

1. Unduh `Peony-Point-Setup-<versi>.exe` versi terbaru dari halaman **Releases**.
2. Jalankan installer, pilih folder bila diminta, lalu tunggu selesai.
3. Data toko tetap tersimpan di `%APPDATA%\Peony Point` dan tidak dihapus oleh pembaruan.

Versi lama sengaja tidak dihapus agar bisa dipakai kembali bila versi baru bermasalah.
