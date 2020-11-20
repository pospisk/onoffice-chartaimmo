<template>
  <div id="app">
    <Header />
    <section class="hero__wrapper">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="hero__title">
              Wir haben Ihre <br>
              Traum&shy;immobilie.
            </div>
          </div>
        </div>
        <form>
          <div class="row">
            <div class="col-12 col-lg-3">
              <input class="hero__input" placeholder="Ort">
            </div>
            <div class="col-12 col-lg-3">
              <select class="hero__input">
                <option value="" disabled selected>Immobilienart</option>
                <option value="1">Büro</option>
                <option value="2">Haus</option>
                <option value="3">Wohnung</option>
              </select>
            </div>
            <div class="col-12 col-lg-3">
              <input class="hero__input" placeholder="Fläche ab">
            </div>
            <div class="col-12 col-lg-3">
              <input class="hero__input" placeholder="Preis bis">
            </div>
          </div>
          <div class="row">
            <div class="col-12 d-flex justify-content-end">
              <button class="hero__button">
                Suchen
              </button>
            </div>
          </div>
        </form>
      </div>
    </section>
    <section class="textblock__wrapper pd__section">
      <div class="container">
        <div class="row">
          <div class="col-12 offset-0 col-lg-8 offset-lg-2">
            <div class="textblock__inner">
              <div class="textblock__title">
                Willkommen bei Charta Immo – <br>
                Ihr Immobilienmakler für Wohnimmobilien in Musterhausen
              </div>
              <div class="textblock__content">
                <p>
                  Allgeier Wohnbau – das ist ein Unternehmen mit Tradition und Weitsicht. Unser Familienbetrieb, 1972
                  gegründet, vermittelt seit fast 50 Jahren Menschen in Immobilien. Unter der Leitung von
                  Geschäftsführer Alexander Vonalt vermitteln wir nicht nur Bestandsimmobilien, sondern entwickeln und
                  setzen auch Wohnprojekte in der Region Freiburg im Breisgau, Gundelfingen und Umgebung um.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="projects__wrapper pd__section">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="projects__title">
              <span class="projects__title--top">
                Projekte
              </span>
              <span class="projects__title--bottom">
                Aktuelle Wohnprojekte
              </span>
            </div>
            <div class="row">
              <Realestate/>
              <Realestate/>
              <Realestate/>
              <Realestate/>
              <Realestate/>
              <Realestate/>
            </div>
          </div>
        </div>
      </div>
    </section>
    <Footer />
  </div>
</template>

<script>
import Header from './components/layout/Header.vue'
import Footer from './components/layout/Footer.vue'
import Realestate from './components/Realestate.vue'

export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Realestate
  }
}
</script>
