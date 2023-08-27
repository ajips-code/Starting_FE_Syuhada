<script setup>
import personPhoto from "../assets/images/person_1.jpg";
import mainPhoto from "../assets/images/image_features.svg";
import ellips1 from "../assets/images/Ellipse1.svg";
import ellips2 from "../assets/images/Ellipse2.svg";
import ellips3 from "../assets/images/Ellipse3.svg";
import ellips4 from "../assets/images/Ellipse4.svg";

const service1SubHeading = "Fitur Aplikasi";
const service1Quote =
  '"Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. A small river named Duden flows by their place and supplies it with the necessary regelialia."';
const personName = "James Anderson";
const designation = "Facebook, Product Lead";
const imgFeature = mainPhoto;

const items = [
  {
    iconBg: "background-color: #6fe7dd",
    title: "Grow Your Business",
    description:
      "Far far away, behind the word mountains, far from the countries Vokalia and Consonantia",
  },
  {
    iconBg: "background-color: #ffc93c",
    title: "Build Products",
    description:
      "Far far away, behind the word mountains, far from the countries Vokalia and Consonantia",
  },
  {
    iconBg: "background-color: #f73859",
    title: "Success Each Day",
    description:
      "Far far away, behind the word mountains, far from the countries Vokalia and Consonantia",
  },
  {
    iconBg: "background-color: #407BFF",
    title: "Bring Ideas to Life",
    description:
      "Far far away, behind the word mountains, far from the countries Vokalia and Consonantia",
  },
];
</script>

