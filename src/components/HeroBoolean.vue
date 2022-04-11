<template>
    <div class="jumbotron">
        <div class="container">
            <h1>Jumbotron</h1>
        </div>
    </div>
</template>

<script lang="ts">
    export default {
        name: 'HeroBoolean'
    }
</script>

<style scoped>
    .jumbotron {
        padding: 30px;
        background-color: #111;
    }

    .container {
        width: 90%;
        margin: 0 auto;
        padding: 0 15px;
        background-color: grey;
    }
    h1{
        color: red;
    }
</style>