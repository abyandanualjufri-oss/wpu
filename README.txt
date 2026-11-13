WEBSITE BIODATA PRIBADI
=======================

Website PHP sederhana dengan beberapa halaman. Data biodata berada di satu
file data.php. Website ini tidak memakai database, MySQL, phpMyAdmin, login,
atau dashboard admin.

MENJALANKAN DENGAN XAMPP
------------------------
1. Pasang dan jalankan Apache dari XAMPP Control Panel.
2. Salin seluruh folder proyek ini ke C:\xampp\htdocs\biodata-pribadi.
3. Buka http://localhost/biodata-pribadi/ di browser.
4. PHP dijalankan melalui Apache; membuka file PHP langsung dari File Explorer
   tidak akan menjalankan kodenya.

MENGUBAH BIODATA
----------------
Edit data.php dengan editor teks atau VS Code. Ubah nilai di dalam array
$biodata untuk nama, alamat, pendidikan, hobi, keahlian, pengalaman,
prestasi, dan kontak. Daftar pendidikan, hobi, minat, keahlian, pengalaman,
prestasi, dan foto galeri menerima beberapa entri.

Gunakan tanda kutip tunggal untuk teks PHP. Jika teks mengandung apostrof,
gunakan tanda kutip ganda atau escape apostrof. Biarkan struktur array dan
tanda koma tetap sesuai format PHP.

GANTI FOTO
----------
Ganti assets/images/profil.svg dengan gambar profil pilihan Anda, lalu sesuaikan
nilai profile_image di data.php dengan nama/path gambar yang baru (contoh:
assets/images/profil.jpg). Ganti gambar galeri dan caption pada array gallery
di data.php dengan gambar milik Anda. Format JPG, PNG, WebP, dan SVG didukung.

CETAK ATAU SIMPAN SEBAGAI PDF
-----------------------------
Pilih tombol "Cetak / PDF" untuk membuka tampilan biodata lengkap dan dialog
cetak browser. Pilih "Save as PDF" atau "Simpan sebagai PDF". Tombol "Cetak
biodata" juga tersedia di halaman Biodata.

FITUR
-----
- Navigasi beranda, biodata, pendidikan, pengalaman, prestasi, dan kontak.
- Tema terang/gelap yang tersimpan di browser.
- Tata letak responsif, animasi ringan, dan galeri.
- Kontak email, telepon dan WhatsApp (telepon/WhatsApp opsional).
- Tidak ada proses pengumpulan atau penyimpanan data pengunjung.
