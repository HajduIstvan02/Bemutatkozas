<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    
    <header>
      
      <div class="container container-fluid my-container my-border my-header-background position-middle">
        <nav>
          <p>
            <RouterLink to="/" class="position-middle fw-bold">Főoldal</RouterLink> <i class="bi bi-amd"></i>
            <RouterLink to="/istvan" class="position-middle fw-bold">István</RouterLink> <i class="bi bi-nvidia"></i>
            <RouterLink to="/alex" class="position-middle fw-bold">Alex</RouterLink>
          </p>
        </nav>
      </div>
      <div class="containre container-fluid my-container my-border my-background position-middle">
        <h1>Rólunk</h1>
        <p>Sziasztok ezen az oldalon fogunk bemutatkozni. Ammyit kell tudni rólunk hogy nem az erősségünk az objektum orientált programozás. Számunkra kényelmesebb a Phyton programozás ami parancsvezérelt.</p>
        <h6>(esetleges hajtépésért a borzalmas dizájn és kódért elnézésüket kérjük)</h6>
        
      </div>
    </header>
    
    <RouterView/>
  </div>
</template>

<style scoped>

</style>
