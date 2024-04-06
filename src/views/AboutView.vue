<template>
  <div class="about-me">
  <img src="../assets/img/DSC_0043-removebg-preview.jpg" alt="Divano Rizqi Anandra">
  <div class="text">
    <h2>Tentang Saya</h2>
    <h3>Mahasiswa Teknik Informatika</h3>
    <h3>Universitas Islam Riau</h3>
    <p>
      Saya berasal dari SMA Negeri 1 Tapung Hilir di Kampar lebih tepatnya di kecamatan Tapung Hilir. Pada masa SMA saya mengikuti kegiatan yang
      lumayan banyak, seperti OSIS dan banyak lagi kegiatan ekstrakulikuler.
    </p>
    <p>Saya pertama kuliah di Universitas Islam Riau pada tahun 2022 pada bulan Oktober. Selama di Universitas Islam Riau, saya telah belajar
      beberapa bahasa pemrograman yaitu HTML, CSS, Javascript, C, dan SQL.
    </p>

    </div>
</div>

</template>


<script>


export default ({
  setup() {
    
  },
})
</script>


<style scoped>
.about-me {
  display: flex;
  align-items: center;
}

.about-me img {
  width: 300px;
  height: auto;
  margin-right: 30px;
}

.about-me .text {
  flex: 1;
}

.about-me h2 {
  font-size: 32px;
  font-weight: bold;
  margin-bottom: 20px;
}

.about-me p {
  font-size: 18px;
  line-height: 1.5;
  margin-bottom: 20px;
}

.pdf-link {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 10px;
  background-color: #007acc;
  color: #fff;
  text-decoration: none;
  font-size: 18px;
  font-weight: bold;
}

.pdf-link img {
  width: 20px;
  height: 20px;
}


</style>
