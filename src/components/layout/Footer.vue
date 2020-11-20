<template>
    <footer>
        <div class="container" data-aos="slide-up">
            <div class="row">
                <div class="col-12">
                    <h1 class="mb-5">Schnell. Einfach. Direkt.</h1>
                </div>
            </div>
            <div class="row">
                <div class="col-12 col-lg-6">
                    <p>
                        Charta Immo GmbH<br>
                        Musterstraße 123<br>
                        12345 Musterhausen
                    </p>

                    <p>
                        Tel <a href="tel:0123-123456-0">0123-123456-0</a><br>
                        Fax <a href="fax:0123-123457">0123-123457</a><br>
                        <a href="mailto:info@charta-immo.dev">info@charta-immo.dev</a>
                    </p>
                </div>
                <div class="col-12 col-lg-6 pt-5 pt-lg-0">
                    <form>
                        <div class="row form-row">
                            <div class="col-12 col-lg-6 pr-lg-3">
                                <input type="text" placeholder="Vorname">
                            </div>
                            <div class="col-12 col-lg-6 pl-lg-3">
                                <input type="text" placeholder="Name">
                            </div>
                        </div>
                        <div class="row form-row">
                            <div class="col-12">
                                <input type="text" placeholder="E-Mail">
                            </div>
                        </div>
                        <div class="row form-row">
                            <div class="col-12">
                                <textarea rows="8" placeholder="Ihre Nachricht"/>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-12 text-right">
                                <a href="#" class="button--outline my-3">
                                    Anfrage abschicken
                                </a>
                            </div>
                        </div>
                    </form>
                </div>
            </div>
            <div class="row border-top py-4 mt-5 d-flex align-items-center flex-column-reverse flex-lg-row">
                <div class="col-12 col-lg-6 pt-4 pt-lg-0">
                    <span>Design by
                        <img src="../../assets/img/onoffice-logo.png" alt="onOffice GmbH Logo">
                    </span>
                </div>
                <div class="col-12 col-lg-6 pb-4 pb-lg-0 d-flex justify-content-start justify-content-lg-end">
                    <b-nav class="footer__nav">
                        <b-nav-item>Impressum</b-nav-item>
                        <b-nav-item>Datenschutz</b-nav-item>
                    </b-nav>
                </div>
            </div>
        </div>
    </footer>
</template>

<script>

export default {
  name: 'Footer'
}
</script>
