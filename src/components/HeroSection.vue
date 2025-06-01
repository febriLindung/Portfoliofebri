<template>
  <section class="hero">
    <div class="text-container">
      <h2>HELLO</h2>
      <h1>
        <span class="highlight">Febri Perlindungan</span><br />
       
      </h1>
      <p>
        Selamat datang di portofolio saya! saya Febri Perlindungan, Mahasiswa Teknik Informatika Universitas Islam Riau.
      </p>
      <p>
       Saya Febri Perlindungan sering dipanggil febri,Saya terus belajar berbagai materi yang diberikan seperti Bahasa Pemrograman,pengembangan Web,Sistem Jaringan,dll.
       saya terus belajar supaya saya bisa menguasai setiap materi yang di berikan, Hobi saya suka berkegiatam di alam sering disebut mendaki gunung, karna digunung saya dapat melepaskan pikiran-pikiran tentang tugas kuliah
      </p>
    </div>
    <div class="image-container">
      <img src="/profile.png" alt="Febri Perlindungan" />
    </div>
  </section>
</template>

<style scoped>
.hero {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: white;
  padding: 40px;
  border-radius: 12px;
}

.text-container {
  max-width: 60%;
}

h2 {
  color: tomato;
  margin-bottom: 10px;
  font-weight: 600;
}

h1 {
  font-size: 32px;
  margin-bottom: 20px;
}

.highlight {
  font-weight: bold;
  color: #111;
}

p {
  font-size: 16px;
  line-height: 1.6;
  margin-bottom: 15px;
}

a {
  color: #7f57f1;
  text-decoration: none;
  font-weight: bold;
}

.image-container img {
  width: 200px;
  height: 200px;
  object-fit: cover;
  border-radius: 50%;
  border: 4px solid tomato;
}
</style>
