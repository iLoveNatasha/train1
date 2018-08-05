<template>
  <div class="home">
    <main-header></main-header>
    <block-view></block-view>
    <main-footer></main-footer>
  </div>
</template>

<script>
import Header from './header/Header'
import Footer from './footer/Footer'
import BlockView from './blockView/BlockView'

export default {
  name: 'Home',
  data () {
    return {
    }
  },
  components: {
    'main-header': Header,
    'main-footer': Footer,
    'block-view': BlockView
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.home {
  width: 1060px;
  margin: auto;
}
</style>
