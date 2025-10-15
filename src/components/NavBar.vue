<script setup>
import { ref } from 'vue'

const isMobileMenuOpen = ref(false)

const toggleMobileMenu = () => {
    isMobileMenuOpen.value = !isMobileMenuOpen.value
}

const closeMobileMenu = () => {
    isMobileMenuOpen.value = false
}
</script>

<template>
    <header class="absolute inset-x-0 top-0 z-50">
        <nav aria-label="Global"
            class="w-full flex items-center justify-between px-2 sm:px-6 lg:px-8 py-3 bg-gradient-to-b from-black/90 via-black/80 via-black/60 via-black/40 via-black/25 via-black/15 via-black/8 to-transparent backdrop-blur-md">
            <div class="mx-auto flex max-w-7xl items-center justify-between w-full">
                <!-- Logo -->
                <div class="flex flex-1 sm:flex-1 lg:flex-1 justify-start">
                    <router-link to="/" class="-m-1.5 p-1.5">
                        <span class="sr-only">The Roaster Grill</span>
                        <img src="/img/logo.png" alt="The Roaster Grill Logo" class="h-12 sm:h-12 lg:h-14 w-auto">
                    </router-link>
                </div>

                <!-- Mobile menu button -->
                <div class="flex lg:hidden">
                    <button type="button" @click="toggleMobileMenu"
                        class="-m-2.5 inline-flex items-center justify-center rounded-md p-2.5 text-gray-200 hover:text-white">
                        <span class="sr-only">Open main menu</span>
                        <svg v-if="!isMobileMenuOpen" viewBox="0 0 24 24" fill="none" stroke="currentColor"
                            stroke-width="1.5" class="size-6">
                            <path d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" stroke-linecap="round"
                                stroke-linejoin="round" />
                        </svg>
                        <svg v-else viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"
                            class="size-6">
                            <path d="M6 18 18 6M6 6l12 12" stroke-linecap="round" stroke-linejoin="round" />
                        </svg>
                    </button>
                </div>

                <!-- Desktop navigation -->
                <div class="hidden lg:flex lg:gap-x-8">
                    <router-link to="/"
                        class="text-base font-semibold text-gray-200 hover:text-white transition-colors">Home</router-link>
                    <router-link to="/about"
                        class="text-base font-semibold text-gray-200 hover:text-white transition-colors">About</router-link>
                    <router-link to="/services"
                        class="text-base font-semibold text-gray-200 hover:text-white transition-colors">Services</router-link>
                    <router-link to="/portfolio"
                        class="text-base font-semibold text-gray-200 hover:text-white transition-colors">Portfolio</router-link>
                    <router-link to="/contact"
                        class="text-base font-semibold text-gray-200 hover:text-white transition-colors">Contact</router-link>
                </div>

                <!-- Desktop CTA -->
                <div class="hidden lg:flex lg:flex-1 lg:justify-end">
                    <router-link to="/contact" class="btn-red hover:no-underline">
                        Order Now
                    </router-link>
                </div>
            </div>
        </nav>

        <!-- Mobile menu -->
        <div v-if="isMobileMenuOpen" class="lg:hidden">
            <div class="fixed inset-0 z-50">
                <div
                    class="fixed inset-y-0 right-0 z-50 w-full overflow-y-auto bg-gray-900 p-6 sm:max-w-sm sm:ring-1 sm:ring-gray-100/10">
                    <div class="flex items-center justify-between">
                        <div class="flex flex-1 justify-start">
                            <router-link to="/" class="-m-1.5 p-1.5 relative -left-5">
                                <span class="sr-only">The Roaster Grill</span>
                                <img src="/img/logo.png" alt="The Roaster Grill Logo" class="h-10 w-auto">
                            </router-link>
                        </div>
                        <button type="button" @click="toggleMobileMenu"
                            class="-m-2.5 rounded-md p-2.5 text-gray-200 hover:text-white">
                            <span class="sr-only">Close menu</span>
                            <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.5"
                                class="size-6">
                                <path d="M6 18 18 6M6 6l12 12" stroke-linecap="round" stroke-linejoin="round" />
                            </svg>
                        </button>
                    </div>
                    <div class="mt-6 flow-root">
                        <div class="-my-6 divide-y divide-gray-500/10">
                            <div class="space-y-2 py-6">
                                <router-link to="/" @click="closeMobileMenu"
                                    class="-mx-3 block rounded-lg px-3 py-2 text-lg font-semibold text-white hover:bg-white/5 transition-colors flex items-center h-10">Home</router-link>
                                <router-link to="/about" @click="closeMobileMenu"
                                    class="-mx-3 block rounded-lg px-3 py-2 text-lg font-semibold text-white hover:bg-white/5 transition-colors flex items-center h-10">About</router-link>
                                <router-link to="/services" @click="closeMobileMenu"
                                    class="-mx-3 block rounded-lg px-3 py-2 text-lg font-semibold text-white hover:bg-white/5 transition-colors flex items-center h-10">Services</router-link>
                                <router-link to="/portfolio" @click="closeMobileMenu"
                                    class="-mx-3 block rounded-lg px-3 py-2 text-lg font-semibold text-white hover:bg-white/5 transition-colors flex items-center h-10">Portfolio</router-link>
                                <router-link to="/contact" @click="closeMobileMenu"
                                    class="-mx-3 block rounded-lg px-3 py-2 text-lg font-semibold text-white hover:bg-white/5 transition-colors flex items-center h-10">Contact</router-link>
                            </div>
                            <div class="py-6">
                                <router-link to="/contact" @click="closeMobileMenu"
                                    class="btn-red -mx-3 block px-3 py-2.5 text-base/7 flex items-center h-10 hover:no-underline">Order
                                    Now</router-link>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<style scoped>
.router-link-active {
    color: #f87171;
    /* red-400 */
    font-weight: 600;
}

/* Ensure Order Now buttons maintain proper styling */
.btn-red {
    text-decoration: none !important;
    color: white !important;
    background: #dc2626 !important;
    border: 2px solid #dc2626 !important;
}

.btn-red:hover {
    background: #b91c1c !important;
    border-color: #b91c1c !important;
    color: white !important;
    text-decoration: none !important;
}

.btn-red:focus {
    background: #b91c1c !important;
    border-color: #b91c1c !important;
    color: white !important;
    text-decoration: none !important;
}
</style>
