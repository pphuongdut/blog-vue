<template>
  <div id="nav">
    <transition name="fade" mode="out-in">
      <component :is="layout">
        <transition name="slide-fade" mode="out-in">
          <router-view />
        </transition>
      </component>
    </transition>
  </div>
</template>
<script>
import defautLayout from "@/layout/default.vue";
import unauthLayout from "@/layout/unauth.vue";

export default {
  components: {
    defautLayout,
    unauthLayout,
  },
  computed: {
    layout() {
      console.log("layout" + this.$route.meta.layout);
      return this.$route.meta.layout === "unauth"
        ? "unauthLayout"
        : "defautLayout";
    },
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #259261;
}
</style>
