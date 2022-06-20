<template>
  <div class="m-6 border-slate-500">
    <goals-list :goals="filteredGoals"></goals-list>
    <add-goal @add-goal="addGoal"></add-goal>
  </div>
</template>

<script>
import { ref, computed } from "vue";
import GoalsList from "./GoalsList";
import AddGoal from "./AddGoal";

export default {
  components: {
    GoalsList,
    AddGoal,
  },
  setup() {
    const goals = ref([]);
    const filteredGoals = computed(function () {
      return goals.value.filter(
        (goal) => !goal.text.includes("Angular") && !goal.text.includes("React")
      );
    });
    function addGoal(text) {
      const newGoal = {
        id: new Date().toISOString(),
        text: text,
      };
      goals.value.push(newGoal);
    }
    return {
      filteredGoals: filteredGoals,
      addGoal: addGoal,
    };
  },
};
</script>
