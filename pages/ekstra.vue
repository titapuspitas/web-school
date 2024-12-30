<template>
    <div class="profile-page">
<!-- Judul Halaman -->
  <div class="page-title">
    <h1 class="judul">Ekstrakulikuler</h1> 
    <p>SMK Negeri 4 Tasikmalaya</p>
  </div>
    <div class="image-gallery">
      <div v-for="(eskul,i) in eskul" :key="i" class="container">
        <img :src="eskul.foto" alt="eskul" class="image">
        <div class="overlay">{{ eskul.nama }}</div>
      </div>
      <!-- <div class="container">
        <img src="/assets/img/2.png" alt="Avatar" class="image">
        <div class="overlay">Patroli Keamanan Sekolah</div>
      </div>
      <div class="container">
        <img src="/assets/img/3.png" alt="Avatar" class="image">
        <div class="overlay">English Club</div>
      </div>
      <div class="container">
        <img src="/assets/img/4.png" alt="Avatar" class="image">
        <div class="overlay">Pasukan Pengibar Bendera</div>
      </div>
      <div class="container">
        <img src="/assets/img/5.png" alt="Avatar" class="image">
        <div class="overlay">Pramuka</div>
      </div>
      <div class="container">
        <img src="/assets/img/6.png" alt="Avatar" class="image">
        <div class="overlay">Pecinta Lingkungan Hidup</div>
      </div>
      <div class="container">
        <img src="/assets/img/7.png" alt="Avatar" class="image">
        <div class="overlay">Palang Merah Remaja</div>
      </div>
      <div class="container">
        <img src="/assets/img/8.png" alt="Avatar" class="image">
        <div class="overlay">Sepak Bola</div>
      </div>
      <div class="container">
        <img src="/assets/img/9.png" alt="Avatar" class="image">
        <div class="overlay">Volly</div>
      </div>
      <div class="container">
        <img src="/assets/img/10.png" alt="Avatar" class="image">
        <div class="overlay">Gerakan Laskar Pustaka</div>
      </div>
      <div class="container">
        <img src="/assets/img/11.png" alt="Avatar" class="image">
        <div class="overlay">Futsal</div>
      </div>
      <div class="container">
          <img src="/assets/img/14.png" alt="Avatar" class="image">
          <div class="overlay">IT Club</div>
        </div>
        <div class="container">
            <img src="/assets/img/21.jpeg" alt="Avatar" class="image">
            <div class="overlay">Rohis</div>
        </div>
        <div class="container">
            <img src="/assets/img/16.png" alt="Avatar" class="image">
            <div class="overlay">Paskibra</div>
        </div>
        <div class="container">
            <img src="/assets/img/18.png" alt="Avatar" class="image">
            <div class="overlay">Safety Riding Lab</div>
        </div>
        <div class="container">
            <img src="/assets/img/12.png" alt="Avatar" class="image">
            <div class="overlay">Dance Art</div>
        </div>
        <div class="container">
            <img src="/assets/img/19.png" alt="Avatar" class="image">
            <div class="overlay">Cinema Fotografi</div>
        </div>
        <div class="container">
            <img src="/assets/img/20.png" alt="Avatar" class="image">
            <div class="overlay">Bola Basket</div>
        </div>
        <div class="container">
            <img src="/assets/img/13.png" alt="Avatar" class="image">
            <div class="overlay">Bulu Tangkis</div>
          </div> -->
    </div>
    </div>
  </template>
  <script setup>
  const supabase = useSupabaseClient()
  const eskul = ref([])
  
  const getEskul = async () => {
    const { data, error } = await supabase.from('eskul').select(`*`)    
    if (data) eskul.value = data;
  }
  onMounted(() => {
    getEskul()
  })
  </script>
  
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
  color: #333;;
  font-weight: bold;
}

.page-title p {
  font-size: 2.5rem;
  color: #333;
  font-weight: bold;
}

body {
  font-family: Arial, sans-serif;
}

.image-gallery {
  display: flex;
  flex-wrap: wrap; /* Agar gambar bisa masuk ke baris berikutnya */
  justify-content: space-around; /* Memberi jarak antar gambar */
  gap: 1rem; /* Jarak antar gambar */
  margin-top: 3rem;
  padding: 10px;
}

.container {
  position: relative;
  width: 100%;
  max-width: 300px;
   /* Lebar maksimum gambar */
}

.image {
  display: block;
  width: 100%;
  height: auto;
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