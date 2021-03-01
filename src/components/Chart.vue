<script>
import { Doughnut } from 'vue-chartjs'

export default {
  extends: Doughnut,
  data: () => ({
    chartdata: {
      labels: ['Skoda Eti', 'Hyundai I30', 'Opel Astra'],
      datasets: [
        {
          label: 'Данные 1',
          backgroundColor: '#00BFFF',
          data: [40, 30, 50]
        }
      ]
    },
    options: {
      responsive: true,
      maintainAspectRatio: false
    }
  }),

  mounted () {
    this.renderChart(this.chartdata, this.options)
  }
}

</script>

<style>
</style>
