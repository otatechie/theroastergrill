<template>
    <!-- Mobile Floating Actions -->
    <div v-if="showActions" class="fixed bottom-0 left-0 right-0 z-50 lg:hidden">
        <div class="flex items-center justify-between gap-3 px-4 py-4 bg-black">
            <!-- Call Button -->
            <a href="tel:+233200000000" 
               class="flex-1 flex items-center justify-center bg-green-600 px-3 py-3 rounded-md">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path>
                </svg>
                <span class="text-white font-semibold text-md font-serif ml-3">CALL NOW</span>
            </a>

            <!-- Order Button -->
            <router-link to="/contact" 
                         class="flex-1 flex items-center justify-center bg-red-600 px-3 py-3 rounded-md">
                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"></path>
                </svg>
                <span class="text-white font-semibold text-md font-serif ml-3">ORDER NOW</span>
            </router-link>
        </div>
    </div>
</template>

<script setup>
import { ref, onMounted, onUnmounted } from 'vue'

const showActions = ref(false)
const scrollThreshold = 300 // Show actions after scrolling 300px
const hideThreshold = 100 // Hide actions when scrolling back up to 100px

const handleScroll = () => {
    const scrollY = window.scrollY
    
    if (scrollY > scrollThreshold) {
        showActions.value = true
    } else if (scrollY < hideThreshold) {
        showActions.value = false
    }
}

const hideActions = () => {
    showActions.value = false
}

onMounted(() => {
    window.addEventListener('scroll', handleScroll)
})

onUnmounted(() => {
    window.removeEventListener('scroll', handleScroll)
})
</script>

