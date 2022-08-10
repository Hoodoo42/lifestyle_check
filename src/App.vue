<template>
  <div id="app">
    <life-style-example></life-style-example>
  </div>
</template>

<script>
import LifeStyleExample from "@/components/LifeStyleExample.vue";

export default {
  name: "App",
  components: {
    LifeStyleExample,
  },

  beforeCreate: function () {
    console.log(`Runs before component is created`);
  },
  created: function () {
    console.log(`Runs when component is created`);
  },
  beforeMount: function () {
    console.log(`Runs before component is mounted`);
  },
  mounted: function () {
    console.log(`Runs when component is mounted`);
  },
};
</script>

<style>
</style>
