<script setup>
defineProps({
    imageUrl: String,
})
</script>

<template>
    <div class="flex justify-center border border-slate-200 p-4 rounded-xl gap-4">
        <img class="w-16 h-16" src="/sneakers/sneakers-1.jpg" alt="Sneaker">
        <div class="flex flex-col">
            <p>Мужские кроссовки Nike Blazer Mid Suede</p>
            <div class="flex justify-between mt-2">
                <b>12990 руб.</b>
                <img class="cursor-pointer opacity-40 hover:opacity-100 transition" src="/close.svg" alt="close">
            </div>
        </div>
    </div>
</template>