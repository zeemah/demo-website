<template>
    <!-- <header> -->
    <nav class="flex-shrink-0 border-b-2 border-gray-200 shadow-md">
        <div class="container px-6 py-4 mx-auto">
            <div class="lg:flex lg:items-center lg:justify-between mr-16 ml-28">
                <div class="flex items-center justify-between">
                    <div class="text-xl font-semibold text-gray-700">
                        <NuxtLink class="text-2xl font-bold text-gray-800 dark:text-white lg:text-3xl hover:text-green-700 dark:hover:text-green-300" to="/home">Techy</NuxtLink>
                    </div>

                    <!-- Mobile menu button -->
                    <div class="flex lg:hidden">
                        <button type="button" class="text-gray-500 dark:text-gray-200 hover:text-green-700 dark:hover:text-green-300 focus:outline-none focus:text-gray-600 dark:focus:text-gray-400" aria-label="toggle menu">
                            <svg viewBox="0 0 24 24" class="w-6 h-6 fill-current">
                                <path fill-rule="evenodd" d="M4 5h16a1 1 0 0 1 0 2H4a1 1 0 1 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2zm0 6h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2z"></path>
                            </svg>
                        </button>
                    </div>
                </div>

                <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
                <div class="hidden -mx-4 lg:flex lg:items-center">
                    <NuxtLink to="#Home" class="block mx-4 mt-2 text-sm text-gray-700 capitalize lg:mt-0 dark:text-gray-200 hover:text-green-700 dark:hover:text-green-300">Home</NuxtLink>
                    <NuxtLink to="#About" class="block mx-4 mt-2 text-sm text-gray-700 capitalize lg:mt-0 dark:text-gray-200 hover:text-green-700 dark:hover:text-green-300">About us</NuxtLink>
                    <NuxtLink to="#Team" class="block mx-4 mt-2 text-sm text-gray-700 capitalize lg:mt-0 dark:text-gray-200 hover:text-green-700 dark:hover:text-green-300">Our Team</NuxtLink>
                    <NuxtLink to="#Services" class="block mx-4 mt-2 text-sm text-gray-700 capitalize lg:mt-0 dark:text-gray-200 hover:text-green-700 dark:hover:text-green-300">Services</NuxtLink>
                    <NuxtLink to="#Newsletter" class="block mx-4 mt-2 text-sm text-gray-700 capitalize lg:mt-0 dark:text-gray-200 hover:text-green-700 dark:hover:text-green-300">Newsletter</NuxtLink>
                    <NuxtLink to="#Contact" class="block mx-4 mt-2 text-sm text-gray-700 capitalize lg:mt-0 dark:text-gray-200 hover:text-green-700 dark:hover:text-green-300">Contact us</NuxtLink>
                </div>
            </div>
        </div>
    </nav>
    <!-- </header> -->

    <!-- <div class="w-full bg-center bg-cover h-96" style="background-image: url(https://images.unsplash.com/photo-1504384308090-c894fdcc538d?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80);">
        <div class="flex items-center justify-center w-full h-full bg-gray-900 bg-opacity-50">
            <div class="text-center">
                <h1 class="text-2xl font-semibold text-white uppercase lg:text-3xl">Build Your new <span class="text-blue-400 underline">Saas</span></h1>
                <button class="w-full px-4 py-2 mt-4 text-sm font-medium text-white uppercase transition-colors duration-200 transform bg-blue-600 rounded-md lg:w-auto hover:bg-blue-500 focus:outline-none focus:bg-blue-500">Start project</button>
            </div>
        </div>
    </div> -->

</template>

