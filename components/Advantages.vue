<template>
  <div class="container mx-auto mb-20">
    <div class="flex justify-around gap-x-20">
      <div
        v-for="item in items"
        :key="item.id"
        class="flex flex-col gap-4 items-center text-center"
      >
        <div class="text-6xl text-black">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="1"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather w-12 h-12 feather-check"
          >
            <polyline points="20 6 9 17 4 12" />
          </svg>
        </div>
        <div class="text-sm font-semibold">{{ item.text }}</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      items: [
        {
          id: 1,
          text: 'ЗАРАБАТЫВАЙТЕ БОЛЬШЕ',
        },
        {
          id: 2,
          text: 'УПРАВЛЯЙТЕ БИЗНЕСОМ ИЗ ЛЮБОГО МЕСТА',
        },
        {
          id: 3,
          text: 'ОСТАНОВИТЕ КРАЖИ И ПОТЕРИ',
        },
        {
          id: 4,
          text: 'ПРИВЛЕКАЙТЕ БОЛЬШЕ КЛИЕНТОВ',
        },
        {
          id: 5,
          text: 'ПРИВЕДИТЕ В ПОРЯДОК СКЛАД',
        },
        {
          id: 6,
          text: 'МОТИВИРУЙТЕ ПЕРСОНАЛ',
        },
      ],
    }
  },
}
</script>

<style scoped></style>
