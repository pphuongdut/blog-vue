<template>
  <div class="bg-black text-white flex justify-around items-center py-5">
    <span class="brand font-bold mr-5">
      <b class="bg-white text-black py-2 pl-2"> BEE</b>CODE.</span
    >
    <div>
      <div class="text-2xl">
        <font-awesome-icon
          @click="searchActive = !searchActive"
          class="mx-2 cursor-pointer"
          :icon="['fab', 'facebook']"
        />
        <font-awesome-icon
          @click="searchActive = !searchActive"
          class="mx-2 cursor-pointer"
          :icon="['fab', 'linkedin']"
        />
        <font-awesome-icon
          @click="searchActive = !searchActive"
          class="mx-2 cursor-pointer"
          :icon="['fab', 'instagram']"
        />
      </div>
    </div>
  </div>
</template>
