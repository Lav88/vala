<template>
    <div class="donation-page-wrapper">

        <Header />

        <OffCanvasMobileMenu />

        <Breadcrumb :items="items" title="Every little helps" />

        <div class="donation-wrapper">
            <div class="container">
                <div class="row">
                    <div class="col-lg-10 m-auto">
                        <DonationForm />
                    </div>
                </div>
            </div>
        </div>

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
            DonationForm: () => import('@/components/DonationForm'),
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
                        text: 'Spenden',
                        active: true
                    }
                ]
            }
        },

        head() {
            return {
                title: 'Spenden'
            }
        },
    };
</script>


