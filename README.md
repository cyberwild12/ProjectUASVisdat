<h1 align="center">
  Pembuatan <i>Dashboard</i> Informasi pada Data Film Indonesia Menggunakan Aplikasi <i>Tableau</i> (Studi Kasus: Dataset IMDb Film Indonesia 1926-2020)
</h1>

<h3 align="center">Tautan dalam mengakses <i>dashboard</i>: https://github.com/Khadafi141/ProjectVisdat.git </h3>
<br>
<h2>Ringkasan Penelitian</h2>
<h3>1. Latar Belakang </h3>
  <p align="justify"> 
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<i>Handphone</i> atau Gadget sudah bukan lagi menjadi barang mewah oleh karenanya kebutuhan ponsel pintar atau smarthphone semakin meningkat, tidak hanya untuk kalangan orang dewaasa tetapi juga anak-anak sekarang banyak yang sudah mempunyai ponsel pintarnya sendiri. Jumlah perputaran pelanggan <i>Handphone</i> di Indonesia diprediksi mencapai 8,6 persen dalam satu bulan (Adiningsih, 2007). Bermacam produk <i>Smartphone</i>, termasuk banyaknya <i>Smartphone</i> buatan China dan juga semakin murah harga paketan internet, makanya konsumen mempunyai banyak sekali alternatif pilihan untuk dipilih. faktor lainnya yang juga mendukung permintaan <i>Smartphone</i> tinggi yaitu fakta bahwa mobilitas individu yang juga didukung fenomena <i>online</i> communities di perkotaan, tidak hanya di negara maju, tetapi juga di negara berkembang (Zhang dan Watts, 2008).
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Angka Buta Huruf (ABH) adalah proporsi penduduk usia 15 tahun ke atas yang tidak dapat membaca dan atau menulis huruf latin atau huruf lainnya terhadap penduduk usia 15 tahun ke atas di suatu daerah (BPS RI, 2015). Angka buta huruf yang semakin kecil diharapkan dapat mengurangi tingkat kemiskinan di suatu daerah sehingga tingkat kesejahteraan daerah tersebut diharapkan dapat semakin meningkat.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tableau adalah <i>tools/platform</i> untuk membuat visualisasi data lebih interaktif, mudah dibaca, dan mudah dianalisa. Visualisasi yang dilakukan adalah mengubah data tabel yang kaku menjadi bentuk grafik, diagram, geo mapping, dan sebagainya yang mampu memperlihatkan perubahan dan perbedaan data menjadi lebih jelas. Alhasil, tampilan data hasil analisis statistik biasa menjadi lebih cantik dengan visual yang <i>eye-catching</i> menggunakan pilihan <i>dashboard</i> interaktif yang disediakan Tableau.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tableau merupakan salah satu perangkat lunak yang digunakan dalam aplikasi <i>Business Intelegence</i>, dengan penerapan <i>Business Intelegence</i> pada Tableau menghasilkan visualisasi data secara interaktif dengan cara meng-import dataset ke dalam Tableau dan membuat visualisasi yang mempermudah dalam memahami suatu informasi.
<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Kemampuan visualisasi data dan informasi yang dimiliki oleh <i>dashboard</i> memudahkan para pemilik kebijakan untuk merencanakan langkah apa yang seharusnya diambil. Oleh karena itu diharapkan dari hasil visualisasi data ini dapat dijadikan sebagai masukan kepada pihak pemerintah khususnya kementrian sosail untuk meningkatkan kualiatas literasi di tiap provinsi yang ada di Indonesia. 
   </p>
  
<h3>2. Tujuan Penelitian</h3>
  <p align="justify">
    <ul>
    <li>Untuk mengetahui sebaran proporsi individu yang memiliki gadget di Indonesia</li>
    <li>Untuk mengetahui sebaran presentase ABH di Indonesia</i></li>
    <li>Meniliti apakah Proporsi individu yang memiliki gadget berkaitan dengan ABH di suatu daerah</li>
  </ul>
  </p>
  
