<template>
	<head>
		<title>Divano Rizqi Anandra | Portfolio</title>
	</head>
  <div> 

    <div id="bandeau">
		<h1 id="text">Divano Rizqi Anandra</h1>
	  </div>

    <NavVue/>
	<Social/>
	  
</div>

</template>



<script>

import NavVue from './components/object/NavVue.vue';
import Social from './components/object/Social.vue';
export default ({
  components : {
    NavVue,
	Social
    
  },
  
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #000000;

  
}


body{
background: linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(141,141,193,1) 0%, rgba(120,144,217,1) 32%, rgba(95,193,225,1) 66%, rgba(50,65,239,1) 100%, rgba(0,212,255,1) 100%); 
}


nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #d54017;
}

#bandeau {
			color: #fff; /* warna teks */
			height: 50px; /* tinggi  */
			overflow: hidden; /* menyembunyikan teks berlebih */
			position: relative; /* posisi relatif untuk menggulir teks */
		}
		
		/* Tetapkan gaya untuk teks */
		#text {
			font-size: 24px; /* ukuran teks */
			position: absolute; /* posisi absolut untuk menggulir teks */
			top: 0; /* posisi vertikal teks */
			left: 100%; /* posisi horizontal awal teks */
			animation: defilement 10s linear infinite; /* gulir animasi */
		}
		
		/* Atur animasi */
		@keyframes defilement {
			0% {
				left: 100%; /* posisi horizontal awal */
			}
			100% {
				left: -100%; /* posisi horizontal akhir */
			}
		}


</style>
