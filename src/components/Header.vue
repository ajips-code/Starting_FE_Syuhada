<script setup>
import { themeColor, siteName} from "../data/items";
import siteLogo from "../assets/images/logo.svg";

</script>
<template>
  <nav class="site-nav dark js-site-navbar mb-5 site-navbar-target">
    <div class="container">
      <div class="site-navigation">
        <img :src="siteLogo" alt="Image" class="img-fluid mr-2" />
        <a href="" class="logo mr-2 float-rigt">{{ siteName }}<span class="text-primary"></span></a>
        <ul class="js-clone-nav d-none d-lg-inline-block site-menu float-right">
          <li class="active">
            <a href="#home-section" class="nav-link">Beranda</a>
          </li>
          <li><a href="#features-section" class="nav-link">Fitur</a></li>
          <li><a href="#pricing-section" class="nav-link">Download</a></li>
          <li><a href="#map-section" class="nav-link">Maps</a></li>
          <li><a href="#about-section" class="nav-link">About</a></li>
          <li><a href="#contact-section" class="nav-link">Contact Me</a></li>
        </ul>

        <a href="#" class="burger ml-auto float-right site-menu-toggle js-menu-toggle d-inline-block dark d-lg-none"
          data-toggle="collapse" data-target="#main-navbar">
          <span></span>
        </a>
      </div>
    </div>
  </nav>
</template>
