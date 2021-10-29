<template>
    <section class="causes-details-area">
        <div class="container">
            <div class="row">
                <div class="col-12">
                    <div class="causes-details-column">
                        <div class="causes-details-content">
                            <div class="causes-details">
                                <div class="thumb">
                                    <img class="w-100" src="/images/sponsors/1.png" alt="image">
                                </div>
                                <h3 class="cause-title">Die Lebensader von VALA | 2021<br class="text-theme-color"> Thank You</h3>
                                <div class="donate-info-wrp">
                                    <div class="row">
                                        <div class="col-md-6">
                                            <ul class="donate-info">
                                                <li class="info-item">
                                                    <span class="info-title">Annual Goal:</span>
                                                    <span class="amount">$ 5,000</span>
                                                </li>
                                                <li class="info-item">
                                                    <span class="info-title">Raised:</span>
                                                    <span class="amount">$ 2,000</span>
                                                </li>
                                                <li class="info-item">
                                                    <span class="info-title">To Go:</span>
                                                    <span class="amount">$ 1,000</span>
                                                </li>
                                            </ul>
                                        </div>
                                        <div class="col-md-6">
                                            <div class="progress-item">
                                                <div class="progress-line">
                                                    <div class="progress-bar-line" style="width: 75%">
                                                        <span class="percent">75%</span>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <p>fand die Spendenübergabe im Rahmen der Landshuter Afrikatage an die geförderten Projekte statt. Wir freuen uns sehr, dass es uns auch dieses Jahr erneut möglich war, einen kleinen Beitrag zur positiven Entwicklung zu leisten.Insgesamt konnten wir wieder vier Projekte unterstützen.</p>
                                <p class="mb-26">Drei Projekte davon engagieren sich im Bereich der Bildung und ein Projekt befasst sich mit Gesundheit und Vorsorge. Vielen Dank an alle Sponsoren, Besucher, die Stadt Landshut, das Haus International und dem Repair Cafe. Insbesondere danken wir auch dem Jugendkulturzentrum Alte Kaserne sowie dem Landkreis Landshut, der FOS Landshut, allen ehrenamtlichen Helfern und auch den vielen afrikanischen Familien, die uns unterstützt haben. Nicht zu vergessen sind unsere VALA e.V.-Mitglieder. </p>
                                <h3>We could not do this without you!</h3>
                                <p>Die AFRIKATAGE Landshut sind zu einem Merkmal und Symbol für die Vielfalt unserer Stadt geworden. Landshut ist BUNT und das ist gut so. Wir freuen uns auf die kommenden Afrikatage Landshut und alle anstehenden Projekte in der Stadt, die sich für Toleranz, Vielfalt und eine insgesamt stärker integrierte Gesellschaft einsetzen. </p>
                                <p class="mb-26">Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500 an when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
                                <h3>Summery And Documents</h3>
                                <div class="row">
                                    <div class="col-sm-6">
                                        <button class="document-item">
                                            Documents.pdf
                                            <img src="/images/icons/file.png" alt="Icon">
                                        </button>
                                    </div>
                                    <div class="col-sm-6">
                                        <button class="document-item bgcolor-theme2">
                                            Documents.pdf
                                            <img src="/images/icons/file.png" alt="Icon">
                                        </button>
                                    </div>
                                </div>
                                <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500 an when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged was popularised in the 1960s with the release of etraset sheets containing Lorem Ipsum passages.</p>
                                <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500 an when an unknown printer took a galley of type and scrambled it to make a type specimen book.</p>
                                <p></p>
                            </div>
                            <DonnerList />
                        </div>
                        <SidebarWrapper />
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        components: {
            DonnerList: () => import('@/components/DonnerList'),
            SidebarWrapper: () => import('@/components/SidebarWrapper'),
        },
    };
</script>
