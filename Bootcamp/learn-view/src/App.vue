<template>
<messege title = "bye bestie"/>
</template>

<script>
import messege from "./components/messege.vue" 


export default {
  name: 'App',
  components: {
    messege
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
