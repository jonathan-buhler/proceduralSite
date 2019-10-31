<template>
    <div id="app">
        <div><img alt="Vue logo" src="./assets/logo.png" /> <HelloWorld msg="Welcome to Your Vue.js App" /></div>
        <div><ColorBox msg="Hello!" /></div>
    </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import ColorBox from './components/ColorBox.vue';

export default {
    name: 'app',
    components: {
        HelloWorld,
        ColorBox
    }
};
</script>

<style>
#app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
}
</style>
