<template>
    <header class="flex flex-col w-full relative">
        <div class="w-full h-6 bg-[#F7BDF6]"></div>
        <div class="grid-container bg-white py-4 max-md:border max-md:border-[#F7BDF6]/70">
            <div class="flex items-center justify-between gap-6">
                <NuxtLink to="/" class="font-Caveat font-bold text-4xl">NailShop</NuxtLink>
                <nav class="flex items-center gap-6 transition-all duration-500 z-[4] max-md:flex-col max-md:bg-white max-md:w-full max-md:absolute max-md:left-0 max-md:py-4" :class="isMenuShow ? 'max-md:top-[calc(100%+1px)]' : 'max-md:top-0 max-md:-translate-y-full'">
                    <NuxtLink class="flex flex-col after:w-0 after:h-px after:bg-[#292929] after:transition-all after:duration-500 hover:after:w-full">Каталог</NuxtLink>
                    <NuxtLink class="transition-all duration-500 hover:text-[#F242EE]/70">
                        <Icon class="text-3xl" name="material-symbols:person"/>
                    </NuxtLink>
                    <NuxtLink class="transition-all duration-500 hover:text-[#F242EE]/70">
                        <Icon class="text-3xl" name="material-symbols:favorite-rounded"/>
                    </NuxtLink>
                    <NuxtLink class="transition-all duration-500 hover:text-[#F242EE]/70">
                        <Icon class="text-3xl" name="ic:sharp-shopping-cart"/>
                    </NuxtLink>
                    <NuxtLink class="px-4 py-2 rounded-xl opacity-70 border border-[#F242EE] bg-[#F242EE] text-white transition-all duration-500 hover:bg-transparent hover:text-[#F242EE]">Вход</NuxtLink>
                </nav>
                <button @click="isMenuShow = !isMenuShow" class="md:hidden">
                    <Icon class="text-3xl" name="ph:list-bold"/>
                </button>
            </div>
        </div>
        <div class="fixed inset-0 top-[100px] bg-black/70 md:hidden z-[3]" :class="{'hidden' : !isMenuShow}"></div>
    </header>
</template>

<script setup>
    /* показ меню */
    const isMenuShow = ref(false)
</script>