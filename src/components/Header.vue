<script setup>
import { themeColor, siteName } from "../data/items";
import siteLogo from "../assets/images/logo.svg";

</script>
<template>
  <nav class="site-nav dark js-site-navbar mb-5 site-navbar-target">
    <div class="container">
      <div class="site-navigation">
        <div class="logo-and-menu-container">
          <div class="logo-container">
            <img :src="siteLogo" alt="Image" class="img-fluid mr-2" />
            <a href="#" class="text-logo-header">{{ siteName }}</a>
          </div>
          <div class="text-logo-container">
            <span class="text-logo-small">Apps</span>
          </div>
          <ul class="js-clone-nav d-none d-lg-inline-block site-menu">
            <li class="active">
              <a href="#home-section" class="nav-link">Beranda</a>
            </li>
            <li><a href="#features-section" class="nav-link">Fitur</a></li>
            <li><a href="#pricing-section" class="nav-link">Download</a></li>
            <li><a href="#map-section" class="nav-link">Maps</a></li>
            <li><a href="#about-section" class="nav-link">About</a></li>
            <li class="contact-text"><a href="#contact-section" class="nav-link button">Contact Me</a></li>
          </ul>
        </div>
        <a href="#" class="burger ml-auto float-right site-menu-toggle js-menu-toggle d-inline-block dark d-lg-none"
          data-toggle="collapse" data-target="#main-navbar">
          <span></span>
        </a>
      </div>
    </div>
  </nav>
</template>

<style>
/* Import the style.css file */
@import "../style.css";
</style>
