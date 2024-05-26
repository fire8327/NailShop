<template>
    <footer class="grid-container bg-[#F7BDF6] py-4">
        <div class="flex max-md:flex-col items-center lg:items-start justify-between gap-4">
            <NuxtLink to="/" class="font-Caveat font-bold text-4xl">NailShop</NuxtLink>
            <div class="flex items-center gap-4 max-md:flex-col">
                <div class="flex items-center gap-2">
                    <NuxtLink class="transition-all duration-500 group">
                        <Icon class="text-4xl transition-all duration-500 group-hover:text-white" name="ic:sharp-telegram"/>
                    </NuxtLink>
                    <NuxtLink class="transition-all duration-500 group">
                        <Icon class="text-4xl transition-all duration-500 group-hover:text-white" name="mdi:whatsapp"/>
                    </NuxtLink>
                    <NuxtLink class="transition-all duration-500 group">
                        <Icon class="text-4xl transition-all duration-500 group-hover:text-white" name="mdi:instagram"/>
                    </NuxtLink>
                </div>
                <NuxtLink to="tel:8 912 345-67-89" class="text-2xl flex flex-col after:w-0 after:h-px after:bg-[#292929] after:transition-all after:duration-500 hover:after:w-full">8 912 345-67-89</NuxtLink>
            </div>
        </div>
        <p class="text-center font-Comforter text-4xl">Влюбись в искусство маникюра</p>
    </footer>
</template>

<script setup>

</script>