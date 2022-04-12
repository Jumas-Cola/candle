<script setup>
import Candle from "./components/Candle.vue";
</script>

<template>
  <main>
    <Candle v-for="c in candles" />
  </main>
</template>

<script>
export default {
  data() {
    return {
      candles: 15892,
    };
  },
};
</script>

<style>
@import "./assets/base.css";

#app {
  margin: 0 auto;
  background: #000000;
}
</style>
