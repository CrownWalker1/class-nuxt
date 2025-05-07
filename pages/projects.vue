<template>
    <div>
        <PageHeader title="Projects Page" />
        <div class="grid grid-cols-4 gap-4 p-4">
            <ProjectCard
                title="Planetary Fidget Spinner"
                image="\ezgif.com.crop (2).gif"
                description="This is similar to an everyday fidget spinner you would see at the store. However, this one is made to perfectly fit the average size fingertip & be child safe! There are no sharp edges on this design. I even made the inner gear portions angled in such a way that you can't really get your fingers crimped in them."
                link="https://makerworld.com/en/models/530921-planetary-gear-spinner-fidget-toy-v4-5-smooth-ring#profileId-447733"
                linkText="Planetary Fidget Spinner"
            />
            <ProjectCard
                title="Hexagonal Helix Fidget Toy"
                image="\ezgif.com.crop (5).gif"
                description="This is my most popular design. It's two pieces that pass through each other seamlessly and provide a really fun illusion."
                link="https://makerworld.com/en/models/550623-spiral-helix-fidget-toy-v4-hexagonal#profileId-469006"
                linkText="Hexagonal Helix Fidget Toy"
            />
            <ProjectCard
                title="Circular Fidget Toy"
                image="\ezgif.com.crop (4).gif"
                description="This is an earlier iteration of my fidget toy. However, I still really like this one. It is also a helix toy, where the two pieces pass through each other seamlessly. However, this one is much smaller than all of my other toys, so it's easier to keep it on your desk."
                link="https://makerworld.com/en/models/548712-spiral-helix-fidget-toy-v2-5-mini#profileId-466897"
                linkText="Circular Fidget Toy"
            />
            <ProjectCard
                title="Pyramid Puzzle"
                image="\IMG_2665.jpg"
                description="This project was extremely fun for me. I'm still newish to making puzzles, but I'm proud of how this one turned out. It's as described, a pyramid that I turned into a puzzle. It's not meant to be a hard puzzle. It is meant to serve as both a puzzle and a showpiece for your desk."
                link="https://makerworld.com/en/models/554331-3d-pyramid-puzzle-illusion-fidget-toy-100x100#profileId-472958"
                linkText="Pyramid Puzzle"
            />
        </div>
    </div>
</template>

<script>
import ProjectCard from '~/components/ProjectCard.vue';

export default {
    components: {
        ProjectCard,
    },
};
</script>