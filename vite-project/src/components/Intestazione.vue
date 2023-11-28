<script>
import AppTitle from "./AppTitle.vue";
import AppHero from "./AppHero.vue";
export default {
    components: {
        AppTitle,
        AppHero
    }
}
</script>

<template>
    <header>
        <AppTitle />
        <AppHero />
    </header>
</template>

<style scoped>
header {
    padding: 1rem 0;
    display: flex;
    flex-direction: column;
    align-items: center;
}
</style>