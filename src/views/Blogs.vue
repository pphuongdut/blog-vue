<template>
  <div class="flex">
    <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
    <h1>BLOGS</h1>
    <div v-for="(blog, index) in blogs" :key="'blog' + blog.id + index">
      <h4>
        {{ blog.content }}
      </h4>
      <img :src="blog.thumbnail" alt="" srcset="" />
    </div>
    <DetailBlog />
  </div>
</template>

<script>
// @ is an alias to /src
import DetailBlog from "@/components/uncommon/Blogs/DetailBlog.vue";

export default {
  name: "Home",
  components: {
    DetailBlog,
  },
  data() {
    return {
      blogs: [
        {
          id: "2",
          categoryId: "2",
          createdAt: "2021-04-23T09:07:41.855Z",
          title: "cross-platform",
          thumbnail: "http://lorempixel.com/640/480/animals",
          description: "Legacy",
          content:
            "I'll compress the cross-platform CSS monitor, that should alarm the JSON program!",
        },
        {
          id: "3",
          categoryId: "3",
          createdAt: "2021-04-23T14:57:39.459Z",
          title: "Bedfordshire",
          thumbnail: "http://lorempixel.com/640/480/transport",
          description: "Investor",
          content:
            "If we transmit the bandwidth, we can get to the SCSI microchip through the back-end JBOD hard drive!",
        },
        {
          id: "4",
          categoryId: "4",
          createdAt: "2021-04-23T13:31:36.828Z",
          title: "programming application quantify",
          thumbnail: "http://lorempixel.com/640/480/city",
          description: "Dynamic",
          content:
            "Use the redundant TCP capacitor, then you can parse the redundant monitor!",
        },
      ],
    };
  },
};
</script>
