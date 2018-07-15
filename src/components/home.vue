<template>
  <div class="home">
    <v-header></v-header>
    <v-menu></v-menu>
    <v-body></v-body>
  </div>
</template>

<script>
import header from '@/components/header/header'
import menu from '@/components/menu/menu'
import body from '@/components/body/body'
export default {
  name: 'HelloWorld',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components: {
    'v-header': header,
    'v-menu': menu,
    'v-body': body
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="stylus" rel="stylesheet/stylus">
</style>
