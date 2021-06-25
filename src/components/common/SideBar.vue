<template>
  <div
    id="sidebar"
    class="sidebar bg-black text-white h-screen fixed top-0 left-0 "
  >
    <div class="flex items-unset flex-col justify-around h-100 px-5">
      <span class="brand font-bold mx-5 my-10">
        <b class="bg-white text-black py-2 pl-2"> BEE</b>CODE.</span
      >
      <router-link class="p-2" to="/dashboard">Dashboard</router-link>
      <router-link class="p-2" to="/">Home</router-link>
      <router-link class="p-2" to="/about">About</router-link>
      <router-link class="p-2" to="/blogs">All blog</router-link>
      <router-link class="p-2" to="/blogs">Write a post</router-link>
      <router-link class="p-2" to="/blogs">Setting</router-link>
      <!-- <router-link to="/auth/login">Login</router-link> -->
      <button
        @click="$router.push('/home')"
        class="rounded-lg border px-4 py-2"
      >
        Logout
      </button>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  },
};
</script>

<style scoped>
#sidebar a.router-link-exact-active {
  color: #54bd8c;
  border-bottom: 1px solid #0f5032;
}
</style>
