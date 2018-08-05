<template>
  <div>
    <div class="images" v-for="(item, index) in items" :key="item.id">
      {{ item.message }} | {{ index }}
      <img class="image" :src="item.src" :alt="item.message" height="206">
    </div>
  </div>
</template>

<script>
export default {
  name: 'BlockView',
  data () {
    return {
      items: [
        {message: 'asd', src: 'https://www.smoladmin.ru/files/catalog/2418/gallery/med/27_1508827929.jpg', id: 1},
        {message: 'sadf', src: 'http://zg-brand.ru/images/Statyi/logo.png', id: 2},
        {message: 'sdfsd', src: 'https://wecreate.pro/wp-content/uploads/2-2-300x262.png.pagespeed.ce.deXa31VSVJ.png', id: 3}
      ]
    }
  }
}
</script>

<style scoped>
.images {
  display: inline-block;
  margin-right: 20px;
}
.image {
  border: 1px solid black;
}
</style>
