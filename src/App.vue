<script setup>
import Header from './components/Header.vue'
import CardList from './components/CardList.vue'
import Drawer from './components/Drawer.vue'
</script>

<template>
    <!-- <Drawer/> -->
    <div class="w-4/5 m-auto bg-white rounded-xl shadow-xl mt-14">
        <Header />
        <div class="p-10">
            <div class="flex justify-between items-center mb-8">
                <h2 class="text-3xl font-bold">Все кроссовки</h2>

                <div class="flex gap-4">
                    <select class="py-2 px-3 border border-gray-200 rounded-md outline-none">
                        <option>По названию</option>
                        <option>По цене (дешевые)</option>
                        <option>По цене (дорогие)</option>
                    </select>
                    
                    <div class="relative">
                        <img class="absolute left-4 top-3"
                        src="/search.svg" alt="search">
                        <input class="border border-gray-200 rounded-md py-2 pl-11 pr-4 outline-none focus:border-gray-400" 
                        placeholder="Поиск...">
                    </div>
                </div>
            </div>
            <CardList />
        </div>
    </div>
</template>

<style scoped>

</style>
