<template>
  <div class="home_header_bg bg-cover bg-center">
    <div
      class="
        h-4/5
        w-3/4 lg:w-4/12
        bg-white
        mx-16
        px-10
        py-5
        text-black
        flex flex-col
        justify-center
      "
    >
      <h2 class="font-bold my-3 header_title">
        {{ post_header.title }}
      </h2>
      <small class="my-2">{{ post_header.description }} - {{ post_header.createdAt }}</small>
      <p>
        {{ post_header.content }}
          {{ post_header.content }}
      </p>
    </div>
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
.home_header_bg {
  background-image: url(../../../../src/assets/img/home/header_bg.jpg);
  width: 100%;
  height: calc(100vh - 1.5rem - 60px);
}
.header_title {
  font-size: 1.9rem;
}
</style>
