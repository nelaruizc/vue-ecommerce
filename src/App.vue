<template>
  <NavBar/>
  <nav>
  </nav>
  <router-view/>
</template>

<script lang="ts">
import NavBar from "@/components/NavBar.vue"
export default {
  name: "App",
  components: {
    NavBar
  }
}
</script>

<style>
#app {
  color: #2c3e50;
}
</style>