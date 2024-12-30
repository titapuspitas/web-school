<template>
  <footer class="footer">
    <div class="footer-content">
      <!-- Hubungi Kami Section -->
      <div class="footer-section">
        <h3 class="footer-title">Hubungi Kami</h3>
        <p class="contact-info">SMKN 4 Tasikmalaya</p>
        <p class="contact-info">Jl Depok Kel. Sukamantri Kec. Purbahitu</p>
        <p class="contact-info">Kota Tasikmalaya 46196</p>
        <p class="contact-info">
          <i class="bi bi-telephone">
          <span class="phone">+6235831299</span></i>
        </p>
        <p class="contact-info">
          <span class="email">info@smkn4-tsm.sch.id</span>
        </p>
      </div>

      <!-- Media Sosial Section -->
      <div class="footer-section">
        <h3 class="footer-title">Media Sosial</h3>
        <ul class="social-links">
          <li><a href="https://www.facebook.com/4smkn" class="social-link"><i class="bi bi-facebook"></i> Facebook</a></li>
          <li><a href="https://youtube.com/@smkn4tasikmalayamediaoffic704?si=IIyWqqo9S_IZV1Q5" class="social-link"><i class="bi bi-youtube"></i> YouTube</a></li>
          <li><a href="https://www.instagram.com/smkn4tsmofficial?igsh=YWRkMTNkaW9jNXE4" class="social-link"><i class="bi bi-instagram"></i> Instagram</a></li>
          <li><a href="https://www.tiktok.com/@smkn4tasikmalaya?_t=8sVa1Ghp5Eu&_r=1" class="social-link"><i class="bi bi-tiktok"></i> TikTok</a></li>
        </ul>
      </div>

      <!-- Link Eksternal Section -->
      <div class="footer-section">
        <h3 class="footer-title">Link Eksternal</h3>
        <ul class="external-links">
          <li><a href="https://www.kemdikbud.go.id/" class="external-link" style="color: #333;">Kemdikbud</a></li>
          <li><a href="https://psmk.kemdikbud.go.id/" class="external-link" style="color: #333;">PSMK</a></li>
          <li><a href="https://disdik.jabarprov.go.id/" class="external-link" style="color: #333;">Disdik Jabar</a></li>
        </ul>
      </div>
    </div>

    <!-- Copyright Section -->
    <div class="footer-bottom">
      <p>© SMKN 4 Tasikmalaya. All right reserved</p>
      <p>Designed and Engineered by Operator</p>
    </div>
  </footer>
</template>

<style scoped>
a{
  text-decoration: none;
}
.footer {
  background-color: #f9f9f9;
  color: #333;
  padding: 40px 0 20px;
  width: 100%;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.footer-content {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  padding: 0 20px;
}

.footer-section {
  flex: 1;
  margin-right: 40px;
}

.footer-section:last-child {
  margin-right: 0;
}

.footer-title {
  font-size: 18px;
  margin-bottom: 20px;
  font-weight: 600;
}

.contact-info {
  margin-bottom: 10px;
  font-size: 14px;
  color: #333;
}

.social-links,
.external-links {
  list-style: none;
  padding: 0;
}

.social-link {
  color: #333;
  text-decoration: none;
  display: block;
  margin-bottom: 10px;
  font-size: 14px;
  transition: color 0.3s ease;
}

.social-link i {
  margin-right: 8px; /* Menambahkan ruang antara ikon dan teks */
}

.social-link:hover {
  color: #333;
}

.footer-bottom {
  max-width: 1200px;
  margin: 40px auto 0;
  padding: 20px;
  text-align: center;
  border-top: 1px solid #333;
  font-size: 14px;
  color: #333;
}

.footer-bottom p {
  margin: 5px 0;
}
</style>
