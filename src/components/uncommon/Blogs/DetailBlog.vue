<template>
  <div class="hello">
    <h1>{{ $route.params.id }}</h1>
    <img :src="blog.thumbnail" alt="" srcset="" />
    <p>{{ blog.content }}</p>
  </div>
</template>

<script>
export default {
  name: "DetailBlog",
  props: {
    blog: {},
  },
  created() {
    console.log(this.$route.params.id);
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
