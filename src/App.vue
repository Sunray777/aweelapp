<template>
<b-container>
  <b-row align-v="center">
    <b-col>
  <div id="app">
    <div class="container">
    <div class="header_img">
  <b-card
    overlay
    img-src="https://picsum.photos/900/250/?image=3"
    img-alt="Card Image"
    text-variant="white"
    title="Image Overlay"
    sub-title="Subtitle"
  >
    <b-card-text>
      Some quick example text to build on the card and make up the bulk of the card's content.
    </b-card-text>
  </b-card>
</div>
<CarTable class="cartableapp"/>
</div>
  </div>
  </b-col>
  </b-row>
</b-container>
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
