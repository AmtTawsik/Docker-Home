<template>
    <div class="md:mt-10">
        <div class="w-full grid grid-cols-12 items-center">
            <div class="md:col-span-3 col-span-12">
                <img :src="hero1" alt="">
            </div>
            <div class="md:col-span-6 col-span-12 text-center">
                <h2 class="md:text-5xl text-2xl font-semibold">Modern marketing tools</h2>
                <h2 class="md:text-5xl text-2xl font-semibold">For <span class="text-blue-600">your business</span></h2>
                <p class="text-lg mt-5">Connect the dots between customer needs</p>
                <p class="text-lg">and your product delivery workows</p>
                <div class="flex justify-center mt-5 items-center">
                    <button type="button"
                        class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:outline-none focus:ring-blue-300 font-medium rounded-full text-sm px-5 py-2 text-center  mr-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800 border border-blue-700">Open Account</button>
                    <button type="button"
                        class="text-gray-900 bg-white border border-gray-300 focus:outline-none hover:bg-gray-100 focus:ring-4 focus:ring-gray-200 font-medium rounded-full text-sm px-5 py-2 dark:bg-gray-800 dark:text-white dark:border-gray-600 dark:hover:bg-gray-700 dark:hover:border-gray-600 dark:focus:ring-gray-700">Learn More</button>
                </div>
            </div>
            <div class="md:col-span-3 col-span-12 text-right">
                <img :src="hero3" alt="">
            </div>
        </div>
        <section class="grid grid-cols-12 justify-center items-center gap-5 w-11/12 mx-auto">
            <div class="md:col-span-2 col-span-6">
                <img :src="p1" alt="">
            </div>
            <div class="md:col-span-2 col-span-6">
                <img :src="p2" alt="">
            </div>
            <div class="md:col-span-2 col-span-6">
                <img :src="p3" alt="">
            </div>
            <div class="md:col-span-2 col-span-6">
                <img :src="p5" alt="">
            </div>
            <div class="md:col-span-2 col-span-6">
                <img :src="p2" alt="">
            </div>
            <div class="md:col-span-2 col-span-6">
                <img :src="p4" alt="">
            </div>
            
        </section>
    </div>
</template>

<script setup>
import hero1 from '../../assets/images/hero1.svg'
import hero3 from '../../assets/images/hero3.svg'

import p1 from '../../assets/images/Brands/ChatGPT.png'
import p2 from '../../assets/images/Brands/CNET.png'
import p3 from '../../assets/images/Brands/Derbi.png'
import p4 from '../../assets/images/Brands/Puma.png'
import p5 from '../../assets/images/Brands/Yahoo.png'
</script>