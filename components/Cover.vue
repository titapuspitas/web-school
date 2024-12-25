<template>
  <div class="hal-utama">
    <div class="row">
      <div class="col">
       <!-- Welcome Section -->
    <div class="welcome-section">
      <img src="/assets/img/brosur.jpeg" alt="Image" class="welcome-image" />
    </div>
    </div>
    </div>

<div class="sambutan">
    <!-- Kolom Foto -->
    <div class="photo-section">
      <img src="/assets/img/kepalaskl.jpg" alt="Kepala Sekolah" class="photo" />
    </div>

    <!-- Kolom Sambutan -->
    <div class="welcome-section">
      <h2 class="welcome-title">Sambutan Kepala Sekolah</h2>
      <h3>Assalamualaikum Warahmatullahi Wabarakatuh</h3>
      <p class="welcome-paragraph">
        Selamat datang di SMKN 4 Tasikmalaya. Segala puji dan syukur kita panjatkan kehadirat Allah SWT, semoga kita semua ada dalam lindungan-Nya. 
        Dan atas perkenan-Nya pula kami dapat menghadirkan website SMK Negeri 4 Tasikmalaya ini.
        Kami berharap dengan adanya website di SMK Negeri 4 Tasikmalaya ini para pengunjung dapat mengenal lebih jauh tentang sekolah kami
        sehingga dapat mempererat tali silaturrahmi antara sekolah dengan masyarakat demi kemajuan kita bersama.
        Tiada gading yang tak retak, website kami ini masih dalam proses pengembangan, masih banyak kekurangan yang harus kami perbaiki.
        Kritik dan sarannya yang membangun sangat kami harapkan untuk pengembangan ke depan.
      </p>
      <p class="welcome-paragraph">
        Akhirnya, saya mengucapkan terimakasih yang sebesar-besarnya kepada semua pihak yang tidak dapat disebutkan satu segala bantuan dan persatu atas fasilitasnya yang telah diberikan semoga semua yang kita lakukan bermanfaat bagi masyarakat. 
        Wassalamu'alaikum Warahmatullahi Wabarakatuh.
      </p>
    </div>
  </div>
  <div class="page-wrapper">
    <div class="news-section">
      <h1 class="title">Berita</h1>
      <div class="title-line"></div>
      
      <div class="news-grid">
        <div class="news-card">
          <img src="~/assets/img/honda.jpeg" alt="Honda" class="card-image">
          <div class="card-date">20 MEI 2024</div>
          <div class="card-content">
            <h2>Honda Resmikan Safety Riding Lab di SMKN 4 Tasikmalaya, Ciptakan Bibit Keselamatan di Jawa Barat</h2>
            <p>Safety Riding Lab ini menjadi fasilitas pelatihan keselamatan Honda ke-7 di Seluruh Indonesia. Sekaligus juga menjadi yang ketiga di daerah Jawa Barat hingga saat ini DAN Diharapkan juga jika fasilitas safety riding ini bisa menciptakan bibit-bibit agen pembawa perubahan bagi keselamatan. Dan menyebarkannya pada masyarakat luas.</p>
          </div>
        </div>
        <div class="news-card">
            <img src="~/assets/img/app.jpeg" alt="app" class="card-image">
          <div class="card-date">29 JULI 2024</div>
          <div class="card-content">
            <h2>Aplikasi SIMORING, Solusi Kekinian dari Universitas BSI untuk PKL di SMKN 4 Tasikmalaya</h2>
            <p>“Aplikasi SIMORING dirancang untuk memudahkan proses monitoring kegiatan PKL bagi siswa, guru, dan mitra industri. Dengan aplikasi ini, siswa dapat dengan mudah membuat laporan harian, proyek, dan laporan akhir PKL, sementara guru dan mitra industri dapat melakukan pengawasan dan evaluasi secara lebih terstruktur dan transparan. Kami berharap aplikasi ini dapat membawa perubahan positif dalam pelaksanaan PKL di SMKN 4 Kota Tasikmalaya,”</p>
          </div>
          </div>
          <div class="news-card">
            <img src="~/assets/img/inovasi.webp" alt="ivovasi" class="card-image">
            <div class="card-date">27 FEBRUARI S.D 2 MARET</div>
            <div class="card-content">
              <h2>Siswa SMKN 4 Tasikmalaya Adu Inovasi dan Kreativitas di Expo Creanova</h2>
              <p>Kepala SMKN 4 Tasikmalaya Kurniawan SPd MPd mengatakan bahwa Expo Creanova dalam rangka memperingati ulang tahun SMKN 4 Tasikmalaya.</p>
            </div>
        </div>
          </div>
      </div>
      <NuxtLink to="https://www.google.com/search?sca_esv=217f92c2b6785191&q=smkn+4+tasikmalaya&tbm=nws&source=lnms&fbs=AEQNm0DRkam6RZP7GtztEOLmt4oJ8Clo4GiuZfu1v-ShpjWeHJx3g_9TgwV1SRaOPx9HL-nRv0CDzo6aKZc4312-ne0dLdN25o9KlRKeWDSNwJ8L22GaZDR4k73q1umvoTrkNs-f5NM_Y6lelKXnPglqZdpzruyQAd1FEpPfGrWRxAH4fN9eklarNC855Om4c-VjzPkuiuiEPVZ0gsOzcQFiW5jl9ml3Bw&sa=X&ved=2ahUKEwi0icn2m8KKAxXDTmwGHUoNOUsQ0pQJegQIDhAB&biw=1920&bih=945&dpr=1">
        <button class="view-more">Lihat Berita Lainnya</button>
      </NuxtLink>
    </div>
  </div>
