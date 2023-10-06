<template>
    <div class="component2">
        <h2>CONOCE MÁS DE BENELLI</h2>
        <p>Benelli, pura pasión desde 1911, ahora en colombia.
            La tradición, emoción e innovación se han convertido en leyenda en una historia que abarca más de cien años, donde se han desarrollado modelos para satisfacer a todo tipo de piloto con innovación y tecnología de vanguardia, garantizando el máximo placer de manejo, confort, agilidad y maniobrabilidad.
            La marca con mayor crecimiento de ventas en europa llega a colombia con el respaldo de auteco mobility.
        </p>
        <componentes1 v-for="post in posts" :key="post.titulo"
        :titulo="post.titulo" 
        :url1="post.url1"
        :url2="post.url2"
        :descripcion="post.descripcion"
        :descripcion2="post.descripcion2"
        />
    </div>
</template>

<script lang="ts">
import { defineComponent, DefineComponent } from 'vue';
import componentes1 from './componentes1.vue';
import Datos from "@/assets/json.json";

export default defineComponent ({
    name: 'componentes2',
    components: {
        componentes1,
    },
    computed: {
         posts: ()=>{
          return Datos.map((post:any)=> {
            return post
          })
         }
      }
    
})
</script>

<style lang="scss" scoped>
p{
    text-align: justify;
}

</style>