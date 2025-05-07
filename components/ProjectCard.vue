<template>
    <div class="p-4 rounded-lg shadow-md">
        <h2 class="text-xl font-bold">{{ title }}</h2>
        <p><img class="pt-2" :src="image" :alt="title" /></p>
        <p class="mt-2">{{ description }}</p>
        <p>If you want to go check this model out for yourself, here is the link:</p>
        <a :href="link" target="_blank" class="text-blue-500 hover:underline">{{ linkText }}</a>
    </div>
</template>

<script>
export default {
    props: {
        title: {
            type: String,
            required: true,
        },
        image: {
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
        linkText: {
            type: String,
            required: true,
        },
    },
};
</script>

<style scoped>
/* Add any specific styles for the card here if needed */
</style>