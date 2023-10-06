<template>
    <div class="container">
        <nav id="navbar-example2" class="navbar bg-body-tertiary px-3 mb-3">
                <a class="navbar-brand" href="#">Benelli</a>
                <ul class="nav nav-pills">
                    <li class="nav-item">
                    <a class="nav-link" href="https://www.benelli.com/co-es#">NAKED</a>
                    </li>
                    <li class="nav-item">
                    <a class="nav-link" href="https://www.benelli.com/co-es">TOURING</a>
                    </li>
                </ul>
        </nav>
        <componentes3/>
    </div>
</template>

<script lang="ts">
import 'bootstrap/dist/css/bootstrap.css';
import { defineComponent, DefineComponent } from 'vue';
import componentes3 from './componentes3.vue';

export default defineComponent ({
    name: 'componentes4',
    components: {
        componentes3,
    }
})
</script>

<style lang="scss" scoped>
img {
    width: 30vw;
    height: 60vh;
}

.container {
  background-color: rgba(0, 0, 0, 0.5); /* Fondo semi-transparente */
  padding: 20px;
  border-radius: 10px;
  text-align: center;
}
</style>