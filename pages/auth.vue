<template>
    <div class="flex flex-col gap-6 items-center justify-center">
        <p class="text-2xl font-semibold tracking-widest">Авторизация</p>
        <form class="flex flex-col gap-4 w-full md:w-1/2 xl:w-1/3">
            <input required type="email" class="px-4 py-2 border border-[#F7BDF6]/70 rounded-xl focus:outline-none" placeholder="Email">
            <input required type="password" class="px-4 py-2 border border-[#F7BDF6]/70 rounded-xl focus:outline-none" placeholder="Пароль">
            <button class="px-4 py-2 rounded-xl border text-white hover:text-[#F242EE]/70 border-[#F242EE]/70 bg-[#F242EE]/70 transition-all duration-500 hover:bg-transparent">Войти</button>
        </form>
        <div class="flex items-center justify-between gap-4 w-full md:w-1/2 xl:w-1/3">
            <div class="w-1/3 h-px bg-[#F7BDF6]/70"></div>
            <p class="font-Caveat text-2xl">или</p>
            <div class="w-1/3 h-px bg-[#F7BDF6]/70"></div>
        </div>
        <NuxtLink to="/reg" class="text-center w-full md:w-1/2 xl:w-1/3 px-4 py-2 rounded-xl border hover:text-white text-[#F242EE]/70 border-[#F242EE]/70 hover:bg-[#F242EE]/70 transition-all duration-500 bg-transparent">Зарегистрироваться</NuxtLink>
    </div>
</template>

<script setup>

</script>