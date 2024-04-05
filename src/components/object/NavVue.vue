<template>
    <nav>
    <router-link to="/">Halaman Utama</router-link> |
    <router-link to="/about">Tentang</router-link> |
    <router-link to="/scolarity">Pendidikan</router-link> |
    <router-link to="/experience">Pengalaman</router-link> |
    <router-link to="/skills">Kemampuan</router-link> |
    
    <br>
    <br>
    <router-link to="/certification">Sertifikat</router-link> |
    <router-link to="/contact">Contact</router-link>
    
</nav>
  <router-view/>
</template>

<script>
export default {
  name: 'NavVue',
  watch: {
        $route: {
            immediate: true,
            handler() {
                document.title  = "Divano Rizqi Anandra | Portfolio"
            }
        },
    }
}




</script>

<style scoped>


</style>