<h3>3. Metode Penelitian</h3>
  <h4> A. Studi Literatur </h4>
  <p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tahap awal penelitian ini adalah melakukan studi literatur dari penelitian lain yang berkenaan dengan pembangunan <i>dashboard</i> visualisasi data dan informasi menggunakan <i>Library Flexdashboard R</i>. Studi literatur penelitian ini diperoleh melalui jurnal dan artikel ilmiah yang membahas tentang teknik visualisasi data dan pembuatan <i>dashboard</i> informasi.
  </p>
  <h4> B. Pengumpulan Data </h4>
  <p>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Data yang akan digunakan merupakan indikator kemiskinan yang dirilis oleh BPS yang terdiri atas 5 variabel meliputi:
  <ol>
    <li>Variabel Jumlah Penduduk Miskin</li>
    <li>Variabel Persentase Penduduk Miskin</li>
    <li>Variabel Garis Kemiskinan</li>
    <li>Variabel Indeks Kedalaman Kemiskinan</li>
    <li>Variabel Indeks Keparahan Kemiskinan</li>
    <li>Variabel Indeks Gini (<i>Gini Ratio</i>)</li>
  </ol> 
Kelima variabel data yang dikumpulkan dari tahun 2011 hingga 2021, baik dalam lingkup nasional maupun lingkup provinsi. 
  </p>
  <h4> C. Pengolahan Data </h4>
  <p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pada proses pengolahan data dilakukan beberapa tahapan sebelum data divisualisasikan. Tahapan pengolahan data ini penting karena data-data yang telah dihimpun perlu disesuaikan dan diseleksi berdasarkan referensi waktu dan wilayah cakupan penelitian. Tahapan pengolahan data ini meliputi pembersihan data (<i>data cleaning</i>), identifikasi variabel, penyatuan data (<i>data integration</i>), perencanaan jenis visualisasi, dan konversi data (<i>data convertion</i>). Seluruh tahapan dalam pengolahan data dilakukan pada <i>Microsoft Office Excel</i> dan <i>R</i>.    
  </p>
  <h4> D. Visualisasi Data </h4>
  <p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Pada tahapan ini, data yang sudah diolah akan dilakukan visualisasi sesuai dengan rencana jenis visualisasi yang telah ditetapkan sebelumnya. Alat atau tools dalam pembuatan visualisasi data ini menggunakan beberapa library visualisasi data di dalam koleksi modul R. Library tersebut antara lain <i>highcharter, DT, plotly, ggplot2, mapview,</i> dan lain-lain. Adapun dalam pemilihan warna dan tema grafik menggunakan library viridis untuk memberikan efek gradien warna pada chart visualisasi data tertentu yang memberikan penekanan atau maksud tertentu. Berikut ini rencana jenis visualisasi yang akan dibuat:
  <ul>
    <li>Visualisasi Teks Sederhana (<i>Simple Text</i>)</li>
    <li>Visualisasi <i>Bar Chart</i></li>
    <li>Visualisasi <i>Pie Chart</i>
    <li>Visualisasi <i>Line Chart</i></li>
    <li>Visualisasi Tabular (<i>Data Table</i>)</li>
    <li>Visualisasi Peta Tematik Interaktif (<i>Interactive Choropleth Map</i>)</li>
  </ul>
  </p>
  
  <h4> E. <i>Design Dashboard</i></h4>
  <p><i>Design Dashboard</i> dibuat menggunakan aplikasi <i>Figma</i>. Berikut ini tampilan <i>design dashboard</i> tiap halaman.</p>
  <ol>
  <li><h5><i>Design Dashboard</i> Halaman Utama (Lingkup Nasional)</h5></li>
  <img src="Images/Design_Dashboard_1.png"> </img>
  
  <li><h5><i>Design Dashboard</i> Halaman Kedua (Lingkup Provinsi)</h5></li>
  <img src="Images/Design_Dashboard_2.png"> </img>
  
  <li><h5><i>Design Dashboard</i> Halaman Pencarian</h5></li>
  <img src="Images/Design_Dashboard_3.png"> </img>
  
  <li><h5><i>Design Dashboard</i> Halaman Informasi</h5></li>
  <img src="Images/Design_Dashboard_4.png"> </img>
  </ol>

  <h4> F. Perancangan <i>Dashboard</i></h4>
  <p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<i>Dashboard</i> yang efektif didesain dengan penuh cermat dan mempertimbangkan peran dari pengguna dalam pengambilan keputusan. Haryanti (2008) menjabarkan mengenai metodologi pembangunan dasbor terdiri atas 7 tahap, meliputi identifikasi kebutuhan, perencanaan, perancangan prototype, <i>review prototype</i>, implementasi, <i>deployment</i>, dan <i>maintenance</i>.
