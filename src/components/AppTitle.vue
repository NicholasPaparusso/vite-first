<script>
export default {
  name: 'AppTitle',

  data(){
  return{
    title: 'La mia prima app con Vite!'
  }
 }
 }

</script>

<template>
  <div>
    <h1>
      {{title}}
    </h1>
  </div>
</template>

<style scoped>

  h1{
    text-align: center;
    color: lightblue
  }

</style>