<template>
    <div>
        <PageHeader title="Contact Page" />

        <div class="font-bold text-2xl text-center"> 
            <p> Social Media Links</p>
            <p>
                <a href="https://www.Patreon.com/CrownWalker" target="_blank" class="text-blue-500 hover:underline">Patreon</a>
            </p>
            <p>
                <a href="https://github.com/CrownWalker1/class-nuxt" target="_blank" class="text-blue-500 hover:underline">GitHub</a>
            </p>
            <p>
                <a href="https://makerworld.com/en/@CrownWalker" target="_blank" class="text-blue-500 hover:underline">MakerWorld</a>
            </p>
            <p>
                <a href="https://understand.me/benson" target="_blank" class="text-blue-500 hover:underline">Understand.Me</a>
            </p>
        </div>

        <ContactForm />

        <div>
            <footer>
                <p class="text-center text-gray-500 italic"> For business inquiries please contact me at MuffinManEatsMuffins@gmail.com</p>
            </footer>
        </div>
    </div>
</template>

<script>
import ContactForm from '~/components/ContactForm.vue';

export default {
    components: {
        ContactForm,
    },
};
</script>

<style>
/* Optional: Add custom styles here if needed */
</style>