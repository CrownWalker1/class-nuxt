<template>
    <div class="max-w-2xl mx-auto p-6 bg-indigo-500 shadow-md rounded-lg">
        <h2 class="text-2xl font-bold mb-4 text-center">Contact Me Directly</h2>
        <form @submit.prevent="handleSubmit">
            <!-- First Name -->
            <div class="mb-4">
                <label for="firstName" class="block text-gray-700 font-medium mb-2">First Name</label>
                <input
                    type="text"
                    id="firstName"
                    v-model="form.firstName"
                    class="w-full p-3 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500"
                    placeholder="Enter your first name here"
                    required
                />
            </div>

            <!-- Last Name -->
            <div class="mb-4">
                <label for="lastName" class="block text-gray-700 font-medium mb-2">Last Name</label>
                <input
                    type="text"
                    id="lastName"
                    v-model="form.lastName"
                    class="w-full p-3 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500"
                    placeholder="Enter your last name here"
                    required
                />
            </div>

            <!-- Email Address -->
            <div class="mb-4">
                <label for="email" class="block text-gray-700 font-medium mb-2">Email Address</label>
                <input
                    type="email"
                    id="email"
                    v-model="form.email"
                    class="w-full p-3 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500"
                    placeholder="Enter your email address here"
                    required
                />
            </div>

            <!-- Phone Number -->
            <div class="mb-4">
                <label for="phone" class="block text-gray-700 font-medium mb-2">Phone Number (Optional)</label>
                <input
                    type="tel"
                    id="phone"
                    v-model="form.phone"
                    class="w-full p-3 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500"
                    placeholder="Enter your phone number here"
                />
            </div>

            <!-- Subject -->
            <div class="mb-4">
                <label for="subject" class="block text-gray-700 font-medium mb-2">Subject</label>
                <input
                    type="text"
                    id="subject"
                    v-model="form.subject"
                    class="w-full p-3 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500"
                    placeholder="Enter the subject of your reason for contacting us here"
                    required
                />
            </div>

            <!-- Message -->
            <div class="mb-4">
                <label for="message" class="block text-gray-700 font-medium mb-2">Message</label>
                <textarea
                    id="message"
                    v-model="form.message"
                    rows="5"
                    class="w-full p-3 border rounded-lg focus:outline-none focus:ring-2 focus:ring-blue-500"
                    placeholder="Type your message here"
                    required
                ></textarea>
            </div>

            <!-- Submit Button -->
            <div class="text-center">
                <button
                    type="submit"
                    class="bg-blue-500 text-white font-bold py-3 px-6 rounded-lg hover:bg-blue-600 focus:outline-none focus:ring-2 focus:ring-blue-500"
                >
                    Contact Us
                </button>
            </div>
        </form>
    </div>
</template>

<script>
export default {
    data() {
        return {
            form: {
                firstName: '',
                lastName: '',
                email: '',
                phone: '',
                subject: '',
                message: '',
            },
        };
    },
    methods: {
        handleSubmit() {
            // Handle form submission logic here
            alert('Your contact request has been submitted!');
            console.log(this.form);
        },
    },
};
</script>

<style scoped>
/* Add any specific styles for the form here if needed */
</style>