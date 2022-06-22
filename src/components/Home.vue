<template>
  <div class="flex flex-row">
    <div class="basis-1/2 m-2"><LeftHomePage1></LeftHomePage1></div>
    <div class="basis-1/2 m-2">
      <img class="absolute right-0" src="../assets/home-dish1.png" />
    </div>
  </div>
  <!-- <LeftHomePage></LeftHomePage>
    <img class="absolute right-0" src="../assets/home-dish1.png" /> -->
</template>

<script>
import LeftHomePage1 from "./LeftHomePage1.vue";
export default {
  name: "Home",
  components: {
    LeftHomePage1,
  },
  data() {
    return {};
  },
};
</script>
