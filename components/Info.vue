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
          <br />
          <p class="text-lg font-semibold">
            Рассчитываем размер порции, пищевые волокна, микроэлементы, КБЖУ по
            рекомендациям ВОЗ
          </p>
        </div>

        <div class="border-b border-gray-500 py-4">
          <h1 class="text-3xl font-bold">250 блюд</h1>
          <br />
          <p class="text-lg font-semibold">
            Блюда не повторяются 4 недели подряд. Вкусно и разнообразно: салаты,
            мясо птицы и говядина
          </p>
        </div>

        <div class="pt-4 pb-12">
          <h1 class="text-3xl font-bold">Бесплатная доставка</h1>
          <br />
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

        <div class="my-4">
          <div class="text-3xl font-bold">Доставка</div>
          <div class="text-gray-500 font-semibold text-lg">
            В понедельник, среду и пятницу в любой двухчасовой интервал с 6 до
            12 утра.
          </div>
        </div>

        <div class="my-4 flex justify-between border-b items-center pb-4">
          <div class="text-3xl font-bold">Скидка на первый заказ</div>
          <div
            class="text-black flex justify-center text-2xl items-center font-semibold text-lg border-4 border-orange px-6 py-2"
            style="border-radius: 50%"
          >
            -20 %
          </div>
        </div>

        <div class="flex justify-end items-center">
          <div
            class="text-black flex justify-center text-3xl items-center font-semibold text-lg"
          >
            <del>6930 ₽</del>
          </div>
        </div>

        <div class="my-4 flex justify-between border-b items-center pb-4">
          <div class="text-3xl font-bold">Итого за 6 дней:</div>
          <div
            class="text-black flex justify-center text-3xl items-center font-semibold text-lg"
          >
            5544 ₽
          </div>
        </div>

        <div class="bg-gray-200">
          <label
            for="name"
            class="block px-6 pt-4 text-xl font-medium text-gray-700"
            >Mobile phone:</label
          >
          <div class="mt-1 border-b-4 px-6 border-gray-300">
            <input
              type="text"
              name="name"
              id="name"
              class="block w-full pb-2 lg:text-4xl font-semibold border-0 bg-gray-200 border-b border-transparent focus:ring-0 sm:text-sm"
              value="+998"
              maxlength="13"
            />
          </div>
        </div>
        <span class="text-gray-500 px-6 -mt-6"
          >Для перехода к оформлению заказа онлайн</span
        >

        <button class="bg-orange rounded-full text-3xl text-white py-8 font-semibold mt-8 w-full">
          Заказать
        </button>

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

input {
  outline: none;
}
</style>
