<template>
    <div class="cb pink">{{ msg }}</div>
</template>

<script>
export default {
    name: 'ColorBox',
    props: {
        msg: String
    }
};
</script>

<style type="text/css">
.cb {
    height: 200px;
    width: 200px;
    text-align: center;
}

.pink {
    background-color: pink;
}

.green {
    background-color: green;
}
</style>
