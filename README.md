# Proyek Analisis Data Transjakarta

## Deskripsi
Proyek ini menganalisis data transaksi **Transjakarta** untuk memahami pola perjalanan penumpang, preferensi, dan tantangan operasional. Analisis ini bertujuan memberikan wawasan berbasis data guna meningkatkan efisiensi layanan dan kenyamanan bagi pengguna Transjakarta di Jakarta.

## Tujuan Proyek
1. **Menganalisis Pola Perjalanan Penumpang**: Mengidentifikasi tren penggunaan Transjakarta berdasarkan waktu, rute, dan demografi.
2. **Meningkatkan Efisiensi Operasional**: Menentukan area yang perlu ditingkatkan untuk mengoptimalkan layanan.
3. **Memberikan Rekomendasi Berbasis Data**: Saran untuk pengelolaan transportasi yang lebih baik.

## Fitur Utama
- **Pembersihan Data**: Melakukan pembersihan data untuk mengatasi nilai yang hilang atau tidak valid.
- **Analisis Tren**: Mengekstraksi dan menganalisis tren utama dari data, seperti jumlah penumpang harian, rute populer, dan waktu puncak.
- **Visualisasi Data**: Menggunakan **Tableau Public** dan Python untuk visualisasi yang mendukung hasil analisis, memberikan gambaran yang jelas.

## Struktur Proyek
1. **data**: Folder ini berisi dataset mentah (`Transjakarta.csv`) serta dataset yang telah diproses.
2. **notebooks**: Berisi notebook Jupyter, termasuk `code.ipynb`, untuk eksplorasi data, pembersihan data, dan analisis.
3. **scripts**: Kode Python yang menjalankan proses pembersihan, analisis, dan visualisasi secara otomatis.
4. **reports**: Menyediakan laporan hasil analisis dalam bentuk visualisasi atau dokumen PDF.
5. **tableau_visualizations**: Menyimpan tautan ke visualisasi yang dibuat di **Tableau Public**.

## Prasyarat
- **Python 3.10
- **Pandas** untuk manipulasi data
- **Matplotlib/Seaborn** untuk visualisasi data
- **Jupyter Notebook** untuk eksplorasi dan analisis interaktif
- **Tableau Public** untuk visualisasi data

## Struktur Dataset
Dataset `Transjakarta.csv` berisi informasi sebagai berikut:
- **Tanggal**: Tanggal operasional
- **Rute**: Nama atau kode rute Transjakarta
- **Jumlah Penumpang**: Jumlah penumpang per rute per hari
- **Waktu**: Waktu keberangkatan atau waktu puncak operasional

## Hasil Akhir
- **Visualisasi Tren**: Grafik harian/mingguan untuk jumlah penumpang, rute populer, dan waktu puncak.
- **Insight Utama**: Rekomendasi untuk perbaikan layanan berdasarkan insight data yang di dapatkanb.

## Insight Utama
- **Demografi Pengguna**: Pengguna utama Transjakarta adalah pria berusia 30-40 tahun, namun pengguna usia 21-40 lebih banyak didominasi perempuan.
- **Jam Sibuk dan Hari Kerja**: Penggunaan tertinggi terjadi pada hari kerja, menunjukkan bahwa mayoritas pengguna adalah pekerja.
- **Lokasi Tap In dan Tap Out Populer**: Titik-titik utama seperti Penjaringan dan BKN memiliki volume tinggi, menunjukkan kebutuhan peningkatan layanan di area ini.

## Rekomendasi
1. **Peningkatan Layanan pada Jam Sibuk**: Tambah jumlah bus pada jam 5 pagi dan 5 sore untuk mengurangi kepadatan.
2. **Penyesuaian Jadwal Berdasarkan Hari Kerja**: Tingkatkan frekuensi layanan pada hari Senin-Jumat.
3. **Layanan Khusus untuk Perempuan**: Tambahkan bus khusus perempuan pada jam sibuk.
4. **Fasilitas Khusus untuk Lansia**: Sediakan area duduk yang lebih nyaman bagi lansia dekat pintu masuk/keluar.
5. **Peningkatan Fasilitas Halte Populer**: Tingkatkan fasilitas di halte-halte dengan tap-in/tap-out tinggi.
6. **Aplikasi Mobile dengan Informasi Real-Time**: Berikan informasi kepadatan bus dan estimasi waktu kedatangan melalui aplikasi untuk membantu perencanaan perjalanan pengguna.
7. **Frekuensi Bus di Rute Tap-In/Tap-Out Tinggi**: Tingkatkan frekuensi bus di rute yang memiliki volume penumpang tinggi.
