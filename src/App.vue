<template>
  <div id="app">
    <div class="container">
<CarTable class="cartableapp"/>
</div>
  </div>
</template>

<script>
import CarTable from './components/CarTable.vue'

export default {
  name: 'App',
  components: {
    CarTable
  }
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
.cartableapp 
{
  max-width: 1000px;
  margin: auto;
}
.container
{
  max-width: 1200px;
  min-height: 1200px;
  margin: auto;
  background: #E3E3E3;
}

</style>
