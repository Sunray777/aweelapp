<template>
<b-container>
  <b-row align-v="center">
    <b-col>
  <div id="app">
    <div class="container">
    <div class="header_img">
  <b-card
    overlay
    img-src="images/BUGATTI_header.png"
    img-alt="Card Image"
    text-variant="white"
    title=""
    sub-title=""
  >
    <b-card-text>
     
    </b-card-text>
  </b-card>
</div>
<Chart class="chart"/>
<div class="top-text-block">
  <span class="top-text">
    Топ 10 самых долговечых авто по мнению пользователей:
  </span>
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
import Chart from './components/Chart.vue'


export default {
  name: 'App',
  
  components: {
    Chart,
        CarTable
  },
  };

</script>

<style>


@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100&display=swap');

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
.chart 
{
padding: 60px 20px 40px;
}
.container
{
  max-width: 1200px;
  min-height: 1400px;
  margin: auto;
  background: #E3E3E3;
}

.top-text-block
{
  padding: 35px 0;
}

.top-text 
{
  /* Топ 10 самых долговечых авто по мнению пользователей: */

width: 100%;
margin: auto;

font-family: 'Roboto', sans-serif;
font-style: normal;
font-weight: 100;
font-size: 20px;
line-height: 35px;

color: #000000;



}

</style>
