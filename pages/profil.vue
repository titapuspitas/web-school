<template>
    <div class="container-fluid">
        <div class="profile-page">
    <!-- Judul Halaman -->
      <div class="page-title">
        <h1 class="judul">Profil SMK Negeri 4 Tasikmalaya</h1>
      </div>
      <div class="row">
        <div class="col">
       <!-- Welcome Section -->
          <div class="welcome-section">
            <img src="/assets/img/guru.jpg" alt="School Image" class="welcome-image" />
          </div>
        </div>
      </div>
      <div class="text-section">
        <h2>Sejarah SMK Negeri 4 Tasikmalaya</h2>
        <p>
          Sejalan dengan Program Pemerintah di bidang pendidikan Menengah Kejuruan pada saat itu, yaitu pemerataan akses, ditambah pula dengan banyaknya keinginan masyarakat yang mengharapkan adanya SMK Negeri di daerah Kecamatan Purbaratu
          Kota Tasikmalaya. Hal ini terutama untuk menampung tamatan dari SLTP yang ingin melanjutkan ke SMK. Beberapa tokoh masyarakat dan unsur pejabat pemerintah di Kecamatan Purbaratu Kota Tasikmalaya mengusulkan kepada Pemerintah Kota
          Tasikmalaya dan Pemerintah Provinsi Jawa Barat agar berdirinya SMK Negeri di Kecamatan Purbaratu Kota Tasikmalaya.
        </p>
        <p>
          Setelah melalui perjuangan yang sangat panjang dari berbagai pihak, khususnya Disdik Kota Tasikmalaya dan pihak-pihak terkait lainnya, sesuai prosedur dan ketentuan yang berlaku pada waktu itu, akhirnya pada tahun pelajaran
          2010/2011 SMK Negeri 4 Tasikmalaya mulai berdiri. Pada awalnya, sekolah ini membuka Kompetensi Keahlian Teknik Komputer dan Jaringan dengan pendaftar peserta didik baru yang berjumlah 44 orang.
        </p>
        <p>
          Tempat belajar pada awalnya menumpang di SMP Negeri 17 Kota Tasikmalaya, dan sekolah induknya adalah SMK Negeri 2 Kota Tasikmalaya. Untuk tenaga pendidik dan tenaga kependidikan masih dibantu sepenuhnya oleh kedua sekolah tersebut.
          Pada tahun 2012, keluarlah surat Izin Pendirian berdasarkan keputusan Kepala Badan Pelayanan Perizinan Terpadu Kota Tasikmalaya No. 420/9/SK-BPPT/2012 Tanggal 06 Februari 2012.
        </p>
      </div>
      <div class="vision-mission-goals">
        <div class="vision">
          <h2>Visi</h2>
          <p>“Menjadi sekolah unggul yang menghasilkan lulusan berkompeten, berkarakter, dan siap menghadapi tantangan global.”</p>
        </div>
        <div class="mission">
          <h2>Misi</h2>
          <ul>
            <li>Menyelenggarakan pendidikan berbasis teknologi dan informasi.</li>
            <li>Meningkatkan kualitas pembelajaran sesuai kebutuhan dunia kerja.</li>
            <li>Menanamkan nilai-nilai karakter pada seluruh peserta didik.</li>
            <li>Memperluas kerjasama dengan dunia usaha dan dunia industri.</li>
            <li>Menyiapkan lulusan yang memiliki jiwa kewirausahaan.</li>
          </ul>
        </div>
        <div class="goals">
          <h2>Tujuan</h2>
          <ul>
            <li>Menciptakan lingkungan belajar yang kondusif dan inovatif.</li>
            <li>Menghasilkan lulusan yang mampu bersaing di tingkat nasional dan internasional.</li>
            <li>Mendorong peserta didik untuk memiliki keterampilan praktis dan adaptif.</li>
            <li>Menjalin kemitraan strategis dengan dunia usaha dan dunia industri.</li>
            <li>Melahirkan generasi yang beretika dan memiliki wawasan global.</li>
          </ul>
        </div>
      </div>
      <div class="row">
      <div class="col">
        <section class="section" id="identitas">
      <h2 class="section-title">Identitas Sekolah</h2>
      <div class="identitas-content">
        <div class="identitas-item">
          <h3>Nama Sekolah</h3>
          <p>SMK Negeri 4 Tasikmalaya</p>
        </div>
        <div class="identitas-item">
          <h3>NPSN</h3>
          <p>20276063</p>
        </div>
        <div class="identitas-item">
          <h3>Nomor Statistik Sekolah</h3>
          <p>401327810004</p>
        </div>
        <div class="identitas-item">
          <h3>Alamat</h3>
          <p>Jalan Depok RT 02 RW 05</p>
        </div>
        <div class="identitas-item">
          <h3>Telepon</h3>
          <p>+(62)265312059</p>
        </div>
        <div class="identitas-item">
          <h3>Email</h3>
          <p>info@smkn4tsm.sch.id</p>
        </div>
      </div>
    </section>
  </div>
</div>
    </div>
    </div>
  </template>
  
  <style scoped>
  .container-fluid {
  margin-top: 60px;
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

.profile-page {
  margin-top: 90px;
}

.judul {
  font-size: 2.5rem;
  color: #333;
}

.page-title {
  text-align: center;
  margin-bottom: 2rem;
  padding-top: 30px;
  color: #333;
}

.page-title h1 {
  font-size: 2.5rem;
  color: #333;
  font-weight: bold;
}


.text-section {
    flex: 2;
    margin-top: 20px;
    padding: 20px;
    background-color: #f9f9f9;
    border: 1px solid #ddd;
    border-radius: 8px;
    min-width: 300px;
}

.text-section h2 {
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 10px;
}
  
  .text-section p {
    font-size: 16px;
    line-height: 1.6;
    margin-bottom: 15px;
  }
  
  .vision-mission-goals {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 20px;
  }
  
  .vision,
  .mission,
  .goals {
    flex: 1;
    padding: 20px;
    background-color: #f9f9f9;
    border: 1px solid #ddd;
    border-radius: 8px;
    min-width: 300px;
  }
  
  .vision h2,
  .mission h2,
  .goals h2 {
    font-size: 20px;
    font-weight: bold;
    margin-bottom: 10px;
  }
  
  .vision p,
  .mission ul,
  .goals ul {
    font-size: 16px;
    line-height: 1.6;
  }
  
  .mission ul,
  .goals ul {
    list-style-type: disc;
    margin-left: 20px;
  }
  .section {
  margin: 2rem 0;
  padding: 1rem;
  background-color: #f9f9f9;
  border-radius: 8px;
}

.section-title {
  font-size: 2rem;
  color: #333;
  margin-bottom: 1rem;
  text-align: center;
}

.section-content {
  font-size: 1rem;
  color: #333;
  line-height: 1.6;
}

.identitas-content {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1rem;
}

.identitas-item {
  background-color: #fff;
  padding: 1rem;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.identitas-item h3 {
  color: #333;
  font-size: 1.1rem;
}
</style>