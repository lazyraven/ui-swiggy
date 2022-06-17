<template>
  <div>
    <Home></Home>
    <HelloWorld />
    <CourseGoal></CourseGoal>
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
