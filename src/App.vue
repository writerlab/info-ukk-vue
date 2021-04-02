<template>
  <div id="app">
    <!-- <Lab1/> -->
    <div class="container">
      <div class="row">
        <div class="col mt-3">
          <img src="https://awsimages.detik.net.id/community/media/visual/2018/01/26/9d33cef6-f18d-4500-9cd9-995cc9e74120.png?w=700&q=90" width="60px" alt="jabar" class="mr-3">
          <img src="https://upload.wikimedia.org/wikipedia/id/thumb/9/9e/Logo_SMK_Negeri_4_Tasikmalaya.png/150px-Logo_SMK_Negeri_4_Tasikmalaya.png" width="60px" alt="smk n 4" class="mr-3">
          <img src="http://lspbrokerproperti.com/wp-content/uploads/2016/01/logo-bnsp.gif" width="100px" alt="bnsp">
        </div>
      </div>
    </div>
    <router-view/>
    <div class="container">
      <div class="row">
        <div class="col-12">
          <div class="text-muted text-center mb-2">
            &copy; POKJA TUK SMK N 4 Tasikmalaya 2021
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// import Lab1 from './components/Lab1.vue'

export default {
  name: 'App',
  mounted() {
    console.log("💚💚💚")
    console.log("👋🏻Hay! Selamat Datang di Info Peserta UKK 2021. 🎉")
    console.log("💚💚💚")
    console.log("Developed by Zul Hilmi.")
  }
  // components: {
  //   Lab1
  // }
}
</script>

<style>
body {
  background-color: #ffffff;
  font-family: 'Quicksand', sans-serif;
  font-size: 17px;
}

.fong-quicksand {
  font-family: 'Quicksand', sans-serif;
}

h1 {
  font-size: 3.9em;
}

/* .container {
  min-width: 75%;
} */
</style>
