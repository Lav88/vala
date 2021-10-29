<template>
    <section class="team-area team-fluid-area">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 offset-lg-3 col-xl-4 offset-xl-0">
                    <div class="section-title">
                        <h5 class="subtitle line-theme-color mb-7">Members</h5>
                        <h2 class="title title-style">VALA Vorstand <img class="img-shape" src="/images/shape/3.png" alt="Image-Givest"></h2>
                        <div class="desc">
                            <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry's standard dummy text ever since and unknown printer took scrambled it make specimen book.</p>
                            <n-link to="/volunteer" class="btn-theme btn-gradient btn-slide">Join Now <img class="icon icon-img" src="/images/icons/arrow-line-right2.png" alt="Icon"></n-link>
                        </div>
                    </div>
                </div>
                <div class="col-xl-8">
                    <div class="team-member-items">
                        <div class="team-slider-container">
                            <swiper :options="teamSlider">
                                <div class="swiper-slide team-member" v-for="(member, index) in teamMembers" :key="index">
                                    <div class="thumb">
                                        <img :src="member.imgSrc" :alt="member.name">
                                        <div class="social-icons">
                                            <a :href="list.url" v-for="(list, index) in member.socialLink" :key="index">
                                                <i :class="list.icon"></i>
                                            </a>
                                        </div>
                                    </div>
                                    <div class="content">
                                        <div class="member-info">
                                            <h4 class="name"><a href="#">{{ member.name }}</a></h4>
                                            <h6 class="designation">{{ member.designation }}</h6>
                                        </div>
                                    </div>
                                    <div class="content">
                                        <div>
                                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit ipsam laboriosam libero.</p>
                                        </div>
                                    </div>
                                </div>
                            </swiper>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        data() {
            return {
                teamSlider: {
                    autoplay: true,
                    loop: true,
                    speed: 1500,
                    slidesPerView: 3,
                    spaceBetween : 30,
                    breakpoints: {
                        1200:{
                            slidesPerView : 3
                        },

                        768:{
                            slidesPerView : 3
                        },

                        320:{
                            slidesPerView : 1
                        }
                    }
                },

                teamMembers: [
                    {
                        imgSrc: "/images/team/1.png",
                        name: "Mustapha Al Mana",
                        designation: "Vorsitzender I",
                        socialLink: [
                            {
                                icon: "icofont-facebook",
                                url: "#"
                            },
                            {
                                icon: "icofont-skype",
                                url: "#"
                            },
                            {
                                icon: "icofont-twitter",
                                url: "#"
                            }
                        ]
                    },
                    {
                        imgSrc: "/images/team/2.png",
                        name: "Gaby Johnson",
                        designation: "Kassierein II",
                        socialLink: [
                            {
                                icon: "icofont-facebook",
                                url: "#"
                            },
                            {
                                icon: "icofont-skype",
                                url: "#"
                            },
                            {
                                icon: "icofont-twitter",
                                url: "#"
                            }
                        ]
                    },
                    {
                        imgSrc: "/images/team/3.png",
                        name: "Theodoro Cordeiro",
                        designation: "Vorsitzender II",
                        socialLink: [
                            {
                                icon: "icofont-facebook",
                                url: "#"
                            },
                            {
                                icon: "icofont-skype",
                                url: "#"
                            },
                            {
                                icon: "icofont-twitter",
                                url: "#"
                            }
                        ]
                    },
                    {
                        imgSrc: "/images/team/4.png",
                        name: "Jamila Fox",
                        designation: "Kassierein I",
                        socialLink: [
                            {
                                icon: "icofont-facebook",
                                url: "#"
                            },
                            {
                                icon: "icofont-skype",
                                url: "#"
                            },
                            {
                                icon: "icofont-twitter",
                                url: "#"
                            }
                        ]
                    },
                    {
                        imgSrc: "/images/team/5.png",
                        name: "Jean Pierre Niyonkuru",
                        designation: "Schriftführer",
                        socialLink: [
                            {
                                icon: "icofont-facebook",
                                url: "#"
                            },
                            {
                                icon: "icofont-skype",
                                url: "#"
                            },
                            {
                                icon: "icofont-twitter",
                                url: "#"
                            }
                        ]
                    },
                    {
                        imgSrc: "/images/team/6.png",
                        name: "Steven Sillah",
                        designation: "Öffentlichkeitbeauftragter",
                        socialLink: [
                            {
                                icon: "icofont-facebook",
                                url: "#"
                            },
                            {
                                icon: "icofont-skype",
                                url: "#"
                            },
                            {
                                icon: "icofont-twitter",
                                url: "#"
                            }
                        ]
                    }
                ]
            }
        },
    };
</script>