<template>
  <NavComp/>
  <nav>
  </nav>
  <router-view/>
</template>

<script lang="ts">
import NavComp from "@/components/NavComp.vue"
export default {
  name: "App",
  components: {
    NavComp
  }
}
</script>

<style>
#app {
  color: #2c3e50;
}
</style>