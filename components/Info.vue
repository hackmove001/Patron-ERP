<template>
  <div class="bg-light-blue py-36">
    <div
      class="container mx-auto flex lg:flex-row md:flex-col sm:flex-col gap-8 justify-between p-10"
    >
      <div
        class="rounded-corner lg:w-3/12 px-12 border-black border-4 flex flex-col gap-y-6"
      >
        <div class="border-b border-gray-500 pb-8 pt-12">
          <h1 class="text-3xl font-bold">Не нужно считать КБЖУ</h1>
          <br> 
          <p class="text-lg font-semibold">
            Рассчитываем размер порции, пищевые волокна, микроэлементы, КБЖУ по
            рекомендациям ВОЗ
          </p>
        </div>

        <div class="border-b border-gray-500 py-4">
          <h1 class="text-3xl font-bold">250 блюд</h1>
          <br> 
          <p class="text-lg font-semibold">
            Блюда не повторяются 4 недели подряд. Вкусно и разнообразно: салаты,
            мясо птицы и говядина
          </p>
        </div>

        <div class="pt-4 pb-12">
          <h1 class="text-3xl font-bold">Бесплатная доставка</h1>
          <br> 
          <p class="text-lg font-semibold">
            Привозим каждые два дня. Интервал доставки 2 часа в любой промежуток
            с 6 до 12 утра
          </p>
        </div>
      </div>
      <div class="rounded-corner bg-white p-12 lg:w-9/12 flex flex-col gap-6">
        <h1 class="text-4xl font-bold">Меню «Базовое» на 6 дней</h1>
        <div class="my-4">
            <div class="text-3xl font-bold">Калорийность</div>
            <div class="text-gray-500 font-semibold text-lg">
                Калорийность влияет только на размер порции и не меняет меню
            </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.rounded-corner {
    border-radius: 4rem;
}
</style>