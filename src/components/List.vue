<template>
  <div>
    <router-link to="/detail/0">{{blog[0].title}}</router-link>
    <p>{{blog[0].date}}</p>
  </div>
  <div>
    <router-link to="/detail/1">{{blog[1].title}}</router-link>
    <p>{{blog[1].date}}</p>
  </div>
  <div>
    <router-link to="/detail/2">{{blog[2].title}}</router-link>
    <p>{{blog[2].date}}</p>
  </div>
  
</template>

<script>

export default {
  data () {
    return {
      
    }
  },
  props: {
    blog : Array
  }
  
}
</script>

<style>

</style>