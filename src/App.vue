<template>

  <div class="post">
    <PostModelo/>
    <Cabecalho/>
    <Postagem1/>
    <Postagem2/>
    <postagem3/>
  </div>
  
</template>

<script>
import Cabecalho from './components/Cabecalho.vue';
import Postagem1 from './components/Postagem1.vue';
import Postagem2 from './components/Postagem2.vue';
import Postagem3 from './components/Postagem3.vue';
import PostModelo from './components/PostModelo.vue';

   export default {
    name: 'App',
    components:{
      Cabecalho,
      Postagem1,
      Postagem2,
      Postagem3,
      PostModelo
    }
   }
</script>






