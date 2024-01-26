<script setup lang="ts">
import Carousel from "../components/Carousel.vue";
</script>

<template>
  <div class="register">
  </div>
  <div class="container">
    <div class="row">
      <div class="col-md-6 col-ms-6">
        <carousel></carousel>
      </div>
    <div class="col-md-6 col-ms-6 border-2 ps-5 ">
      <form action="" >
        <h3 class="text-center ps-3" style="color: #dd0034
;">Registrate</h3>
        <div class="mb-3 ps-3">
    <label for="exampleInputEmail1" class="form-label text-start ps-3">Ingrese su correo institucional</label>
    <input type="email" class="form-control ps-3" id="exampleInputEmail1" aria-describedby="emailHelp">
  
  </div>
  <div class="mb-3 ps-3">
    <label for="exampleInputPassword1" class="form-label ps-3">Contraseña</label>
    <input type="password" class="form-control ps-3" id="exampleInputPassword1">
  </div>
  <div class="mb-3 form-check">
    <input type="checkbox" class="form-check-inputps-3" id="exampleCheck1">
    <label class="ps-2 form-check-label" for="exampleCheck1">Acepta terminos y condiciones</label>
  </div>
  <div>
      
      <router-link class="btn btn-link fs-6" to="/">Iniciar Sesion</router-link>
     <!-- 
      <router-link class="btn btn-link fs-6" to="/register">Registrarse</router-link>
-->
    </div>
  <div class="text-center">
  <button type="submit" class="btn btn-outline-danger p-2 align-content-center">Crear Cuenta</button>
</div>  
      </form>
    
    </div>
  </div>
</div>
</template>


