<template>
  <div>
    <p>hey!</p>
    <greeting></greeting>
  </div>
</template>

<script>
import Greeting from "./components/Greeting.vue";
export default {
  name: "App",
  components: {
    Greeting,
  },
};
</script>
