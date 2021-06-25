<template>
  <div class="flex flex-col items-center">
    <!-- <h1>{{ $route.params.id }}</h1> -->
    <img
      class="w-full blog_thumbnail object-cover object-center"
      :src="blog.thumbnail"
      alt=""
      srcset=""
    />
   <div class="w-1/2">
      <h1 class="text-center text-xl font-bold text-green-900 my-5">
      {{ blog.title }}
    </h1>

    <!-- <small class="text-gray-500 text-center w-full"> {{ blog.createdAt }} </small> -->
    <p class="my-5">{{ blog.description + blog.description  +blog.description  + blog.description }}</p>
   </div>
  </div>
</template>

<script>
export default {
  name: "DetailBlog",
  props: {
    blog: {},
  },
  created() {
    // console.log(this.$route.params.id);
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.blog_thumbnail {
  height: 50vh;
}
</style>
