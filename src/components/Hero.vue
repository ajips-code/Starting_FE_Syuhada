<script setup>
import mainPhoto from "../assets/images/hero.svg";
import { themeColor } from "../data/items";

const heroHeading = "Smart Mosque, Digital Mosque, Be Inclusive.";
const buttonSeeFeature = "See Features";

</script>

<template>
  <div class="untree_co-hero" id="home-section">
    <div class="container">
      <div class="row align-items-center">
        <div class="col-12">
          <div class="row align-items-center">
            <div class="col-lg-6 ml-auto order-lg-2" data-aos="fade-right" data-aos-delay="400">
              <img :src="mainPhoto" alt="Image" class="img-fluid img-hero" />
            </div>
            <div class="col-lg-6">
              <h1 class="heading-text heading mt-7" data-aos="fade-up" data-aos-delay="0">
                {{ heroHeading }}
              </h1>
              <div class="excerpt" data-aos="fade-up" data-aos-delay="100">
                <p style="
                  margin-left: 7px; text-align: justify;">
                  Lorem ipsum dolor sit amet consectetur.
                  <span style="
                      background-color: rgba(64, 123, 255, 0.07);
                      color: #407bff;
                    ">Syuhada</span>
                  Lorem ipsum dolor sit amet consectetur.
                  Gravida venenatis aliquet leo elit feugiat nibh egestas purus sit.
                </p>
                <a href="#pricing-section" class="nav-link button">Download Apps</a>
              </div>
              <p data-aos="fade-up" data-aos-delay="200">
                <a href="#features-section" class="btn btn-primary smoothscroll" style="margin-right: 5px" :style="[
                  { background: themeColor },
                  { borderColor: themeColor },
                ]">{{ buttonSeeFeature }}</a>
                <a href="#pricing-section" class="btn btn-outline-primary smoothscroll pricing"
                  :style="[{ color: themeColor }, { borderColor: themeColor }]">Download Apps</a>
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.pricing:hover {
  color: #fff !important;
}

.img-hero {
  height: 475px;
  width: 475px;
  margin-left: 60px;
  margin-top: 40px;
}

.heading-text {
  margin-top: -20px;
  font-size: 65px;
  color: #436129;
}

.button {
  display: inline-block;
  padding: 5px 15px 5px 15px;
  background-color: #436129; /* Button background color */
  color: #fff; /* Button text color */
  border-radius: 15px; /* Button border radius */
  text-decoration: none;
  transition: background-color 0.3s ease, color 0.3s ease;
  margin-top:10px;
  margin-left: -2px;
  font-size: 24.3px;
}

.button:hover {
  background-color: #436129; /* Hover background color */
  color: #fff; /* Hover text color */
}
</style>
