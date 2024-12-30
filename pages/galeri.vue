<template>
    <div class="profile-page">
      <!-- Judul Halaman -->
      <div class="page-title">
        <h1 class="judul">Galeri</h1>
        <p>SMK Negeri 4 Tasikmalaya</p>
      </div>
      
      <div class="image-gallery">
        <div class="container">
          <img src="/assets/img/upcr.jpeg" alt="Avatar" class="image">
          <div class="overlay">Upacara Bendera</div>
        </div>
        <div class="container">
          <img src="/assets/img/beasiswa.jpeg" alt="Avatar" class="image">
          <div class="overlay">bea siswa</div>
        </div>
        <div class="container">
          <img src="/assets/img/filmkarya.jpeg" alt="Avatar" class="image">
          <div class="overlay">juara dalam bidang Film dan Karya</div>
        </div>
        <div class="container">
          <img src="/assets/img/job.jpg" alt="Avatar" class="image">
          <div class="overlay">Job Fair</div>
        </div>
        <div class="container">
          <img src="/assets/img/binsik.jpeg" alt="Avatar" class="image">
          <div class="overlay">Binsik</div>
        </div>
        <div class="container">
          <img src="/assets/img/kebangkitan.jpg" alt="Avatar" class="image">
          <div class="overlay">EXPO</div>
        </div>
        <div class="container">
          <img src="/assets/img/t.jpeg" alt="Avatar" class="image">
          <div class="overlay">Pengajian Jumat</div>
        </div>
        <div class="container">
          <img src="/assets/img/inovasi.webp" alt="Avatar" class="image">
          <div class="overlay">EXPO</div>
        </div>
        <div class="container">
          <img src="/assets/img/pd.webp" alt="Avatar" class="image">
          <div class="overlay">Kumpulan Perisai Diri</div>
        </div>
        <div class="container">
          <img src="/assets/img/sf.jpg" alt="Avatar" class="image">
          <div class="overlay">Safety Riding</div>
        </div>
        <div class="container">
          <img src="/assets/img/siswa.jpg" alt="Avatar" class="image">
          <div class="overlay">Penyuluhan</div>
        </div>
        <div class="container">
          <img src="/assets/img/job.jpg" alt="Avatar" class="image">
          <div class="overlay">bea siswa</div>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  * {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  
  .profile-page {
    margin-top: 100px;
  }
  
  .judul {
    font-size: 2.5rem;
    color: #333;
  }
  
  .page-title {
    text-align: center;
    margin-bottom: 1rem;
    padding-top: 30px;
  }
  
  .page-title h1 {
    font-size: 2.5rem;
    color: #333;
    font-weight: bold;
  }
  
  .page-title p {
    font-size: 1.2rem;
    color: #333;
    font-weight: bold;
  }
  
  .image-gallery {
    display: flex;
    flex-wrap: wrap; /* Agar gambar bisa masuk ke baris berikutnya */
    justify-content: space-around; /* Memberi jarak antar gambar */
    gap: 1rem; /* Jarak antar gambar */
    margin-top: 3rem;
    padding: 10px;
    object-fit: contain;
  }
  
  .container {
    position: relative;
    width: 100%;
    max-width: 300px;
    /* Membatasi lebar maksimum */
    height: 300px; /* Menetapkan tinggi yang tetap untuk kotak gambar */
    overflow: hidden; /* Menyembunyikan gambar yang melebihi kotak */
  }
  
  .image {
    display: block;
    width: 100%;
    height: 100%;
    object-fit: cover; /* Menyesuaikan gambar untuk mengisi seluruh kotak, mempertahankan proporsi */
  }
  
  .overlay {
    position: absolute;
    bottom: 0;
    background: rgba(0, 0, 0, 0.5); /* Black see-through */
    color: #f1f1f1;
    width: 100%;
    transition: 0.5s ease;
    opacity: 0;
    font-size: 20px;
    padding: 10px;
    text-align: center;
  }
  
  .container:hover .overlay {
    opacity: 1;
  }
  
  </style>
  