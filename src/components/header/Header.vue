<template>
  <div class="all">
    <a class="home-link" href="/" rel="home">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRTGPRQzOrZUqlUjaadqrVx-reragtFq5tEO8JB7FaL-6h1GW4A" alt="SkrepkaNaKepku.ru" width="66">
      <h1 class="site-name">Скрепка на кепку</h1>
    </a>
    <button class="header-button" @click="goHome()">Участвовать</button>
    <hr>
  </div>
</template>

<script>
export default {
  name: 'Header',
  data () {
    return {
    }
  },
  methods: {
    goHome () {
      alert(1)
    }
  }
}
</script>

<style scoped>
.all {
  background: #c0e5e7;
}
.site-name {
  text-transform: uppercase;
  display:inline-block;
}
.home-link {
  text-decoration: none;
  color: #e45940;
  display:inline-block;
}
.header-button {
  float: right;
}
</style>
