<template>
  <AppHeader />
  <div class="w-full flex">
    <!-- <DcHeros /> -->
    <Calendar />
  </div>
</template>

<script>
  import AppHeader from "./components/AppHeader.vue";
  import Calendar from "./components/Calendar.vue";
  // import DcHeros from "./components/DcHeros.vue";
  export default {
      components: { AppHeader, Calendar }
  };
</script>
<style></style>