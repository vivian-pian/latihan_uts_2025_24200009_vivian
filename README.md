Buatlah external style sheet berdasarkan petunjuk berikut ini:

1. Definisikan Variabel CSS di :root
--primary: gunakan warna #2c3e50
--accent: gunakan warna #6c63ff
--gradient-bg: buat gradien dari kiri ke kanan dengan kombinasi #6c63ff, #7b68ee, dan #a067e3
--text: gunakan warna #333

2. Atur Reset CSS
Terapkan box-sizing: border-box untuk semua elemen.
Hilangkan margin dan padding default.

3. Atur Tampilan body
Gunakan font 'Inter', sans-serif
Latar belakang #f4f6fa
Warna teks menggunakan variabel --text

4. Desain Bagian header
Gunakan latar belakang gradien dari variabel --gradient-bg
Warna teks putih
Padding atas bawah 80px, kiri kanan 20px
Teks rata tengah
Untuk elemen <h1> dalam header:
Ukuran font 3rem
Tebal font 800
Margin bawah 15px
Untuk elemen <p> dalam header:
Ukuran font 1.2rem
Margin bawah 30px

5. Desain Tombol cta-btn
Warna latar putih, teks menggunakan warna --accent
Padding 12px atas bawah dan 24px kiri kanan
Border radius 30px, tanpa border
Ukuran font 1rem dan tebal 600
Tambahkan efek hover: ubah latar belakang jadi #ddd

6. Desain section Konten
Padding 60px atas bawah dan 20px kiri kanan
Lebar maksimum 1100px dan berada di tengah (center)
Teks rata tengah
Untuk elemen h2 dalam section:
Ukuran font 2rem
Margin bawah 20px
Warna menggunakan --primary
Untuk elemen p dalam section:
Ukuran font 1.1rem
Margin bawah 30px
Batasi lebar maksimum 800px dan pusatkan ke tengah

7. Tambahkan Border pada Section Aktivitas
Tambahkan garis atas 1px dashed gray untuk class .activities

8. Buat Grid Aktivitas
Gunakan class .activity-grid dengan:
Display: grid
Kolom otomatis dengan minimal 250px per elemen
Jarak antar item (gap) 30px
Margin atas 40px

- Untuk tiap .activity:
  Latar putih, padding 30px atas bawah dan 20px kiri kanan
  Border radius 12px
  Efek bayangan halus (box-shadow)
  Transisi halus saat hover → naik sedikit translateY(-5px)
 
- Untuk ikon di dalam aktivitas (.activity i):
  Ukuran font 2.5rem
  Warna menggunakan --accent
  
- Untuk judul aktivitas (.activity h3):
  Ukuran font 1.3rem
  Warna --primary

9. Desain Footer
Latar belakang #222, teks #bbb
Rata tengah, padding 30px atas bawah dan 20px kiri kanan
Margin atas 40px

10. Responsif di Mobile (max-width: 768px)
Ukuran font header <h1> menjadi 2.2rem
Ukuran paragraf di section menjadi 1rem
