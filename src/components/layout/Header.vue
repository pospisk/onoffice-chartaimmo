<template>
    <header>
        <b-navbar toggleable="lg" type="">
            <div class="container">
                <b-navbar-brand to="/">
                    <img class="navbar-brand__logo" src="../../assets/img/logo.svg" alt="ChartaImmo Logo">
                </b-navbar-brand>

                <b-navbar-toggle target="mobile-nav-collapse">
                    <div class="navbar-toggler__line"></div>
                    <div class="navbar-toggler__line"></div>
                    <div class="navbar-toggler__line"></div>
                </b-navbar-toggle>

                <b-collapse id="nav-collapse" class="justify-content-end" is-nav>
                    <b-navbar-nav>
                        <b-nav-item>
                            Immobilien
                        </b-nav-item>
                        <b-nav-item>
                            Bauträger
                        </b-nav-item>
                        <b-nav-item>
                            Für Privatverkaufer
                        </b-nav-item>
                        <b-nav-item>
                            Über uns
                        </b-nav-item>
                        <b-nav-item>
                            Kontakt
                        </b-nav-item>
                    </b-navbar-nav>
                </b-collapse>
            </div>
        </b-navbar>
        <b-collapse class="navbar-collapse--mobile" id="mobile-nav-collapse" is-nav>
            <b-navbar-nav class="container pd__fix">
                <b-nav-item>
                    Immobilien
                </b-nav-item>
                <b-nav-item>
                    Bauträger
                </b-nav-item>
                <b-nav-item>
                    Für Privatverkaufer
                </b-nav-item>
                <b-nav-item>
                    Über uns
                </b-nav-item>
                <b-nav-item>
                    Kontakt
                </b-nav-item>
            </b-navbar-nav>

            <b-navbar-nav class="container navbar-footer pd__fix">
                <b-nav-item>
                    Impressum
                </b-nav-item>
                <b-nav-item>
                    Datenschutz
                </b-nav-item>
            </b-navbar-nav>
        </b-collapse>
    </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>
