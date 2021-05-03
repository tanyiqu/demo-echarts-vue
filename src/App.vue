<template>
  <div id="app">
    <Pie />
    <LineChart />
  </div>
</template>

<script>
import Pie from './components/Pie.vue';
import LineChart from './components/Line.vue';

export default {
  name: 'App',
  components: {
    Pie, LineChart
  }
}
</script>

