<template>
    <!-- <header> -->
    <nav class="flex-shrink-0 border-b-2 border-gray-200 shadow-md">
        <div class="container px-6 py-4 mx-auto" >
            <div class="lg:flex lg:items-center lg:justify-between mr-16 ml-28">
                <div class="flex items-center justify-between">
                    <div class="text-xl font-semibold text-gray-700">
                        <NuxtLink class="text-2xl font-bold text-gray-800 dark:text-white lg:text-3xl hover:text-green-700 dark:hover:text-green-300" to="/home">Techy</NuxtLink>
                    </div>

                    <!-- Mobile menu button -->
                    <div class="flex lg:hidden" x-data="{isOpen : false}">
                        <button type="button"  @click="isOpen = !isOpen" class="text-gray-500 dark:text-gray-200 hover:text-green-700 dark:hover:text-green-300 focus:outline-none focus:text-gray-600 dark:focus:text-gray-400" aria-label="toggle menu">
                            <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current">
                                <path fill-rule="evenodd" d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"></path>
                            </svg>
                        </button>
                    </div>
                </div>

                <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
                <div class="hidden -mx-4 lg:flex lg:items-center"  :class="isOpen ? '' : 'hidden'">
                    <NuxtLink to="#Home" id="Home" class="block mx-4 mt-2 text-sm text-gray-700 capitalize lg:mt-0 dark:text-gray-200 hover:text-green-700 dark:hover:text-green-300">Home</NuxtLink>
                    <NuxtLink to="#About" id="About" class="block mx-4 mt-2 text-sm text-gray-700 capitalize lg:mt-0 dark:text-gray-200 hover:text-green-700 dark:hover:text-green-300">About us</NuxtLink>
                    <NuxtLink to="#Team" id="Team" class="block mx-4 mt-2 text-sm text-gray-700 capitalize lg:mt-0 dark:text-gray-200 hover:text-green-700 dark:hover:text-green-300">Our Team</NuxtLink>
                    <NuxtLink to="#Services" id="Services" class="block mx-4 mt-2 text-sm text-gray-700 capitalize lg:mt-0 dark:text-gray-200 hover:text-green-700 dark:hover:text-green-300">Services</NuxtLink>
                    <NuxtLink to="#Newsletter" id="Newsletter" class="block mx-4 mt-2 text-sm text-gray-700 capitalize lg:mt-0 dark:text-gray-200 hover:text-green-700 dark:hover:text-green-300">Newsletter</NuxtLink>
                    <NuxtLink to="#Contact" id="Contact" class="block mx-4 mt-2 text-sm text-gray-700 capitalize lg:mt-0 dark:text-gray-200 hover:text-green-700 dark:hover:text-green-300">Contact us</NuxtLink>
                </div>
            </div>
        </div>
    </nav>
    <!-- </header> -->

</template>
