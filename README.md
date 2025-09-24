![alt text](https://g.top4top.io/p_35541mox51.png?raw=true)

🧠 Gambaran Umum Script

Script ini adalah alat otomatisasi untuk:
1. Mengonversi domain ke IP
2. Mendeteksi jenis CMS (Content Management System) dari sebuah website
3. Menyimpan IP yang menggunakan WordPress

Fitur utama:
1. Multi-threading (hingga 900 thread sekaligus)
2. Deteksi CMS berbasis konten HTML
3. Penyimpanan IP untuk WordPress
4. CLI berwarna agar mudah dibaca

🎯 Tujuan Utama Script

Script ini digunakan untuk:
1. Mengubah list domain menjadi IP
2. Mengecek jenis CMS (Content Management System) yang digunakan oleh website (khususnya WordPress)
3. Menyimpan IP domain yang menggunakan WordPress ke file cms/wordpress.txt

✍️ Catatan Emosional:
1. WordPress satu-satunya CMS yang disimpan IP-nya, menunjukkan bahwa skrip ini spesifik untuk WordPress hunter.
2. CMS lain hanya untuk informasi tambahan saja (tidak disimpan ke file).
3. cms_cache dipakai untuk menghindari pengecekan berulang terhadap domain yang sama.

📁 Output dan Struktur File

Jika menemukan WordPress:
1. Direktori cms/ akan dibuat jika belum ada.
2. IP disimpan ke cms/wordpress.txt

😈 Intent atau Emosi Tersirat
1. Fokus pada WordPress Hunting – mungkin untuk security scanning, auditing, atau bahkan automation exploit.
2. User Experience diperhatikan – pemakaian warna dan output yang rapi.
3. Speed & Scale – kemampuan threading tinggi, cocok untuk scan ribuan domain.
4. Gaya underground/hackertool – banner, style, penamaan, dan komentar.
