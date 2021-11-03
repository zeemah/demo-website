<template>
     <main class="bg-white font-montserrat">
        <header class="h-24 sm:h-32 flex items-center">
            <div class="container mx-auto px-6 sm:px-12 flex items-center justify-between">
                <div class="text-black font-black text-2xl flex items-center">
                    <NuxtLink to="#home" class="w-6 h-6 rounded-full bg-green-300 mr-4">  </NuxtLink>Techy Inc.
                </div>
                <div class="flex items-center">
                    <nav class="text-black text-lg hidden lg:flex items-center">
                        <NuxtLink to="#home" class="py-2 px-6 flex hover:text-green-600">
                            Home
                        </NuxtLink>
                        <NuxtLink to="#about" class="py-2 px-6 flex hover:text-green-600">
                            About us
                        </NuxtLink>
                        <NuxtLink to="#team" class="py-2 px-6 flex hover:text-green-600">
                            Our Team
                        </NuxtLink>
                        <NuxtLink to="#services" class="py-2 px-6 flex hover:text-green-600">
                            Services
                        </NuxtLink>
                        <NuxtLink to="#contact" class="py-2 px-6 flex hover:text-green-600">
                            Contact us
                        </NuxtLink>
                        <NuxtLink to="#newsletter" class="py-2 px-6 flex hover:text-green-600">
                            Newsletter
                        </NuxtLink>
                    </nav>
                    <button class="lg:hidden flex flex-col">
                        <span class="w-6 h-px bg-gray-900 mb-1"></span>
                        <span class="w-6 h-px bg-gray-900 mb-1"></span>
                        <span class="w-6 h-px bg-gray-900 mb-1"></span>
                    </button>
                </div>
            </div>
        </header>
    </main>
</template>
