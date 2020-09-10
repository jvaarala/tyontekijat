<template>
    <div style="width: 75%; margin: 0 auto">
        <b-table striped hover :items="tableItems"/>
    </div>
</template>

<script>
    export default {
        name: "Tyontekijat",
        props: {
            tableItems: Array
        }
    }
</script>

<style scoped>

</style>