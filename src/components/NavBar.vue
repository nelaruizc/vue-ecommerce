<template>
     <nav class="navbar navbar-expand-lg bg-light">
        <div class="container justify-content-evenly d-flex align-items-center text-center">

            <router-link to="/" class="nav-link active" aria-current="page">
              <span class="material-icons">home</span>
            </router-link>
        
            <router-link to="/store" class="nav-link active" aria-current="page">
              <span class="material-icons">storefront</span>
            </router-link>
        
            <router-link to="/profile" class="nav-link active" aria-current="page">
              <span class="material-icons">person</span>
            </router-link>
        </div>
    </nav>
</template>
  
<script lang="ts">
  export default {
    name: "NavBar"
  }
</script>

<style scoped>
.material-icons {
  color: white;
  font-size: 1.4em;
  background-color: #A0C3D2;
  padding: 0.3em;
  border-radius: 50%;
  margin: 0.1em;
}
</style>