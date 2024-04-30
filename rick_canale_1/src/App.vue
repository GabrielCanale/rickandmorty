<script setup>
import {ref} from 'vue'
</script>

<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark border-bottom border-body">
  <div class="container-fluid">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <router-link class="nav-link" aria-current="page" to="/">Inicio</router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/about">Sobre</router-link>
        </li>
      </ul>
    </div>
  </div>
</nav>

<div class="main">
  <router-view></router-view>
</div>


</template>
<style>
  
.section{
  width: 100%;
  justify-content: center;
  position: relative;
}


.template{
  align-items: center;
} 

</style>


