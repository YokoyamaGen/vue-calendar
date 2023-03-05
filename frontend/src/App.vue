<template>
  <v-app>
    <v-main>
      <CalendarBasic />
    </v-main>
  </v-app>
</template>

<script>
import CalendarBasic from "./components/pages/CalendarBasic";

export default {
  name: "App",
  components: {
    CalendarBasic,
  },
};
</script>
