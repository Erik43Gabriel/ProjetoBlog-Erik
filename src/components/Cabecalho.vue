<template>
    <div class="cabecalho">
        <div class="post">
            <p class="h1">Etec</p>
            <img src="../assets/cabecalho.jpg" class="img">
            <div>
                <a href="">Login</a>
            </div>
        </div>
    </div>
</template>

<script>
import cabecalho1 from '@/assets/cabecalho.jpg'
   export default {
    name: 'Cabecalho',
    data(){
        return{
            nome:'Erik Gabriel Messias'
        }
    }
   }
</script>

<style scroped>



.post{
    display:inline;
    align-items: center;
    justify-content: center;
    height: 100vh;
    flex-direction: column; 

}
.img{
 width: 100px;
 height: 100px;
}

.h1{
    font-size: 100px;
}
 
</style>
