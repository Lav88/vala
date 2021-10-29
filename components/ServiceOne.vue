<template>
    <section class="service-area service-default-area">
        <div class="container">
            <div class="row mtn-30" data-aos="fade-up" data-aos-duration="1000">
                <div class="col-md-6 col-lg-3 mt-30" v-for="(service, index) in services" :key="index">
                    <div class="icon-box-item" :class="service.addClassName">
                        <div class="icon-box-top">
                            <div class="icon-box">
                                <img class="icon-img" :src="service.icon" alt="icon" />
                            </div>
                            <div class="icon-title">
                                <h4 class="title" style="flex-wrap: wrap;">{{ service.title }}</h4>
                            </div>
                            
                        </div>
                        <div class="content">
                            <div class="separator-line">
                                <img src="/images/shape/line-s1.png" alt="shape" />
                            </div>
                            <p>{{ service.desc }}</p>
                            <n-link to="/causes-details" class="btn-theme btn-white btn-border btn-size-md">
                                Mehr Zeigen
                                <img class="icon icon-img" src="/images/icons/arrow-line-right.png" alt="Icon" />
                            </n-link>
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
                services: [
                    {
                        icon: "/images/icons/s1.png",
                        title: "AfrikaTag",
                        desc: "Die jährlichen Afrikatage und das Familienfest sind ein Beitrag zum friedlichen Miteinander der Kulturen.",
                        addClassName: "item-one"
                    },
                    {
                        icon: "/images/icons/s2.png",
                        title: "VALA Cafe",
                        desc: "Some text here about Cafe Vala monthly theme",
                        addClassName: "item-two"
                    },
                    {
                        icon: "/images/icons/s3.png",
                        title: "FC Vala",
                        desc: "Die erste kulturelle Fußballmannschaft in Landshut trainiert für den jährlichen Afrika-Cup.",
                        addClassName: "item-three"
                    },
                    {
                        icon: "/images/icons/s4.png",
                        title: "Aktionen",
                        desc: "Wir stehen für Vielfalt und Gleichberechtigung und beteiligen uns an Aktionen für eine offene Gesellschaft.",
                        addClassName: "item-four"
                    }
                ]
            }
        },
    };
</script>
