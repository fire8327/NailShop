<template>
    <div class="flex max-lg:flex-col gap-6">
        <div class="lg:w-3/4 flex flex-col gap-6">
            <div class="flex max-md:flex-col items-center gap-4 p-4 rounded-xl border border-[#F7BDF6]/70 shadow-[0px_0px_13px_-7px_black]" v-for="n in 3">
                <img src="/images/products/3.jpg" alt="" class="aspect-square object-cover w-full md:w-2/5 rounded-xl">
                <div class="flex flex-col gap-2 w-full md:w-3/5">
                    <p class="text-2xl font-semibold tracking-widest">Гель Premium Milk</p>
                    <p>Цвет: розовый</p>
                    <p>350 ₽</p>
                    <div class="flex items-center gap-4">
                        <button class="flex items-center justify-center w-10 h-10 border border-[#F7BDF6]/70 rounded-xl">-</button>
                        <p>1</p>
                        <button class="flex items-center justify-center w-10 h-10 border border-[#F7BDF6]/70 rounded-xl">+</button>
                    </div>
                </div>
            </div>
        </div>
        <form class="lg:w-1/4 flex flex-col gap-6 p-4 rounded-xl border border-[#F7BDF6]/70 shadow-[0px_0px_13px_-7px_black] h-fit">
            <input required type="text" class="px-4 py-2 border border-[#F7BDF6]/70 rounded-xl focus:outline-none" placeholder="Адрес доставки">
            <textarea class="px-4 py-2 border border-[#F7BDF6]/70 rounded-xl focus:outline-none" placeholder="Комментарий к заказу"></textarea>
            <div class="flex flex-col gap-2">
                <p class="font-semibold tracking-widest">Способ оплаты</p>
                <label class="flex items-center gap-2">
                    <input type="radio">
                    <span>Онлайн</span>
                </label>
                <label class="flex items-center gap-2">
                    <input type="radio">
                    <span>При получении</span>
                </label>
            </div>
            <p>Итого: 350 ₽</p>
            <button class="px-4 py-2 rounded-xl border text-white hover:text-[#F242EE]/70 border-[#F242EE]/70 bg-[#F242EE]/70 transition-all duration-500 hover:bg-transparent">Оформить заказ</button>
        </form>
    </div>
</template>

<script setup>

</script>