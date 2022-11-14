  <script>
  export default {
    name: 'AppTitle',
    data(){
      return{
        titolo: 'La mia prima app con Vite!'
      }
    }
  }
  </script>

<template>
  <div>
    <h2>{{titolo}}</h2>
  </div>
</template>


<style scoped>
  h2 {
    color: green;
  }
</style>