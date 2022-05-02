<template>
  <div class="jumbotron">
     <TitlePage/>
  </div>
</template>

<script>

import TitlePage from './Title.vue';

export default {
  name: 'HeroJumbo',
  components: {
     TitlePage ,
   
  }
 
 
}
</script>


<style >
    .jumbotron{
  width: 100%;
  height: 100vh;
  background-image: url(https://www.bitdegree.org/learn/storage/media/images/e0a8e8e4-cb50-4b9e-b044-bba1a97b0e4d.o.jpg);
  color: white;
}
</style>
