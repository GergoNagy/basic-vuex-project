<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <Counter />
    <CounterSquare />
    <Buttons />
    <ColorCode />
  </div>
</template>

<script>
import Counter from "@/components/Counter.vue";
import CounterSquare from "@/components/CounterSquare.vue";
import Buttons from "@/components/Buttons.vue";
import ColorCode from "@/components/ColorCode.vue";

export default {
  name: "HomeView",
  components: {
    Counter,
    CounterSquare,
    Buttons,
    ColorCode,
  },
};
</script>

<style>
div {
  margin-bottom: 10px;
}

.counter {
  font-size: 80px;
}

.buttons button {
  font-size: 80px;
  width: 100px;
  margin: 0 10px;
}
</style>
