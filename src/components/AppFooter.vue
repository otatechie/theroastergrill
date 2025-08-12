<script setup>
import { computed } from 'vue'

const props = defineProps({
    address: { type: String, default: 'Accra, Ghana' },
    phone: { type: String, default: '+233 20 000 0000' },
    email: { type: String, default: 'hello@theroastergrill.com' },
    instagram: { type: String, default: 'https://instagram.com/theroastergrill' },
    linkedin: { type: String, default: 'https://linkedin.com/company/theroastergrill' },
})

const phoneHref = computed(() => `tel:${props.phone.replace(/\s+/g, '')}`)
const emailHref = computed(() => `mailto:${props.email}`)
</script>

<template>
    <footer id="contact"
        class="relative bg-gradient-to-br from-gray-900 via-black to-gray-900 text-white overflow-hidden">
        <!-- Repeating header pattern -->
        <div class="border-b border-red-500/40 font-serif relative overflow-hidden">
            <div class="flex items-center justify-center py-6 sm:py-8 px-4">
                <!-- Left decorative element -->
                <div class="hidden sm:flex items-center space-x-2 mr-6">
                    <div class="w-2 h-2 bg-red-400 rounded-full animate-pulse"></div>
                    <div class="w-1 h-1 bg-red-300 rounded-full animate-pulse delay-75"></div>
                    <div class="w-2 h-2 bg-red-400 rounded-full animate-pulse delay-150"></div>
                </div>

                <!-- Main text with enhanced styling -->
                <div class="flex flex-col sm:flex-row items-center space-y-2 sm:space-y-0 sm:space-x-6 text-center">
                    <span class="text-sm sm:text-lg font-bold tracking-[0.3em] uppercase text-red-400 relative group">
                        <span class="relative z-10">Traditional roasting</span>
                        <div
                            class="absolute inset-0 bg-gradient-to-r from-transparent via-red-500/10 to-transparent transform scale-x-0 group-hover:scale-x-100 transition-transform duration-500 origin-left">
                        </div>
                    </span>

                    <div class="flex items-center space-x-1">
                        <div class="w-1 h-1 bg-red-400 rounded-full"></div>
                        <div class="w-1 h-1 bg-red-300 rounded-full"></div>
                        <div class="w-1 h-1 bg-red-400 rounded-full"></div>
                    </div>

                    <span class="text-sm sm:text-lg font-bold tracking-[0.3em] uppercase text-red-400 relative group">
                        <span class="relative z-10">Family-run</span>
                        <div
                            class="absolute inset-0 bg-gradient-to-r from-transparent via-red-500/10 to-transparent transform scale-x-0 group-hover:scale-x-100 transition-transform duration-500 origin-right">
                        </div>
                    </span>

                    <div class="flex items-center space-x-1">
                        <div class="w-1 h-1 bg-red-400 rounded-full"></div>
                        <div class="w-1 h-1 bg-red-300 rounded-full"></div>
                        <div class="w-1 h-1 bg-red-400 rounded-full"></div>
                    </div>

                    <span class="text-sm sm:text-lg font-bold tracking-[0.3em] uppercase text-red-400 relative group">
                        <span class="relative z-10">Accra, Ghana</span>
                        <div
                            class="absolute inset-0 bg-gradient-to-r from-transparent via-red-500/10 to-transparent transform scale-x-0 group-hover:scale-x-100 transition-transform duration-500 origin-center">
                        </div>
                    </span>
                </div>

                <!-- Right decorative element -->
                <div class="hidden sm:flex items-center space-x-2 ml-6">
                    <div class="w-2 h-2 bg-red-400 rounded-full animate-pulse delay-150"></div>
                    <div class="w-1 h-1 bg-red-300 rounded-full animate-pulse delay-75"></div>
                    <div class="w-2 h-2 bg-red-400 rounded-full animate-pulse"></div>
                </div>
            </div>

            <!-- Subtle animated background pattern -->
            <div class="absolute inset-0 opacity-5">
                <div class="absolute inset-0 bg-gradient-to-r from-red-400 via-transparent to-red-400 animate-pulse">
                </div>
            </div>
        </div>

        <!-- Main title section -->
        <div class="relative px-4 sm:px-6 py-12 sm:py-16 text-center">
            <h2
                class="font-black text-[clamp(3.5rem,10vw,8rem)] sm:text-[clamp(3.5rem,12vw,8rem)] leading-[0.85] tracking-tight text-red-400 drop-shadow-lg">
                <span class="block">THE</span>
                <span class="block">ROASTER GRILL</span>
            </h2>
        </div>

        <!-- Contact information - prominently placed after title -->
        <div class="px-4 sm:px-6 py-8 sm:py-10 lg:py-14 text-center border-b border-red-500/30">
            <div class="max-w-5xl mx-auto">
                <!-- Contact subtext -->
                <div class="mb-8 sm:mb-10 lg:mb-12">
                    <p
                        class="text-lg sm:text-xl lg:text-2xl text-gray-200 leading-relaxed font-medium max-w-3xl mx-auto">
                        Ready to experience the finest flame-kissed pork? Get in touch with us for catering inquiries,
                        event bookings, or to place your order.
                    </p>
                </div>

                <!-- Contact grid -->
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6 sm:gap-8 lg:gap-12 items-center max-w-4xl mx-auto">
                    <!-- Phone -->
                    <div class="flex flex-col items-center md:items-start space-y-2 sm:space-y-3">
                        <div class="text-center md:text-left">
                            <p class="text-sm sm:text-md uppercase tracking-wider text-red-300 font-medium">Phone</p>
                            <a :href="phoneHref"
                                class="text-2xl sm:text-3xl lg:text-4xl font-semibold text-white hover:text-red-200 transition-colors duration-300 block break-words">
                                {{ props.phone }}
                            </a>
                        </div>
                    </div>

                    <!-- Email -->
                    <div class="flex flex-col items-center md:items-end space-y-2 sm:space-y-3">
                        <div class="text-center md:text-right">
                            <p class="text-sm sm:text-md uppercase tracking-wider text-red-300 font-medium">Email</p>
                            <a :href="emailHref"
                                class="text-2xl sm:text-3xl lg:text-4xl font-semibold text-white hover:text-red-200 transition-colors duration-300 block break-words">
                                {{ props.email }}
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Brand messaging section -->
        <div class="px-4 sm:px-6 py-8 text-center">
            <div class="max-w-4xl mx-auto">
                <p class="text-sm text-gray-100 leading-relaxed sm:leading-loose font-medium mb-6 px-2">
                    "Flame‑kissed, fresh, and fast. Premium pork sourcing and open-flame roasting - succulent, tender,
                    smoky results for weddings, corporate events, and home meals."
                </p>
            </div>
        </div>

        <!-- Information columns -->
        <div class="px-4 sm:px-6 py-8 sm:py-8">
            <div
                class="max-w-5xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-6 sm:gap-8 md:gap-12 text-sm tracking-[0.15em] uppercase">
                <div class="space-y-3 sm:space-y-4 text-center md:text-left">
                    <div
                        class="text-red-300 hover:text-red-200 transition-colors duration-300 cursor-pointer hover:scale-105">
                        TERMS &amp; CONDITIONS</div>
                </div>
                <div class="space-y-3 sm:space-y-4 text-center md:text-right">
                    <div class="text-xs font-medium text-red-300/80">
                        © {{ new Date().getFullYear() }} THE ROASTER GRILL
                    </div>
                </div>
            </div>
        </div>

        <!-- Social icons -->
        <div class="px-4 sm:px-6 pb-16 sm:pb-24">
            <div class="max-w-2xl mx-auto text-center">
                <!-- Icons container with minimal design -->
                <div class="flex items-center justify-center gap-4 sm:gap-6">
                    <!-- Instagram -->
                    <a :href="props.instagram" target="_blank" rel="noopener" aria-label="Instagram" class="group">
                        <div
                            class="size-8 sm:size-10 rounded-lg bg-gradient-to-br from-pink-500 via-purple-500 to-orange-500 p-[1.5px] hover:scale-105 transition-all duration-300">
                            <div class="w-full h-full rounded-lg bg-black flex items-center justify-center">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                                    class="bi bi-instagram size-4 sm:size-5 text-white" viewBox="0 0 16 16">
                                    <path
                                        d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.9 3.9 0 0 0-1.417.923A3.9 3.9 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.9 3.9 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.9 3.9 0 0 0-.923-1.417A3.9 3.9 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599s.453.546.598.92c.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.5 2.5 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.5 2.5 0 0 1-.92-.598 2.5 2.5 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233s.008-2.388.046-3.231c.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92s.546-.453.92-.598c.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92m-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217m0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334" />
                                </svg>
                            </div>
                        </div>
                    </a>

                    <!-- TikTok -->
                    <a href="https://tiktok.com/@theroastergrill" target="_blank" rel="noopener" aria-label="TikTok"
                        class="group">
                        <div
                            class="size-8 sm:size-10 rounded-lg bg-gradient-to-br from-gray-700 via-gray-800 to-gray-900 p-[1.5px] hover:scale-105 transition-all duration-300">
                            <div class="w-full h-full rounded-lg bg-black flex items-center justify-center">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                                    class="bi bi-tiktok size-4 sm:size-5 text-white" viewBox="0 0 16 16">
                                    <path
                                        d="M9 0h1.98c.144.715.54 1.617 1.235 2.512C12.895 3.389 13.797 4 15 4v2c-1.753 0-3.07-.814-4-1.829V11a5 5 0 1 1-5-5v2a3 3 0 1 0 3 3z" />
                                </svg>
                            </div>
                        </div>
                    </a>

                    <!-- Snapchat -->
                    <a href="https://snapchat.com/add/theroastergrill" target="_blank" rel="noopener"
                        aria-label="Snapchat" class="group">
                        <div
                            class="size-8 sm:size-10 rounded-lg bg-gradient-to-br from-yellow-400 to-yellow-500 p-[1.5px] hover:scale-105 transition-all duration-300">
                            <div class="w-full h-full rounded-lg bg-black flex items-center justify-center">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                                    class="bi bi-snapchat size-4 sm:size-5 text-white" viewBox="0 0 16 16">
                                    <path
                                        d="M15.943 11.526c-.111-.303-.323-.465-.564-.599a1 1 0 0 0-.123-.064l-.219-.111c-.752-.399-1.339-.902-1.746-1.498a3.4 3.4 0 0 1-.3-.531c-.034-.1-.032-.156-.008-.207a.3.3 0 0 1 .097-.1c.129-.086.262-.173.352-.231.162-.104.289-.187.371-.245.309-.216.525-.446.66-.702a1.4 1.4 0 0 0 .069-1.16c-.205-.538-.713-.872-1.329-.872a1.8 1.8 0 0 0-.487.065c.006-.368-.002-.757-.035-1.139-.116-1.344-.587-2.048-1.077-2.61a4.3 4.3 0 0 0-1.095-.881C9.764.216 8.92 0 7.999 0s-1.76.216-2.505.641c-.412.232-.782.53-1.097.883-.49.562-.96 1.267-1.077 2.61-.033.382-.04.772-.036 1.138a1.8 1.8 0 0 0-.487-.065c-.615 0-1.124.335-1.328.873a1.4 1.4 0 0 0 .067 1.161c.136.256.352.486.66.701.082.058.21.14.371.246l.339.221a.4.4 0 0 1 .109.11c.026.053.027.11-.012.217a3.4 3.4 0 0 1-.295.52c-.398.583-.968 1.077-1.696 1.472-.385.204-.786.34-.955.8-.128.348-.044.743.28 1.075q.18.189.409.31a4.4 4.4 0 0 0 1 .4.7.7 0 0 1 .202.09c.118.104.102.26.259.488q.12.178.296.3c.33.229.701.243 1.095.258.355.014.758.03 1.217.18.19.064.389.186.618.328.55.338 1.305.802 2.566.802 1.262 0 2.02-.466 2.576-.806.227-.14.424-.26.609-.321.46-.152.863-.168 1.218-.181.393-.015.764-.03 1.095-.258a1.14 1.14 0 0 0 .336-.368c.114-.192.11-.327.217-.42a.6.6 0 0 1 .19-.087 4.5 4.5 0 0 0 1.014-.404c.16-.087.306-.2.429-.336l.004-.005c.304-.325.38-.709.256-1.047m-1.121.602c-.684.378-1.139.337-1.493.565-.3.193-.122.61-.34.76-.269.186-1.061-.012-2.085.326-.845.279-1.384 1.082-2.903 1.082s-2.045-.801-2.904-1.084c-1.022-.338-1.816-.14-2.084-.325-.218-.15-.041-.568-.341-.761-.354-.228-.809-.187-1.492-.563-.436-.24-.189-.39-.044-.46 2.478-1.199 2.873-3.05 2.89-3.188.022-.166.045-.297-.138-.466-.177-.164-.962-.65-1.18-.802-.36-.252-.52-.503-.402-.812.082-.214.281-.295.49-.295a1 1 0 0 1 .197.022c.396.086.78.285 1.002.338q.04.01.082.011c.118 0 .16-.06.152-.195-.026-.433-.087-1.277-.019-2.066.094-1.084.444-1.622.859-2.097.2-.229 1.137-1.22 2.93-1.22 1.792 0 2.732.987 2.931 1.215.416.475.766 1.013.859 2.098.068.788.009 1.632-.019 2.065-.01.142.034.195.152.195a.4.4 0 0 0 .082-.01c.222-.054.607-.253 1.002-.338a1 1 0 0 1 .197-.023c.21 0 .409.082.49.295.117.309-.04.56-.401.812-.218.152-1.003.638-1.18.802-.184.169-.16.3-.139.466.018.14.413 1.991 2.89 3.189.147.073.394.222-.041.464" />
                                </svg>
                            </div>
                        </div>
                    </a>

                    <!-- Whatsapp -->
                    <a href="https://wa.me/233540000000" target="_blank" rel="noopener" aria-label="Whatsapp"
                        class="group">
                        <div
                            class="size-8 sm:size-10 rounded-lg bg-gradient-to-br from-green-500 to-green-600 p-[1.5px] hover:scale-105 transition-all duration-300">
                            <div class="w-full h-full rounded-lg bg-black flex items-center justify-center">
                                <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                                    class="bi bi-whatsapp" viewBox="0 0 16 16">
                                    <path
                                        d="M13.601 2.326A7.85 7.85 0 0 0 7.994 0C3.627 0 .068 3.558.064 7.926c0 1.399.366 2.76 1.057 3.965L0 16l4.204-1.102a7.9 7.9 0 0 0 3.79.965h.004c4.368 0 7.926-3.558 7.93-7.93A7.9 7.9 0 0 0 13.6 2.326zM7.994 14.521a6.6 6.6 0 0 1-3.356-.92l-.24-.144-2.494.654.666-2.433-.156-.251a6.56 6.56 0 0 1-1.007-3.505c0-3.626 2.957-6.584 6.591-6.584a6.56 6.56 0 0 1 4.66 1.931 6.56 6.56 0 0 1 1.928 4.66c-.004 3.639-2.961 6.592-6.592 6.592m3.615-4.934c-.197-.099-1.17-.578-1.353-.646-.182-.065-.315-.099-.445.099-.133.197-.513.646-.627.775-.114.133-.232.148-.43.05-.197-.1-.836-.308-1.592-.985-.59-.525-.985-1.175-1.103-1.372-.114-.198-.011-.304.088-.403.087-.088.197-.232.296-.346.1-.114.133-.198.198-.33.065-.134.034-.248-.015-.347-.05-.099-.445-1.076-.612-1.47-.16-.389-.323-.335-.445-.34-.114-.007-.247-.007-.38-.007a.73.73 0 0 0-.529.247c-.182.198-.691.677-.691 1.654s.71 1.916.81 2.049c.098.133 1.394 2.132 3.383 2.992.47.205.84.326 1.129.418.475.152.904.129 1.246.08.38-.058 1.171-.48 1.338-.943.164-.464.164-.86.114-.943-.049-.084-.182-.133-.38-.232" />
                                </svg>
                            </div>
                        </div>
                    </a>
                </div>
            </div>
        </div>
        <!-- Subtle texture overlay -->
        <div
            class="absolute inset-0 bg-[radial-gradient(circle_at_50%_50%,rgba(239,68,68,0.05)_0%,transparent_50%)] pointer-events-none">
        </div>
    </footer>
</template>
