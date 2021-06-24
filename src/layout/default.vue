<template>
  <div>
    <Navbar />
    <slot />
  </div>
</template>
<script>
import Navbar from "../components/common/Navbar.vue";
export default {
  components: {
    Navbar,
  },
};
</script>
