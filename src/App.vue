<template>
    <div id="app">
        <doughnut-container
            v-for="(chart, index) in chartConfig"
            :key="index"
            :labels="chart.labels"
            :color="chart.color"
            :datasets="chart.data"
        />
    </div>
</template>

<script>
import DoughnutContainer from "./components/DoughnutContainer.vue";
import chartConfig from "./data/config.json";

export default {
    name: "app",
    data() {
        return {
            chartConfig: chartConfig
        };
    },
    components: {
        DoughnutContainer
    }
};
</script>

<style>
#app {
    text-align: center;
    display: flex;
    align-items: center;
    justify-content: center;
}
</style>
