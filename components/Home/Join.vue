<template>
    <div class="bg-gray-900 py-10 mt-10 md:mt-20">
        <section class="w-11/12 mx-auto grid grid-cols-12 items-center">
            <div class="md:col-span-6 col-span-12 md:hidden">
                <img :src="right" alt="">
            </div>
            <div class="md:col-span-6 col-span-12 text-white">
                <h2 class="text-3xl md:text-5xl">Join million people who</h2>
                <h2 class="text-3xl md:text-5xl">already trust with us.</h2>

                <p class="md:text-lg text-gray-500 mt-5">Connect the dots between customer needs</p>
                <p class="md:text-lg text-gray-500">and your product delivery workflows.</p>

                <button class="py-2 px-5 rounded-full bg-violet-600 font-bold my-5 hover:bg-violet-700">Open Account
                    ></button>

                <p class="flex items-center"><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor"
                        class="w-5 h-5 text-blue-600 mr-2">
                        <path fill-rule="evenodd"
                            d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.857-9.809a.75.75 0 00-1.214-.882l-3.483 4.79-1.88-1.88a.75.75 0 10-1.06 1.061l2.5 2.5a.75.75 0 001.137-.089l4-5.5z"
                            clip-rule="evenodd" />
                    </svg>
                    Try free for 30 days with no bills.</p>
            </div>
            <div class="md:col-span-6 col-span-12 hidden md:flex">
                <img :src="right" alt="">
            </div>
        </section>
    </div>
</template>

<script setup>
import right from '../../assets/images/Join/right.png'
</script>