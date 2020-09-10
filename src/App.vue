<template>
    <div id="app">
        <Tyontekijat :tableItems="tyontekijatArray"/>
    </div>
</template>

<script>
    import Tyontekijat from "@/components/Tyontekijat";
    import json from './assets/tyontekijat.json'

    export default {
        components: {
            Tyontekijat,
        },
        data: function () {
            return {
                tyontekijatArray: json.tyontekijat
            }
        }
    }
</script>

<style>
    #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px;
    }
</style>
