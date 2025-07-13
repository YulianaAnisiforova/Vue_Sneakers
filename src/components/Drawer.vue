<script setup>
import CartList from './CartList.vue'
</script>

<template>
    <div class="fixed top-0 left-0 h-full w-full bg-black z-10 opacity-70"></div>
    <div class="bg-white w-96 h-full fixed right-0 top-0 z-20 p-8">
        <div class="flex items-center gap-5 mb-8">
            <span class="opacity-30 cursor-pointer hover:opacity-100 transition hover:-translate-x-1">←</span>
            <h2 class="text-2xl font-bold">Корзина</h2>
        </div>
        <CartList />
    </div>
</template>