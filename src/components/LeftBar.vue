<template>
    <header>
        <h1>
            My tracker
        </h1>
    </header>
</template>

<script lang="ts">
    import { defineComponent } from 'vue';

    export default defineComponent({
        name:'LeftBar'
    })
</script>

<style>

    h1 {
        color: #fff;
        font-size: 25px;
        font-weight: 600px;
    }
    header {
    padding: 1rem;
    background: #0d3b66;
    width: 100%;
    height: 100vh;
    }

    @media only screen and (max-width: 768px) {
        header {
            padding: 2.5rem;
            height: auto;
        }
    }
</style>