</p>
  
  <h4> G. Evaluasi Sistem</h4>
  <p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Evaluasi sistem yang digunakan menggunakan pengukuran dengan <i>System Usability Scale (SUS)</i>. Pengujian SUS dilakukan untuk mengukur tingkat kegunaan suatu aplikasi. SUS dilakukan dengan mengisi kuesioner yang terdiri atas 10 item pernyataan mengenai sistem yang dibangun. Pernyataan diukur menggunakan skala likert 1-5 dengan definisi sangat tidak setuju hingga sangat setuju. Dalam konteks ini, aplikasi yang akan dievaluasi berupa <i>dashboard</i> informasi profil kemiskinan Indonesia tahun 2021.
  </p>
  
  <h4> H. Penyusunan Laporan</h4>
  <p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Tahap akhir dalam penelitian ini adalah melakukan penyusunan laporan. Laporan ini akan dibuat dalam format IEEE dengan menyesuaikan isi yang terdapat pada proposal penelitian dan hasil yang diperoleh dari pembuatan dashboard informasi mengenai profil kemiskinan di Indonesia tahun 2021 hingga proses publikasi ke dalam web server telah selesai dilakukan. 
  </p>
  
  <h3>4. Hasil dan Pembahasan</h3>
  <h4>A. Hasil Tampilan <i>Dashboard</i> dan Visualisasi Data</h4>
    <ol type="1">
      <li><h5>Tampilan <i>Dashboard</i> Halaman Utama pada Sub-Menu 1</h5></li>
      <img src="Images/Dashboard_HalamanUtama.png"> </img>
      <li><h5>Tampilan <i>Dashboard</i> Halaman Utama pada Sub-Menu 2</h5></li>
      <img src="Images/Dashboard_HalamanUtama_1.png"> </img>
      <li><h5>Tampilan <i>Dashboard</i> Halaman Utama pada Sub-Menu 3</h5></li>
      <img src="Images/Dashboard_HalamanUtama_2.png"> </img>
      <li><h5>Tampilan <i>Dashboard</i> Halaman Utama pada Sub-Menu 4</h5></li>
      <img src="Images/Dashboard_HalamanUtama_3.png"> </img>
      <li><h5>Tampilan <i>Dashboard</i> Halaman Utama pada Sub-Menu 5</h5></li>
      <img src="Images/Dashboard_HalamanUtama_4.png"> </img>
      <li><h5>Tampilan <i>Dashboard</i> Halaman Kedua pada Sub-Menu 1</h5></li>
      <img src="Images/Dashboard_HalamanKedua.png"> </img>
      <li><h5>Tampilan <i>Dashboard</i> Halaman Kedua pada Sub-Menu 2</h5></li>
      <img src="Images/Dashboard_HalamanKedua_1.png"> </img>
      <li><h5>Tampilan <i>Dashboard</i> Halaman Kedua pada Sub-Menu 3</h5></li>
      <img src="Images/Dashboard_HalamanKedua_2.png"> </img>
      <li><h5>Tampilan <i>Dashboard</i> Halaman Kedua pada Sub-Menu 4</h5></li>
      <img src="Images/Dashboard_HalamanKedua_3.png"> </img>
      <li><h5>Tampilan <i>Dashboard</i> Halaman Pencarian</h5></li>
      <img src="Images/Dashboard_HalamanPencarian.png"> </img>
      <li><h5>Tampilan <i>Dashboard</i> Halaman Pencarian dengan Mencoba Fitur Filter Data</h5></li>
      <img src="Images/Dashboard_HalamanPencarian_demo.png"> </img>
      <li><h5>Tampilan <i>Dashboard</i> Halaman Informasi</h5></li>
      <img src="Images/Dashboard_HalamanInformasi.png"> </img>
    </ol>
    
 <h4>B. Evaluasi <i>Dashboard</i></h4>
