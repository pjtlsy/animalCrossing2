<template>
  <v-app>
    <v-content>
      <!-- <RightTab /> -->
      <Board />
    </v-content>
  </v-app>
</template>
<script>
// import RightTab from "@/components/RightTab.vue";
import Board from "./views/Board.vue";

export default {
  name: "App",
  components: {
    // RightTab,
    Board
  }
};
</script>
