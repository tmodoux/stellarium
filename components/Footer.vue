<template>
    <footer>
        <NuxtLink to="/" tag="img" :src="require('~/static/galaxies.svg')"></NuxtLink>
        <NuxtLink to="/ship" tag="img" :src="require('~/static/ship.svg')"></NuxtLink>
        <NuxtLink to="/research" tag="img" :src="require('~/static/research.svg')"></NuxtLink>
        <NuxtLink to="/rewards" tag="img" :src="require('~/static/rewards.svg')"></NuxtLink>
        <NuxtLink to="/graph" tag="img" :src="require('~/static/graph.svg')"></NuxtLink>
    </footer>
</template>
<script>
export default {};
</script>
<style scoped>
    footer {
        overflow: hidden;
        position: fixed;
        bottom: 20px;
        width: 100%;
        display: flex;
        justify-content: space-around;
    }
</style>