<template>
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
<div class="footer">
  <p>Copyright <i class="fa-regular fa-copyright"></i> SMKN 4 Tasikmalaya 2024</p>
</div>

  </template>
  
  <style scoped>
  .footer {
    position: fixed; 
    top: 0;
    left: 0;
    background-color: #8B0000; /* Warna merah */
    color: white; /* Warna teks putih */
    text-align: center; /* Teks di tengah */
    padding: 0.5rem 0; /* Padding lebih kecil */
    position: relative; /* Footer berada setelah konten */
    width: 100%; /* Memastikan footer selebar layar */
    font-size: 0.9rem; /* Ukuran font lebih kecil */
    margin-top: 20px; /* Jarak dengan konten atas */
  }

  .section {
  margin: 2rem 0;
  padding: 1rem;
  background-color: #f9f9f9;
  border-radius: 8px;
}

.section-title {
  font-size: 2rem;
  color: #8B0000;
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
  color: #8B0000;
  font-size: 1.1rem;
}
  </style>