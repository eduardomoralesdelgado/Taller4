<template>
    <div class="post-card">
        <h3>{{titulo}}</h3>
        <div class="cont-imag">
        <div class="img">
            <img :src="url1" alt="">
            <p>{{ descripcion }}</p>
        </div>
        <div class="img">
            <img :src="url2" alt="">
            <p>{{ descripcion2 }}</p>
        </div>
    </div>
    </div>
</template>

<script lang="ts">
import { defineComponent, DefineComponent } from 'vue';

export default defineComponent ({
    name: 'componentes1',
    props: {
        url1: {
            type: String,
            default:""    
        },
        url2: {
            type: String,
            default:""    
        },
        descripcion: {
            type: String,
            default: ""
        },
        descripcion2: {
            type: String,
            default: ""
        },
        titulo: {
            type:String,
            default:""
        }
    }
    })
</script>

<style lang="scss" scoped>
.post-card {
  display: flex;
  flex-direction: column;
  align-items: center; 
  text-align: center; 
}

.cont-imag {
  display: flex;
  justify-content: space-between; 
  width: 100%;
}

.img {
  flex: 0 0 calc(50% - 20px); 
  margin: 10px; 
}

img {
  width: 100%; 
  max-width: 300px; 
  height: auto; 
  background-color: white;
}

.description {
  width: 100%;
  text-align: justify;
  background-color: white;
}

</style>