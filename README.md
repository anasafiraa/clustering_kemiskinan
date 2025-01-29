# Penerapan Metode Clustering sebagai Strategi Penanganan Khusus Kemiskinan di Jakarta

## Deskripsi
Proyek ini bertujuan untuk menerapkan algoritma K-Means dan Agglomerative Clustering dalam mengelompokkan wilayah di DKI Jakarta berdasarkan tingkat kemiskinan. Data yang digunakan mencakup berbagai faktor seperti persentase penduduk miskin, tingkat pengangguran, pengeluaran per kapita, rata-rata lama sekolah (RLS), serta Indeks Pembangunan Manusia (IPM). Data ini dikumpulkan dari Badan Pusat Statistik (BPS) DKI Jakarta selama periode 2011-2022. Dengan metode klasterisasi, proyek ini membantu Pemerintah DKI Jakarta mengidentifikasi wilayah yang membutuhkan penanganan khusus berdasarkan pola kemiskinan yang ditemukan dalam data.

## Tujuan
- Menganalisis data kemiskinan di DKI Jakarta untuk mengidentifikasi wilayah yang memiliki pola kemiskinan serupa.
- Menerapkan algoritma klasterisasi untuk mengelompokkan wilayah berdasarkan karakteristik kemiskinan.
- Memberikan rekomendasi strategi penanganan kemiskinan berdasarkan hasil klasterisasi.

## Dataset
Dataset yang digunakan berasal dari BPS DKI Jakarta dengan variabel sebagai berikut:
- Persentase Penduduk Miskin (%) – Persentase penduduk yang memiliki pengeluaran per kapita di bawah garis kemiskinan.
- Tingkat Pengangguran (%) – Persentase jumlah pengangguran terhadap total angkatan kerja.
- Rata-rata Lama Sekolah (RLS) (tahun) – Jumlah tahun pendidikan yang telah ditempuh oleh penduduk.
- Pengeluaran Per Kapita (ribu rupiah) – Rata-rata pengeluaran per kapita per bulan yang mencerminkan daya beli masyarakat.
- Indeks Pembangunan Manusia (IPM) – Indeks yang mencerminkan kualitas hidup melalui pendidikan, kesehatan, dan standar hidup layak.

## Metode
Proyek ini menggunakan dua algoritma klasterisasi untuk menganalisis data:
- K-Means Clustering
  - Algoritma K-Means membagi data ke dalam sejumlah klaster yang telah ditentukan sebelumnya. Dalam proyek ini, K-Means digunakan untuk mengidentifikasi pola kemiskinan berdasarkan data yang tersedia.
  - Penentuan jumlah klaster optimal dilakukan dengan metode Elbow Method dan Silhouette Score.
- Agglomerative Clustering
  - Metode klasterisasi hierarkis yang tidak memerlukan jumlah klaster yang ditentukan sebelumnya.
  - Dendrogram digunakan untuk menentukan jumlah klaster optimal berdasarkan jarak antar klaster.

## Tahapan Implementasi
- Pra-Pemrosesan Data:
  - Memeriksa dan membersihkan data dari nilai yang hilang atau duplikat.
  - Melakukan standarisasi data agar semua variabel memiliki skala yang seragam, jika diperlukan.
- Penerapan K-Means:
  - Menentukan jumlah klaster menggunakan Elbow Method dan Silhouette Score.
  - Menerapkan algoritma K-Means dan memvisualisasikan hasilnya.
- Penerapan Agglomerative Clustering:
  - Membuat dendrogram untuk menentukan jumlah klaster optimal.
  - Menerapkan Agglomerative Clustering dan memvisualisasikan hasilnya.

Setelah wilayah dikelompokkan ke dalam klaster, dilakukan analisis lebih lanjut untuk memberikan rekomendasi strategi penanganan kemiskinan sesuai dengan karakteristik masing-masing klaster.

## Hasil dan Rekomendasi

Hasil klasterisasi membagi wilayah menjadi beberapa kelompok dengan karakteristik kemiskinan yang serupa. Berdasarkan hasil tersebut, berikut adalah rekomendasi strategi penanganan kemiskinan di DKI Jakarta:

