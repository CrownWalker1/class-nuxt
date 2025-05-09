<template>
    <a
        :href="link"
        class="text-red-500 hover:underline whitespace-nowrap bg-gray-700 hover:bg-gray-600 py-2 rounded px-10 inline-block text-center"
    >
        <slot>Click Here</slot>
    </a>
</template>

<script>
export default {
    props: {
        link: {
            type: String,
            required: true,
        },
    },
};
</script>

<style scoped>
/* Add any custom styles here if needed */
</style>