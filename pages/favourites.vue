<template>
    <div class="flex flex-col gap-6">
        <p class="text-2xl font-semibold tracking-widest">Избранное</p>
        <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-4 gap-6">
            <ProductCard v-for="n in 8"></ProductCard>
        </div>
    </div>
</template>

<script setup>

</script>