<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import router from './router/index';
</script>
<template>
  <nav class="navbar mb-5 mt-2">
    <div class="container ">
      <router-link class="navbar-brand" to="/">
        <img alt="UE logo" width="380" height="70" class="d-inline-block img-responsive" src="@/assets/Logo_UE_CCB.png" />
      </router-link>
    <!--
    <div>
      
      <router-link class="btn btn-link m-4 fs-4" to="/">Iniciar Sesion</router-link>
      
      <router-link class="btn btn-link fs-5" to="/register">Registrarse</router-link>

    </div>
    -->
  </div>
</nav>
    <!--
    <img alt="UE logo" class="img-fluid" src="@/assets/Logo_UE_CCB.png" />
    -->
   <div class="">
    <RouterView />
   </div>
  
</template>
