<template>
    <section class="contact-area">
        <div class="container-fluid">
            <div class="row">
                <div class="col-lg-12">
                    <div class="contact-colunm">
                        <div class="contact-form">
                            <form class="contact-form-wrapper">
                                <div class="row">
                                    <div class="col-lg-12">
                                        <div class="section-title">
                                            <h5 class="subtitle line-theme-color">Jetzt kontaktieren</h5>
                                            <h2 class="title">Nehmen Sie Kontakt auf.</h2>
                                            <p>Wir helfen Ihnen bei allen Fragen gerne weiter. </p>
                                        </div>
                                    </div>
                                </div>
                                <div class="row">
                                    <div class="col-lg-12">
                                        <div class="row row-gutter-20">
                                            <div class="col-md-12">
                                                <div class="form-group">
                                                    <input class="form-control" type="text" name="name" placeholder="Name">
                                                </div>
                                            </div>
                                            <div class="col-md-12">
                                                <div class="form-group">
                                                    <input class="form-control" type="email" name="email" placeholder="Email">
                                                </div>
                                            </div>
                                            <div class="col-md-12">
                                                <div class="form-group">
                                                    <input class="form-control" type="text" name="phone" placeholder="Phone">
                                                </div>
                                            </div>
                                            <div class="col-md-12">
                                                <div class="form-group">
                                                    <label for="enquiry">PLEASE SELECT ONE OF THE FOLLOWING:</label>
                                                    <select  class="form-control" id="enquiry" name="message">
                                                        <option value="volunteer">Volunteer</option>
                                                        <option value="joinfc">Join Vala FC</option>
                                                        <option value="events">Events</option>
                                                        <option value="sponsor">Sponsor</option>
                                                        <option value="other">Other</option>
                                                    </select>
                                                </div>
                                            </div>
                                            <div class="col-md-12">
                                                <div class="form-group mb-0">
                                                    <textarea class="form-control textarea" name="message" placeholder="Message"></textarea>
                                                </div>
                                            </div>
                                            <div class="col-md-12">
                                                <div class="form-group mb-0">
                                                    <button class="btn-theme btn-gradient btn-slide no-border" type="submit">Submit Now</button>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </form>
                        </div>
                        <div class="contact-map-area">
                            <div class="contact-info-content">
                                <div class="contact-info-item">
                                    <div class="icon">
                                        <img class="icon-img" src="/images/icons/c1.png" alt="Icon">
                                    </div>
                                    <div class="content">
                                        <h4>Phone</h4>
                                        <img class="line-icon" src="/images/shape/line-s1.png" alt="Image-vala">
                                        <a href="tel:0123456789">0123456789</a>
                                        <a href="tel:0123456789">0123456789</a>
                                    </div>
                                </div>
                                <div class="contact-info-item">
                                    <div class="icon icon-mail">
                                        <img class="icon-img" src="/images/icons/c2.png" alt="Icon">
                                    </div>
                                    <div class="content">
                                        <h4>Social</h4>
                                        <img class="line-icon" src="/images/shape/line-s1.png" alt="Image-vala">
                                        <a href="https://www.facebook.com/VALA.Landshut/">Facebook | vala.landshut</a>
                                        <a href="https://www.facebook.com/VALA.Landshut">Linkedin | Vala</a>
                                    </div>
                                </div>
                                <div class="contact-info-item mb-0 pb-0">
                                    <div class="icon icon-location">
                                        <img class="icon-img" src="/images/icons/c3.png" alt="Icon">
                                    </div>
                                    <div class="content">
                                        <h4>Address</h4>
                                        <img class="line-icon" src="/images/shape/line-s1.png" alt="Image-vala">
                                        <p>VALA e. V Postfach 2731<br>84011 Landshut</p>
                                    </div>
                                </div>
                            </div>
                            <iframe src="https://maps.google.com/maps?q=Orbankai%203,%2084028%20Landshut&t=&z=17&ie=UTF8&iwloc=&output=embed"></iframe>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {

    };
</script>
