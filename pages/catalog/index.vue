<template>
    <div class="flex flex-col gap-6">
        <p class="text-2xl font-semibold tracking-widest">Каталог товаров</p>
        <div class="flex max-lg:flex-col gap-6">
            <div class="lg:w-1/4 flex flex-col gap-4 p-4 border border-[#F7BDF6]/70 shadow-[0px_0px_13px_-7px_black] bg-white rounded-xl py-8 h-fit">
                <div class="flex flex-col gap-2">
                    <p>Тип продукции</p>
                    <select class="w-full px-4 py-2 border border-[#F7BDF6]/70 rounded-xl focus:outline-none">
                        <option value="1">1</option>
                    </select>
                </div>
                <div class="flex flex-col gap-2">
                    <p>Цена</p>
                    <div class="flex items-center gap-2 w-full">
                        <input type="text" class="w-1/2 px-4 py-2 border border-[#F7BDF6]/70 rounded-l-xl focus:outline-none" placeholder="От">
                        <input type="text" class="w-1/2 px-4 py-2 border border-[#F7BDF6]/70 rounded-r-xl focus:outline-none" placeholder="До">
                    </div>
                </div>
                <button class="px-4 py-2 rounded-xl border text-white hover:text-[#F242EE]/70 border-[#F242EE]/70 bg-[#F242EE]/70 transition-all duration-500 hover:bg-transparent">Применить</button>
            </div>
            <div class="lg:w-3/4">
                <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-4 gap-6">
                    <ProductCard v-for="n in 10"></ProductCard>
                </div>
            </div>   
        </div>
    </div>
</template>

<script setup>

</script>