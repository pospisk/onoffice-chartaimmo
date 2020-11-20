<template>
    <div class="col-12 col-lg-4">
        <div class="project__item">
            <div class="row">
                <div class="col-12">
                    <div class="project__imageWrapper">
                        <img class="project__image" src="./../assets/img/clarisse-croset-MET1RiKQRjg-unsplash.png" alt="">
                    </div>

                    <div class="row">
                        <div class="col-6 bd__bottom bd__bottom--primary"></div>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="project__inner col-12">

                <div class="row mx-0">
                    <div class="col-12">
                        <div class="project__title">
                            {{realestateTitle}}
                        </div>
                    </div>
                </div>
                <div class="row mx-0">
                    <div class="col-6">
                        <span class="project__detail">
                            Objekt-Nr.
                        </span>
                        <span class="project__info">
                            {{realestateNumber}}
                        </span>
                    </div>
                    <div class="col-6">
                        <span class="project__detail">
                            Kaufpreis
                        </span>
                        <span class="project__info">
                            {{realestatePrice}} €
                        </span>
                    </div>
                </div>
                <div class="row mx-0">
                    <div class="col-6">
                        <span class="project__detail">
                            Wohnfläche
                        </span>
                        <span class="project__info">
                            ca. {{realestateArea}} m<sup>2</sup>
                        </span>
                    </div>
                    <div class="col-6">
                        <span class="project__detail">
                            Zimmer
                        </span>
                        <span class="project__info">
                            {{realestateRooms}}
                        </span>
                    </div>
                </div>
                <div class="row mx-0 project__footer">
                    <div class="col-6 d-flex flex-row">
                        <a href="tel:000000000" class="project__button project__button--call">
                            <span class="sr-only">Anrufen</span>
                        </a>
                        <a href="mailto:mail@chartaimmo.de" class="project__button project__button--mail">
                            <span class="sr-only">E-Mail</span>
                        </a>
                        <a href="#" class="project__button project__button--chat">
                            <span class="sr-only">Chat</span>
                        </a>
                    </div>
                    <div class="col-6 text-right">
                        <a class="project__link" href="#">mehr erfahren</a>
                    </div>
                </div>

                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Realestate',
  data: function () {
    return {
      realestateTitle: 'Neubauprojekt: Allbach - Wohnen in Muhausen',
      realestateNumber: 345623,
      realestatePrice: '414.400,00',
      realestateArea: 101,
      realestateRooms: 4
    }
  }
}
</script>
