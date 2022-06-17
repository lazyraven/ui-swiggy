<template>
  <section class="container">
    <form @submit.prevent="addGoal">
      <div class="">
        <label for="goaltext"></label>
        <input
          class="border-4"
          type="text"
          name=""
          id="goaltext"
          v-model="enteredText"
        />
      </div>
      <p>Please enter a valid goal text (non-empty).</p>
    </form>
    <button>Add Goal</button>
  </section>
</template>


<script>
import { ref } from "vue";

export default {
  setup() {
    const enteredText = ref("");
    // const invalidInput = ref(false);

    return {
      enteredText,
      //   invalidInput,
    };
  },
};
</script>