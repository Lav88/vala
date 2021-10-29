<template>
    <div class="volunteer-page-wrapper">

        <Header />

        <OffCanvasMobileMenu />

        <Breadcrumb :items="items" title="Das Team" />

        <TeamTwo />

        <JoinValaFC />

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
            
            TeamTwo: () => import('@/components/TeamTwo'),
            JoinValaFC: () => import('@/components/JoinValaFC'),
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
                        text: 'Das Team',
                        active: true
                    }
                ]
            }
        },

        head() {
            return {
                title: 'Das Team'
            }
        },
    };
</script>


