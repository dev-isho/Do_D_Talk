<template>
  <div class="pt-32">
    <div class="mt-5 bg-white px-16 py-10 flex">
      <div class="w-1/2">
        <img src="~/assets/images/About.jpg" />
      </div>
      <div class="w-1/2">
        <p class="text-3xl font-semibold uppercase">PLUMBING REPAIR SERVICES</p>
        <p
          class="mt-5"
        >Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsa eius qui consectetur accusamus delectus cupiditate, quia magnam ad amet! Similique architecto velit necessitatibus dignissimos distinctio obcaecati temporibus modi. Autem, iste officiis. Quaerat molestias voluptatibus libero quis ipsam esse quae enim vel eligendi deleniti quidem labore ad, quam modi rerum cumque adipisci incidunt unde quod impedit voluptas repellat aperiam itaque. Iusto quae facilis nobis quisquam! Molestias sit ipsa dicta corrupti dolores eligendi illo quod consequatur eveniet sed blanditiis voluptas porro commodi nobis exercitationem, natus accusantium harum debitis in eos veritatis. Inventore magnam adipisci quis fugit vel totam aspernatur cupiditate dicta esse, provident voluptatibus distinctio labore ea repellendus ipsam recusandae ex accusamus reprehenderit ullam repellat, animi fugiat, perferendis delectus quaerat? Dignissimos, autem explicabo sequi perspiciatis perferendis error cumque commodi, aspernatur exercitationem et hic aperiam quam impedit veritatis quibusdam similique suscipit deserunt! Ut placeat nostrum eius. Ab, nam nostrum fugit soluta quo minus voluptates, ipsum voluptas eos veritatis, quam itaque assumenda fuga vero quae praesentium eligendi saepe? Accusamus at autem libero ullam aut, tempora cupiditate atque consequuntur incidunt sapiente quibusdam eaque, culpa molestias aliquid odit amet assumenda!</p>
        <button
          class="uppercase rounded-full mt-5 text-white font-semibold px-10 py-3 bg-green-500"
        >More</button>
      </div>
    </div>
    <div class="bg-gray-100 pt-16 px-20 border-t-2 border-white">
      <div class="flex">
        <div class="w-1/3">
          <img src="~/assets/images/footer-big.png" />
        </div>
        <div class="w-2/3">
          <div class="flex flex-wrap">
            <div class="flex w-1/2 py-8 px-2">
              <img src="~/assets/images/toilet.jpg" alt class="w-32 h-20 mr-2" />
              <div>
                <p class="text-xl font-semibold">TOILETS</p>
                <p
                  class="mt-3 text-sm"
                >Lorem ipsum dolor sit amet timeam deleniti mnesarchum ex sed alii hinc dolores ad cum. Urbanitas similique ex nam paulo temporibus ea vis id odio adhuc nostrum eos.</p>
              </div>
            </div>
            <div class="flex w-1/2 py-8 px-2">
              <img src="~/assets/images/hot.jpg" alt class="w-32 h-20 mr-2" />
              <div>
                <p class="text-xl font-semibold">HOT WATER DISPENCER</p>
                <p
                  class="mt-3 text-sm"
                >Lorem ipsum dolor sit amet timeam deleniti mnesarchum ex sed alii hinc dolores ad cum. Urbanitas similique ex nam paulo temporibus ea vis id odio adhuc nostrum eos.</p>
              </div>
            </div>
            <div class="flex w-1/2 py-8 px-2">
              <img src="~/assets/images/bath.jpg" alt class="w-32 h-20 mr-2" />
              <div>
                <p class="text-xl font-semibold">BATH TUB</p>
                <p
                  class="mt-3 text-sm"
                >Lorem ipsum dolor sit amet timeam deleniti mnesarchum ex sed alii hinc dolores ad cum. Urbanitas similique ex nam paulo temporibus ea vis id odio adhuc nostrum eos.</p>
              </div>
            </div>
            <div class="flex w-1/2 py-8 px-2">
              <img src="~/assets/images/basin.jpg" alt class="w-32 h-20 mr-2" />
              <div>
                <p class="text-xl font-semibold">HAND BASIN</p>
                <p
                  class="mt-3 text-sm"
                >Lorem ipsum dolor sit amet timeam deleniti mnesarchum ex sed alii hinc dolores ad cum. Urbanitas similique ex nam paulo temporibus ea vis id odio adhuc nostrum eos.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="bg-gray-400">
      <div class="flex items-center h-full p-16">
        <div class="w-1/4 flex flex-col items-center mx-5 my-12">
          <img src="~/assets/images/wrench.png" />
          <p class="text-xl mt-8 font-semibold">RESIDENTIAL</p>
          <p
            class="text-center mt-3"
          >Lorem ipsum dolor sit amet timeam deleniti mnesarchum ex sed alii hinc dolores ad cum. Urbanitas similique ex nam paulo temporibus ea vis id odio adhuc nostrum eos.</p>
        </div>
        <div class="w-1/4 flex flex-col items-center mx-5 my-12">
          <img src="~/assets/images/sink.png" />
          <p class="text-xl mt-8 font-semibold">KITCHEN PLUMBING</p>
          <p
            class="text-center mt-3"
          >Lorem ipsum dolor sit amet timeam deleniti mnesarchum ex sed alii hinc dolores ad cum. Urbanitas similique ex nam paulo temporibus ea vis id odio adhuc nostrum eos.</p>
        </div>
        <div class="w-1/4 flex flex-col items-center mx-5 my-12">
          <img src="~/assets/images/plumbing.png" />
          <p class="text-xl mt-8 font-semibold">COMMERCIAL</p>
          <p
            class="text-center mt-3"
          >Lorem ipsum dolor sit amet timeam deleniti mnesarchum ex sed alii hinc dolores ad cum. Urbanitas similique ex nam paulo temporibus ea vis id odio adhuc nostrum eos.</p>
        </div>
        <div class="w-1/4 flex flex-col items-center mx-5 my-12">
          <img src="~/assets/images/toilet.png" />
          <p class="text-xl mt-8 font-semibold">EMERGENCY</p>
          <p
            class="text-center mt-3"
          >Lorem ipsum dolor sit amet timeam deleniti mnesarchum ex sed alii hinc dolores ad cum. Urbanitas similique ex nam paulo temporibus ea vis id odio adhuc nostrum eos.</p>
        </div>
      </div>
    </div>
    <our-services-vue />
  </div>
</template>
<script>
import OurServicesVue from "../components/OurServices.vue";

export default {
  components: {
    OurServicesVue
  }
};
</script>
