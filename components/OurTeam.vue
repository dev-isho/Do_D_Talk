<template>
  <div class="bg-green-500 text-white px-16 py-24">
    <p class="uppercase text-3xl font-bold mx-4">MEET OUR SPECIALISTS</p>
    <div class="flex mt-10">
      <div class="px-3 w-1/4">
        <img src="~/assets/images/T1.jpg" class="h-64 w-full" />
        <p class="mt-3 text-base font-semibold">JOANNA OLLEY</p>
        <p class="text-sm">Plumbing Mechanic</p>
        <p
          class="mt-3 text-sm"
        >Aenean consectetur ipsum ante, vel egestas enim tincidunt quis. Pellentesque vitae congue neque, vel mattis ante. In vitae tempus nunc.</p>
      </div>
      <div class="px-4 w-1/4">
        <img src="~/assets/images/T2.jpg" class="h-64 w-full" />
        <p class="mt-3 text-base font-semibold">JOANNA OLLEY</p>
        <p class="text-sm">Plumbing Mechanic</p>
        <p
          class="mt-3 text-sm"
        >Aenean consectetur ipsum ante, vel egestas enim tincidunt quis. Pellentesque vitae congue neque, vel mattis ante. In vitae tempus nunc.</p>
      </div>
      <div class="px-4 w-1/4">
        <img src="~/assets/images/T3.jpg" class="h-64 w-full" />
        <p class="mt-3 text-base font-semibold">JOANNA OLLEY</p>
        <p class="text-sm">Plumbing Mechanic</p>
        <p
          class="mt-3 text-sm"
        >Aenean consectetur ipsum ante, vel egestas enim tincidunt quis. Pellentesque vitae congue neque, vel mattis ante. In vitae tempus nunc.</p>
      </div>
      <div class="px-4 w-1/4">
        <img src="~/assets/images/T4.jpg" class="h-64 w-full" />
        <p class="mt-3 text-base font-semibold">JOANNA OLLEY</p>
        <p class="text-sm">Plumbing Mechanic</p>
        <p
          class="mt-3 text-sm"
        >Aenean consectetur ipsum ante, vel egestas enim tincidunt quis. Pellentesque vitae congue neque, vel mattis ante. In vitae tempus nunc.</p>
      </div>
    </div>
    <button
      @click="about"
      class="uppercase rounded-full mt-5 mx-3 border rounded font-semibold px-5 mt-10 py-3 bg-green-500"
    >Meet PROFESSIONAL PLUMBER</button>
  </div>
</template>
<script>
export default {
  methods: {
    about() {
      this.$router.push("/about");
    }
  }
};
</script>