<p align="justify"> 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<i>Dashboard</i> yang telah dibuat perlu dievaluasi kepada pengguna (<i>user</i>) agar dapat dinilai secara objektif. Penilaian evaluasi menggunakan pengukuran <i>System Usability Scale</i> (SUS). Ketika SUS digunakan, responden akan diminta untuk menilai sepuluh item pertanyaan dengan memilih salah satu jawaban dari lima tanggapan berkisar dari sangat setuju hingga sangat tidak setuju. Survei telah dilakukan untuk memperoleh nilai SUS untuk <i>dashboard</i> informasi profil kemiskinan Indonesia tahun 2021. Periode survei dilakukan selama 3 hari, yaitu 18-20 Juni 2022. Dari survei tersebut diperoleh jumlah responden sebanyak 89 orang. Gambar berikut merupakan visualisasi yang menggambarkan karakteristik responden berdasarkan kelompok pengguna yang mengikuti survei evaluasi <i>dashboard</i> informasi profil kemiskinan Indonesia tahun 2021.
</p>

<p align="center">
<img src="Images/proporsi_responden.png"> </img>
</p>

<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Responden yang menjadi sasaran survei merupakan kelompok pengguna dari kalangan masyarakat umum dan kelompok mahasiswa STIS. Jumlah responden dari kalangan masyarakat umum yaitu 39 orang, sedangkan responden dari kelompok mahasiswa STIS yaitu 50 orang. Jumlah responden tersebut sudah dirasa cukup untuk digunakan sebagai penilaian evaluasi pada <i>dashboard</i>. Setelah itu dilakukan penghitungan skor dengan aturan sebagai berikut:
Q_odd=(scale position-1)×2.5
Q_even=(5-scale position)×2.5
Pada pertanyaan bernomor ganjil, semakin tinggi nilai scale position, maka skor pada item pertanyaan tersebut akan semakin besar. Sedangkan pada pertanyaan bernomor genap, semakin tinggi nilai scale position, maka skor pada item pertanyaan tersebut akan semakin kecil. Berdasarkan rumus sebelumnya, maka diperoleh distribusi frekuensi skor-skor dari 89 responden yang ditampilkan pada histogram.  
</p>
<p align="center">
<img src="Images/histogram_skor_sus.png"> </img>
</p>

<p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dari histogram di atas, distribusi skor dari sebagian besar responden cenderung berada di atas rata-rata. Adapun rata-rata skor yang dihasilkan adalah sebesar 76,88, dengan nilai minimum sebesar 37,5 dan nilai maksimum sebesar 100. Rata-rata skor SUS menunjukkan tingkat penerimaan pengguna terhadap sistem (dashboard). Skor SUS 76,88 masuk ke dalam kategori acceptable karena bernilai lebih dari 70, kategori adjective berupa excellent, dan kategori grade B. Kategori penilaian skor SUS dijelaskan pada gambar di bawah ini.
</p>
<p align="center">
<img src="Images/kategori_skor_sus.jpg"> </img>
</p>  
  
