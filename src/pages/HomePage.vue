<template>
    <main class="min-h-dvh bg-gradient-to-br from-black via-gray-900 to-black text-white">
        <!-- Hero Section -->
        <section class="relative min-h-[90vh] flex items-center justify-center overflow-hidden">
            <!-- Background Image -->
            <div class="absolute inset-0">
                <img src="https://images.unsplash.com/photo-1555939594-58d7cb561ad1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2000&q=80"
                    alt="Roasted pork on grill" class="w-full h-full object-cover" />
                <!-- Dark Overlay for Better Text Readability -->
                <div class="absolute inset-0 bg-black/60"></div>
                <!-- Subtle Gradient Overlay -->
                <div class="absolute inset-0 bg-gradient-to-br from-black/40 via-transparent to-red-900/30"></div>
            </div>

            <!-- Main Content -->
            <div
                class="relative z-10 text-center px-4 sm:px-6 max-w-7xl mx-auto pt-36 sm:pt-40 md:pt-36 lg:pt-32 xl:pt-28">
                <!-- Main Title -->
                <h1
                    class="font-black font-serif text-4xl sm:text-6xl lg:text-8xl xl:text-9xl leading-[0.9] sm:leading-[0.85] tracking-tight mb-6 sm:mb-8">
                    <span
                        class="block text-transparent bg-clip-text bg-gradient-to-br from-yellow-300 via-orange-500 to-red-600 shadow-lg">
                        PORK ROASTING
                    </span>
                    <span
                        class="block text-transparent bg-clip-text bg-gradient-to-t from-white via-gray-200 to-gray-400 mt-1 sm:mt-2">MASTERS</span>
                </h1>

                <!-- Subtitle -->
                <p
                    class="text-xl text-gray-100 leading-relaxed max-w-4xl mx-auto mb-8 sm:mb-12 font-light drop-shadow-lg px-2">
                    Experience the art of <span class="text-red-400 font-semibold">flame-kissed perfection</span> with
                    our premium
                    pork sourcing and traditional open-flame roasting techniques.
                </p>

                <!-- CTA Buttons -->
                <div class="flex flex-col sm:flex-row gap-4 sm:gap-6 justify-center items-center mb-20 sm:mb-16 px-4">
                    <router-link to="/contact" class="btn-red text-center w-full sm:w-auto">
                        Order Now
                    </router-link>

                    <router-link to="/about" class="btn-red-outline text-center w-full sm:w-auto">
                        Read Reviews
                    </router-link>
                </div>
            </div>


        </section>

        <!-- About Us Section -->
        <section class="relative py-20 px-4 sm:px-6 overflow-hidden">
            <!-- Background Image -->
            <div class="absolute inset-0 bg-black">
                <div
                    class="absolute inset-0 bg-[radial-gradient(circle_at_30%_70%,rgba(239,68,68,0.15)_0%,transparent_50%)]">
                </div>
            </div>

            <div class="relative z-10 max-w-7xl mx-auto">
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 lg:gap-20 items-center">
                    <!-- Text Content -->
                    <div class="text-white">
                        <h2 class="text-4xl font-serif sm:text-5xl font-bold mb-8">
                            The Roaster Grill Story
                        </h2>
                        <div class="text-lg leading-relaxed">
                            <p class="mb-6">
                                Founded in 2018, we specialize in <strong class="text-red-300">premium roasted
                                    pork</strong> using
                                traditional open-flame techniques.
                            </p>
                            <p class="mb-8">
                                Quality ingredients, expert craftsmanship, unforgettable taste.
                            </p>
                        </div>
                        <div class="mt-8">
                            <router-link to="/about" class="btn-red-outline w-full sm:w-auto text-center">
                                Our Story
                            </router-link>
                        </div>
                    </div>

                    <!-- Image Section -->
                    <div class="relative">
                        <img src="https://images.unsplash.com/photo-1555939594-58d7cb561ad1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1000&q=80"
                            alt="Traditional roasted pork preparation"
                            class="w-full h-64 sm:h-80 lg:h-96 rounded-lg sm:rounded-xl shadow-lg object-cover">
                    </div>
                </div>
            </div>
        </section>

        <!-- Our Offerings Section -->
        <div class="relative overflow-hidden bg-black py-16 sm:py-20 lg:py-24">
            <!-- Section Header -->
            <div class="text-center mb-12 sm:mb-16 px-4 sm:px-6">
                <h2 class="text-3xl font-serif sm:text-4xl lg:text-5xl font-bold text-white mb-3 sm:mb-4">
                    Our Offerings
                </h2>
                <div class="w-16 sm:w-20 h-0.5 bg-red-500 mx-auto"></div>
            </div>

            <div class="space-y-16 sm:space-y-20 lg:space-y-24">
                <!-- Catering Section -->
                <div class="relative">
                    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
                        <div class="lg:grid lg:grid-cols-2 lg:gap-12 xl:gap-16 lg:items-center">
                            <div class="order-2 lg:order-1 mb-8 lg:mb-0">
                                <div class="max-w-xl mx-auto lg:mx-0">
                                    <h3
                                        class="text-2xl sm:text-3xl font-bold text-white mb-3 sm:mb-4 leading-tight text-center lg:text-left">
                                        Catering for All Occasions
                                    </h3>
                                    <p
                                        class="text-gray-300 mb-6 leading-relaxed text-center lg:text-left text-sm sm:text-base">
                                        From intimate gatherings to grand celebrations, we bring our signature roasted
                                        pork to make your
                                        event unforgettable.
                                    </p>

                                    <div class="text-center lg:text-left">
                                        <router-link to="/contact" class="btn-red-outline w-full sm:w-auto text-center">
                                            Book Your Event
                                            <svg class="ml-2 h-3 w-3 sm:h-4 sm:w-4" fill="none" stroke="currentColor"
                                                viewBox="0 0 24 24">
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                    d="M9 5l7 7-7 7"></path>
                                            </svg>
                                        </router-link>
                                    </div>
                                </div>
                            </div>

                            <div class="order-1 lg:order-2">
                                <div class="relative">
                                    <img src="https://images.unsplash.com/photo-1555939594-58d7cb561ad1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1000&q=80"
                                        alt="Catering event with roasted pork"
                                        class="w-full h-64 sm:h-80 lg:h-96 rounded-lg sm:rounded-xl shadow-lg object-cover">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Takeaway Section -->
                <div class="relative">
                    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
                        <div class="lg:grid lg:grid-cols-2 lg:gap-12 xl:gap-16 lg:items-center">
                            <div class="order-2 mb-8 lg:mb-0">
                                <div class="max-w-xl mx-auto lg:mx-0">
                                    <h3
                                        class="text-2xl sm:text-3xl font-bold text-white mb-3 sm:mb-4 leading-tight text-center lg:text-left">
                                        Takeaway & Delivery
                                    </h3>
                                    <p
                                        class="text-gray-300 mb-6 leading-relaxed text-center lg:text-left text-sm sm:text-base">
                                        Enjoy our fresh, raw packaged pork wherever you are. Customized to your desired
                                        weight for the
                                        perfect cooking experience.
                                    </p>

                                    <div class="text-center lg:text-left">
                                        <router-link to="/shop" class="btn-red-outline w-full sm:w-auto text-center">
                                            Order Now
                                            <svg class="ml-2 h-3 w-3 sm:h-4 sm:w-4" fill="none" stroke="currentColor"
                                                viewBox="0 0 24 24">
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                    d="M9 5l7 7-7 7"></path>
                                            </svg>
                                        </router-link>
                                    </div>
                                </div>
                            </div>

                            <div class="order-1">
                                <div class="relative">
                                    <img src="https://images.unsplash.com/photo-1544025162-d76694265947?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1000&q=80"
                                        alt="Fresh packaged pork meat"
                                        class="w-full h-64 sm:h-80 lg:h-96 rounded-lg sm:rounded-xl shadow-lg object-cover">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Spices Section -->
                <div class="relative">
                    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
                        <div class="lg:grid lg:grid-cols-2 lg:gap-12 xl:gap-16 lg:items-center">
                            <div class="order-2 lg:order-1 mb-8 lg:mb-0">
                                <div class="max-w-xl mx-auto lg:mx-0">
                                    <h3
                                        class="text-2xl sm:text-3xl font-bold text-white mb-3 sm:mb-4 leading-tight text-center lg:text-left">
                                        Signature Spices & Marinades
                                    </h3>
                                    <p
                                        class="text-gray-300 mb-6 leading-relaxed text-center lg:text-left text-sm sm:text-base">
                                        Our carefully crafted blend of spices and marinades elevates every dish,
                                        creating flavors that are
                                        uniquely Roaster Grill.
                                    </p>

                                    <div class="text-center lg:text-left">
                                        <router-link to="/shop" class="btn-red-outline w-full sm:w-auto text-center">
                                            Order Now
                                            <svg class="ml-2 h-3 w-3 sm:h-4 sm:w-4" fill="none" stroke="currentColor"
                                                viewBox="0 0 24 24">
                                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                                    d="M9 5l7 7-7 7"></path>
                                            </svg>
                                        </router-link>
                                    </div>
                                </div>
                            </div>

                            <div class="order-1 lg:order-2">
                                <div class="relative">
                                    <img src="https://images.unsplash.com/photo-1556909114-f6e7ad7d3136?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1000&q=80"
                                        alt="Spices and seasonings"
                                        class="w-full h-64 sm:h-80 lg:h-96 rounded-lg sm:rounded-xl shadow-lg object-cover">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Testimonials Section -->
        <section class="relative py-20 px-4 sm:px-6 overflow-hidden bg-gradient-to-br from-black to-gray-900">
            <!-- Background Elements -->
            <div class="absolute inset-0">
                <div
                    class="absolute inset-0 bg-[radial-gradient(circle_at_20%_80%,rgba(239,68,68,0.05)_0%,transparent_50%)]">
                </div>
                <div
                    class="absolute inset-0 bg-[radial-gradient(circle_at_80%_20%,rgba(59,130,246,0.03)_0%,transparent_50%)]">
                </div>
            </div>

            <div class="relative z-10 max-w-7xl mx-auto">
                <!-- Section Header -->
                <div class="text-center mb-16">
                    <h2 class="text-3xl font-serif sm:text-4xl lg:text-5xl font-bold text-white mb-4">
                        What Our Customers Say
                    </h2>
                    <div class="w-16 sm:w-20 h-0.5 bg-red-500 mx-auto mb-6"></div>
                    <p class="text-gray-300 text-lg max-w-2xl mx-auto">
                        Don't just take our word for it - hear from the people who've experienced our flame-kissed
                        perfection
                    </p>
                </div>

                <!-- Testimonials Grid -->
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 lg:gap-10">
                    <!-- Testimonial 1 -->
                    <div
                        class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-2xl p-8 hover:border-red-500/30 transition-all duration-300 hover:scale-105 group">
                        <div class="flex items-center mb-6">
                            <div
                                class="w-12 h-12 bg-gradient-to-br from-red-500 to-red-600 rounded-full flex items-center justify-center mr-4">
                                <span class="text-white font-bold text-lg">S</span>
                            </div>
                            <div>
                                <h4 class="text-white font-semibold text-lg">Sarah Mitchell</h4>
                                <p class="text-gray-400 text-sm">Wedding Catering</p>
                            </div>
                        </div>
                        <p class="text-gray-300 leading-relaxed">
                            "The Roaster Grill catered our wedding and it was absolutely incredible! The pork was
                            perfectly seasoned and the presentation was stunning. Our guests are still talking about it
                            months later!"
                        </p>
                    </div>

                    <!-- Testimonial 2 -->
                    <div
                        class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-2xl p-8 hover:border-red-500/30 transition-all duration-300 hover:scale-105 group">
                        <div class="flex items-center mb-6">
                            <div
                                class="w-12 h-12 bg-gradient-to-br from-blue-500 to-blue-600 rounded-full flex items-center justify-center mr-4">
                                <span class="text-white font-bold text-lg">M</span>
                            </div>
                            <div>
                                <h4 class="text-white font-semibold text-lg">Michael Chen</h4>
                                <p class="text-gray-400 text-sm">Regular Customer</p>
                            </div>
                        </div>
                        <p class="text-gray-300 leading-relaxed">
                            "I've been ordering their takeaway pork for months now. The quality is consistently amazing
                            and their signature spices make every meal special. Highly recommend!"
                        </p>
                    </div>

                    <!-- Testimonial 3 -->
                    <div
                        class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-2xl p-8 hover:border-red-500/30 transition-all duration-300 hover:scale-105 group">
                        <div class="flex items-center mb-6">
                            <div
                                class="w-12 h-12 bg-gradient-to-br from-purple-500 to-purple-600 rounded-full flex items-center justify-center mr-4">
                                <span class="text-white font-bold text-lg">L</span>
                            </div>
                            <div>
                                <h4 class="text-white font-semibold text-lg">Lisa Rodriguez</h4>
                                <p class="text-gray-400 text-sm">Corporate Events</p>
                            </div>
                        </div>
                        <p class="text-gray-300 leading-relaxed">
                            "We hired Roaster Grill for our company's annual celebration. The team was professional, the
                            food was exceptional, and they handled everything perfectly. Will definitely use them
                            again!"
                        </p>
                    </div>
                </div>

                <!-- CTA Section -->
                <div class="text-center mt-16">
                    <p class="text-gray-300 text-lg mb-8">
                        Ready to experience the difference that flame-kissed perfection makes?
                    </p>
                    <div class="flex justify-center">
                        <router-link to="/contact" class="btn-red-outline w-full sm:w-auto text-center">
                            Order Your Roast
                        </router-link>
                    </div>
                </div>
            </div>
        </section>

    </main>
</template>

<script setup>
// Home page component
</script>
