<template>
  <div id="app">
    <PieChart />
    <LineChart />
  </div>
</template>

<script>
import PieChart from './components/PieChart.vue';
import LineChart from './components/LineChart.vue';

export default {
  name: 'App',
  components: {
    PieChart,
    LineChart
  }
}
</script>

