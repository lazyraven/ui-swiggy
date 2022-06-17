<template>
  <div>
    <goals-list :goals="filteredGoals"></goals-list>
    <add-goal @add-goal="addGoal"></add-goal>
  </div>
</template>

<script>
import GoalsList from "./GoalsList";
import AddGoal from "./AddGoal";

export default {
  components: {
    GoalsList,
    AddGoal,
  },
};
</script>