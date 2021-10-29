<template>
    <section class="team-area">
        <div class="container">
            <div class="row">
                <div class="col-lg-8 m-auto">
                    <div class="section-title text-center">
                        <h5 class="subtitle line-theme-color mb-7">FC VALA Team</h5>
                        <h2 class="title title-style">Talented VALA Team &amp; their story. <img class="img-shape" src="/images/shape/3.png" alt="Image-Givest"></h2>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-lg-12">
                    <div class="team-member-items">
                        <div class="row">
                            <div class="col-sm-6 col-lg-4" v-for="(member, index) in teamMembers" :key="index">
                                <TeamMember :member="member" />
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        components: {
            TeamMember: () => import('@/components/TeamMember'),
        },

        data() {
            return {
                teamMembers: [
                    {
                        imgSrc: "/images/football/1.png",
                        name: "Harvey Harrington",
                        designation: "Center",
                        url: "#",
                        bio: "write something here about the player: where they are from, their story etc.Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since 1500 an when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
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
                        imgSrc: "/images/football/1.png",
                        name: "Alejandra Bobbitt",
                        designation: "Striker",
                        url: "#",
                        bio: "write something here about the player: where they are from, their story etc.Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since 1500 an when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
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
                        imgSrc: "/images/football/1.png",
                        name: "Sherika Hankins",
                        designation: "Goal Keeper",
                        url: "#",
                        bio: "write something here about the player: where they are from, their story etc. Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since 1500 an when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
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
                        imgSrc: "/images/football/1.png",
                        name: "Destiny Kendall",
                        designation: "Marketing Manager",
                        url: "#",
                        bio: "write something here about the player: where they are from, their story etc.Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since 1500 an when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
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
                        imgSrc: "/images/football/1.png",
                        name: "Marleen Larry",
                        designation: "PHP Expert",
                        url: "#",
                        bio: "write something here about the player: where they are from, their story etc. Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since 1500 an when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
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
                        imgSrc: "/images/football/1.png",
                        name: "Digital Marketer",
                        designation: "Senior Developer",
                        url: "#",
                        bio: "write something here about the player: where they are from, their story etc. Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since 1500 an when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
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