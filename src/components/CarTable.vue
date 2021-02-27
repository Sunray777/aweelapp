<template>
  <div>
    <b-table striped hover :items="items"></b-table>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        fields: ['Марка авто', 'Модель', 'Год выпуска'],
        items: [
          { Марка_авто: 'Dickerson', Модель: 'Macdonald', Год_выпуска: 1940 },
          { Марка_авто: 'Dickerson', Модель: 'Macdonald', Год_выпуска: 2018 },
          { Марка_авто: 'Dickerson', Модель: 'Macdonald', Год_выпуска: 1925 },
          { Марка_авто: 'Dickerson', Модель: 'Macdonald', Год_выпуска: 1995 },
          { Марка_авто: 'Dickerson', Модель: 'Macdonald', Год_выпуска: 2020 },
          
        ],
  
      }
    }
  }
</script>

<style scoped>

</style>