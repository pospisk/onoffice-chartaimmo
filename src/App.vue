<template>
  <div id="app">
    <script type='application/ld+json'>
      {
        "@context": "http://www.schema.org",
        "@type": "RealEstateAgent",
        "name": "ChartaImmo",
        "url": "charta-immo.dev",
        "logo": "https://charta-immo.dev/assets/img/logo.svg",
        "description": "ChartaImmo – das ist ein Unternehmen mit Tradition und Weitsicht. Unser Familienbetrieb, vermittelt seit fast 15 Jahren Menschen in Immobilien. Unter der Leitung von Geschäftsführer Max Mustermann vermitteln wir nicht nur Bestandsimmobilien, sondern entwickeln und setzen auch Wohnprojekte in der Region Musterhause und Umgebung um.",
        "address": {
          "@type": "PostalAddress",
          "streetAddress": "Musterstraße 123",
          "addressLocality": "Musterhausen",
          "addressRegion": "NRW",
          "postalCode": "12345",
          "addressCountry": "Germany"
        },
        "openingHours": "Mo, Tu, We, Th, Fr 08:00-17:00",
        "contactPoint": {
          "@type": "ContactPoint",
          "telephone": "0123-123456-0",
          "contactType": "Business"
        }
      }
    </script>
    <Header />
    <section class="hero__wrapper">
      <div class="container">
        <div class="row" data-aos="slide-right"  data-aos-delay="0">
          <div class="col-12">
            <div class="hero__title">
              Wir haben Ihre <br>
              Traum&shy;immobilie.
            </div>
          </div>
        </div>
        <form>
          <div class="row" data-aos="slide-up" data-aos-delay="100">
            <div class="col-12 col-lg-3">
              <input placeholder="Ort">
            </div>
            <div class="col-12 col-lg-3">
              <select>
                <option value="" disabled selected>Immobilienart</option>
                <option value="1">Büro</option>
                <option value="2">Haus</option>
                <option value="3">Wohnung</option>
              </select>
            </div>
            <div class="col-12 col-lg-3">
              <input placeholder="Fläche ab">
            </div>
            <div class="col-12 col-lg-3">
              <input placeholder="Preis bis">
            </div>
          </div>
          <div class="row" data-aos="slide-up">
            <div class="col-12 d-flex justify-content-end">
              <button class="hero__button button--outline">
                Suchen
              </button>
            </div>
          </div>
        </form>
      </div>
    </section>
    <section class="pd__section" data-aos="fade-in"  data-aos-delay="200">
      <div class="container">
        <div class="row">
          <div class="col-12 offset-0 col-lg-8 offset-lg-2">
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
    </section>
    <section class="pd__section bg--gray" data-aos="fade-in">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <div class="headline__title mb-lg-5">
              <span class="headline__title--top">
                Projekte
              </span>
              <h1 class="headline__title--bottom">
                Aktuelle Wohnprojekte
              </h1>
            </div>
            <div class="row">
              <Realestate data-aos="slide-up"/>
              <Realestate data-aos="slide-up" data-aos-delay="50"/>
              <Realestate data-aos="slide-up" data-aos-delay="100"/>
              <Realestate data-aos="slide-up" data-aos-delay="150"/>
              <Realestate data-aos="slide-up" data-aos-delay="200"/>
              <Realestate data-aos="slide-up" data-aos-delay="250"/>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="pd__section bg--dark">
      <div class="container">
        <div class="row offset__lg--y--enlarge">
          <div class="col-12 col-lg-7" data-aos="slide-right">
            <img class="img-fluid boxshadow" src="./assets/img/douglas-sheppard-9rYfG8sWRVo-unsplash.png" alt="">
          </div>
        </div>
        <div class="row">
          <div class="col-12 col-lg-8 offset-0 offset-lg-4 bg--dark" data-aos="slide-left">
            <div class="row">
              <div class="col-12 col-lg-11 offset-0 offset-lg-1 my-5">
                <div class="headline__title">
                  <span class="headline__title--top">
                    15 Jahre Erfahrung
                  </span>
                  <h1 class="headline__title--bottom">
                    Mehr Wohn- und Lebensqualität mit Charta Immo
                  </h1>
                </div>
                <p>
                  Als Familienbetrieb für Wohnimmobilien stehen wir für eine kompetente, persönliche, engagierte und professionelle Arbeitsweise. Diese bringen wir nur durch unsere hohe Qualität als Bauträger und Projektentwickler zum Ausdruck, sondern auch durch unsere Verbundenheit zu den Menschen, den Dienstleistern und der Region Musterhausen.
                  <br>
                  <br>
                  In jedes unserer Projekte – ob Neubau oder Vermittlung – lassen wir unsere gesamte Erfahrung einfließen, die wir aus über 50 Jahren als Bauträger und Unternehmen im Immobiliengeschäft sammeln konnten.
                  <br>
                  <br>
                  Wir arbeiten für Menschen. Die Kundenwünsche stellen wir daher immer in den Fokus und berücksichtigen sie bei all unseren Überlegungen und Entscheidungen.
                  <br>
                  <br>
                  Wir legen großen Wert auf eine hohe Wohn- und Lebensqualität und engagieren uns daher bei jedem Projekt und Auftrag so, als wäre er der wichtigste.
                  <br>
                  <br>
                  Ob für unsere eigenen Bauprojekte, die Revitalisierung von Bestandsimmobilien oder die Vermittlung von Immobilien an Privatpersonen: Wir vertrauen auf die zuverlässigen Handwerker und Dienstleister aus der Region und empfehlen diese gerne weiter.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="pd__section" data-aos="fade-in">
      <div class="container">
        <div class="row">
          <div class="col-12 col-lg-8 offset-0 offset-lg-2">
            <div class="headline__title">
              <span class="headline__title--top">
                Rundum Service
              </span>
              <h1 class="headline__title--bottom">
                Marktgerechte Vermittlung für Eigentümer
              </h1>
            </div>
            <p>
              Möchten Sie Ihre Immobilie in der Region Freiburg verkaufen,
              kümmern wir uns um eine professionelle Vermarktung und Vermittlung.
              Dazu gehört nicht nur unsere fundierte Immobilienmarktwerteinschätzung
              nach geltenden Richtlinien, sondern auch die hochwertige Präsentation
              mit allen modernen Foto- und Videotechniken. So wecken wir einerseits
              ein Wohngefühl beim Interessenten und sorgen andererseits für
              qualifiziertere Besichtigungen und damit einen erfolgreicheren Verkauf.
            </p>
            <a href="#" class="button--outline my-2">
              mehr erfahren
            </a>
          </div>
        </div>
      </div>

    </section>
    <section class="pd__section bg--darkgray">
      <div class="container">
        <div class="row">
          <div class="col-12 col-lg-6 mb-5 mb-lg-0" data-aos="slide-right">
            <img class="img-fluid boxshadow" src="./assets/img/stephan-bechert-yFV39g6AZ5o-unsplash.png" alt="">
          </div>
          <div class="col-12 col-lg-6" data-aos="slide-left">
            <div class="row">
              <div class="col-12 col-lg-10 offset-0 offset-lg-1">
                <div class="headline__title mb-lg-5">
                  <span class="headline__title--top">
                    Arbeits&shy;erleichterung
                  </span>
                  <h1 class="headline__title--bottom">
                    Unser Verkaufs&shy;service für Sie:
                  </h1>
                </div>
                  <ul class="ul-theme">
                    <li>
                      Fachgerechte Wertermittlung für Ihre Immobilie
                    </li>
                    <li>
                      Beschaffung und professionelle Aufbereitung aller relevanter Unterlagen
                    </li>
                    <li>
                      Erstellung eines hochwertigen Exposés inklusive ansprechender Fotos
                    </li>
                    <li>
                      Moderne Präsentation durch Luftaufnahmen und virtuelle Rundgänge
                    </li>
                    <li>
                      Durchführung der Besichtigungen und Bonitätsprüfung der Kaufinteressenten
                    </li>
                  </ul>
              </div>
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
