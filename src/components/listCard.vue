 <!-- eslint-disable no-new -->
<template>
  <section class="head">
    <h2 class="section-title.no-margin.text-white.base-margin-bottom"/>
    <strong>test and try to open console also network</strong>
    <ul class="col list-nostyle flex-container">
      <li class="align-center">
        <div class="m-card m-card--on-desktop">
          <div class="m-card__head">
            <figure>
              <img
                src="https://img.kitabisa.cc/size/664x357/6c28767b-703f-4afd-9dc3-f142257012d0.jpg"
                alt="50-60 ribuan peserta ujian, bantu mereka Lulus !"
                class="m-card__thumb"
              >
            </figure>
          </div>
          <div class="m-card__body">
            <h3
              class="m-card__title text-semibold"
            >
              50-60 ribuan peserta ujian, bantu mereka Lulus !
            </h3>
            <div class="m-card__subtitle">
              <div class="m-card__subtitle-wording">
                <span class="text-14">Brajakson Siokal</span>
                <!---->
              </div>
            </div>
          </div>
          <div class="m-card__footer">
            <div class="m-card__bar">
              <div
                class="m-card__progress"
                style="width: 21.4168%; background: rgb(0, 174, 239);"
              ></div>
            </div>
            <div class="m-card__count">
              <div class="m-card__countitem">
                <div class="m-card__stats">
                  <span>Terkumpul</span>
                  <span class="text-14">Rp 16.062.606</span>
                </div>
              </div>
              <div class="m-card__countitem">
                <div class="m-card__stats">
                  <span>Sisa hari</span>
                  <span class="text-14">53</span>
                </div>
              </div>
            </div>
          </div>
          <a
            href="https://kitabisa.com/bantululusujian?utm_source=microsite_bcf&amp;utm_medium=campaign_card&amp;utm_campaign=lead_indonesia"
            onclick="cardEventListener();"
            class="m-card__href js-tracker-card"
          ></a>
        </div>
      </li>
    </ul>
  </section>
</template>

<script>
import axios from 'axios';

/* eslint-disable */
export default {
  name: 'listCard',
  mounted() {
    axios
      .get('https://api.coindesk.com/v1/bpi/currentprice.json')
      .then(response => console.log('res',response.data))
  }
};
</script>

