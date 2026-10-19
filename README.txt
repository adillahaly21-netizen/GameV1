PETUALANGAN SI CAMPURAN — PANDUAN PEMULA

Isi paket:
- index.html: seluruh game (HTML, CSS, JavaScript) dalam satu file.
- Tidak perlu menginstal framework atau mengunduh gambar/suara dari internet.
- Bisa dibuka offline setelah file tersimpan di perangkat.

CARA MENJALANKAN DI KOMPUTER
1. Ekstrak file ZIP.
2. Buka folder petualangan_si_campuran.
3. Klik dua kali index.html.
4. Game terbuka di Chrome, Edge, Firefox, atau browser modern lain.
5. Klik "Mulai / Lanjutkan". Gunakan tombol panah kiri/kanan dan Spasi/atas.

CARA MENJALANKAN DI HP ANDROID
1. Ekstrak ZIP memakai aplikasi pengelola berkas.
2. Buka index.html dengan browser. Jika pengelola berkas tidak menawarkan browser, pindahkan folder ke komputer atau unggah sebagai website.
3. Gunakan tombol kiri, kanan, dan lompat di bawah area game.

CARA MENERBITKAN GRATIS DENGAN GITHUB PAGES
1. Masuk ke GitHub dan buat repository baru, misalnya petualangan-si-campuran.
2. Unggah index.html ke halaman utama repository (root).
3. Buka Settings > Pages.
4. Pada Build and deployment, pilih Deploy from a branch.
5. Pilih branch main dan folder /(root), lalu Save.
6. Tunggu beberapa menit. GitHub akan menampilkan URL Pages untuk dibagikan.
7. Buka URL itu sekali saat online. Untuk mode offline di perangkat, unduh file ZIP dan buka index.html secara lokal.
Catatan: versi ini belum memasang service worker/PWA. Karena semua kode ada dalam satu file tanpa aset eksternal, file lokal dapat dimainkan offline. Website yang dibuka lewat URL tidak otomatis bisa offline jika belum pernah di-cache oleh browser.

FITUR
- Platformer dengan gerak, lompat, kristal, rintangan, nyawa, dan 10 level.
- Kuis pilihan ganda dari beberapa mata pelajaran SMA.
- Skor: kristal +25, jawaban benar +100, level selesai +250, bonus nyawa +20 per nyawa.
- Efek suara sederhana memakai Web Audio setelah interaksi pengguna.
- Papan peringkat lokal, laporan belajar, dan ekspor CSV.
- Nama pemain/tim dapat diganti.

BATASAN PENTING
- Papan peringkat dan data tersimpan di browser/perangkat yang sama (localStorage), belum tersinkron antarperangkat atau antarpemain secara online.
- Untuk permainan multiplayer online sungguhan, akun, dan peringkat global, perlu backend/database dan pengamanan tambahan.
- Isi soal adalah contoh pembelajaran. Guru sebaiknya meninjau dan menyesuaikannya dengan kurikulum sekolah sebelum digunakan untuk penilaian resmi.
- Hindari menyimpan nama lengkap, NISN, atau data sensitif siswa di versi demo.
