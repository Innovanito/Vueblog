<template>
  <Navbar />  

  <RouterView :blog="blog" ref=""/>





</template>

<script>
import blog from './assets/blog'
import Navbar from './components/Navbar.vue'


export default {
  data() {
    return {
      blog
    }
  },
  components: {
    Navbar,
  }

}
</script>

<style>
#app {
  text-align: center;
}
.headline {
  padding: 20px;
}

</style>