<template>
  <div class="w-screen h-screen text-black">
    <form
     
      class="border rounded-lg w-1/2 m-auto p-10 text-center"
    >
      <h2 class="text-xl font-bold">Welcome back !</h2>
      <small> Sign in to get the most out of nuntium.</small>
      <div class="relative m-2">
        <input
          placeholder="Username"
          required
          class="border rounded-lg w-full p-2"
          type="text"
        />

        <!-- <font-awesome-icon
        
          class=" cursor-pointer"
          :icon="['fas', 'search']"
        /> -->
      </div>
      <div class="relative m-2">
        <input
          placeholder="Password"
          required
          class="border w-full rounded-lg p-2"
          type="text"
        />

        <!-- <font-awesome-icon
          class=" cursor-pointer"
          :icon="['fas', 'search']"
        /> -->
      </div>
      <div class="flex m-2 items-center">
        <input type="checkbox" name="" id="" />
        <small class="mx-3">Remember me ?</small>
      </div>
      <button type="submit"
        @click="this.$router.push('/dashboard')"
        class="rounded-lg border border-black px-4 py-2 w-full"
      >
        Login
      </button>
    </form>
  </div>
</template>
