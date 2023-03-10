<template>
  <main class="columns is-gapless is-multiline">
    <div class="column is-one-quarter">
      <LeftBar/>
    </div>
    <div class="column is-three-quarter">

    </div>
  </main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import LeftBar from './components/LeftBar.vue';

export default defineComponent({
  name: 'App',
  components: {
    LeftBar
  }
});
</script>

<style>

</style>
