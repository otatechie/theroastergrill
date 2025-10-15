<template>
    <main class="min-h-dvh bg-gradient-to-br from-black via-gray-900 to-black text-white">
        <!-- Hero Section -->
        <section class="relative min-h-[60vh] sm:min-h-[70vh] flex items-center justify-center overflow-hidden">
            <!-- Background Image -->
            <div class="absolute inset-0">
                <img src="https://images.unsplash.com/photo-1555939594-58d7cb561ad1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=2000&q=80"
                    alt="Contact us for roasted pork catering" 
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
                        GET IN TOUCH
                    </span>
                </h1>

                <!-- Subtitle -->
                <p class="text-base sm:text-lg md:text-xl text-gray-200 leading-relaxed max-w-2xl sm:max-w-3xl mx-auto mb-6 sm:mb-8 md:mb-12 font-serif px-2">
                    Ready to experience <span class="text-red-400 font-semibold">flame-kissed perfection</span>? Let's make your event unforgettable.
                </p>
            </div>
        </section>

        <!-- Contact Content Section -->
        <section class="relative py-8 sm:py-12 md:py-16 lg:py-20 px-4 sm:px-6 overflow-hidden">
            <!-- Background Image -->
            <div class="absolute inset-0 bg-black">
                <div class="absolute inset-0 bg-[radial-gradient(circle_at_30%_70%,rgba(239,68,68,0.15)_0%,transparent_50%)]"></div>
            </div>

            <div class="relative z-10 max-w-7xl mx-auto">
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 sm:gap-8 md:gap-12 lg:gap-20 items-start">
                    <!-- Contact Information -->
                    <div class="text-white">
                        <h2 class="text-2xl sm:text-3xl md:text-4xl lg:text-5xl font-serif font-bold mb-4 sm:mb-6 md:mb-8 tracking-tight">
                            Contact Information
                        </h2>
                        <div class="text-sm sm:text-base md:text-lg leading-relaxed text-gray-300 mb-6 sm:mb-8">
                            <p class="mb-3 sm:mb-4 md:mb-6">
          Get in touch with us for your catering needs, event bookings, or any questions you might have.
                                We're here to make your special occasions truly memorable.
                            </p>
                        </div>

                        <!-- Contact Details -->
                        <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8">
                            <div class="space-y-3 sm:space-y-4 md:space-y-6">
                                <!-- Phone -->
                                <div class="flex items-center">
                                    <div class="w-10 h-10 sm:w-12 sm:h-12 bg-gradient-to-br from-red-500 to-red-600 rounded-full flex items-center justify-center mr-3 sm:mr-4 flex-shrink-0">
                                        <svg class="w-4 h-4 sm:w-5 sm:h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path>
                                        </svg>
                                    </div>
                                    <div>
                                        <p class="text-white font-semibold text-base sm:text-lg">Phone</p>
                                        <p class="text-gray-300 text-sm sm:text-base">+233 20 000 0000</p>
                                    </div>
                                </div>

                                <!-- Email -->
                                <div class="flex items-center">
                                    <div class="w-10 h-10 sm:w-12 sm:h-12 bg-gradient-to-br from-blue-500 to-blue-600 rounded-full flex items-center justify-center mr-3 sm:mr-4 flex-shrink-0">
                                        <svg class="w-4 h-4 sm:w-5 sm:h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                                        </svg>
                                    </div>
                                    <div>
                                        <p class="text-white font-semibold text-base sm:text-lg">Email</p>
                                        <p class="text-gray-300 text-sm sm:text-base">hello@theroastergrill.com</p>
                                    </div>
                                </div>

                                <!-- Location -->
                                <div class="flex items-center">
                                    <div class="w-10 h-10 sm:w-12 sm:h-12 bg-gradient-to-br from-green-500 to-green-600 rounded-full flex items-center justify-center mr-3 sm:mr-4 flex-shrink-0">
                                        <svg class="w-4 h-4 sm:w-5 sm:h-5 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path>
                                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path>
                                        </svg>
                                    </div>
                                    <div>
                                        <p class="text-white font-semibold text-base sm:text-lg">Location</p>
                                        <p class="text-gray-300 text-sm sm:text-base">Accra, Ghana</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Contact Form -->
                    <div class="text-white">
                        <h3 class="text-xl sm:text-2xl md:text-3xl font-serif font-bold mb-4 sm:mb-6 md:mb-8 tracking-tight">
                            Send us a Message
                        </h3>
                        <form class="space-y-3 sm:space-y-4 md:space-y-6" @submit.prevent="handleSubmit">
                            <!-- Name -->
                            <div>
                                <label for="name" class="block text-xs sm:text-sm font-medium text-gray-300 mb-1 sm:mb-2">Full Name</label>
                                <input type="text" id="name" name="name" required
                                    class="w-full px-3 sm:px-4 py-2 sm:py-3 bg-gray-900/50 border border-gray-700 rounded-lg text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-red-500 focus:border-transparent text-sm sm:text-base">
                            </div>

                            <!-- Email -->
                            <div>
                                <label for="email" class="block text-xs sm:text-sm font-medium text-gray-300 mb-1 sm:mb-2">Email Address</label>
                                <input type="email" id="email" name="email" required
                                    class="w-full px-3 sm:px-4 py-2 sm:py-3 bg-gray-900/50 border border-gray-700 rounded-lg text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-red-500 focus:border-transparent text-sm sm:text-base">
                            </div>

                            <!-- Phone -->
                            <div>
                                <label for="phone" class="block text-xs sm:text-sm font-medium text-gray-300 mb-1 sm:mb-2">Phone Number</label>
                                <input type="tel" id="phone" name="phone"
                                    class="w-full px-3 sm:px-4 py-2 sm:py-3 bg-gray-900/50 border border-gray-700 rounded-lg text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-red-500 focus:border-transparent text-sm sm:text-base">
                            </div>

                            <!-- Event Type -->
                            <div>
                                <label for="event-type" class="block text-xs sm:text-sm font-medium text-gray-300 mb-1 sm:mb-2">Event Type</label>
                                <select id="event-type" name="event-type"
                                    class="w-full px-3 sm:px-4 py-2 sm:py-3 bg-gray-900/50 border border-gray-700 rounded-lg text-white focus:outline-none focus:ring-2 focus:ring-red-500 focus:border-transparent text-sm sm:text-base">
                                    <option value="">Select an option</option>
                                    <option value="wedding">Wedding</option>
                                    <option value="corporate">Corporate Event</option>
                                    <option value="birthday">Birthday Party</option>
                                    <option value="anniversary">Anniversary</option>
                                    <option value="other">Other</option>
                                </select>
                            </div>

                            <!-- Message -->
                            <div>
                                <label for="message" class="block text-xs sm:text-sm font-medium text-gray-300 mb-1 sm:mb-2">Message</label>
                                <textarea id="message" name="message" rows="4" required
                                    class="w-full px-3 sm:px-4 py-2 sm:py-3 bg-gray-900/50 border border-gray-700 rounded-lg text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-red-500 focus:border-transparent resize-none text-sm sm:text-base"></textarea>
                            </div>

                            <!-- Submit Button -->
                            <div class="pt-2 sm:pt-4">
                                <button type="submit" class="btn-red w-full sm:w-auto text-center group relative overflow-hidden disabled:opacity-50 disabled:cursor-not-allowed">
                                    <span class="relative z-10">Send Message</span>
                                    <div class="absolute inset-0 bg-white/10 transform -translate-x-full group-hover:translate-x-0 transition-transform duration-500"></div>
                                </button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- Map Section -->
        <section class="relative py-8 sm:py-12 md:py-16 lg:py-20 px-4 sm:px-6 overflow-hidden">
            <!-- Background -->
            <div class="absolute inset-0 bg-black">
                <div class="absolute inset-0 bg-[radial-gradient(circle_at_70%_30%,rgba(239,68,68,0.1)_0%,transparent_50%)]"></div>
            </div>

            <div class="relative z-10 max-w-7xl mx-auto">
                <!-- Section Header -->
                <div class="text-center mb-8 sm:mb-12">
                    <h2 class="text-2xl sm:text-3xl md:text-4xl lg:text-5xl font-serif font-bold text-white mb-4 sm:mb-6 tracking-tight">
                        Find Us
                    </h2>
                    <div class="w-16 sm:w-24 h-0.5 bg-red-500 mx-auto mb-4 sm:mb-6"></div>
                    <p class="text-base sm:text-lg text-gray-300 max-w-2xl mx-auto font-serif">
                        Visit us in Accra, Ghana for the best roasted pork experience
                    </p>
                </div>

                <!-- Map Container -->
                <div class="relative">
                    <!-- Map -->
                    <div class="w-full h-64 sm:h-80 md:h-96 lg:h-[500px] rounded-lg sm:rounded-xl overflow-hidden shadow-2xl border border-gray-700/50">
                        <iframe 
                            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3970.755!2d-0.1869644!3d5.6037168!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zNcKwMzYnMTMuNCJOIDDCsDExJzEzLjEiVw!5e0!3m2!1sen!2sgh!4v1234567890123!5m2!1sen!2sgh"
                            width="100%" 
                            height="100%" 
                            style="border:0; filter: grayscale(100%) invert(92%) contrast(83%);" 
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade"
                            title="The Roaster Grill Location in Accra, Ghana">
                        </iframe>
                    </div>

                    <!-- Map Overlay Info -->
                    <div class="absolute top-4 left-4 bg-black/80 backdrop-blur-sm border border-gray-700/50 rounded-lg p-4 max-w-xs">
                        <div class="flex items-center mb-2">
                            <div class="w-8 h-8 bg-gradient-to-br from-red-500 to-red-600 rounded-full flex items-center justify-center mr-3">
                                <svg class="w-4 h-4 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path>
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path>
                                </svg>
                            </div>
                            <div>
                                <h3 class="text-white font-semibold text-sm">The Roaster Grill</h3>
                                <p class="text-gray-300 text-xs">Accra, Ghana</p>
                            </div>
                        </div>

                    </div>

                    <!-- Directions Button -->
                    <div class="absolute bottom-4 right-4">
                        <a 
                            href="https://www.google.com/maps/dir//Accra,+Ghana" 
                            target="_blank" 
                            rel="noopener noreferrer"
                            class="bg-red-600 hover:bg-red-700 text-white px-4 py-2 rounded-lg text-sm font-medium transition-colors duration-200 flex items-center shadow-lg">
                            <svg class="w-4 h-4 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 20l-5.447-2.724A1 1 0 013 16.382V5.618a1 1 0 011.447-.894L9 7m0 13l6-3m-6 3V7m6 10l4.553 2.276A1 1 0 0021 18.382V7.618a1 1 0 00-1.447-.894L15 4m0 13V4m0 0L9 7"></path>
                            </svg>
                            Get Directions
                        </a>
                    </div>
                </div>

            </div>
        </section>

        <!-- FAQ Section -->
        <section class="relative py-8 sm:py-12 md:py-16 lg:py-20 px-4 sm:px-6 overflow-hidden">
            <!-- Background -->
            <div class="absolute inset-0 bg-black">
                <div class="absolute inset-0 bg-[radial-gradient(circle_at_70%_30%,rgba(239,68,68,0.1)_0%,transparent_50%)]"></div>
            </div>

            <div class="relative z-10 max-w-4xl mx-auto">
                <!-- Section Header -->
                <div class="text-center mb-8 sm:mb-12 md:mb-16">
                    <h2 class="text-2xl sm:text-3xl md:text-4xl lg:text-5xl font-serif font-bold text-white mb-4 sm:mb-6 tracking-tight">
                        Frequently Asked Questions
                    </h2>
                    <div class="w-16 sm:w-24 h-0.5 bg-red-500 mx-auto mb-4 sm:mb-6"></div>
                    <p class="text-base sm:text-lg text-gray-300 max-w-2xl mx-auto font-serif">
                        Can't find what you're looking for? Contact us and we'll be happy to help.
                    </p>
                </div>

                <!-- FAQ Items -->
                <div class="space-y-4 sm:space-y-6">
                    <!-- FAQ Item 1 -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8">
                        <h3 class="text-md sm:text-md md:text-md font-semibold text-white mb-3 sm:mb-4 flex items-center">
                            <div class="w-7 h-7 sm:w-8 sm:h-8 bg-black rounded-full flex items-center justify-center mr-3 sm:mr-4 flex-shrink-0">
                                <span class="text-white font-bold text-xs sm:text-sm">1</span>
                            </div>
                            How far in advance should I book catering for my event?
                        </h3>
                        <p class="text-sm sm:text-base text-gray-300 leading-relaxed ml-10 sm:ml-12">
                            We recommend booking at least 2-3 weeks in advance for small to medium events, and 4-6 weeks for large events or weddings. This ensures we can secure the best quality pork and provide you with our full attention to detail. For last-minute requests, please contact us directly as we may have availability.
                        </p>
                    </div>

                    <!-- FAQ Item 2 -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8">
                        <h3 class="text-md sm:text-md md:text-md font-semibold text-white mb-3 sm:mb-4 flex items-center">
                            <div class="w-7 h-7 sm:w-8 sm:h-8 bg-black rounded-full flex items-center justify-center mr-3 sm:mr-4 flex-shrink-0">
                                <span class="text-white font-bold text-xs sm:text-sm">2</span>
                            </div>
                            What areas do you serve for delivery?
                        </h3>
                        <p class="text-sm sm:text-base text-gray-300 leading-relaxed ml-10 sm:ml-12">
                            We primarily serve the Greater Accra area, including Accra Central, East Legon, West Legon, Tema, and surrounding areas. Delivery fees vary by location (₵15-25). For areas outside our standard delivery zone, please contact us for availability and pricing. We also offer pickup options at our central location.
                        </p>
                    </div>

                    <!-- FAQ Item 3 -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8">
                        <h3 class="text-md sm:text-md md:text-md font-semibold text-white mb-3 sm:mb-4 flex items-center">
                            <div class="w-7 h-7 sm:w-8 sm:h-8 bg-black rounded-full flex items-center justify-center mr-3 sm:mr-4 flex-shrink-0">
                                <span class="text-white font-bold text-xs sm:text-sm">3</span>
                            </div>
                            Do you accommodate dietary restrictions or special requests?
                        </h3>
                        <p class="text-sm sm:text-base text-gray-300 leading-relaxed ml-10 sm:ml-12">
                            Yes! We can accommodate various dietary needs including halal preparation, reduced spice levels, and custom marinades. Please inform us of any dietary restrictions or special requests when placing your order. We're committed to ensuring everyone can enjoy our flame-kissed perfection.
                        </p>
                    </div>

                    <!-- FAQ Item 4 -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8">
                        <h3 class="text-md sm:text-md md:text-md font-semibold text-white mb-3 sm:mb-4 flex items-center">
                            <div class="w-7 h-7 sm:w-8 sm:h-8 bg-black rounded-full flex items-center justify-center mr-3 sm:mr-4 flex-shrink-0">
                                <span class="text-white font-bold text-xs sm:text-sm">4</span>
                            </div>
                            What's included in your catering service?
                        </h3>
                        <p class="text-sm sm:text-base text-gray-300 leading-relaxed ml-10 sm:ml-12">
                            Our full-service catering includes: premium roasted pork, professional setup and presentation, serving utensils, cleanup service, and our expert team to ensure everything runs smoothly. We can also provide additional items like side dishes, beverages, and dessert options upon request. All pricing is transparent with no hidden fees.
                        </p>
                    </div>

                    <!-- FAQ Item 5 -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8">
                        <h3 class="text-md sm:text-md md:text-md font-semibold text-white mb-3 sm:mb-4 flex items-center">
                            <div class="w-7 h-7 sm:w-8 sm:h-8 bg-black rounded-full flex items-center justify-center mr-3 sm:mr-4 flex-shrink-0">
                                <span class="text-white font-bold text-xs sm:text-sm">5</span>
                            </div>
                            How do you ensure food safety and quality?
                        </h3>
                        <p class="text-sm sm:text-base text-gray-300 leading-relaxed ml-10 sm:ml-12">
                            We maintain the highest standards of food safety and quality. Our pork is sourced from trusted suppliers, stored at proper temperatures, and prepared using traditional methods combined with modern food safety practices. Our team is trained in proper handling, cooking temperatures, and hygiene protocols. We're committed to delivering not just great taste, but safe, high-quality food every time.
                        </p>
                    </div>

                    <!-- FAQ Item 6 -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8">
                        <h3 class="text-md sm:text-md md:text-md font-semibold text-white mb-3 sm:mb-4 flex items-center">
                            <div class="w-7 h-7 sm:w-8 sm:h-8 bg-black rounded-full flex items-center justify-center mr-3 sm:mr-4 flex-shrink-0">
                                <span class="text-white font-bold text-xs sm:text-sm">6</span>
                            </div>
                            What payment methods do you accept?
                        </h3>
                        <p class="text-sm sm:text-base text-gray-300 leading-relaxed ml-10 sm:ml-12">
                            We accept cash, mobile money (MTN, Vodafone, AirtelTigo), bank transfers, and major credit cards. For large events, we typically require a 50% deposit to secure your booking, with the balance due on the day of service. We can provide detailed invoices and receipts for all transactions.
                        </p>
                    </div>

                    <!-- FAQ Item 7 -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8">
                        <h3 class="text-md sm:text-md md:text-md font-semibold text-white mb-3 sm:mb-4 flex items-center">
                            <div class="w-7 h-7 sm:w-8 sm:h-8 bg-black rounded-full flex items-center justify-center mr-3 sm:mr-4 flex-shrink-0">
                                <span class="text-white font-bold text-xs sm:text-sm">7</span>
                            </div>
                            Can I get cooking instructions for takeaway orders?
                        </h3>
                        <p class="text-sm sm:text-base text-gray-300 leading-relaxed ml-10 sm:ml-12">
                            Absolutely! Every takeaway order comes with detailed cooking instructions tailored to your specific cut and preparation preferences. We also provide our signature spice recommendations and cooking tips to help you achieve that perfect flame-kissed result at home. Our team is always available to answer any cooking questions you might have.
                        </p>
                    </div>

                    <!-- FAQ Item 8 -->
                    <div class="bg-gradient-to-br from-gray-900/50 to-black/50 backdrop-blur-sm border border-gray-700/50 rounded-xl sm:rounded-2xl p-5 sm:p-6 md:p-8">
                        <h3 class="text-md sm:text-md md:text-md font-semibold text-white mb-3 sm:mb-4 flex items-center">
                            <div class="w-7 h-7 sm:w-8 sm:h-8 bg-black rounded-full flex items-center justify-center mr-3 sm:mr-4 flex-shrink-0">
                                <span class="text-white font-bold text-xs sm:text-sm">8</span>
                            </div>
                            What's your cancellation policy?
                        </h3>
                        <p class="text-sm sm:text-base text-gray-300 leading-relaxed ml-10 sm:ml-12">
                            For catering events, we require 48 hours notice for cancellations to receive a full refund. Cancellations within 24-48 hours will receive a 50% refund. Same-day cancellations are non-refundable due to food preparation costs. For takeaway orders, cancellations are accepted up to 2 hours before scheduled pickup/delivery time. We understand emergencies happen, so please contact us to discuss your specific situation.
                        </p>
                    </div>
        </div>
      </div>
    </section>
  </main>
</template>

<script setup>
import { ref } from 'vue'

// Form handling
const handleSubmit = (event) => {
  event.preventDefault()
  // Here you would typically handle form submission
  // For now, we'll just show an alert
  alert('Thank you for your message! We\'ll get back to you soon.')
  
  // Reset form
  event.target.reset()
}
</script>
