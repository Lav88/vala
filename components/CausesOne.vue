<template>
    <section class="causes-area causes-default-area">
        <div class="container">
            <div class="row">
                <div class="col-lg-8 m-auto">
                    <div class="section-title text-center" data-aos="fade-up" data-aos-duration="1000">
                        <h5 class="subtitle line-theme-color">Siehe unsere Ursachen</h5>
                        <h2 class="title title-style">Wir brauchen Ihre Hilfe. Unterstützen Sie VALAs Anliegen
                            <img class="img-shape" src="/images/shape/3.png" alt="Image">
                        </h2>
                    </div>
                </div>
            </div>
            <div class="row mtn-30" data-aos="fade-up" data-aos-duration="1000">
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
                                    Donate Now 
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
                        title: "Diabetes prevention in Ghana",
                        desc: "Dolores Graf führt uns mit ihrem Diabetesprogramm durch Ghana. Dieses Programm zu unterstützen bedeutet, die frühzeitige Prävention von Diabetes in Gemeinden zu fördern, die es am meisten brauchen.",
                        name: "Dolores Graf",
                        infoList: [
                            {
                                infoTitle: "Goal",
                                amount: "$ 5000"
                            },
                            {
                                infoTitle: "Raised",
                                amount: "$ 2000"
                            },
                            {
                                infoTitle: "To Go",
                                amount: "$ 1000"
                            }
                        ]
                    },
                    {
                        imgSrc: "/images/causes/02.png",
                        title: "Wasser für Senegal",
                        desc: "Heike Messenzehl im Senegal, um dort zusammen mit Ehepaar Dr. Graf verschiedene Projekte zu begutachten. Natürlich lag ihr Schwerpunkt wieder bei den Schulen und den Patenschaften. Einen sehr ausführlichen Reisebericht mit vielen Bildern clicken Sie hier.",
                        name: "Heike Messenzehl",
                        infoList: [
                            {
                                infoTitle: "Goal",
                                amount: "$ 3000"
                            },
                            {
                                infoTitle: "Raised",
                                amount: "$ 4000"
                            },
                            {
                                infoTitle: "To Go",
                                amount: "$ 2000"
                            }
                        ]
                    },
                    {
                        imgSrc: "/images/causes/03.png",
                        title: "Gambia's Fishing Industry",
                        desc: "Supporting Gambia's local fish trade. Unsustainable levels of fishing not only affect the tens of thousands of artisanal fishers in the Gambia, but also those employed smoking and drying fish, who are predominantly women",
                        name: "Maria Jeccy",
                        infoList: [
                            {
                                infoTitle: "Goal",
                                amount: "$ 8000"
                            },
                            {
                                infoTitle: "Raised",
                                amount: "$ 7000"
                            },
                            {
                                infoTitle: "To Go",
                                amount: "$ 3000"
                            }
                        ]
                    }
                ]
            }
        },
    };
</script>