
<template>
    
        <div id="carouselExample" class="carousel slide">
         <div class="carousel-inner">
            <div class="carousel-item active">
            <img src="https://mas.autecomobility.com/wp-content/uploads/2022/02/moto_benelli_verde.png" class="d-block w-100"  >
            </div>
            <div class="carousel-item ">
            <img src="https://publimotos.com/wp-content/uploads/2023/09/benelli-tnt-600i-02.jpg" class="d-block w-100" >
            </div>
            <div class="carousel-item  ">
            <img src="https://mcn-images.bauersecure.com/wp-images/2876/1440x960/01_hi-01.jpg?mode=max&quality=90&scale=down" class="d-block w-100" >
            </div>
         </div>
           <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Previous</span>
           </button>
           <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="visually-hidden">Next</span>
           </button>
        </div>
        <componentes2/>
</template>

<script lang="ts">
import { defineComponent, DefineComponent } from 'vue';
import componentes2 from './componentes2.vue';
import 'bootstrap/dist/css/bootstrap.css'; // Importa los estilos de Bootstrap
import 'bootstrap/dist/js/bootstrap.bundle.min.js';

export default defineComponent ({
    name: 'componentes3',
    components: {
        componentes2,
    }, 
    
})

</script>

<style lang="scss" scoped>

</style>