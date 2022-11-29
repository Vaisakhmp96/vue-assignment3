<template>
  <div id="app">
    
  <h2>{{name}}</h2>
  </div>
</template>

<script>

export default {
  data(){
    return{
      name:'Vaisakh'
    }
  },
  created(){
     console.log(this.$el)
  },
  mounted(){
    console.log(this.$el)
  }
  }

</script>

<style>

</style>
