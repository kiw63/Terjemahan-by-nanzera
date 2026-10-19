LINGUASHELF — PEMBACA PDF TERJEMAHAN
====================================

Isi paket
---------
- index.html : website LinguaShelf

PENTING: hosting melalui HTTPS (contohnya GitHub Pages) disarankan. Membuka index.html langsung dari aplikasi File/Downloads dapat membuat browser memblokir PDF worker.

CARA MEMASANG DI GITHUB PAGES
-----------------------------
1. Unduh lalu ekstrak ZIP ini.
2. Di GitHub, buat repository baru, atau buka repository website kamu yang sudah ada.
3. Unggah index.html ke folder utama repository (root), lalu commit perubahan.
   Jika repository sudah memiliki index.html, buat salinan cadangan terlebih dahulu sebelum menggantinya.
4. Buka Settings -> Pages.
5. Di bagian Build and deployment, pilih Deploy from a branch.
6. Pilih branch main dan folder /(root), lalu tekan Save.
7. Tunggu GitHub Pages selesai menerbitkan website; buka alamat HTTPS yang ditampilkan di halaman Pages.

CARA MENGGUNAKAN
----------------
1. Buka website dengan koneksi internet.
2. Pilih PDF atau jatuhkan file ke area unggah.
3. Atur bahasa sumber (boleh Deteksi otomatis) dan bahasa tujuan.
4. Tekan Terjemahkan seluruh buku.
5. Untuk halaman scan/foto yang teksnya tidak terbaca, buka halaman itu dan tekan Kenali teks dengan OCR. Setelah OCR selesai, terjemahan akan berjalan.
6. Gunakan mode Asli + terjemahan untuk membandingkan hasil terjemahan dengan tampilan PDF asli.
7. Tekan Unduh teks .txt untuk mengunduh hasil terjemahan dengan nomor halaman.

LAYANAN DAN PRIVASI
-------------------
- Pembacaan PDF dilakukan di browser; file PDF tidak diunggah ke server LinguaShelf.
- Teks hasil ekstraksi/OCR dikirim ke penyedia terjemahan yang kamu pilih (MyMemory atau Google Cloud Translation) ketika proses terjemahan dijalankan.
- MyMemory tidak perlu API key, tetapi memiliki batas pemakaian dan kualitas terjemahan tidak dijamin sempurna.
- Google Cloud Translation memerlukan API key dan konfigurasi akun Google Cloud. Jangan menaruh API key pribadi pada website publik: pengunjung dapat melihat permintaan browser. Untuk penggunaan publik yang serius, gunakan backend/proxy yang aman.
- OCR mungkin perlu mengunduh model bahasa saat pertama kali dipakai, jadi koneksi internet diperlukan.

BATASAN
--------
LinguaShelf menjaga urutan serta nomor halaman dan menyediakan tampilan PDF asli untuk pembanding. Teks terjemahan ditata ulang agar mudah dibaca; ukuran kalimat yang berubah antarbahasa membuat tata letak, posisi baris, tabel, rumus, dan diagram tidak selalu bisa dipertahankan persis. Terjemahan mesin dan OCR dapat salah—periksa istilah penting, angka, serta rumus dengan PDF asli.
