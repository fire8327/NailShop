<template>
     <div class="flex flex-col gap-6 items-center justify-center">
        <p class="text-2xl font-semibold tracking-widest">Регистрация</p>
        <form class="flex flex-col gap-4 w-full md:w-1/2 xl:w-1/3">
            <input required type="text" class="px-4 py-2 border border-[#F7BDF6]/70 rounded-xl focus:outline-none" placeholder="Фамилия">
            <input required type="text" class="px-4 py-2 border border-[#F7BDF6]/70 rounded-xl focus:outline-none" placeholder="Имя">
            <input required type="text" class="px-4 py-2 border border-[#F7BDF6]/70 rounded-xl focus:outline-none" placeholder="Отчество">
            <select required class="px-4 py-2 border border-[#F7BDF6]/70 rounded-xl focus:outline-none">
                <option value="Мужской">Мужской</option>
                <option value="Женский">Женский</option>
            </select>
            <input required type="date" class="px-4 py-2 border border-[#F7BDF6]/70 rounded-xl focus:outline-none" placeholder="Дата рождения">
            <input required type="email" class="px-4 py-2 border border-[#F7BDF6]/70 rounded-xl focus:outline-none" placeholder="Email">
            <input required type="password" class="px-4 py-2 border border-[#F7BDF6]/70 rounded-xl focus:outline-none" placeholder="Пароль">
            <input required type="text" class="px-4 py-2 border border-[#F7BDF6]/70 rounded-xl focus:outline-none" placeholder="Телефон">
            <input required type="text" class="px-4 py-2 border border-[#F7BDF6]/70 rounded-xl focus:outline-none" placeholder="Ваш город">
            <button class="px-4 py-2 rounded-xl border text-white hover:text-[#F242EE]/70 border-[#F242EE]/70 bg-[#F242EE]/70 transition-all duration-500 hover:bg-transparent">Зарегистрироваться</button>
        </form>
        <div class="flex items-center justify-between gap-4 w-full md:w-1/2 xl:w-1/3">
            <div class="w-1/3 h-px bg-[#F7BDF6]/70"></div>
            <p class="font-Caveat text-2xl">или</p>
            <div class="w-1/3 h-px bg-[#F7BDF6]/70"></div>
        </div>
        <NuxtLink to="/auth" class="text-center w-full md:w-1/2 xl:w-1/3 px-4 py-2 rounded-xl border hover:text-white text-[#F242EE]/70 border-[#F242EE]/70 hover:bg-[#F242EE]/70 transition-all duration-500 bg-transparent">Войти</NuxtLink>
    </div>
</template>

<script setup>
    
</script>