<template>
  <div class="all">
    <div class="sas">
      <a class="vk-link" href="https://vk.com/kapystareni" rel="vk" target="_blank">
        <h3 class="vk">VK</h3>
      </a>
    </div>
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
  background: #b2b6b6;
}
.sas {
  width: 40px;
  margin-left: auto;
  margin-right: auto;
}
.vk-link {
  text-decoration: none;
  color: #4077b6;
  display:inline-block;
}
.header-button {
  float: right;
}
</style>
