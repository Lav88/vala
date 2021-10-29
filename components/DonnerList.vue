<template>
    <div class="donners-info">
        <h3>Unsere Sponsoren</h3>
        <div class="donners-item">
            <div class="donner-item" v-for="(donner, index) in donnerList" :key="index">
                <img :src="donner.imgSrc" :alt="donner.alt">
            </div>
            <div class="donner-item donner-number">+183</div>
        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                donnerList: [
                    {
                        imgSrc: "/images/photos/doner1.png",
                        alt: "image"
                    },
                    {
                        imgSrc: "/images/photos/doner1.png",
                        alt: "image"
                    },
                    {
                        imgSrc: "/images/photos/doner1.png",
                        alt: "image"
                    },
                    {
                        imgSrc: "/images/photos/doner1.png",
                        alt: "image"
                    },
                    {
                        imgSrc: "/images/photos/doner1.png",
                        alt: "image"
                    },
                    {
                        imgSrc: "/images/photos/doner1.png",
                        alt: "image"
                    },
                    {
                        imgSrc: "/images/photos/doner1.png",
                        alt: "image"
                    },
                    {
                        imgSrc: "/images/photos/doner1.png",
                        alt: "image"
                    },
                    {
                        imgSrc: "/images/photos/doner1.png",
                        alt: "image"
                    },
                    {
                        imgSrc: "/images/photos/doner1.png",
                        alt: "image"
                    },
                    {
                        imgSrc: "/images/photos/doner1.png",
                        alt: "image"
                    },
                    {
                        imgSrc: "/images/photos/doner1.png",
                        alt: "image"
                    },
                    {
                        imgSrc: "/images/photos/doner1.png",
                        alt: "image"
                    },
                ]
            }
        },
    };
</script>