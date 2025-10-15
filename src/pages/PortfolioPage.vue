<template>
    <main class="min-h-dvh bg-gradient-to-br from-black via-gray-900 to-black text-white">
        <!-- Hero Section -->
        <section class="relative min-h-[60vh] sm:min-h-[70vh] flex items-center justify-center overflow-hidden">
            <!-- Background Image -->
            <div class="absolute inset-0">
                <img src="https://images.unsplash.com/photo-1555939594-58d7cb561ad1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2000&q=80"
                    alt="Our portfolio of roasted pork excellence" 
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
                    <span class="block text-transparent bg-clip-text bg-gradient-to-br from-yellow-300 via-orange-500 to-red-600 shadow-lg">
                        OUR WORK
                    </span>
                </h1>

                <!-- Subtitle -->
                <p class="text-base sm:text-lg md:text-xl text-gray-200 leading-relaxed max-w-2xl sm:max-w-3xl mx-auto mb-6 sm:mb-8 md:mb-12 font-serif px-2">
                    See the <span class="text-red-400 font-semibold">flame-kissed perfection</span> that makes every event unforgettable.
                </p>
            </div>
        </section>

        <!-- Gallery Section -->
        <section class="relative py-8 sm:py-12 md:py-16 lg:py-20 px-4 sm:px-6 overflow-hidden">
            <!-- Background -->
            <div class="absolute inset-0 bg-black">
                <div class="absolute inset-0 bg-[radial-gradient(circle_at_30%_70%,rgba(239,68,68,0.15)_0%,transparent_50%)]"></div>
            </div>

            <div class="relative z-10 max-w-7xl mx-auto">
                <!-- Section Header -->
                <div class="text-center mb-12 sm:mb-16">
                    <h2 class="text-2xl sm:text-3xl md:text-4xl lg:text-5xl font-serif font-bold text-white mb-4 tracking-tight">
                        Gallery
                    </h2>
                    <div class="w-16 sm:w-24 h-0.5 bg-red-500 mx-auto mb-4 sm:mb-6"></div>
                    <p class="text-base sm:text-lg text-gray-300 max-w-2xl mx-auto font-serif">
                        A visual journey through our culinary excellence and memorable events.
                    </p>
                </div>

                <!-- Gallery Grid -->
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-6 md:gap-8">
                    <!-- Gallery Item 1 -->
                    <div class="group relative overflow-hidden rounded-xl shadow-2xl">
                        <img src="https://images.unsplash.com/photo-1555939594-58d7cb561ad1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1000&q=80"
                            alt="Premium roasted pork display" 
                            loading="lazy"
                            width="1000"
                            height="800"
                            class="w-full h-64 sm:h-80 object-cover group-hover:scale-110 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                            <div class="absolute bottom-4 left-4 right-4">
                                <h3 class="text-white font-semibold text-lg mb-2">Premium Roasted Pork</h3>
                                <p class="text-gray-300 text-sm">Perfectly seasoned and flame-kissed to perfection</p>
                            </div>
                        </div>
                    </div>

                    <!-- Gallery Item 2 -->
                    <div class="group relative overflow-hidden rounded-xl shadow-2xl">
                        <img src="https://images.unsplash.com/photo-1544025162-d76694265947?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1000&q=80"
                            alt="Wedding catering setup" 
                            loading="lazy"
                            width="1000"
                            height="800"
                            class="w-full h-64 sm:h-80 object-cover group-hover:scale-110 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                            <div class="absolute bottom-4 left-4 right-4">
                                <h3 class="text-white font-semibold text-lg mb-2">Wedding Catering</h3>
                                <p class="text-gray-300 text-sm">Elegant presentation for special celebrations</p>
                            </div>
                        </div>
                    </div>

                    <!-- Gallery Item 3 -->
                    <div class="group relative overflow-hidden rounded-xl shadow-2xl">
                        <img src="https://images.unsplash.com/photo-1556909114-f6e7ad7d3136?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1000&q=80"
                            alt="Signature spices and marinades" 
                            loading="lazy"
                            width="1000"
                            height="800"
                            class="w-full h-64 sm:h-80 object-cover group-hover:scale-110 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                            <div class="absolute bottom-4 left-4 right-4">
                                <h3 class="text-white font-semibold text-lg mb-2">Signature Spices</h3>
                                <p class="text-gray-300 text-sm">Carefully crafted blends for authentic flavor</p>
                            </div>
                        </div>
                    </div>

                    <!-- Gallery Item 4 -->
                    <div class="group relative overflow-hidden rounded-xl shadow-2xl">
                        <img src="https://images.unsplash.com/photo-1555939594-58d7cb561ad1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1000&q=80"
                            alt="Corporate event catering" 
                            loading="lazy"
                            width="1000"
                            height="800"
                            class="w-full h-64 sm:h-80 object-cover group-hover:scale-110 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                            <div class="absolute bottom-4 left-4 right-4">
                                <h3 class="text-white font-semibold text-lg mb-2">Corporate Events</h3>
                                <p class="text-gray-300 text-sm">Professional catering for business gatherings</p>
                            </div>
                        </div>
                    </div>

                    <!-- Gallery Item 5 -->
                    <div class="group relative overflow-hidden rounded-xl shadow-2xl">
                        <img src="https://images.unsplash.com/photo-1544025162-d76694265947?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1000&q=80"
                            alt="Traditional roasting process" 
                            loading="lazy"
                            width="1000"
                            height="800"
                            class="w-full h-64 sm:h-80 object-cover group-hover:scale-110 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                            <div class="absolute bottom-4 left-4 right-4">
                                <h3 class="text-white font-semibold text-lg mb-2">Traditional Methods</h3>
                                <p class="text-gray-300 text-sm">Time-honored techniques meet modern excellence</p>
                            </div>
                        </div>
                    </div>

                    <!-- Gallery Item 6 -->
                    <div class="group relative overflow-hidden rounded-xl shadow-2xl">
                        <img src="https://images.unsplash.com/photo-1556909114-f6e7ad7d3136?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1000&q=80"
                            alt="Fresh takeaway packaging" 
                            loading="lazy"
                            width="1000"
                            height="800"
                            class="w-full h-64 sm:h-80 object-cover group-hover:scale-110 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-transparent to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                            <div class="absolute bottom-4 left-4 right-4">
                                <h3 class="text-white font-semibold text-lg mb-2">Fresh Takeaway</h3>
                                <p class="text-gray-300 text-sm">Premium quality for home cooking</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Testimonials Section -->
        <section class="relative py-8 sm:py-12 md:py-16 lg:py-20 px-4 sm:px-6 overflow-hidden bg-gradient-to-br from-black to-gray-900">
            <!-- Background Elements -->
            <div class="absolute inset-0">
                <div class="absolute inset-0 bg-[radial-gradient(circle_at_20%_80%,rgba(239,68,68,0.05)_0%,transparent_50%)]"></div>
                <div class="absolute inset-0 bg-[radial-gradient(circle_at_80%_20%,rgba(59,130,246,0.03)_0%,transparent_50%)]"></div>
            </div>

            <div class="relative z-10 max-w-7xl mx-auto">
                <!-- Section Header -->
                <div class="text-center mb-12 sm:mb-16">
                    <h2 class="text-2xl sm:text-3xl md:text-4xl lg:text-5xl font-serif font-bold text-white mb-4 tracking-tight">
                        What Our Customers Say
                    </h2>
                    <div class="w-16 sm:w-24 h-0.5 bg-red-500 mx-auto mb-4 sm:mb-6"></div>
                    <p class="text-base sm:text-lg text-gray-300 max-w-2xl mx-auto font-serif">
                        Don't just take our word for it - hear from the people who've experienced our flame-kissed perfection
                    </p>
                </div>

                <!-- Testimonials Grid -->
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-6 md:gap-8 lg:gap-10">
                    <!-- Testimonial 1 -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8 hover:border-red-500/30 transition-all duration-300 hover:scale-105 group">
                        <div class="flex items-center mb-4 sm:mb-6">
                            <div class="w-10 h-10 sm:w-12 sm:h-12 bg-black rounded-full flex items-center justify-center mr-3 sm:mr-4">
                                <span class="text-white font-bold text-sm sm:text-lg">S</span>
                            </div>
                            <div>
                                <h4 class="text-white font-semibold text-base sm:text-lg">Sarah Mitchell</h4>
                                <p class="text-gray-400 text-xs sm:text-sm">Wedding Catering</p>
                                <div class="flex text-yellow-400 text-xs sm:text-sm mt-1">
                                    ⭐⭐⭐⭐⭐
                                </div>
                            </div>
                        </div>
                        <p class="text-sm sm:text-base text-gray-300 leading-relaxed">
                            "The Roaster Grill catered our wedding and it was absolutely incredible! The pork was perfectly seasoned and the presentation was stunning. Our guests are still talking about it months later!"
                        </p>
                    </div>

                    <!-- Testimonial 2 -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8 hover:border-red-500/30 transition-all duration-300 hover:scale-105 group">
                        <div class="flex items-center mb-4 sm:mb-6">
                            <div class="w-10 h-10 sm:w-12 sm:h-12 bg-black rounded-full flex items-center justify-center mr-3 sm:mr-4">
                                <span class="text-white font-bold text-sm sm:text-lg">M</span>
                            </div>
                            <div>
                                <h4 class="text-white font-semibold text-base sm:text-lg">Michael Chen</h4>
                                <p class="text-gray-400 text-xs sm:text-sm">Regular Customer</p>
                                <div class="flex text-yellow-400 text-xs sm:text-sm mt-1">
                                    ⭐⭐⭐⭐⭐
                                </div>
                            </div>
                        </div>
                        <p class="text-sm sm:text-base text-gray-300 leading-relaxed">
                            "I've been ordering their takeaway pork for months now. The quality is consistently amazing and their signature spices make every meal special. Highly recommend!"
                        </p>
                    </div>

                    <!-- Testimonial 3 -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8 hover:border-red-500/30 transition-all duration-300 hover:scale-105 group">
                        <div class="flex items-center mb-4 sm:mb-6">
                            <div class="w-10 h-10 sm:w-12 sm:h-12 bg-black rounded-full flex items-center justify-center mr-3 sm:mr-4">
                                <span class="text-white font-bold text-sm sm:text-lg">L</span>
                            </div>
                            <div>
                                <h4 class="text-white font-semibold text-base sm:text-lg">Lisa Rodriguez</h4>
                                <p class="text-gray-400 text-xs sm:text-sm">Corporate Events</p>
                                <div class="flex text-yellow-400 text-xs sm:text-sm mt-1">
                                    ⭐⭐⭐⭐⭐
                                </div>
                            </div>
                        </div>
                        <p class="text-sm sm:text-base text-gray-300 leading-relaxed">
                            "We hired Roaster Grill for our company's annual celebration. The team was professional, the food was exceptional, and they handled everything perfectly. Will definitely use them again!"
                        </p>
                    </div>

                    <!-- Testimonial 4 -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8 hover:border-red-500/30 transition-all duration-300 hover:scale-105 group">
                        <div class="flex items-center mb-4 sm:mb-6">
                            <div class="w-10 h-10 sm:w-12 sm:h-12 bg-black rounded-full flex items-center justify-center mr-3 sm:mr-4">
                                <span class="text-white font-bold text-sm sm:text-lg">K</span>
                            </div>
                            <div>
                                <h4 class="text-white font-semibold text-base sm:text-lg">Kwame Asante</h4>
                                <p class="text-gray-400 text-xs sm:text-sm">Birthday Party</p>
                                <div class="flex text-yellow-400 text-xs sm:text-sm mt-1">
                                    ⭐⭐⭐⭐⭐
                                </div>
                            </div>
                        </div>
                        <p class="text-sm sm:text-base text-gray-300 leading-relaxed">
                            "Amazing service for my daughter's birthday party! The pork was tender, flavorful, and everyone loved it. The team was punctual and professional. Highly recommended!"
                        </p>
                    </div>

                    <!-- Testimonial 5 -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8 hover:border-red-500/30 transition-all duration-300 hover:scale-105 group">
                        <div class="flex items-center mb-4 sm:mb-6">
                            <div class="w-10 h-10 sm:w-12 sm:h-12 bg-black rounded-full flex items-center justify-center mr-3 sm:mr-4">
                                <span class="text-white font-bold text-sm sm:text-lg">A</span>
                            </div>
                            <div>
                                <h4 class="text-white font-semibold text-base sm:text-lg">Ama Osei</h4>
                                <p class="text-gray-400 text-xs sm:text-sm">Anniversary Dinner</p>
                                <div class="flex text-yellow-400 text-xs sm:text-sm mt-1">
                                    ⭐⭐⭐⭐⭐
                                </div>
                            </div>
                        </div>
                        <p class="text-sm sm:text-base text-gray-300 leading-relaxed">
                            "Perfect for our anniversary celebration! The quality of the pork and the attention to detail was outstanding. Made our special day even more memorable."
                        </p>
                    </div>

                    <!-- Testimonial 6 -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8 hover:border-red-500/30 transition-all duration-300 hover:scale-105 group">
                        <div class="flex items-center mb-4 sm:mb-6">
                            <div class="w-10 h-10 sm:w-12 sm:h-12 bg-black rounded-full flex items-center justify-center mr-3 sm:mr-4">
                                <span class="text-white font-bold text-sm sm:text-lg">J</span>
                            </div>
                            <div>
                                <h4 class="text-white font-semibold text-base sm:text-lg">John Mensah</h4>
                                <p class="text-gray-400 text-xs sm:text-sm">Takeaway Customer</p>
                                <div class="flex text-yellow-400 text-xs sm:text-sm mt-1">
                                    ⭐⭐⭐⭐⭐
                                </div>
                            </div>
                        </div>
                        <p class="text-sm sm:text-base text-gray-300 leading-relaxed">
                            "Best roasted pork in Accra! The takeaway service is convenient and the quality is always top-notch. Their spices are incredible - my family loves it!"
                        </p>
                    </div>
                </div>

                <!-- CTA Section -->
                <div class="text-center mt-12 sm:mt-16">
                    <p class="text-base sm:text-lg text-gray-300 mb-6 sm:mb-8 font-serif">
                        Ready to experience the difference that flame-kissed perfection makes?
                    </p>
                    <div class="flex flex-col sm:flex-row gap-3 sm:gap-4 justify-center max-w-md sm:max-w-none mx-auto">
                        <router-link to="/contact" class="btn-red w-full sm:w-auto text-center group relative overflow-hidden">
                            <span class="relative z-10">Book Your Event</span>
                            <div class="absolute inset-0 bg-white/10 transform -translate-x-full group-hover:translate-x-0 transition-transform duration-500"></div>
                        </router-link>
                        <router-link to="/services" class="btn-red-outline w-full sm:w-auto text-center group relative overflow-hidden">
                            <span class="relative z-10">View Services</span>
                            <div class="absolute inset-0 bg-red-500/10 transform -translate-x-full group-hover:translate-x-0 transition-transform duration-500"></div>
                        </router-link>
                    </div>
                </div>
            </div>
        </section>
    </main>
</template>

<script setup>
// Portfolio page component
</script>
