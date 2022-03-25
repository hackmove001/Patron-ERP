<template>
  <no-ssr>
    <carousel class="my-10 pb-10 container mx-auto" v-bind="options" infinite="true">
      <div
        v-for="image in images"
        :key="image.id"
        class="flex flex-col items-center justify-center"
      >
        <div>
          <img :src="image.src" class="border-r" :alt="image.alt" :title="image.alt" />
        </div>
        <div class="flex flex-col gap-4 items-center">
          <div class="flex gap-x-4">
            <button class="bg-orange rounded-full text-white px-2">More</button>
            <span class="font-bold">
              12$ <span class="text-gray-500">/ month</span>
            </span>
          </div>
          <div class="text-center font-semibold">Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam, ea.</div>
        </div>
      </div>
    </carousel>
  </no-ssr>
</template>

<script>
export default {
  data() {
    return {
      images: [
        {
          id: 1,
          src: 'https://logobank.uz:8005/media/logos_png/payme-01.png',
          alt: 'Payme',
        },
        {
          id: 2,
          src: 'https://logobank.uz:8005/media/logos_png/click-01.png',
          alt: 'Click',
        },
        {
          id: 3,
          src: 'https://logobank.uz:8005/media/logos_png/PAYMO-01.png',
          alt: 'Paymo',
        },
        {
          id: 4,
          src: 'https://paynet.uz/templates/paynet//images/white.jpg',
          alt: 'Paynet',
        },
        {
          id: 5,
          src: 'https://logobank.uz:8005/media/logos_png/Apelsin-01.png',
          alt: 'Apelsin',
        },
      ],
      options: {
        dots: false,
        loop: true,
        autoplay: true,
        nav: true,
        rewindNav: false,
        responsive: {
          0: {
            items: 1,
          },
          600: {
            items: 3,
          },
          1000: {
            items: 6,
          },
        },
      },
    }
  },
}
</script>

<style></style>
