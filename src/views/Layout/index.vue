<script setup lang="ts">
    import AppTopnav from './components/LayoutNav.vue'
    import AppHeader from './components/LayoutHeader.vue'
    import AppFooter from './components/LayoutFooter.vue'
</script>

<template>
    <LayoutNav />
    <LayoutHeader />
    <RouterView />
    <LayoutFooter />
</template>