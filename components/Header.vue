<template>
  <div class="px-24 fixed min-w-full border-b-2 z-50 bg-green-400 shadow-2xl text-white">
    <div class="flex items-center py-5 justify-between">
      <div>
        <img src="~/assets/images/dologo.png" class="h-16 w-48 cursor-pointer" />
      </div>
      <div class="flex text-sm font-semibold">
        <div class="mx-2">
          <nuxt-link to="/">Home</nuxt-link>
        </div>
        <div class="mx-2">
          <nuxt-link to="/about">About Us</nuxt-link>
        </div>
        <div class="mx-2">
          <nuxt-link to="/services">Services</nuxt-link>
        </div>
        <div class="mx-2">
          <nuxt-link to="/portfolio">Portfolio</nuxt-link>
        </div>
        <div class="mx-2">
          <nuxt-link to="/Contact">Contact Us</nuxt-link>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
