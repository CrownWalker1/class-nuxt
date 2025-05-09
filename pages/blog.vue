<template>
    <div>
        <PageHeader title="Blog Page" />
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 p-6">
            <BlogPostCard
                title="Post Title 1"
                publishedDate="May 6, 2025"
                description="This is a short description or excerpt of the first blog post. It gives readers an idea of what the post is about."
                link="/blogpost-1"
                postedDate="5/5/2025"
            />
            <BlogPostCard
                title="Post Title 2"
                publishedDate="May 5, 2025"
                description="This is a short description or excerpt of the second blog post. It gives readers an idea of what the post is about."
                link="/blogpost-2"
                postedDate="5/5/2025"
            />
            <BlogPostCard
                title="Post Title 3"
                publishedDate="May 4, 2025"
                description="This is a short description or excerpt of the third blog post. It gives readers an idea of what the post is about."
                link="/blogpost-3"
                postedDate="5/5/2025"
            />
        </div>
    </div>
</template>

<script>
import BlogPostCard from '~/components/BlogPostCard.vue';

export default {
    components: {
        BlogPostCard,
    },
};
</script>