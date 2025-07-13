<script setup>
import CardItem from './CardItem.vue'

const onClickAdd = () => {
    alert('onClickAdd')
}

const onClickFav = () => {
    alert('onClickFav')
}

</script>

<template>
    <div class="grid grid-cols-4 gap-5">
        <CardItem imageUrl="/sneakers/sneakers-1.jpg" 
        title="Мужские кроссовки Nike Blazer Mid Suede" 
        :price="5000"
        :is-favorite="false" 
        :is-added="false"
        :onClickFav="onClickFav"
        :onClickAdd="onClickAdd"
        />
     </div>
</template>