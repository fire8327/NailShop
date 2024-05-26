<template>
    <div class="flex flex-col gap-6">
        <p class="text-2xl font-semibold tracking-widest">Новинки</p>
        <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-4 gap-6">
            <div class="flex flex-col gap-4">
                <NuxtLink class="overflow-hidden rounded-xl border border-[#F7BDF6]/70 group shadow-[0px_0px_13px_-7px_black]">
                    <img src="/images/products/1.jpg" alt="" class="transition-all duration-500 group-hover:scale-110 aspect-[7/10] object-cover">
                </NuxtLink>
                <p>Фреза ёлка зеленая Wilson</p>
            </div>
            <div class="flex flex-col gap-4">
                <NuxtLink class="overflow-hidden rounded-xl border border-[#F7BDF6]/70 group shadow-[0px_0px_13px_-7px_black]">
                    <img src="/images/products/2.jpg" alt="" class="transition-all duration-500 group-hover:scale-110 aspect-[7/10] object-cover">
                </NuxtLink>
                <p>База shell</p>
            </div>
            <div class="flex flex-col gap-4">
                <NuxtLink class="overflow-hidden rounded-xl border border-[#F7BDF6]/70 group shadow-[0px_0px_13px_-7px_black]">
                    <img src="/images/products/3.jpg" alt="" class="transition-all duration-500 group-hover:scale-110 aspect-[7/10] object-cover">
                </NuxtLink>
                <p>Гель Розовая жемчужина</p>
            </div>
            <div class="flex flex-col gap-4">
                <NuxtLink class="overflow-hidden rounded-xl border border-[#F7BDF6]/70 group shadow-[0px_0px_13px_-7px_black]">
                    <img src="/images/products/4.jpeg" alt="" class="transition-all duration-500 group-hover:scale-110 aspect-[7/10] object-cover">
                </NuxtLink>
                <p>Антисептик малиновый смузи 150 мл</p>
            </div>
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
                <p>МОЩНЫЙ И КОМПАКТНЫЙ АППАРАТ ДЛЯ МАНИКЮРА ОТ AEROPUFFING</p>
            </div>
            <div class="flex flex-col gap-4">
                <div class="overflow-hidden rounded-xl border border-[#F7BDF6]/70 group shadow-[0px_0px_13px_-7px_black]">
                    <img src="/images/news/2.jpg" alt="" class="w-full transition-all duration-500 group-hover:scale-110 aspect-square object-cover">
                </div>
                <p>ПРОФЕССИОНАЛЬНЫЕ КИСТИ ДЛЯ МАНИКЮРА TNL PROFESSIONAL</p>
            </div>
            <div class="flex flex-col gap-4">
                <div class="overflow-hidden rounded-xl border border-[#F7BDF6]/70 group shadow-[0px_0px_13px_-7px_black]">
                    <img src="/images/news/3.png" alt="" class="w-full transition-all duration-500 group-hover:scale-110 aspect-square object-cover">
                </div>
                <p>ГЕЛЬ СО СТЕКЛОВОЛОКНОМ "SТЕКЛО" ДЛЯ УКРЕПЛЕНИЯ НОГТЕЙ И РЕМОНТА ТРЕЩИН ОТ BSG</p>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>