# Domain Extractor

Domain Extractor adalah alat web sederhana untuk mengekstrak nama domain dari teks atau daftar URL.

Demo: https://mister-rdanm19.github.io/Domain-Extractor/

Deskripsi

Alat ini mengambil teks atau kumpulan URL yang Anda masukkan dan mengekstrak domain unik (root domain) seperti example.com. Sangat berguna untuk membersihkan daftar URL, melakukan analisis, atau mendapatkan daftar target domain dari teks mentah.

Fitur

- Ekstraksi domain dari teks atau daftar URL (dengan atau tanpa protokol)
- Menghapus duplikat secara otomatis
- Menyajikan daftar domain unik yang dapat disalin
- Ekspor hasil (copy dan kemungkinan unduh sebagai teks)
- Antarmuka web ringan dan mudah digunakan

Cara Pakai (Web)

1. Kunjungi demo: https://mister-rdanm19.github.io/Domain-Extractor/
2. Tempelkan teks atau daftar URL ke area input.
3. Klik tombol "Extract" atau "Ekstrak".
4. Salin atau ekspor daftar domain yang muncul.

Menjalankan Secara Lokal

Repository ini adalah situs statis (HTML/CSS/JS). Untuk menjalankan secara lokal, cukup buka `index.html` di browser, atau jalankan server statis sederhana:

- Menggunakan Python 3:

  python -m http.server 8000

  lalu buka http://localhost:8000

- Menggunakan Node (http-server):

  npx http-server . -p 8000

Kontribusi

Perbaikan bug, fitur baru, atau perbaikan dokumentasi sangat disambut. Silakan buka issue atau ajukan pull request.

Lisensi

Lisensi proyek ini mengikuti lisensi yang ada di repository. Jika belum ada, tambahkan LICENSE sesuai kebutuhan.

Kontak

Dibuat oleh Mister-RdanM19. Demo online tersedia di: https://mister-rdanm19.github.io/Domain-Extractor/
