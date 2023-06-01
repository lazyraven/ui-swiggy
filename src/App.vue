<template>
  <div class="inline">
    <CourseGoal></CourseGoal>
    <!-- <div class="flex flex-row">
      <div class="basis-1/4 bg-blue-400 m-2">
        01
        <div class="flex flex-row">
          <div class="basis-1/4 bg-orange-400 m-2">01</div>
          <div class="basis-1/4 bg-orange-400 m-2">02</div>
          <div class="basis-1/2 bg-orange-400 m-2">03</div>
        </div>
      </div>
      <div class="basis-1/4 bg-blue-400 m-2">02</div>
      <div class="basis-1/2 bg-blue-400 m-2">03</div>
    </div> -->
    <Home></Home>
    <HelloWorld />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Home from "./components/Home.vue";
import CourseGoal from "./composition-api/CourseGoal.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Home,
    CourseGoal,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
