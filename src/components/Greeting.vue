<template>
  <div>
    <p v-if="age >= 25">{{ msg }}</p>
    <p v-else>You must be 25 to view this message</p>
  </div>
</template>

<script>
export default {
  name: "Greeting",
  props: ["age"],
  data() {
    return {
      msg: "Hello World!",
    };
  },
};
</script>

<style scoped lang="scss">
$color: red;
p {
  color: $color;
}
</style>
