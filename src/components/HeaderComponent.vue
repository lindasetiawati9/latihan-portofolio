<script setup>
import { Carousel } from 'flowbite-vue'

const props = defineProps({
    pictures: {
        type: Array,
        default() {
            return [
                {
                    'src': 'https://i.pinimg.com/originals/54/d5/bf/54d5bf82aca91246e02ee3b8a370560c.jpg',
                    'alt': 'Picture 1',
                },
                {
                    'src': 'https://mir-s3-cdn-cf.behance.net/project_modules/hd/e5bac9125679929.611e0281c610a.jpg',
                    'alt': 'Picture 2',
                },
                {
                    'src': 'https://mir-s3-cdn-cf.behance.net/project_modules/hd/f6bfe3125679809.611e01e916803.jpg',
                    'alt': 'Picture 3',
                },
            ]
        },
    },
})

</script>
<template>
  <Carousel :pictures="pictures" :controls="false" :slide-interval="1000"></Carousel>
</template>
