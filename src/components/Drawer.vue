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

        <div class="flex flex-col gap-4 mb-6 mt-7">
            <div class="flex gap-2">
                <span>Итого:</span>
                <div class="flex-1 border-b border-dashed"></div>
                <b>12990 ₽</b>
            </div>
            <div class="flex gap-2">
                <span>Налог 5%:</span>
                <div class="flex-1 border-b border-dashed"></div>
                <b>900 ₽</b>
            </div>
            <button disabled="" class="mt-4 bg-lime-500 w-full rounded-xl py-3 cursor-pointer text-white disabled:bg-slate-300 disabled:cursor-auto hover:bg-lime-600 transition active:bg-lime-700">Оформить заказ</button>
        </div>
    </div>
</template>