<template>
    <nav>
            <div class="flex py-8 px-4 lg:px-8 justify-between items-center">
            <a class="text-2xl text-gray-900 font-bold" href="#">
                <img class="h-7" src="zospace-assets/logos/zospace-dark-logo.svg" alt="" width="auto">
            </a>
            <div class="lg:hidden ml-auto">
                <button class="navbar-burger flex items-center p-3 hover:bg-gray-50 text-gray-900 rounded">
                <svg class="w-10 h-3" width="39" height="13" viewBox="0 0 39 13" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <rect width="39" height="2" rx="1" fill="currentColor"></rect><rect x="19" y="11" width="20" height="2" rx="1" fill="currentColor"></rect>
                    <title>Mobile menu</title>
                </svg>
                </button>
            </div>
            <div class="hidden lg:block ml-auto mr-16">
                <ul class="flex items-center space-x-16 text-lg font-bold">
                <li><a class="hover:underline" href="#">Product</a></li>
                <li><a class="hover:underline" href="#">Story</a></li>
                <li><a class="hover:underline" href="#">Features</a></li>
                <li><a class="hover:underline" href="#">Contact</a></li>
                </ul>
            </div>
            <div class="hidden lg:block"><a class="inline-block px-12 py-4 text-white font-bold bg-black border border-black hover:bg-white hover:text-black rounded-full transition duration-200" href="#">Sign Up</a></div>
            </div>
        </nav>
</template>

<script>
    export default {
        
    }
</script>

<style lang="scss" scoped>

</style>