<template>
  <div class="main">
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
import secretLayout from "@/layout/secret.vue";
export default {
  components: {
    defautLayout,
    unauthLayout,
    secretLayout,
  },
  computed: {
    layout() {
      // console.log("layout" + this.$route.meta.layout);
      if (this.$route.meta.layout === "secret") {
        return "secretLayout";
      }
      return this.$route.meta.layout === "unauth"
        ? "unauthLayout"
        : "defautLayout";
    },
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500&display=swap");
* {
  font-family: "Roboto", sans-serif !important;
}
.main {
  padding: 1.5rem;
  padding-bottom: 0px;
}
.padding {
  
}
</style>
