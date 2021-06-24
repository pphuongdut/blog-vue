<template>
  <transition name="slide-fade" mode="out-in">
    <slot />
  </transition>
</template>
<script>
// import Navbar from "../components/common/Navbar.vue";
export default {
  components: {
    // Navbar,
  },
};
</script>
