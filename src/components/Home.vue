<template>
  <div class="inline">
    <LeftHomePage></LeftHomePage>
    <img class="absolute right-0" src="../assets/home-dish1.png" />
  </div>
</template>

<script>
import LeftHomePage from "./LeftHomePage.vue";
export default {
  name: "Home",
  components: {
    LeftHomePage,
  },
  data() {
    return {};
  },
};
</script>