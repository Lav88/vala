<template>
    <section class="causes-area causes-default-area">
        <div class="container">
            <div class="row mtn-30">
                <div class="col-md-6 col-lg-4 mt-30" v-for="(causes, index) in causesData" :key="index">
                    <div class="causes-item">
                        <div class="thumb">
                            <img :src="causes.imgSrc" :alt="causes.title">
                        </div>
                        <div class="content">
                            <ul class="donate-info">
                                <li class="info-item" v-for="(info, index) in causes.infoList" :key="index">
                                    <span class="info-title">{{ info.infoTitle }}:</span>
                                    <span class="amount">{{ info.amount }}</span>
                                </li>
                            </ul>
                            <h4 class="title">
                                <n-link to="/causes-details">{{ causes.title }}</n-link>
                            </h4>
                            <p>{{ causes.desc }}</p>
                        </div>
                        <div class="causes-footer">
                            <div class="admin">
                                <h5>
                                    <n-link to="/causes">
                                        <span class="icon-img">
                                            <img src="/images/icons/admin1.png" alt="Icon">
                                        </span> {{ causes.name }}
                                    </n-link>
                                </h5>
                            </div>
                            <n-link to="/donation" class="btn-theme btn-border-gradient gray-border btn-size-md">
                                <span>
                                    See Menu
                                    <img class="icon icon-img" src="/images/icons/arrow-line-right-gradient.png" alt="Icon">
                                </span>
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
                causesData: [
                    {
                        imgSrc: "/images/causes/01.png",
                        title: "Theme | The Gambia",
                        desc: "Lorem Ipsum is simply dummy text of the industry's since the unknown.",
                        name: "Kristin Horton",
                        infoList: [
                            {
                                infoTitle: "Menu",
                                amount: "Gambia"
                            },
                            {
                                infoTitle: "Date",
                                amount: "12 Dec"
                            },
                            {
                                infoTitle: "Ending",
                                amount: "18:00pm"
                            }
                        ]
                    },
                    {
                        imgSrc: "/images/causes/01.png",
                        title: "Theme | The Gambia",
                        desc: "Lorem Ipsum is simply dummy text of the industry's since the unknown.",
                        name: "Kristin Horton",
                        infoList: [
                            {
                                infoTitle: "Menu",
                                amount: "Gambia"
                            },
                            {
                                infoTitle: "Opening",
                                amount: "12:00pm"
                            },
                            {
                                infoTitle: "Closing",
                                amount: "18:00pm"
                            }
                        ]
                    },
                    {
                        imgSrc: "/images/causes/01.png",
                        title: "Theme | The Gambia",
                        desc: "Lorem Ipsum is simply dummy text of the industry's since the unknown.",
                        name: "Kristin Horton",
                        infoList: [
                            {
                                infoTitle: "Menu",
                                amount: "Gambia"
                            },
                            {
                                infoTitle: "Opening",
                                amount: "12:00pm"
                            },
                            {
                                infoTitle: "Closing",
                                amount: "18:00pm"
                            }
                        ]
                    },
                    {
                        imgSrc: "/images/causes/01.png",
                        title: "Theme | The Gambia",
                        desc: "Lorem Ipsum is simply dummy text of the industry's since the unknown.",
                        name: "Kristin Horton",
                        infoList: [
                            {
                                infoTitle: "Menu",
                                amount: "Gambia"
                            },
                            {
                                infoTitle: "Opening",
                                amount: "12:00pm"
                            },
                            {
                                infoTitle: "Closing",
                                amount: "18:00pm"
                            }
                        ]
                    },
                    {
                        imgSrc: "/images/causes/01.png",
                        title: "Theme | The Gambia",
                        desc: "Lorem Ipsum is simply dummy text of the industry's since the unknown.",
                        name: "Kristin Horton",
                        infoList: [
                            {
                                infoTitle: "Menu",
                                amount: "Gambia"
                            },
                            {
                                infoTitle: "Opening",
                                amount: "12:00pm"
                            },
                            {
                                infoTitle: "Closing",
                                amount: "18:00pm"
                            }
                        ]
                    },
                    {
                        imgSrc: "/images/causes/01.png",
                        title: "Theme | The Gambia",
                        desc: "Lorem Ipsum is simply dummy text of the industry's since the unknown.",
                        name: "Kristin Horton",
                        infoList: [
                            {
                                infoTitle: "Menu",
                                amount: "Gambia"
                            },
                            {
                                infoTitle: "Opening",
                                amount: "12:00pm"
                            },
                            {
                                infoTitle: "Closing",
                                amount: "18:00pm"
                            }
                        ]
                    }
                ]
            }
        },
    };
</script>