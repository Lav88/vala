<template>
    <section class="events-area events-default-area">
        <div class="container">
            <div class="row">
                <div class="col-lg-8">
                    <div class="section-title" data-aos="fade-up" data-aos-duration="1000">
                        <h5 class="subtitle line-theme-color mb-7">Recent Events</h5>
                        <h2 class="title title-style">
                            See All VALA Events &amp; Projects. 
                            <img class="img-shape" src="/images/shape/3.png" alt="Image">
                        </h2>
                    </div>
                    <div class="events-content events-list" data-aos="fade-up" data-aos-duration="1000">
                        <div class="event-item">
                            <div class="thumb">
                                <img class="thumb-img" src="/images/events/1.png" alt="Image">
                                <n-link to="/event-details" class="btn-theme btn-gradient btn-size-sm">
                                    Join Now 
                                    <img class="icon icon-img" src="/images/icons/arrow-line-right.png" alt="Icon">
                                </n-link>
                            </div>
                            <div class="content">
                                <div class="event-info">15 Oktober 2021  // <span>Familienfest</span></div>
                                <h4 class="event-name">
                                    <n-link to="/event-details">Familienfest WAKA WAKA</n-link>
                                </h4>
                            </div>
                        </div>
                        <div class="event-item">
                            <div class="thumb">
                                <img class="thumb-img" src="/images/events/2.png" alt="Image">
                                <n-link to="/event-details" class="btn-theme btn-gradient btn-size-sm">
                                    Join Now 
                                    <img class="icon icon-img" src="/images/icons/arrow-line-right.png" alt="Icon">
                                </n-link>
                            </div>
                            <div class="content">
                                <div class="event-info">15 January 2022  // <span>Sport</span></div>
                                <h4 class="event-name">
                                    <n-link to="/event-details">FC VALA Afrika League</n-link>
                                </h4>
                            </div>
                        </div>
                        <div class="event-item">
                            <div class="thumb">
                                <img class="thumb-img" src="/images/events/3.png" alt="Image">
                                <n-link to="/event-details" class="btn-theme btn-gradient btn-size-sm">
                                    Join Now 
                                    <img class="icon icon-img" src="/images/icons/arrow-line-right.png" alt="Icon">
                                </n-link>
                            </div>
                            <div class="content">
                                <div class="event-info">21 März 2022  // <span>Education</span></div>
                                <h4 class="event-name">
                                    <n-link to="/event-details">Internationale Wochen gegen Rassismus.</n-link>
                                </h4>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-8 offset-2 col-sm-8 offset-sm-2 col-md-8 offset-md-2 col-lg-4 offset-lg-0">
                    <div class="layer-style">
                        <div class="thumb tilt-animation">
                            <img src="/images/photos/event1.png" alt="Image">
                            <CoolLightBox 
                                :items="items" 
                                :index="index"
                                @close="index = null">
                            </CoolLightBox>
                            <div class="play-video-btn">
                                <a class="btn-play play-video-popup wave-btn" href="javascript:void(0)" @click="index = imageIndex" v-for="(image, imageIndex) in items" :key="imageIndex">
                                    <span></span>
                                    <span></span>
                                    <span></span>
                                    <div class="icon">
                                        <img src="/images/icons/play.png" alt="Icon">
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="shape-style1">
                            <img src="/images/shape/line1.png" alt="Image">
                        </div>
                        <div class="shape-style2">
                            <img src="/images/shape/line2.png" alt="Image">
                        </div>
                        <div class="shape-style3">
                            <img src="/images/shape/line3.png" alt="Image">
                        </div>
                        <div class="shape-style4">
                            <img src="/images/shape/line4.png" alt="Image">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    import CoolLightBox from 'vue-cool-lightbox'
    import 'vue-cool-lightbox/dist/vue-cool-lightbox.min.css'

    export default {
        components: {
            CoolLightBox,
        },

        data() {
            return {
                items: [
                    {
                        src: "https://www.facebook.com/VALA.Landshut/videos/1104494176270420",
                        autoplay: true
                    },
                ],
                index: null
            }
        },
    };
</script>