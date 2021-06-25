<template>
  <div class="bg-black text-white flex justify-around items-center py-8">
    <div>
      <span class="brand font-bold mr-5">
        <b class="bg-white text-black py-2 pl-2"> BEE</b>CODE.</span
      >
      <p class="my-4">Developer. Writer.</p>

      <p>© 2021 Made with ❤️</p>
    </div>
    <div>
      <div class="text-2xl">
        <font-awesome-icon
          @click="$router.push('facebook.com')"
          class="mx-2 cursor-pointer"
          :icon="['fab', 'facebook']"
        />
        <font-awesome-icon
          @click="$router.push('linkedin.com')"
          class="mx-2 cursor-pointer"
          :icon="['fab', 'linkedin']"
        />
        <font-awesome-icon
          @click="$router.redirect('instagram.com')"
          class="mx-2 cursor-pointer"
          :icon="['fab', 'instagram']"
        />
      </div>
    </div>
  </div>
</template>
