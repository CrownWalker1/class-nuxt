<template>
    <section
        class="bg-cover h-96 bg-no-repeat rounded-xl overflow-hidden"
        style="
            background-image: url('https://images.unsplash.com/photo-1741761446510-7804410eade3?q=80&w=1750&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');
        "
    >
        <article
            class="bg-gray-800/50 h-full w-full flex flex-col p-16 items-center text-white text-center justify-center"
        >
            <h1 class="text-4xl font-bold">CWC Custom Designs</h1>
            <h2>3D Models of All Varieties</h2>

            <div class="w-full mt-4 pt-40">
                <h3>
                    <CallToActionButton link="http://localhost:3000/projects">
                        Click Here to See My Models
                    </CallToActionButton>
                </h3>
            </div>
        </article>
    </section>
</template>

<script>
import CallToActionButton from '~/components/CallToActionButton.vue';

export default {
    components: {
        CallToActionButton,
    },
};
</script>