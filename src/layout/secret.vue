<template>
  <div>
    <Navbar />
    <div class="flex justify-between">
      <SideBar />
      <slot />
    </div>
  </div>
</template>
<script>
import Navbar from "../components/common/Navbar.vue";
import SideBar from "../components/common/SideBar.vue";
export default {
  components: {
    SideBar,
    Navbar,
  },
};
</script>
