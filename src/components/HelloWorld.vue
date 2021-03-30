<template>
  <div class="hello">
    <div class="container">
      <div class="row">
        <div class="col-12">
          <h1 class="text-center">{{ msg }}</h1>
          <nav class="nav">
            <router-link to="/lab1" class="nav-link">Lab. 1</router-link>
            <router-link to="/lab2" class="nav-link">Lab. 2</router-link>
          </nav>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: "INFO PESERTA UKK"
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin: 0 auto;
}
</style>
