<template>
    <main class="min-h-dvh bg-gradient-to-br from-black via-gray-900 to-black text-white">
        <!-- Hero Section -->
        <section class="relative min-h-[60vh] sm:min-h-[70vh] flex items-center justify-center overflow-hidden">
            <!-- Background Image -->
            <div class="absolute inset-0">
                <img src="https://images.unsplash.com/photo-1555939594-58d7cb561ad1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2000&q=80"
                    alt="Our premium roasted pork services" 
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
                        OUR SERVICES
                    </span>
                </h1>

                <!-- Subtitle -->
                <p class="text-base sm:text-lg md:text-xl text-gray-200 leading-relaxed max-w-2xl sm:max-w-3xl mx-auto mb-6 sm:mb-8 md:mb-12 font-serif px-2">
                    From intimate gatherings to grand celebrations, we bring <span class="text-red-400 font-semibold">flame-kissed perfection</span> to every occasion.
                </p>
            </div>
        </section>

        <!-- Services Section -->
        <section class="relative py-8 sm:py-12 md:py-16 lg:py-20 px-4 sm:px-6 overflow-hidden">
            <!-- Background -->
            <div class="absolute inset-0 bg-black">
                <div class="absolute inset-0 bg-[radial-gradient(circle_at_30%_70%,rgba(239,68,68,0.15)_0%,transparent_50%)]"></div>
            </div>

            <div class="relative z-10 max-w-7xl mx-auto">
                <!-- Section Header -->
                <div class="text-center mb-12 sm:mb-16 md:mb-20">
                    <h2 class="text-2xl sm:text-3xl md:text-4xl lg:text-5xl font-serif font-bold text-white mb-4 sm:mb-6 tracking-tight">
                        What We Offer
                    </h2>
                    <div class="w-16 sm:w-24 h-0.5 bg-red-500 mx-auto mb-4 sm:mb-6"></div>
                    <p class="text-base sm:text-lg text-gray-300 max-w-2xl sm:max-w-3xl mx-auto font-serif">
                        Choose from our range of premium pork services, each crafted with the same dedication to quality and tradition.
                    </p>
                </div>

                <!-- Services Grid -->
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-6 md:gap-8 lg:gap-10">
                    <!-- Catering Service -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8 hover:border-red-500/30 transition-all duration-300 hover:scale-105 group">
                        <div class="w-14 h-14 sm:w-16 sm:h-16 bg-gradient-to-br from-red-500 to-red-600 rounded-full flex items-center justify-center mx-auto mb-4 sm:mb-6">
                            <svg class="w-7 h-7 sm:w-8 sm:h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"></path>
                            </svg>
                        </div>
                        <h3 class="text-xl sm:text-2xl font-serif font-bold text-white mb-3 sm:mb-4 text-center">Event Catering</h3>
                        <p class="text-sm sm:text-base text-gray-300 mb-4 sm:mb-6 leading-relaxed">
                            Full-service catering for weddings, corporate events, and special occasions. We handle everything from setup to cleanup.
                        </p>
                        <ul class="text-gray-300 text-xs sm:text-sm space-y-1.5 sm:space-y-2 mb-4 sm:mb-6">
                            <li class="flex items-center">
                                <svg class="w-3 h-3 sm:w-4 sm:h-4 text-red-400 mr-2 flex-shrink-0" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                                </svg>
                                Wedding receptions
                            </li>
                            <li class="flex items-center">
                                <svg class="w-3 h-3 sm:w-4 sm:h-4 text-red-400 mr-2 flex-shrink-0" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                                </svg>
                                Corporate events
                            </li>
                            <li class="flex items-center">
                                <svg class="w-3 h-3 sm:w-4 sm:h-4 text-red-400 mr-2 flex-shrink-0" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                                </svg>
                                Birthday parties
                            </li>
                            <li class="flex items-center">
                                <svg class="w-3 h-3 sm:w-4 sm:h-4 text-red-400 mr-2 flex-shrink-0" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                                </svg>
                                Custom menus available
                            </li>
                        </ul>
                        <div class="text-center">
                            <router-link to="/contact" class="btn-red-outline w-full text-center group relative overflow-hidden">
                                <span class="relative z-10">Book Catering</span>
                                <div class="absolute inset-0 bg-red-500/10 transform -translate-x-full group-hover:translate-x-0 transition-transform duration-500"></div>
                            </router-link>
                        </div>
                    </div>

                    <!-- Takeaway Service -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8 hover:border-red-500/30 transition-all duration-300 hover:scale-105 group">
                        <div class="w-14 h-14 sm:w-16 sm:h-16 bg-gradient-to-br from-blue-500 to-blue-600 rounded-full flex items-center justify-center mx-auto mb-4 sm:mb-6">
                            <svg class="w-7 h-7 sm:w-8 sm:h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"></path>
                            </svg>
                        </div>
                        <h3 class="text-xl sm:text-2xl font-serif font-bold text-white mb-3 sm:mb-4 text-center">Takeaway & Delivery</h3>
                        <p class="text-sm sm:text-base text-gray-300 mb-4 sm:mb-6 leading-relaxed">
                            Fresh, raw packaged pork for home cooking. Customized to your desired weight and preparation preferences.
                        </p>
                        <ul class="text-gray-300 text-xs sm:text-sm space-y-1.5 sm:space-y-2 mb-4 sm:mb-6">
                            <li class="flex items-center">
                                <svg class="w-3 h-3 sm:w-4 sm:h-4 text-blue-400 mr-2 flex-shrink-0" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                                </svg>
                                Custom weight portions
                            </li>
                            <li class="flex items-center">
                                <svg class="w-3 h-3 sm:w-4 sm:h-4 text-blue-400 mr-2 flex-shrink-0" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                                </svg>
                                Fresh daily preparation
                            </li>
                            <li class="flex items-center">
                                <svg class="w-3 h-3 sm:w-4 sm:h-4 text-blue-400 mr-2 flex-shrink-0" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                                </svg>
                                Home delivery available
                            </li>
                            <li class="flex items-center">
                                <svg class="w-3 h-3 sm:w-4 sm:h-4 text-blue-400 mr-2 flex-shrink-0" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                                </svg>
                                Cooking instructions included
                            </li>
                        </ul>
                        <div class="text-center">
                            <router-link to="/contact" class="btn-red-outline w-full text-center group relative overflow-hidden">
                                <span class="relative z-10">Order Now</span>
                                <div class="absolute inset-0 bg-red-500/10 transform -translate-x-full group-hover:translate-x-0 transition-transform duration-500"></div>
                            </router-link>
                        </div>
                    </div>

                    <!-- Spices & Marinades -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8 hover:border-red-500/30 transition-all duration-300 hover:scale-105 group">
                        <div class="w-14 h-14 sm:w-16 sm:h-16 bg-gradient-to-br from-green-500 to-green-600 rounded-full flex items-center justify-center mx-auto mb-4 sm:mb-6">
                            <svg class="w-7 h-7 sm:w-8 sm:h-8 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 100 4m0-4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 100 4m0-4v2m0-6V4"></path>
                            </svg>
                        </div>
                        <h3 class="text-xl sm:text-2xl font-serif font-bold text-white mb-3 sm:mb-4 text-center">Signature Spices</h3>
                        <p class="text-sm sm:text-base text-gray-300 mb-4 sm:mb-6 leading-relaxed">
                            Our carefully crafted blend of spices and marinades elevates every dish, creating flavors that are uniquely Roaster Grill.
                        </p>
                        <ul class="text-gray-300 text-xs sm:text-sm space-y-1.5 sm:space-y-2 mb-4 sm:mb-6">
                            <li class="flex items-center">
                                <svg class="w-3 h-3 sm:w-4 sm:h-4 text-green-400 mr-2 flex-shrink-0" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                                </svg>
                                Traditional spice blends
                            </li>
                            <li class="flex items-center">
                                <svg class="w-3 h-3 sm:w-4 sm:h-4 text-green-400 mr-2 flex-shrink-0" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                                </svg>
                                Custom marinades
                            </li>
                            <li class="flex items-center">
                                <svg class="w-3 h-3 sm:w-4 sm:h-4 text-green-400 mr-2 flex-shrink-0" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                                </svg>
                                Premium ingredients
                            </li>
                            <li class="flex items-center">
                                <svg class="w-3 h-3 sm:w-4 sm:h-4 text-green-400 mr-2 flex-shrink-0" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M9 12.75 11.25 15 15 9.75M21 12c0 1.268-.63 2.39-1.593 3.068a3.745 3.745 0 0 1-1.043 3.296 3.745 3.745 0 0 1-3.296 1.043A3.745 3.745 0 0 1 12 21c-1.268 0-2.39-.63-3.068-1.593a3.746 3.746 0 0 1-3.296-1.043 3.745 3.745 0 0 1-1.043-3.296A3.745 3.745 0 0 1 3 12c0-1.268.63-2.39 1.593-3.068a3.745 3.745 0 0 1 1.043-3.296 3.746 3.746 0 0 1 3.296-1.043A3.746 3.746 0 0 1 12 3c1.268 0 2.39.63 3.068 1.593a3.746 3.746 0 0 1 3.296 1.043 3.746 3.746 0 0 1 1.043 3.296A3.745 3.745 0 0 1 21 12Z" />
                                </svg>
                                Family recipe secrets
                            </li>
                        </ul>
                        <div class="text-center">
                            <router-link to="/contact" class="btn-red-outline w-full text-center group relative overflow-hidden">
                                <span class="relative z-10">Order Spices</span>
                                <div class="absolute inset-0 bg-red-500/10 transform -translate-x-full group-hover:translate-x-0 transition-transform duration-500"></div>
                            </router-link>
                        </div>
                    </div>
                </div>

                <!-- Pricing Section -->
                <div class="mt-12 sm:mt-16 md:mt-20">
                    <div class="text-center mb-8 sm:mb-12">
                        <h3 class="text-2xl sm:text-3xl md:text-4xl font-serif font-bold text-white mb-3 sm:mb-4 tracking-tight">
                            Pricing Information
                        </h3>
                        <div class="w-16 sm:w-24 h-0.5 bg-red-500 mx-auto mb-4 sm:mb-6"></div>
                        <p class="text-base sm:text-lg text-gray-300 max-w-2xl mx-auto font-serif">
                            Transparent pricing for all our services. Contact us for custom quotes and special event packages.
                        </p>
                    </div>

                    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-6 md:gap-8">
                        <!-- Catering Pricing -->
                        <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-red-500/20 rounded-xl sm:rounded-2xl p-5 sm:p-6 hover:border-red-500/40 transition-all duration-300 group">
                            <div class="flex items-center mb-4 sm:mb-6">
                                <div class="w-10 h-10 sm:w-12 sm:h-12 bg-gradient-to-br from-red-500 to-red-600 rounded-full flex items-center justify-center mr-3 sm:mr-4">
                                    <svg class="w-5 h-5 sm:w-6 sm:h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"></path>
                                    </svg>
                                </div>
                                <h4 class="text-lg sm:text-xl font-serif font-bold text-white">Event Catering</h4>
                            </div>
                            <div class="space-y-3 sm:space-y-4">
                                <div class="flex justify-between items-center py-2 border-b border-gray-700/30">
                                    <span class="text-sm sm:text-base text-gray-300">Small Events (10-25 people)</span>
                                    <span class="text-red-400 font-bold text-sm sm:text-base">From ₵150/person</span>
                                </div>
                                <div class="flex justify-between items-center py-2 border-b border-gray-700/30">
                                    <span class="text-sm sm:text-base text-gray-300">Medium Events (25-50 people)</span>
                                    <span class="text-red-400 font-bold text-sm sm:text-base">From ₵120/person</span>
                                </div>
                                <div class="flex justify-between items-center py-2">
                                    <span class="text-sm sm:text-base text-gray-300">Large Events (50+ people)</span>
                                    <span class="text-red-400 font-bold text-sm sm:text-base">From ₵100/person</span>
                                </div>
                            </div>
                            <div class="mt-4 sm:mt-6 pt-4 border-t border-gray-700/30">
                                <p class="text-xs text-gray-400">* Includes setup, service, and cleanup</p>
                            </div>
                        </div>

                        <!-- Takeaway Pricing -->
                        <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-blue-500/20 rounded-xl sm:rounded-2xl p-5 sm:p-6 hover:border-blue-500/40 transition-all duration-300 group">
                            <div class="flex items-center mb-4 sm:mb-6">
                                <div class="w-10 h-10 sm:w-12 sm:h-12 bg-gradient-to-br from-blue-500 to-blue-600 rounded-full flex items-center justify-center mr-3 sm:mr-4">
                                    <svg class="w-5 h-5 sm:w-6 sm:h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z"></path>
                                    </svg>
                                </div>
                                <h4 class="text-lg sm:text-xl font-serif font-bold text-white">Takeaway & Delivery</h4>
                            </div>
                            <div class="space-y-3 sm:space-y-4">
                                <div class="flex justify-between items-center py-2 border-b border-gray-700/30">
                                    <span class="text-sm sm:text-base text-gray-300">Small Portion (2-3 people)</span>
                                    <span class="text-blue-400 font-bold text-sm sm:text-base">₵80-120</span>
                                </div>
                                <div class="flex justify-between items-center py-2 border-b border-gray-700/30">
                                    <span class="text-sm sm:text-base text-gray-300">Medium Portion (4-6 people)</span>
                                    <span class="text-blue-400 font-bold text-sm sm:text-base">₵150-200</span>
                                </div>
                                <div class="flex justify-between items-center py-2 border-b border-gray-700/30">
                                    <span class="text-sm sm:text-base text-gray-300">Large Portion (8+ people)</span>
                                    <span class="text-blue-400 font-bold text-sm sm:text-base">₵250+</span>
                                </div>
                                <div class="flex justify-between items-center py-2">
                                    <span class="text-sm sm:text-base text-gray-300">Delivery Fee</span>
                                    <span class="text-gray-400 font-semibold text-sm sm:text-base">₵15-25</span>
                                </div>
                            </div>
                            <div class="mt-4 sm:mt-6 pt-4 border-t border-gray-700/30">
                                <p class="text-xs text-gray-400">* Fresh daily preparation</p>
                            </div>
                        </div>

                        <!-- Spices Pricing -->
                        <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-green-500/20 rounded-xl sm:rounded-2xl p-5 sm:p-6 hover:border-green-500/40 transition-all duration-300 group">
                            <div class="flex items-center mb-4 sm:mb-6">
                                <div class="w-10 h-10 sm:w-12 sm:h-12 bg-gradient-to-br from-green-500 to-green-600 rounded-full flex items-center justify-center mr-3 sm:mr-4">
                                    <svg class="w-5 h-5 sm:w-6 sm:h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 100 4m0-4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 100 4m0-4v2m0-6V4"></path>
                                    </svg>
                                </div>
                                <h4 class="text-lg sm:text-xl font-serif font-bold text-white">Signature Spices</h4>
                            </div>
                            <div class="space-y-3 sm:space-y-4">
                                <div class="flex justify-between items-center py-2 border-b border-gray-700/30">
                                    <span class="text-sm sm:text-base text-gray-300">Small Pack (250g)</span>
                                    <span class="text-green-400 font-bold text-sm sm:text-base">₵25</span>
                                </div>
                                <div class="flex justify-between items-center py-2 border-b border-gray-700/30">
                                    <span class="text-sm sm:text-base text-gray-300">Medium Pack (500g)</span>
                                    <span class="text-green-400 font-bold text-sm sm:text-base">₵45</span>
                                </div>
                                <div class="flex justify-between items-center py-2 border-b border-gray-700/30">
                                    <span class="text-sm sm:text-base text-gray-300">Large Pack (1kg)</span>
                                    <span class="text-green-400 font-bold text-sm sm:text-base">₵80</span>
                                </div>
                                <div class="flex justify-between items-center py-2">
                                    <span class="text-sm sm:text-base text-gray-300">Custom Marinades</span>
                                    <span class="text-gray-400 font-semibold text-sm sm:text-base">Quote on request</span>
                                </div>
                            </div>
                            <div class="mt-4 sm:mt-6 pt-4 border-t border-gray-700/30">
                                <p class="text-xs text-gray-400">* Family recipe blends</p>
                            </div>
                        </div>
                    </div>

                    <!-- CTA Section -->
                    <div class="text-center mt-8 sm:mt-12">
                        <p class="text-base sm:text-lg text-gray-300 mb-6 sm:mb-8 font-serif">
                            Ready to experience the difference that <span class="text-red-400 font-semibold">flame-kissed perfection</span> makes?
                        </p>
                        <div class="flex flex-col sm:flex-row gap-3 sm:gap-4 justify-center max-w-md sm:max-w-none mx-auto">
                            <router-link to="/contact" class="btn-red w-full sm:w-auto text-center group relative overflow-hidden">
                                <span class="relative z-10">Get a Quote</span>
                                <div class="absolute inset-0 bg-white/10 transform -translate-x-full group-hover:translate-x-0 transition-transform duration-500"></div>
                            </router-link>
                            <router-link to="/portfolio" class="btn-red-outline w-full sm:w-auto text-center group relative overflow-hidden">
                                <span class="relative z-10">View Our Work</span>
                                <div class="absolute inset-0 bg-red-500/10 transform -translate-x-full group-hover:translate-x-0 transition-transform duration-500"></div>
                            </router-link>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>
</template>

<script setup>
// Services page component
</script>
