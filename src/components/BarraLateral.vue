<template>
    <header>
        <h1>
            <img src="https://i.pinimg.com/originals/10/d9/63/10d9631abb9778072c1da264a6d4709a.png"
                alt="100%"  class="imagem-logo">
        </h1>
    </header>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'BarraLateral'
})
</script>

<style scoped>
header {
    background: rgb(255,255,255);
    background: linear-gradient(180deg, rgba(255,255,255,1) 0%, rgba(151,207,228,1) 67%, rgb(14, 201, 239) 100%);
    width: 100%;
    height: 100vh;
    padding: 0.5vw;
}

@media only screen and (max-width: 768) {
    header {
        padding: 2.5rem;
        height: auto;
    }
}
imagem-logo {
    object-fit: cover;
    border-radius: 20px;
}
</style>