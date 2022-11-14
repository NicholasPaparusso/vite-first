
<script>
import AppTitle from './components/AppTitle.vue'

export default {  

name: 'App',
components:{
  AppTitle
}
}
</script>

<template>
  <div class="container">
    <AppTitle/>
  </div>
</template>  
<style>

.container{
  margin: 0 auto;
  background-color: black;
  height: 70px;
  display: flex;
  justify-content: center;
  align-items: center;
}

</style>
