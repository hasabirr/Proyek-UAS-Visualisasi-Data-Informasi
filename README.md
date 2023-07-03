# Visualisasi Interaktif Potret Provinsi Jawa Barat dalam SDGs
Repository ini sebagai dokumentasi resmi dari project visualisasi UAS Mata Kuliah Visualisasi Data dan Informasi yang hasilnya dapat diakses melalui tautan [berikut](https://public.tableau.com/app/profile/rafif.hasabi/viz/VisualisasiInteraktifPotretSDGs4ProvinsiJawaBarat/VisualisasiInteraktifPotretProvinsiJawaBaratdalamSDGs4). 

## Abstrak

Pendidikan merupakan tujuan keempat dalam Sustainable Development Goals (SDGs) yaitu mendorong pendidikan yang berkualitas, inklusif, setara, dan mendukung kesempatan belajar bagi setiap orang. Data pendidikan yang tersebar dan dari berbagai tahun membuat sulitnya mendapatkan akses data pendidikan secara keseluruhan. Selain itu data yang ada masih berupa tabel sehingga audiens data membutuhkan waktu untuk memahami data tersebut. Data pendidikan diperoleh dari website Badan Pusat Statistik dan Open Data Provinsi Jawa Barat. Penelitian ini berusaha mengimplementasikan visualisasi interaktif terkait potret Provinsi Jawa Barat dalam SDGs keempat untuk menyatukan data pendidikan yang beragam menjadi satu tempat berbentuk story board dan dilakukan evaluasi menggunakan kuesioner system usability scale. Penelitian ini menghasilkan visualisasi interaktif yang menarik serta dari hasil evaluasi diperoleh skor 81.5 yang dapat dikategorikan Excellent. Dari hasil uji Mann-Whitney diperoleh bahwa tidak terdapat perbedaan persepsi penilaian antara kalangan lingkup pendidikan dan kalangan masyarakat umum.

## Tujuan

1. Mengimplementasikan visualisasi data interaktif menggunakan Tableau terkait data pendidikan di Provinsi Jawa Barat dalam satu Story Board yang menarik.
2. Mengevaluasi visualisasi data interaktif yang telah dibuat berdasarkan persepsi penilaian oleh dua kelompok pengguna.

## Pengumpulan Data

>📋 Data terdiri dari data primer dan sekunder.

- Data primer dari hasil pengisian kuesioner System Usability Scale (SUS) untuk evaluasi visualisasi interaktif data pendidikan Provinsi Jawa Barat.
- Data dari website [Badan Pusat Statistik Provinsi Jawa Barat](https://jabar.bps.go.id/) seperti Indeks Pembangunan Manusia (IPM), Indeks Pendidikan, Angka Melek Huruf (AMH), Angka Partisipasi Murni (APM), Jumlah Sekolah, dan Rasio Guru dengan Murid.
- Data yang dari website [Open Data Provinsi Jawa Barat](https://opendata.jabarprov.go.id/id) adalah Ketersediaan Fasilitas Pendidikan.
- Data dari website [Indonesia Geospatial Portal](https://tanahair.indonesia.go.id/) yaitu data shape file batas administrasi Provinsi Jawa Barat.

## Alat yang Digunakan

1. Microsoft Excel untuk organisasi raw data hasil kuesioner SUS dan data visualisasi
2. Tableau Versi 2022.4 untuk membuat visualisasi interaktif berbentuk *story board*
3. IBM SPSS Statistics Versi 26 untuk melakukan uji *Mann-Whitney*
4. QGIS Desktop Versi 3.20.2 untuk melakukan pemotongan *shape file*

## Alur Penelitian

1. Pengumpulan data sekunder
2. *Preprocessing* data sekunder
3. Pemilihan *Chart* dan pembuatan visualisasi
4. Publikasi visualisasi ke Tableau *Public*
5. Evaluasi visualisasi interaktif
6. Analisis deskriptif dan inferensia

>📋 Alur penelitian dalam bentuk gambar dapat diakses melalui tautan [berikut](https://github.com/hasabirr/Proyek-UAS-Visualisasi-Data-Informasi/blob/main/Alur%20Penelitian/Alur%20Proyek%20Visdat.png)

## Hasil

Hasil yang diperoleh dari penelitian didasarkan pada tujuan yang ingin dicapai. Hasil tersebut dijabarkan dalam beberapa poin berikut.

### Visualisasi Interaktif Data Pendidikan Provinsi Jawa Barat

Hasil visualisasi dipublikasikan melalui server Tableau *Public* dan dapat diakses melalui tautan [berikut](https://public.tableau.com/app/profile/rafif.hasabi/viz/VisualisasiInteraktifPotretSDGs4ProvinsiJawaBarat/VisualisasiInteraktifPotretProvinsiJawaBaratdalamSDGs4). Visualisasi memuat fitur-fitur yang berkaitan dengan interaksi pengguna. Pengguna dapat mengatur tahun yang ingin ditampilkan, mengatur filter yang ingin digunakan, dan berpindah dari satu *story* ke *story* yang lainnya. Visualisasi interaktif ini akan maksimal apabila dijalankan pada Desktop dengan mode *full screen* dan koneksi internet yang memadai. Tampilan awal dari visualisasi adalah sebagai berikut. 

### Evaluasi Visualisasi Interaktif Data Pendidikan Provinsi Jawa Barat

Terdapat 10 responden dengan rincian 5 responden dari kalangan lingkup pendidikan dan 5 responden dari kalangan masyarakat umum. Evaluasi dilakukan dengan 10 pertanyaan berdasarkan kuesioer *System Usability Scale* (SUS). Setiap pertanyaan diisi menggunakan skala *likert* (1 - 5) dimana 1 berarti **Sangat tidak setuju** dan 5 berarti **Sangat setuju**. Hasil pengumpulan data kemudian diolah untuk dihitung skor setiap responden dan skor akhir secara keseluruhan. Diperoleh hasil perhitungan seperti berikut. 

|Responden	|Q1  |Q2	|Q3	 |Q4	|Q5	 |Q6	|Q7	 |Q8	|Q9	 |Q10	|Jumlah |	Skor |
|-----------|----|----|----|----|----|----|----|----|----|----|-------|------|
|1	        |4	 |3	  |3	 |3	  |3	 |3	  |3	 |3	  |3	 |3	  |31	    |77.5  |
|2          |	4	 |4	  |4	 |4	  |4	 |4  	|4	 |4	  |4	 |4	  |40	    |100   |
|3	        |4	 |4	  |4	 |4	  |4	 |4	  |4	 |4	  |4	 |3	  |39	    |97.5  |
|4	        |3	 |3	  |3	 |4	  |3	 |2	  |3	 |3	  |3	 |2	  |29	    |72.5  |
|5	        |3	 |3	  |3	 |3	  |3	 |2	  |3	 |3	  |3	 |3	  |29	    |72.5  |
|6	        |4	 |3	  |4	 |3	  |4	 |4	  |4	 |4	  |4	 |3	  |37	    |92.5  |
|7	        |3	 |2	  |3	 |4	  |4	 |4	  |2	 |3	  |3	 |2	  |30	    |75    |
|8	        |4	 |2	  |2	 |3	  |4	 |3	  |3	 |3	  |3	 |3	  |30 	  |75    |
|9       	  |4	 |3	  |3	 |3	  |4	 |3	  |3	 |3	  |3	 |2	  |31	    |77.5  |
|10	        |3	 |3	  |3	 |3	  |3	 |3	  |3	 |3	  |3	 |3	  |30	    |75    |
|Jumlah	    |36	 |30	|32	 |34	|36	 |32	|32	 |33	|33	 |28	|326	  |815   |

| Model name         | Top 1 Accuracy  | Top 5 Accuracy |
| ------------------ |---------------- | -------------- |
| My awesome model   |     85%         |      95%       |

>📋  Include a table of results from your paper, and link back to the leaderboard for clarity and context. If your main result is a figure, include that figure and link to the command or notebook to reproduce it. 
