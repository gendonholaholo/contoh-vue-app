<template>
  <div class="app-container">
    <header>
      <h1>Biografi Singkat</h1>
    </header>

    <section class="bio-card">
      <div class="bio-img">
        <img src="./assets/Gos.png" alt="Foto Profil" />
      </div>
      <div class="bio-content">
        <h2>Nama: Gos</h2>
        <p><strong>Profesi:</strong> Web Developer</p>
        <p><strong>Lokasi:</strong> Yogyakarta, Indonesia</p>
        <p>
          Ini dibuat sesederhana & sesingkat mungkin untuk keperluan contoh penggunaan Vue.js
        </p>
        <div class="social-links">
          <a href="https://github.com" target="https://github.com/gendonholaholo"><i class="fab fa-github"></i></a>
          <a href="https://instagram.com" target="https://www.instagram.com/shafadonia/"><i class="fab fa-instagram"></i></a>
          <a href="https://tiktok.com" target="https://www.tiktok.com/@emohmendem"><i class="fab fa-tiktok"></i></a>
        </div>
      </div>
    </section>

    <footer>
      <p>&copy; 2024 Ghaws Shafadonia, salam kenal.</p>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style scoped>
.app-container {
  font-family: 'Arial', sans-serif;
  background-color: #121212;
  color: #fff;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

header {
  text-align: center;
  padding: 2rem;
  background-color: #1e1e1e;
}

header h1 {
  font-size: 3rem;
  color: #ffffff;
}

.bio-card {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 2rem;
  background-color: #1e1e1e;
  margin: 2rem;
  border-radius: 10px;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5);
}

.bio-img img {
  border-radius: 50%;
  width: 150px;
  height: 150px;
  object-fit: cover;
  margin-right: 2rem;
}

.bio-content {
  max-width: 600px;
}

.bio-content h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
  color: #fff;
}

.bio-content p {
  font-size: 1.1rem;
  margin-bottom: 1rem;
  color: #bbb;
}

.bio-content p strong {
  color: #fff;
}

.social-links {
  margin-top: 1.5rem;
}

.social-links a {
  color: #bbb;
  font-size: 1.5rem;
  margin: 0 10px;
  text-decoration: none;
  transition: color 0.3s;
}

.social-links a:hover {
  color: #fff;
}

footer {
  background-color: #1e1e1e;
  text-align: center;
  padding: 1rem;
  color: #aaa;
}

footer p {
  font-size: 1rem;
}
</style>