<h3>5. Kesimpulan dan Saran</h3>
<h4>A. Kesimpulan</h4>
  <ol>
  <li>Informasi data indikator kemiskinan beserta visualisasi yang ditampilkan ke dalam <i>dashboard</i> meliputi:</li>
    <ul>
      <li>Jumlah penduduk miskin Indonesia tahun 2011-2021 (<i>line chart</i>).</li>
      <li>Persentase penduduk miskin Indonesia pada bulan September 2021 (<i>simple text chart</i>).</li>
      <li>Indeks kedalaman kemiskinan Indonesia tahun 2011-2021 (<i>line chart</i>).</li>
      <li>Garis kemiskinan Indonesia menurut kebutuhan pokok (makanan dan bukan makanan) pada tahun 2011-2021 (<i>line chart</i>).</li>
      <li>Indeks keparahan kemiskinan Indonesia tahun 2011-2021 (<i>line chart</i>).</li>
      <li>Indeks gini Indonesia tahun 2011-2021 (<i>line chart</i>).</li>
      <li>Persentase jumlah penduduk miskin Indonesia menurut klasifikasi wilayah (perkotaan dan perdesaan) pada bulan September2021 (<i>pie chart</i>).</li>
      <li>Persentase angka garis kemiskinan Indonesia menurut klasifikasi wilayah (perkotaan dan perdesaan) pada bulan September 2021 (<i>pie chart</i>).</li>
      <li>Jumlah penduduk miskin menurut provinsi di Indonesia (<i>horizontal bar chart</i> dan peta tematik interaktif).</li>
      <li>Indeks kedalaman kemiskinan berdasarkan klasifikasi wilayah menurut provinsi di Indonesia (<i>stacked horizontal bar chart</i>).</li>
      <li>Indeks keparahan kemiskinan berdasarkan klasifikasi wilayah menurut provinsi di Indonesia (<i>stacked horizontal bar chart</i>).</li>
      <li>Indeks gini berdasarkan klasifikasi wilayah menurut provinsi di Indonesia (<i>stacked horizontal bar chart</i>).</li>
      <li>Persentase penduduk miskin menurut provinsi di Indonesia tahun 2011-2021 (tabular dan <i>line chart</i>).</li>
    </ul>
  <li><i>Dashboard</i> informasi profil kemiskinan di Indonesia tahun 2021 berhasil dibuat sesuai sesuai desain melalui beberapa tahapan perancangan dan diakhiri dengan mempublikasikannya pada server Github pribadi. Halaman <i>dashboard</i> dapat diakses melalui tautan atau link berikut ini: https://public.tableau.com/app/profile/muamar.khadafi8365/viz/Book2_16557144619270/DashboardProporsiABH</li>
  <li>Berdasarkan hasil survei pengujian evaluasi pada <i>dashboard</i> menggunakan pengukuran System Usability Scale (SUS) diperoleh nilai rata-rata skor SUS sebesar 76,88. Skor SUS tersebut masuk ke dalam kategori <i>acceptable, excellent</i>, dan <i>grade</i> B.</li>
  </ol>
  
 <h4>B. Saran </h4>
  <p align="justify">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Saran terhadap penelitian tugas proyek ini didasarkan pada jawaban dari beberapa responden yang dianggap masuk akal dan diterima oleh penulis berdasarkan hasil survei evaluasi <i>dashboard</i> sebelumnya. Berikut ini beberapa saran yang diajukan oleh responden dan dapat dipertimbangkan untuk dilakukan perbaikan pada <i>dashboard</i> ke depannya.
  <ul>
   <li>Gaya <i>font</i> kurang menarik, terutama di bagian header.</li>
   <li>Memberikan kotak penanda pada navbar utama agar pengguna bisa mengetahui sedang berada pada halaman <i>dashboard</i> yang mana.</li>
   <li>Visualisasi peta sebaiknya diberikan fitur <i>download</i>.</li>
   <li>Ilustrasi dashboard lebih dikembangkan lagi agar <i>easy to use</i>.</li>
   <li>Tampilan <i>dashboard</i> lebih diakomodasikan secara responsif untuk pengguna <i>smartphone</i>.</li>
  </ul>
 </p>
  

    
    
    
    

