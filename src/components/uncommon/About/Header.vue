<template>
  <div
    class="
      about_header_bg
      bg-cover bg-center bg-white
      text-black
      flex
      justify-center
      items-center
      flex-col
    "
  >
    <span class="brand text-3xl font-bold mr-5" @click="$router.push('/')">
      <b class="bg-black text-white py-2 pl-2"> BEE</b>CODE.</span
    >
    <p class="my-5">A publishing company that focuses on the essentials.</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      post_header: {
        id: "2",
        categoryId: "2",
        createdAt: "2021-04-23T09:07:41.855Z",
        title: "WELCOME TO MY LAND !",
        thumbnail: "http://lorempixel.com/640/480/animals",
        description: "Legacy",
        content:
          "I'll compress the cross-platform CSS monitor, that should alarm the JSON program!",
      },
    };
  },
};
</script>

<style scoped>
.about_header_bg {
  width: 100%;
  height: calc(100vh - 1.5rem - 60px);
}
.header_title {
  font-size: 1.9rem;
}
</style>