<template>
  <div class="untree_co-section feature-page" id="features-section">
    <div class="container">
      <div class="row justify-content-between">
        <div class="col-lg-4" data-aos="fade-up" data-aos-delay="400">
          <img :src="imgFeature" alt="Image" class="img-fluid img-feature" />
        </div>
        <div class="col-lg-6 description-features">
          <h3 class="heading mb-4" data-aos="fade-up" data-aos-delay="100">
            {{ service1SubHeading }}
          </h3>
          <div class="mb-4" data-aos="fade-up" data-aos-delay="200">
            <div class="row justify-content-between features1">
              <div class="col-lg-0">
                <img :src="ellips1" alt="" class="img-fluid img-ellipse" />
              </div>
              <div class="col-lg-10">
                <p>
                  Lorem ipsum dolor sit amet consectetur. Gravida venenatis aliquet leo elit feugiat nibh egestas purus
                  sit.
                </p>
              </div>
            </div>
            <div class="row justify-content-between features1">
              <div class="col-lg-0">
                <img :src="ellips2" alt="" class="img-fluid img-ellipse" />
              </div>
              <div class="col-lg-10">
                <p>
                  Lorem ipsum dolor sit amet consectetur. Gravida venenatis aliquet leo elit feugiat nibh egestas purus
                  sit.
                </p>
              </div>
            </div>
            <div class="row justify-content-between features1">
              <div class="col-lg-0">
                <img :src="ellips3" alt="" class="img-fluid img-ellipse" />
              </div>
              <div class="col-lg-10">
                <p>
                  Lorem ipsum dolor sit amet consectetur. Gravida venenatis aliquet leo elit feugiat nibh egestas purus
                  sit.
                </p>
              </div>
            </div>
            <div class="row justify-content-between features1">
              <div class="col-lg-0">
                <img :src="ellips4" alt="" class="img-fluid img-ellipse" />
              </div>
              <div class="col-lg-10">
                <p>
                  Lorem ipsum dolor sit amet consectetur. Gravida venenatis aliquet leo elit feugiat nibh egestas purus
                  sit.
                </p>
              </div>
            </div>
          </div>
          <div class="mb-4" data-aos="fade-up" data-aos-delay="300">
            <div class="untree_co-testimonial d-flex">
              <div class="text">
                <blockquote>
                  {{ service1Quote }}
                </blockquote>
                <div class="author d-flex">
                  <div class="pic mr-3">
                    <img :src="personPhoto" alt="Image" class="img-fluid" />
                  </div>
                  <div>
                    <strong class="d-block">{{ personName }}</strong><span class="d-block">{{ designation }}</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="container" style="display: block; margin-top: 30px;">
      <div class="row" style="text-align: justify;">
        <div
          class="col-md-6 mb-4 mb-lg-0 col-lg-3"
          data-aos="fade-up"
          data-aos-delay="0"
        >
          <div class="service">
            <div class="service-icon color-1 mb-4" :style="[items[0].iconBg]">
              <svg
                class="bi bi-app-indicator"
                width="1em"
                height="1em"
                viewBox="0 0 16 16"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M5.5 2A3.5 3.5 0 0 0 2 5.5v5A3.5 3.5 0 0 0 5.5 14h5a3.5 3.5 0 0 0 3.5-3.5V8a.5.5 0 0 1 1 0v2.5a4.5 4.5 0 0 1-4.5 4.5h-5A4.5 4.5 0 0 1 1 10.5v-5A4.5 4.5 0 0 1 5.5 1H8a.5.5 0 0 1 0 1H5.5z"
                />
                <path d="M16 3a3 3 0 1 1-6 0 3 3 0 0 1 6 0z" />
              </svg>
            </div>
            <div class="service-contents">
              <h3>{{ items[0].title }}</h3>
              <p>{{ items[0].description }}</p>
            </div>
          </div>
        </div>
        <div
          class="col-md-6 mb-4 mb-lg-0 col-lg-3"
          data-aos="fade-up"
          data-aos-delay="100"
        >
          <div class="service">
            <div class="service-icon color-2 mb-4" :style="[items[1].iconBg]">
              <svg
                class="bi bi-arrow-repeat"
                width="1em"
                height="1em"
                viewBox="0 0 16 16"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M2.854 7.146a.5.5 0 0 0-.708 0l-2 2a.5.5 0 1 0 .708.708L2.5 8.207l1.646 1.647a.5.5 0 0 0 .708-.708l-2-2zm13-1a.5.5 0 0 0-.708 0L13.5 7.793l-1.646-1.647a.5.5 0 0 0-.708.708l2 2a.5.5 0 0 0 .708 0l2-2a.5.5 0 0 0 0-.708z"
                />
                <path
                  fill-rule="evenodd"
                  d="M8 3a4.995 4.995 0 0 0-4.192 2.273.5.5 0 0 1-.837-.546A6 6 0 0 1 14 8a.5.5 0 0 1-1.001 0 5 5 0 0 0-5-5zM2.5 7.5A.5.5 0 0 1 3 8a5 5 0 0 0 9.192 2.727.5.5 0 1 1 .837.546A6 6 0 0 1 2 8a.5.5 0 0 1 .501-.5z"
                />
              </svg>
            </div>
            <div class="service-contents">
              <h3>{{ items[1].title }}</h3>
              <p>{{ items[1].description }}</p>
            </div>
          </div>
        </div>
        <div
          class="col-md-6 mb-4 mb-lg-0 col-lg-3"
          data-aos="fade-up"
          data-aos-delay="200"
        >
          <div class="service">
            <div class="service-icon color-3 mb-4" :style="[items[2].iconBg]">
              <svg
                class="bi bi-briefcase"
                width="1em"
                height="1em"
                viewBox="0 0 16 16"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M0 12.5A1.5 1.5 0 0 0 1.5 14h13a1.5 1.5 0 0 0 1.5-1.5v-6h-1v6a.5.5 0 0 1-.5.5h-13a.5.5 0 0 1-.5-.5v-6H0v6z"
                />
                <path
                  fill-rule="evenodd"
                  d="M0 4.5A1.5 1.5 0 0 1 1.5 3h13A1.5 1.5 0 0 1 16 4.5v2.384l-7.614 2.03a1.5 1.5 0 0 1-.772 0L0 6.884V4.5zM1.5 4a.5.5 0 0 0-.5.5v1.616l6.871 1.832a.5.5 0 0 0 .258 0L15 6.116V4.5a.5.5 0 0 0-.5-.5h-13zM5 2.5A1.5 1.5 0 0 1 6.5 1h3A1.5 1.5 0 0 1 11 2.5V3h-1v-.5a.5.5 0 0 0-.5-.5h-3a.5.5 0 0 0-.5.5V3H5v-.5z"
                />
              </svg>
            </div>
            <div class="service-contents">
              <h3>{{ items[2].title }}</h3>
              <p>{{ items[2].description }}</p>
            </div>
          </div>
        </div>
        <div
          class="col-md-6 mb-4 mb-lg-0 col-lg-3"
          data-aos="fade-up"
          data-aos-delay="300"
        >
          <div class="service">
            <div class="service-icon color-4 mb-4" :style="[items[3].iconBg]">
              <svg
                class="bi bi-collection"
                width="1em"
                height="1em"
                viewBox="0 0 16 16"
                fill="currentColor"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  fill-rule="evenodd"
                  d="M14.5 13.5h-13A.5.5 0 0 1 1 13V6a.5.5 0 0 1 .5-.5h13a.5.5 0 0 1 .5.5v7a.5.5 0 0 1-.5.5zm-13 1A1.5 1.5 0 0 1 0 13V6a1.5 1.5 0 0 1 1.5-1.5h13A1.5 1.5 0 0 1 16 6v7a1.5 1.5 0 0 1-1.5 1.5h-13zM2 3a.5.5 0 0 0 .5.5h11a.5.5 0 0 0 0-1h-11A.5.5 0 0 0 2 3zm2-2a.5.5 0 0 0 .5.5h7a.5.5 0 0 0 0-1h-7A.5.5 0 0 0 4 1z"
                />
              </svg>
            </div>
            <div class="service-contents">
              <h3>{{ items[3].title }}</h3>
              <p>{{ items[3].description }}</p>
            </div>
          </div>
        </div>
      </div>
    </div>
    </div>
  </div>
</template>

<style>
@import "../style.css";

.feature-page {
  background-color: #CCD591;
}

.description-features {
  font-family: 'Space Grotesk';
}

.img-ellipse {
  width: 35px;
  height: 35px;
}

.service-contents p {
  padding: 10px 10px 0px 0px;
  text-align: left;
}

h3 {
  margin-left: -18px;
  color: #436129;
  -webkit-text-fill-color: #436129;
}

p {
  margin-left: -45px;
  text-align: left;
  color:#000000;  
}
</style>