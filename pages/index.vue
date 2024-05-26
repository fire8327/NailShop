<template>
    <div class="flex flex-col gap-6">
        <p class="text-2xl font-semibold tracking-widest">Новинки</p>
        <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-4 gap-6">
            <ProductCard v-for="n in 4"></ProductCard>
        </div>
    </div>
    <img src="/images/hero/main.jpg" alt="" class="w-full rounded-xl border border-[#F7BDF6]/70">
    <div class="flex flex-col gap-6">
        <p class="text-2xl font-semibold tracking-widest">Популярные бренды</p>
        <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-4 gap-6">
            <div class="bg-white rounded-xl border border-[#F7BDF6]/70 p-4 flex items-center justify-center">
                <img src="/public/images/brands/1.png" alt="" class="w-full">
            </div>
            <div class="bg-white rounded-xl border border-[#F7BDF6]/70 p-4 flex items-center justify-center">
                <img src="/public/images/brands/2.jpeg" alt="" class="w-full">
            </div>
            <div class="bg-white rounded-xl border border-[#F7BDF6]/70 p-4 flex items-center justify-center">
                <img src="/public/images/brands/3.jpg" alt="" class="w-full">
            </div>
            <div class="bg-white rounded-xl border border-[#F7BDF6]/70 p-4 flex items-center justify-center">
                <img src="/public/images/brands/4.png" alt="" class="w-full">
            </div>
        </div>
    </div>
    <div class="flex flex-col gap-6">
        <p class="text-2xl font-semibold tracking-widest">Свежие новости</p>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="flex flex-col gap-4">
                <div class="overflow-hidden rounded-xl border border-[#F7BDF6]/70 group shadow-[0px_0px_13px_-7px_black]">
                    <img src="/images/news/1.png" alt="" class="w-full transition-all duration-500 group-hover:scale-110 aspect-square object-cover">
                </div>
                <p>Мощный и компактный аппарат для маникюра от aeropuffing</p>
            </div>
            <div class="flex flex-col gap-4">
                <div class="overflow-hidden rounded-xl border border-[#F7BDF6]/70 group shadow-[0px_0px_13px_-7px_black]">
                    <img src="/images/news/2.jpg" alt="" class="w-full transition-all duration-500 group-hover:scale-110 aspect-square object-cover">
                </div>
                <p>Профессиональные кисти для маникюра TNL PROFESSIONAL</p>
            </div>
            <div class="flex flex-col gap-4">
                <div class="overflow-hidden rounded-xl border border-[#F7BDF6]/70 group shadow-[0px_0px_13px_-7px_black]">
                    <img src="/images/news/3.png" alt="" class="w-full transition-all duration-500 group-hover:scale-110 aspect-square object-cover">
                </div>
                <p>Гель со стекловолокном "SТЕКЛО" для укрепления ногтей и ремонта трещин от BSG</p>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>