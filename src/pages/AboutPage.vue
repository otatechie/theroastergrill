<template>
    <main class="min-h-dvh bg-gradient-to-br from-black via-gray-900 to-black text-white">
        <!-- Hero Section -->
        <section class="relative min-h-[60vh] sm:min-h-[70vh] flex items-center justify-center overflow-hidden">
            <!-- Background Image -->
            <div class="absolute inset-0">
                <img src="https://images.unsplash.com/photo-1555939594-58d7cb561ad1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2000&q=80"
                    alt="Traditional roasted pork preparation" 
                    loading="eager"
                    class="w-full h-full object-cover" />
                <!-- Dark Overlay for Better Text Readability -->
                <div class="absolute inset-0 bg-black/70 sm:bg-black/60"></div>
                <!-- Subtle Gradient Overlay -->
                <div class="absolute inset-0 bg-gradient-to-br from-black/50 via-transparent to-red-900/30"></div>
            </div>

            <!-- Main Content -->
            <div class="relative z-10 text-center px-4 sm:px-6 max-w-7xl mx-auto pt-20 sm:pt-24 md:pt-28">
                <!-- Main Title -->
                <h1 class="font-black font-serif text-4xl sm:text-5xl md:text-6xl lg:text-7xl xl:text-8xl leading-[1.1] sm:leading-[1.05] tracking-tight mb-4 sm:mb-6 md:mb-8">
                    <span class="block text-transparent bg-clip-text bg-gradient-to-br from-yellow-300 via-orange-500 to-red-600">
                        OUR STORY
                    </span>
                </h1>

                <!-- Subtitle -->
                <p class="text-base sm:text-lg md:text-xl text-gray-200 leading-relaxed max-w-2xl sm:max-w-3xl mx-auto mb-6 sm:mb-8 md:mb-12 font-serif px-2">
                    Tradition, passion, and a deep love for <span class="text-red-400 font-semibold">flame-kissed perfection</span>
                </p>
            </div>
        </section>

        <!-- About Content Section -->
        <section class="relative py-8 sm:py-12 md:py-16 lg:py-20 px-4 sm:px-6 overflow-hidden">
            <!-- Background Image -->
            <div class="absolute inset-0 bg-black">
                <div class="absolute inset-0 bg-[radial-gradient(circle_at_30%_70%,rgba(239,68,68,0.15)_0%,transparent_50%)]"></div>
            </div>

            <div class="relative z-10 max-w-7xl mx-auto">
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 sm:gap-8 md:gap-12 lg:gap-20 items-center">
                    <!-- Text Content -->
                    <div class="text-white order-2 lg:order-1">
                        <h2 class="text-2xl sm:text-3xl md:text-4xl lg:text-5xl font-serif font-bold mb-4 sm:mb-6 md:mb-8 tracking-tight">
                            The Roaster Grill Story
                        </h2>
                        <div class="text-sm sm:text-base md:text-lg leading-relaxed text-gray-300 space-y-4 sm:space-y-6">
                            <p>
                                At The Roaster Grill, our story is one of tradition, passion, and a deep love for great food. What
                                started as a small family tradition—roasting pork over open flames for gatherings and
                                celebrations—has grown into a trusted name for quality pork sourcing and roasting. Rooted in a commitment to excellence, we continue to bring that same homemade touch to every order, whether it's fresh, raw packaged pork for home cooking or perfectly roasted pork for special events.
                            </p>
                            <p>
                                As a family-run business, we understand the importance of good food bringing people together. That's
                                why we go the extra mile to source the finest pork, ensuring every bite is rich, flavorful, and
                                satisfying. Our expert team, trained in traditional roasting methods, combines experience with modern techniques to deliver pork that's succulent, tender, and bursting with smoky goodness.
                            </p>
                            <!-- Mission Statement - Enhanced -->
                            <div class="bg-gradient-to-r from-gray-900/50 to-black/50 backdrop-blur-sm border border-red-500/20 rounded-lg sm:rounded-xl p-4 sm:p-6 md:p-8">
                                <div class="flex flex-col sm:flex-row items-start space-y-3 sm:space-y-0 sm:space-x-4">
                                    <div class="w-10 h-10 sm:w-12 sm:h-12 bg-gradient-to-br from-red-500 to-red-600 rounded-full flex items-center justify-center flex-shrink-0 mx-auto sm:mx-0">
                                        <svg class="w-5 h-5 sm:w-6 sm:h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path>
                                        </svg>
                                    </div>
                                    <div class="text-center sm:text-left">
                                        <h3 class="text-base sm:text-lg md:text-xl font-serif font-semibold text-white mb-2 sm:mb-3">Our Mission</h3>
                                        <p class="text-sm sm:text-base md:text-lg leading-relaxed text-gray-200">
                                            At The Roaster Grill, our mission is simple: to provide high-quality, expertly prepared pork with the warmth and care of a family kitchen. Whether you're hosting a wedding, a corporate event, or a simple meal at home, we're here to make sure every bite is unforgettable.
                                        </p>
                                    </div>
                                </div>
                            </div>
                            <p class="text-gray-300">
                                Based in <strong class="text-red-300">Accra, Ghana</strong>, we proudly serve the Greater Accra area and events across
                                Ghana. 
                            </p>
                        </div>
                        <div class="mt-6 sm:mt-8 md:mt-10">
                            <router-link to="/contact" 
                                class="btn-red-outline w-full sm:w-auto text-center group relative overflow-hidden">
                                <span class="relative z-10">Get In Touch</span>
                                <div class="absolute inset-0 bg-red-500/10 transform -translate-x-full group-hover:translate-x-0 transition-transform duration-500"></div>
                            </router-link>
                        </div>
                    </div>

                    <!-- Image Section -->
                    <div class="relative overflow-hidden rounded-lg sm:rounded-xl order-1 lg:order-2">
                        <img src="https://images.unsplash.com/photo-1544025162-d76694265947?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1000&q=80"
                            alt="Family tradition of roasting pork"
                            loading="lazy"
                            width="1000"
                            height="800"
                            class="w-full h-48 sm:h-56 md:h-64 lg:h-80 xl:h-96 object-cover shadow-lg transform transition-transform duration-700 hover:scale-105">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/20 to-transparent"></div>
                    </div>
                </div>
            </div>
        </section>
    </main>
</template>

<script setup>
// About page component
</script>
