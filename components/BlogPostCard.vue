<template>
    <div class="p-4 border rounded-lg shadow-md">
   
        <h2 class="text-xl font-bold" v-text="title"></h2>

        <p class="text-gray-500 text-sm">
            Published on <span v-text="publishedDate"></span>
        </p>

        <p class="mt-2 text-gray-700" v-text="description"></p>

     
        <div class="flex items-center justify-between mt-4">
            <a :href="link" class="text-blue-500 hover:underline whitespace-nowrap">Read More</a>
            <p class="text-gray-800 whitespace-nowrap" v-text="'Posted: ' + postedDate"></p>
        </div>
    </div>
</template>

<script>
export default {
    props: {
        title: {
            type: String,
            required: true,
        },
        publishedDate: {
            type: String,
            required: true,
        },
        description: {
            type: String,
            required: true,
        },
        link: {
            type: String,
            required: true,
        },
        postedDate: {
            type: String,
            required: true
        } 
    }
}
</script>

<style scoped>
.example-class {
    color: red;
}
</style>
