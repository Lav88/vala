<template>
    <section class="donate-area donate-default-area bgcolor-theme3">
        <div class="container">
            <div class="row">
                <div class="col-lg-7 col-xxl-7">
                    <div class="content" data-aos="fade-up" data-aos-duration="1000">
                        <div class="section-title">
                            <h5 class="subtitle line-theme-color mb-7">Spenden Sie</h5>
                            <h2 class="title title-style text-white">Wir brauchen Hilfe für den Africa Tag 2022. 
                                <img class="img-shape" src="/images/shape/3.png" alt="Image">
                            </h2>
                        </div>
                        <div class="donate-form">
                            <form action="#">
                                <div class="amount-info">
                                    <div class="donate-amount">€5</div>
                                    <div class="donate-amount">€15</div>
                                    <div class="donate-amount">€40</div>
                                    <div class="donate-amount donate-custom-amount">
                                        <input class="form-control" type="text" placeholder="Sonderspende">
                                    </div>
                                </div>
                                <div class="btn-wrp">
                                    <a href="javascript:void(0)" class="btn-theme btn-gradient btn-slide">
                                        Spenden 
                                        <img class="icon icon-img" src="/images/icons/arrow-line-right2.png" alt="Icon">
                                    </a>
                                    <n-link to="/event-details" class="btn-theme btn-gradient btn-border">
                                        Event-Infos
                                        <img class="icon icon-img" src="/images/icons/arrow-line-right2-gradient.png" alt="Icon">
                                    </n-link>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
                <div class="col-lg-5 col-xxl-4 offset-xxl-1 position-static">
                    <div class="donners-content">
                        <div class="thumb-bg-layer" :style="{ backgroundImage: `url('/images/photos/bg-donate4.png')` }"></div>
                        <div class="donners-info" data-aos="fade-up" data-aos-duration="1000">
                            <h3>Personen, die gespendet haben</h3>
                            <p>By working with local communities we are able to ensure that all the fund received go towards a more tolerant and integrated community.</p>
                            <p>Thanks for your support</p>
                            <div class="donners-item">
                                <div class="donner-item">
                                    <img src="/images/photos/donner1.png" alt="Image">
                                </div>
                                <div class="donner-item">
                                    <img src="/images/photos/donner2.png" alt="Image">
                                </div>
                                <div class="donner-item">
                                    <img src="/images/photos/donner3.png" alt="Image">
                                </div>
                                <div class="donner-item donner-number">+286</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>