# LILITH NOTCH

Notch untuk Windows: panel kecil di tepi layar yang menampilkan jam, musik Spotify,
metrik sistem, pengingat, dan asisten AI, lengkap dengan karakter yang mengambang di layar.

## Unduh dan pasang

1. Buka halaman [Releases](../../releases/latest) dan unduh berkas `LILITH-NOTCH_..._x64-setup.exe`.
2. Jalankan berkasnya. Aplikasi terpasang untuk pengguna Windows saat ini (tanpa hak admin).
3. Aplikasi memperbarui dirinya sendiri dari rilis di halaman ini. Tidak perlu instal ulang.

### Peringatan "Windows protected your PC" (SmartScreen)
Aplikasi ini belum memakai sertifikat penanda tangan kode berbayar, jadi Windows bisa
memperingatkan saat pertama kali dijalankan. Periksa dulu SHA-256 berkas di catatan rilis,
lalu pilih **More info > Run anyway** bila cocok.

## Privasi

- **Kunci API asisten** disimpan di Windows Credential Manager milikmu sendiri. Kunci tidak
  dikirim ke server proyek ini dan tidak ikut dalam pembaruan.
- **Obrolan asisten** hanya dikirim ke penyedia AI yang kamu pilih (Gemini, Groq, Claude, dan
  lainnya, atau Ollama yang berjalan lokal). Riwayat obrolan disimpan di komputermu.
- **Pembaruan otomatis** hanya menghubungi github.com untuk memeriksa versi baru. Alamat IP dan
  versi aplikasi terlihat oleh GitHub. Bisa dimatikan di Pengaturan > Pembaruan.
- Fitur yang membaca data (papan klip, metrik sistem, cuaca) bersifat terbatas dan
  bisa dimatikan di Pengaturan.

## Dukungan

Sistem operasi: Windows 10/11 (64-bit). Laporkan masalah lewat tab Issues di repo ini.
