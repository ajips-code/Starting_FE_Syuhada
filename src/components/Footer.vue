<script setup>
import { themeColor, siteName } from "../data/items";
import whiteLogo from "../assets/images/logo_white.svg";
const copyrightText = "Made with ❤️ | DevSyuhada © 2023";
const column1Text =
  "Kontak kami jika anda memiliki saran dan kritik, masukan anda sangat berarti bagi kami";
const column2Heading = "Media Sosial";
const column3Heading = "Menu Utama";
const socialItems = [
  {
    link: "https://www.instagram.com/"
  },
  {
    link: "https://www.twitter.com/"
  },
  {
    link: "https://www.facebook.com/"
  },
  {
    link: "https://www.youtube.com/"
  },
];
</script>

<template>
  <div class="footer">
    <div class="container">
      <div class="row">
        <div class="col-lg-4">
          <div class="widget mb-4">
            <div class="logo-and-menu-container">
              <div class="logo-container">
                <img :src="whiteLogo" alt="Image" class="img-fluid mr-2" />
                <a href="#" class="text-logo-footer">{{ siteName }}</a>
              </div>
              <div class="text-logo-container">
                <span class="text-logo-small-footer">Apps</span>
              </div>
            </div>
          </div>
          <div class="excerpt-footer">
              <p>{{ column1Text }}</p>
              <a href="#contact-section" class=" button-footer smoothscroll">Contact Me</a>
          </div>
        </div>
        <div class="col-lg-2 ml-auto mt-5" style="text-align: right;">
          <div class="widget text-footer">
            <ul class="list-unstyled links">
              <h6>{{ column2Heading }}</h6>
              <li><a :href="socialItems[0].link">Instagram</a></li>
              <li><a :href="socialItems[1].link">Twitter</a></li>
              <li><a :href="socialItems[2].link">Facebook</a></li>
              <li><a :href="socialItems[3].link">Youtube</a></li>
            </ul>
          </div>
        </div>
        <div class="col-lg-2 mt-5" style="text-align: right;">
          <div class="widget text-footer">
            <ul class="list-unstyled links">
              <h6 class="mb-3">{{ column3Heading }}</h6>
              <li><a href="#">Beranda</a></li>
              <li><a href="#">Fitur</a></li>
              <li><a href="#">Download</a></li>
              <li><a href="#">Maps</a></li>
            </ul>
          </div>
        </div>
      </div>
      <div class="row mt-5">
        <div class="col-12 text-center">
          <span>
            {{ copyrightText }}
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
@import "../style.css";

.footer {
  background-color: #436129;
  padding-top: 50px;
  padding-bottom: 5px;
  color: #fff;
}

.text-logo-footer {
  margin-right: 3px; /* Adjust margin as needed */
  font-weight: bold; /* Example style */
  color: #fff;
  font-size: 25.04px;
  font-family: "Space Grotesk";
}

.text-logo-small-footer {
  font-weight: normal; /* Example style for thinner font */
  display: block; /* Display the element as a block to move it to a new line */
  margin-top: 45px; /* Adjust margin as needed */
  margin-left: -110px;
  color: #fff;
  font-size: 25.04px; 
  font-family: "Space Grotesk";
}

.text-logo-footer {
  margin-right: 3px; /* Adjust margin as needed */
  font-weight: bold; /* Example style */
  color: #fff;
  font-size: 25.04px;
  font-family: "Space Grotesk";
}

.text-logo-footer:hover {
  color: #fff;
}

.text-logo-small-footer {
  font-weight: normal; /* Example style for thinner font */
  display: block; /* Display the element as a block to move it to a new line */
  margin-top: 45px; /* Adjust margin as needed */
  margin-left: -110px;
  color: #fff;
  font-size: 25.04px;
  font-family: "Space Grotesk";
}

.excerpt-footer p {
  font-family: 'Roboto', sans-serif;
  margin-left: 0px;
  color:#fff; 
}

.button-footer{
  display: inline-block;
  padding: 5px 10px;
  background-color: #fff; /* Button background color */
  color: #436129; /* Button text color */
  border-radius: 10px; /* Button border radius */
  text-decoration: none;
  font-size: 16px;
  font-family: "Space Grotesk";
  font-weight: bold;
  transition: background-color 0.3s ease, color 0.3s ease;
}

.button-footer:hover {
  background-color: #fff; /* Hover background color */
  color: #000000; /* Hover text color */
}

.text-footer {
  color: #fff;
  font-family: 'Roboto', sans-serif;
}

.text-footer h6 {
  color: #fff;
}

.links a {
  color: #fff;
}

.links a:hover {
  color: #CCD591;
}
</style>