### 1. Klaster 2 "Sangat Miskin" (Prioritas 1)
Strategi Penanganan:
- Meningkatkan Akses Pendidikan dan Kesehatan:
  Memperkuat layanan pendidikan dasar dan kesehatan sebagai langkah utama dalam upaya pengentasan kemiskinan.
- Pemberian Bantuan Sosial:
  Memberikan bantuan langsung kepada keluarga miskin untuk memenuhi kebutuhan dasar seperti pangan, perumahan, dan pendidikan.
- Program Pelatihan Keterampilan:
Menyediakan pelatihan keterampilan kerja guna meningkatkan daya saing di pasar tenaga kerja.
- Subsidi Kesehatan dan Jaminan Sosial:
Menyediakan layanan kesehatan yang lebih terjangkau, termasuk asuransi kesehatan bagi keluarga miskin.

Penduduk dalam klaster ini memiliki tingkat kemiskinan yang sangat tinggi (>10%) dan angka pengangguran yang besar. Mereka membutuhkan intervensi langsung untuk memenuhi kebutuhan dasar dan meningkatkan peluang ekonomi. (Sumber: World Bank, 2021; UNDP, 2020)

## 2. Klaster 0 "Miskin" (Prioritas 2)
Strategi Penanganan:
- Pembangunan Infrastruktur Ekonomi:
Meningkatkan infrastruktur dasar seperti jalan, listrik, dan transportasi untuk membuka akses pasar dan lapangan kerja.
- Pemberdayaan Ekonomi Lokal:
Mendorong usaha mikro, kecil, dan menengah (UMKM) serta memberikan modal usaha untuk mengembangkan wirausaha lokal.
- Pengembangan Program Pendidikan dan Keterampilan:
Meningkatkan kualitas pelatihan kerja dan pendidikan lanjutan agar penduduk dapat beradaptasi dengan pasar tenaga kerja yang lebih luas.
- Program Kesehatan Preventif:
Memberikan program kesehatan preventif dan penyuluhan gizi untuk mengurangi pengeluaran akibat masalah kesehatan.

Penduduk dalam klaster ini memiliki tingkat kemiskinan sedang, tetapi tidak ekstrem. Strategi ini bertujuan untuk memperbaiki kondisi mereka dengan membuka akses ke peluang ekonomi dan sosial. (Sumber: ADB, 2020; Bappenas, 2019)

### 3. Klaster 0 "Rentan Miskin" (Prioritas 3)
Strategi Penanganan:
- Memperkuat Ketahanan Sosial dan Ekonomi:
Mendorong diversifikasi sumber pendapatan dan menciptakan lapangan kerja di sektor-sektor baru seperti digital dan teknologi.
- Program Perlindungan Sosial dan Asuransi:
Memberikan perlindungan sosial seperti asuransi pengangguran atau dana darurat untuk mengurangi kerentanan terhadap guncangan ekonomi.
- Fasilitas Pembiayaan dan Kredit Usaha:
Menyediakan skema pembiayaan yang lebih mudah diakses bagi UMKM dan wirausahawan baru.
- Penyuluhan Manajemen Keuangan dan Investasi:
Memberikan pelatihan tentang manajemen keuangan keluarga dan perencanaan jangka panjang.

Penduduk dalam klaster ini belum tergolong miskin, tetapi rentan terhadap penurunan ekonomi. Strategi yang proaktif diperlukan untuk menjaga stabilitas keuangan mereka dan mencegah jatuh ke dalam kemiskinan. (Sumber: ILO, 2019; BPS, 2021)

## Kesimpulan
Setiap klaster memiliki kebutuhan dan tantangan yang berbeda. Oleh karena itu, strategi penanganan disusun berdasarkan prioritas dan kondisi masing-masing klaster, mulai dari intervensi langsung bagi kelompok sangat miskin hingga penguatan ketahanan ekonomi bagi kelompok rentan miskin. Strategi ini bertujuan untuk menciptakan kondisi yang lebih baik dan mencegah kemiskinan yang lebih dalam bagi seluruh lapisan masyarakat.

# Kontak
Untuk pertanyaan atau saran lebih lanjut, hubungi saya di anasafira579@gmail.com.
