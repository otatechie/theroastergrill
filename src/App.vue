<script setup>
import NavBar from './components/NavBar.vue'
import AppFooter from './components/AppFooter.vue'
import MobileActions from './components/MobileActions.vue'
</script>

<template>
    <div class="min-h-dvh bg-white text-gray-800">
        <NavBar />
        
        <router-view />
        
        <AppFooter />
        
        <!-- Mobile Actions Component -->
        <MobileActions />
    </div>
</template>

<style scoped></style>