</template>


<style scoped>

.hal-utama {
  margin-top: 100px;
}

.welcome-section {
  position: relative;
  text-align: center;
}
.welcome-image {
  margin: 0;
  width: 100%;
  height: 600px;
  object-fit: cover;
  
}
.sambutan {
  display: flex;
  align-items: flex-start;
  gap: 2rem; /* Jarak antar kolom */
  padding: 2rem; /* Padding keseluruhan */
}

/* Kolom Foto */
.photo-section {
  flex: 1; /* Ukuran fleksibel agar proporsional */
  display: flex;
  justify-content: center;
  align-items: center;
}
.photo {
  width: 100%;
  max-width: 400px; /* Batas ukuran maksimal foto */
  height: 500px;
  border-radius: 8px;
  object-fit: cover; /* Memastikan proporsi foto tetap baik */
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); /* Efek bayangan */
}

/* Kolom Sambutan */
.welcome-section {
  flex: 2; /* Ukuran fleksibel agar lebih besar */
}
.welcome-title {
  margin: 0 0 1rem; /* Margin atas dan bawah */
  font-size: 2rem;
  color:  #8B0000;; /* Warna utama */
}
.welcome-paragraph {
  font-size: 1rem;
  line-height: 2.0;
  color: #333; /* Warna teks */
}
.page-wrapper {
  min-height: 100vh;
  padding: 40px 20px;
}

.news-section {
  max-width: 1200px;
  margin: 0 auto;
}

.title {
  color: #8B0000;
  text-align: center;
  font-size: 32px;
  font-weight: 500;
  margin-bottom: 10px;
}

.title-line {
  width: 120px;
  height: 2px;
  background-color: #8B0000;
  margin: 0 auto 40px;
}

.news-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 25px;
  margin-bottom: 30px;
}

.news-card {
  background: white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 10px rgba(0,0,0,0.1);
}

.card-image {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.card-date {
  background: #8B0000;
  color: white;
  padding: 4px 12px;
  font-size: 14px;
  display: inline-block;
  margin: 16px 0 0 16px;
  border-radius: 4px;
}

.card-content {
  padding: 16px;
}

.card-content h2 {
  font-size: 18px;
  color: #333;
  margin-bottom: 12px;
  line-height: 1.4;
}

.card-content p {
  font-size: 14px;
  color: #666;
  line-height: 1.6;
}
.view-more {
  display: block;
  margin: 0 auto;
  padding: 12px 24px;
  background: white;
  border: none;
  border-radius: 4px;
  color: #666;
  font-size: 14px;
  cursor: pointer;
  transition: all 0.3s ease;
}

.view-more:hover {
  background: #f5f5f5;
  transform: translateY(-2px);
}
a{
  text-decoration: none;
}
</style>