<template>
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid">
            <router-link to="/" class="nav-link active" aria-current="page">LOGO(home)</router-link>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                <router-link to="/login" class="nav-link active" aria-current="page">Login</router-link>
                </li>
                <li class="nav-item">
                <router-link to="/profile" class="nav-link active" aria-current="page">Perfil</router-link>
                </li>
                <li class="nav-item">
                <router-link to="/products" class="nav-link active" aria-current="page">Productos</router-link>
                </li>
            </ul>
            <form class="d-flex" role="search">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-success" type="submit">Search</button>
            </form>
            </div>
        </div>
    </nav>
</template>
  
  <script lang="ts">
    export default {
      name: "NavComp"
    }
  </script>
  
  <style scoped>
  .material-icons-round {
    color: white;
    font-size: 1.4em;
    background-color: rgba(218, 218, 218, 0.158);
    padding: 0.3em;
    border-radius: 50%;
    margin: 0.1em;
  }
  </style>