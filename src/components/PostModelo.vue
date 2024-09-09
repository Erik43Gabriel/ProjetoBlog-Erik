<script>
   export default{
    props: {
        titulo: String,
        imagem: String,
        corpoDoTexto: String,
        autor: String
    }
   }
</script>

<template>
    <div class="post">
        <h2>{{ titulo }}</h2>
          <br>
        <img :src=imagem>
          <br>
          <p>
           {{ corpoDoTexto }}
          </p>
          <br>
        <p class="autor">
         {{ autor }}
        </p>
        <br>
    </div>
</template>

<style>

  .post{
    
    display:inline;
    align-items: center;
    justify-content: center;
    height: 100vh; /* Altura da viewport */
    text-align: center; /* Opcional: centraliza o texto dentro da div */
    flex-direction: column; /* Alinha os itens verticalmente */
    color:white;
   }
   
   .imagem{
      width: 1193px;
      height: 700px;
   }

   .autor {
      position:absolute;
      left: 1100px;
      top: auto;
      font-weight: bolder;
   
}
 
 
 

</style>