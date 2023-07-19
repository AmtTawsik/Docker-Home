<template>
    <div class="w-11/12 mx-auto mt-10">
        <section>
            <div class="flex justify-center">
                <button class="rounded-full border border-purple-600 text-purple-600 px-5 py-1.5">
                    TESTIMONY
                </button>
            </div>
            <h2 class="md:text-5xl text-3xl text-center my-4">What our customers say</h2>
            <p class="text-center text-gray-900">Join hundreds of all sizes and across all</p>
            <p class="text-center text-gray-900">industries have made a big improvements</p>
            <p class="text-center text-gray-900 md:mb-5">with us.</p>
        </section>
        <section>
            <div class="hidden md:block">
                <Carousel :items-to-show="2.5" :wrap-around="true">
                    <Slide v-for="(card, index) in cards" :key="index">
                        <div
                            class="block p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700">
                            <img class="w-1/3" :src="card.link" alt="">
                            <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 text-left dark:text-white">{{
                                card.title }}
                            </h5>
                            <p class="font-normal text-gray-700 text-xl dark:text-gray-400 text-left">{{ card.description }}
                            </p>
                            <h5 class="font-bold mt-3 text-left text-lg">{{ card.name }}</h5>
                            <p class="text-sm text-gray-600 text-left">{{ card.deg }}</p>
                        </div>
                    </Slide>

                    <template #addons>
                        <!-- <Navigation /> -->
                        <Pagination />
                    </template>
                </Carousel>
            </div>
            <div class="md:hidden">
                <Carousel>
                    <Slide v-for="(card, index) in cards" :key="index">
                        <div
                            class="block p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700">
                            <img class="w-1/3" :src="card.link" alt="">
                            <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 text-left dark:text-white">{{
                                card.title }}
                            </h5>
                            <p class="font-normal text-gray-700 text-xl dark:text-gray-400 text-left">{{ card.description }}
                            </p>
                            <h5 class="font-bold mt-3 text-left text-lg">{{ card.name }}</h5>
                            <p class="text-sm text-gray-600 text-left">{{ card.deg }}</p>
                        </div>
                    </Slide>

                    <template #addons>
                        <Navigation />
                        <!-- <Pagination /> -->
                    </template>
                </Carousel>
            </div>
        </section>
    </div>
</template>
  
<script>
import { defineComponent } from 'vue'
import { Carousel, Navigation, Pagination, Slide } from 'vue3-carousel'

import 'vue3-carousel/dist/carousel.css'

export default defineComponent({
    name: 'WrapAround',
    components: {
        Carousel,
        Slide,
        Navigation,
        Pagination,
    },

    data() {
        return {
            cards: [
                {
                    link: 'https://i.ibb.co/MVVmkrr/Derbi.png',
                    title: 'Derbi',
                    name: 'John Wiliam',
                    deg: 'Project Manager',
                    description: '"Success to resolve my issue quickly and efficiently, and their friendly and helpful made the experience even better."',
                },
                {
                    link: 'https://i.ibb.co/Pw3hg3y/Yahoo.png',
                    title: 'Yahoo',
                    name: 'Fahim Quarishi',
                    deg: 'Diractor',
                    description: 'Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.',
                },
                {
                    link: 'https://i.ibb.co/NN0PMRZ/Puma.png',
                    title: 'Puma',
                    name: 'Ibrahim Nur',
                    deg: 'Project Manager',
                    description: 'Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.',
                },

                {
                    link: 'https://i.ibb.co/C6gHLq5/ChatGPT.png',
                    title: 'ChatGPT',
                    name: 'Critive Diractor',
                    deg: 'Project Manager',
                    description: 'Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.',
                },
                {
                    link: 'https://i.ibb.co/QfT5dFJ/CNET.png',
                    title: 'CNET',
                    name: 'Ariana Grande',
                    deg: 'Project Manager',
                    description: 'Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.',
                },
            ],
        }
    },
})
</script>
  
<style>
.carousel__slide {
    padding: 20px;
}

.carousel__prev,
.carousel__next {
    box-sizing: content-box;
    /* border: 5px solid white; */
}
</style>
