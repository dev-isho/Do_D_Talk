<template>
  <div class="px-24 shadow">
    <div class="flex items-center py-5 justify-between">
      <div>
        <img src="~/assets/images/dologo.png" class="h-16 w-48 cursor-pointer" />
      </div>
      <div class="flex text-sm">
        <div class="mx-2">
          <nuxt-link to>Home</nuxt-link>
        </div>
        <div class="mx-2">
          <nuxt-link to>About Us</nuxt-link>
        </div>
        <div class="mx-2">
          <nuxt-link to>Services</nuxt-link>
        </div>
        <div class="mx-2">
          <nuxt-link to>Portfolio</nuxt-link>
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
