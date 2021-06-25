<template>
  <div id="nav" class="navbar flex justify-start relative">

    <div v-if="this.$route.meta.layout !== 'secret'" class="flex items-center">
      <span class="brand font-bold mr-5"   @click="$router.push('/')">
        <b class="bg-black text-white py-2 pl-2"> BEE</b>CODE.</span
      >
      <div>
        <router-link class="p-2" to="/">Home</router-link>
        <router-link class="p-2" to="/about">About</router-link>
        <router-link class="p-2" to="/blogs">Blog</router-link>
      </div>
      <!-- <router-link to="/auth/login">Login</router-link> -->
    </div>
    <div class="flex absolute top-0 right-0 h-100">
      <div class="relative mx-2">
        <transition name="fade">
          <input
            v-if="searchActive"
            class="border rounded-lg p-2"
            type="text"
          />
        </transition>
        <font-awesome-icon
          @click="searchActive = !searchActive"
          class="icon_search cursor-pointer"
          :icon="['fas', 'search']"
        />
      </div>

      <button
        @click="$router.push('/auth/login')"
        class="rounded-lg border px-4 py-2"
      >
        Login
      </button>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      searchActive: false,
    };
  },
  created() {
  
  }
};
</script>

<style scoped>
#nav {
  height: 50px;
  margin-bottom: 10px;
}
#nav a {
  font-weight: bold;
  color: #2c3e50;
  transition: all 0.3s ease-in-out;
  cursor: pointer;
}

#nav a.router-link-exact-active {
  color: #0f5032;
  border-bottom: 1px solid #0f5032;
}
.icon_search {
  position: absolute;
  top: 50%;
  right: 0;
  transform: translate(-50%, -50%);
}
</style>
