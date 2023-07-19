<template>
    <div class="w-11/12 mx-auto mt-10 md:mt-20">
        <div class="flex justify-center">
            <button class="rounded-full border border-purple-600 text-purple-600 px-5 py-1.5">
                PRODUCTS
            </button>
        </div>
        <h2 class="md:text-5xl text-3xl text-center my-4">The ultimate product we serve</h2>
        <p class="text-center text-gray-900">With tools to make every part of your process more</p>
        <p class="text-center text-gray-900">human and a support team to help you</p>
        <section class="grid grid-cols-12 mt-10 gap-5 md:gap-0">
            <div class="border p-5 md:col-span-4 col-span-12">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor"
                    class="w-8 h-8 text-blue-600 mb-3">
                    <path d="M1.5 8.67v8.58a3 3 0 003 3h15a3 3 0 003-3V8.67l-8.928 5.493a3 3 0 01-3.144 0L1.5 8.67z" />
                    <path
                        d="M22.5 6.908V6.75a3 3 0 00-3-3h-15a3 3 0 00-3 3v.158l9.714 5.978a1.5 1.5 0 001.572 0L22.5 6.908z" />
                </svg>
                <h5 class="text-lg font-semibold mb-2 text-gray-900">Email Marketing</h5>
                <p class="text-gray-600">Involves sending promotional emails to a</p>
                <p class="text-gray-600">group of people or subscribers.</p>
                <button
                    class="px-5 py-2 mt-5 border rounded-full font-semibold text-sm hover:text-white hover:bg-purple-700">Learn
                    More ></button>
            </div>
            <div class="border p-5 md:col-span-4 col-span-12 flex justify-center">
                <img class="w-2/3" :src="p1" alt="">
            </div>
            <div class="border p-5 md:col-span-4 col-span-12">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-8 h-8 text-blue-600 mb-3">
                    <path fill-rule="evenodd"
                        d="M2.25 4.125c0-1.036.84-1.875 1.875-1.875h5.25c1.036 0 1.875.84 1.875 1.875V17.25a4.5 4.5 0 11-9 0V4.125zm4.5 14.25a1.125 1.125 0 100-2.25 1.125 1.125 0 000 2.25z"
                        clip-rule="evenodd" />
                    <path
                        d="M10.719 21.75h9.156c1.036 0 1.875-.84 1.875-1.875v-5.25c0-1.036-.84-1.875-1.875-1.875h-.14l-8.742 8.743c-.09.089-.18.175-.274.257zM12.738 17.625l6.474-6.474a1.875 1.875 0 000-2.651L15.5 4.787a1.875 1.875 0 00-2.651 0l-.1.099V17.25c0 .126-.003.251-.01.375z" />
                </svg>
                <h5 class="text-lg font-semibold mb-2 text-gray-900">Email Marketing</h5>
                <p class="text-gray-600">Involves sending promotional emails to a</p>
                <p class="text-gray-600">group of people or subscribers.</p>
                <button
                    class="px-5 py-2 mt-5 border rounded-full font-semibold text-sm hover:text-white hover:bg-purple-700">Learn
                    More ></button>
            </div>
            <div class="border p-5 md:col-span-4 col-span-12">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-8 h-8 text-blue-600 mb-3">
                    <path
                        d="M12.75 12.75a.75.75 0 11-1.5 0 .75.75 0 011.5 0zM7.5 15.75a.75.75 0 100-1.5.75.75 0 000 1.5zM8.25 17.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zM9.75 15.75a.75.75 0 100-1.5.75.75 0 000 1.5zM10.5 17.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zM12 15.75a.75.75 0 100-1.5.75.75 0 000 1.5zM12.75 17.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zM14.25 15.75a.75.75 0 100-1.5.75.75 0 000 1.5zM15 17.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zM16.5 15.75a.75.75 0 100-1.5.75.75 0 000 1.5zM15 12.75a.75.75 0 11-1.5 0 .75.75 0 011.5 0zM16.5 13.5a.75.75 0 100-1.5.75.75 0 000 1.5z" />
                    <path fill-rule="evenodd"
                        d="M6.75 2.25A.75.75 0 017.5 3v1.5h9V3A.75.75 0 0118 3v1.5h.75a3 3 0 013 3v11.25a3 3 0 01-3 3H5.25a3 3 0 01-3-3V7.5a3 3 0 013-3H6V3a.75.75 0 01.75-.75zm13.5 9a1.5 1.5 0 00-1.5-1.5H5.25a1.5 1.5 0 00-1.5 1.5v7.5a1.5 1.5 0 001.5 1.5h13.5a1.5 1.5 0 001.5-1.5v-7.5z"
                        clip-rule="evenodd" />
                </svg>
                <h5 class="text-lg font-semibold mb-2 text-gray-900">Email Marketing</h5>
                <p class="text-gray-600">Involves sending promotional emails to a</p>
                <p class="text-gray-600">group of people or subscribers.</p>
                <button
                    class="px-5 py-2 mt-5 border rounded-full font-semibold text-sm hover:text-white hover:bg-purple-700">Learn
                    More ></button>
            </div>
            <div class="border p-5 md:col-span-4 col-span-12">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-8 h-8 text-blue-600 mb-3">
                    <path
                        d="M9.375 3a1.875 1.875 0 000 3.75h1.875v4.5H3.375A1.875 1.875 0 011.5 9.375v-.75c0-1.036.84-1.875 1.875-1.875h3.193A3.375 3.375 0 0112 2.753a3.375 3.375 0 015.432 3.997h3.943c1.035 0 1.875.84 1.875 1.875v.75c0 1.036-.84 1.875-1.875 1.875H12.75v-4.5h1.875a1.875 1.875 0 10-1.875-1.875V6.75h-1.5V4.875C11.25 3.839 10.41 3 9.375 3zM11.25 12.75H3v6.75a2.25 2.25 0 002.25 2.25h6v-9zM12.75 12.75v9h6.75a2.25 2.25 0 002.25-2.25v-6.75h-9z" />
                </svg>
                <h5 class="text-lg font-semibold mb-2 text-gray-900">Email Marketing</h5>
                <p class="text-gray-600">Involves sending promotional emails to a</p>
                <p class="text-gray-600">group of people or subscribers.</p>
                <button
                    class="px-5 py-2 mt-5 border rounded-full font-semibold text-sm hover:text-white hover:bg-purple-700">Learn
                    More ></button>
            </div>
            <div class="border p-5 md:col-span-4 col-span-12">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-8 h-8 text-blue-600 mb-3">
                    <path
                        d="M6.25 6.375a4.125 4.125 0 118.25 0 4.125 4.125 0 01-8.25 0zM3.25 19.125a7.125 7.125 0 0114.25 0v.003l-.001.119a.75.75 0 01-.363.63 13.067 13.067 0 01-6.761 1.873c-2.472 0-4.786-.684-6.76-1.873a.75.75 0 01-.364-.63l-.001-.122zM19.75 7.5a.75.75 0 00-1.5 0v2.25H16a.75.75 0 000 1.5h2.25v2.25a.75.75 0 001.5 0v-2.25H22a.75.75 0 000-1.5h-2.25V7.5z" />
                </svg>
                <h5 class="text-lg font-semibold mb-2 text-gray-900">Email Marketing</h5>
                <p class="text-gray-600">Involves sending promotional emails to a</p>
                <p class="text-gray-600">group of people or subscribers.</p>
                <button
                    class="px-5 py-2 mt-5 border rounded-full font-semibold text-sm hover:text-white hover:bg-purple-700">Learn
                    More ></button>
            </div>
        </section>
    </div>
</template>

<script setup>
import p1 from '../../assets/images/hero4.jpg'
</script>