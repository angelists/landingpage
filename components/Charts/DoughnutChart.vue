<script>
import { Doughnut } from 'vue-chartjs'

export default {
  extends: Doughnut,
  props: {
    chartData: Object
  },
  data() {
    return {
      options: { responsive: true, maintainAspectRatio: false, legend: { labels: { fontColor: '#fff' } } }
    }
  },
  mounted() {
    this.renderChart(this.chartData, this.options)
  }
}
</script>
