<template>
    <div class="small">
        <doughnut-chart :chart-data="datacollection" />
    </div>
</template>

<script>
import DoughnutChart from "./DoughnutChart.vue";

export default {
    components: {
        DoughnutChart
    },
    data() {
        return {
            datacollection: {
                labels: this.labels,
                datasets: [
                    {
                        data: this.datasets,
                        backgroundColor: this.color
                    }
                ]
            }
        };
    },
    props: {
        color: Array,
        labels: Array,
        datasets: Array
    }
};
</script>

<style>
.small {
    max-width: 600px;
    margin: 150px auto;
}
</style>
