<template>
  <div class="about">
    <h1>This is an about page</h1>
    <main-test />
  </div>
</template>

<script>
import MainTest from "@/components/MainTest.vue";
export default {
  components: { MainTest },
  name: "AboutView",
};
</script>
