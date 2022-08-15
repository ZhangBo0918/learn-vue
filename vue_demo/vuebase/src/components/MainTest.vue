<template>
  <div>
    <span>{{ number | multiply() }}</span>
  </div>
</template>

<script>
export default {
  name: "MainTest",
  filters: {
    multiply: function (val, time = 2) {
      if (!val) return "";
      return val * parseInt(time);
    },
  },
  data() {
    return {
      number: 99,
    };
  },
};
</script>

<style>
</style>