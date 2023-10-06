<template> 
   <componentes4/>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import componentes4 from './components/componentes4.vue';




export default defineComponent ({
      components: {
        componentes4,
      },
})
</script>

<style lang="scss">
body {
  background-image: url('/src/assets/motofondo.jpg');
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  min-height: 100vh; 
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  color: white; 
}
h1 {
  font-size: 36px;
}

p {
  font-size: 18px;
}


</style>
