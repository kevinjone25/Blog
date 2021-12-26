<template>
  <div>
    <Sidebar :name="sidebar"></Sidebar>
  </div>
</template>

<script>
import Sidebar from "./components/Sidebar";
export default {
  name: "intro",
  components: {
    Sidebar,
  },
  data() {
    return {
      sidebar:"Kevin Blog",
    };
  },
  }

</script>

<style lang="postcss">
.intro {
  @apply font-bold text-2xl text-blue-500 m-12
}
</style>
