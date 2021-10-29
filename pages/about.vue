<template>
    <div class="main-container">

        <Header />

        <OffCanvasMobileMenu />

        <Breadcrumb :items="items" title="Vision and Mission" />

        <AboutTwo />

        <TeamOne />

        <Footer />

        <client-only>
            <back-to-top class="scroll-top" bottom="30px">
                <i class="arrow-top icofont-rounded-up"></i>
                <i class="arrow-bottom icofont-rounded-up"></i>
            </back-to-top>
        </client-only>

    </div>
</template>

<script>
    export default {
        components: {
            Header: () => import('@/components/Header'),
            OffCanvasMobileMenu: () => import('@/components/OffCanvasMobileMenu'),
            Breadcrumb: () => import('@/components/Breadcrumb'),
            AboutTwo: () => import('@/components/AboutTwo'),
            TeamOne: () => import('@/components/TeamOne'),
            Footer: () => import('@/components/Footer'),
        },

        data() {
            return {
                items: [
                    {
                        text: 'Home',
                        to: "/"
                    },
                    {
                        text: 'Vision and Mission',
                        active: true
                    }
                ]
            }
        },

        head() {
            return {
                title: 'Vision and Mission'
            }
        },
    };
</script>


