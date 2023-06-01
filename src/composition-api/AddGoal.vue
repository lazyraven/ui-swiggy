<template>
  <section class="border-4 p-4 border-slate-500">
    <form @submit.prevent="addGoal">
      <div>
        <label for="goaltext"></label>
        <input class="border-4" type="text" id="goaltext" v-model="enteredText" />
      </div>
      <p v-if="invalidInput">Please enter a valid goal text (non-empty).</p>
    </form>
    <button type="button" class="bg-blue-100 p-2" @click="addGoal()">Add Goal</button>
  </section>
</template>

<script>
import { ref, watch } from "vue";
export default {
  emits: ["add-goal"],
  setup(_, context) {
    const enteredText = ref("");
    const invalidInput = ref(false);
    watch(invalidInput, function (val) {
      if (val) {
        console.log("Analytics: Invalid Input");
      }
    });
    function addGoal() {
      console.log("addGoal called")
      invalidInput.value = false;
      if (enteredText.value === "") {
        invalidInput.value = true;
        return;
      }
      context.emit("add-goal", enteredText.value);
      enteredText.value = "";
    }
    return {
      enteredText,
      invalidInput,
      addGoal,
    };
  },
};
</script>
