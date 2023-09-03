<script setup>
const heading = "Thanks to Contributor";
const subHeading = "Lorem ipsum dolor sit amet consectetur. Gravida venenatis aliquet leo elit feugiat nibh egestas purus sit.";
import icon_1 from "../assets/images/aboutIcon_1.svg";
import icon_2 from "../assets/images/aboutIcon_2.svg";
import icon_3 from "../assets/images/aboutIcon_3.svg";
import teamPhoto from "../assets/images/person_1.jpg";
const teamItems = [
  {
    name: "Chief Project Manager",
    team_1: teamPhoto,
    team_2: teamPhoto,
    team_3: teamPhoto,
  },
  {
    name: "Backend Developer",
    team_1: teamPhoto,
    team_2: teamPhoto,
    team_3: teamPhoto,
    team_4: teamPhoto,
  },
  {
    name: "UI/UX Designer",
    team_1: teamPhoto,
    team_2: teamPhoto,
    team_3: teamPhoto,
    team_4: teamPhoto,
  },
  {
    name: "Frontend Developer",
    team_1: teamPhoto,
    team_2: teamPhoto,
    team_3: teamPhoto,
    team_4: teamPhoto,
  },
  {
    name: "Quality Assurance",
    team_1: teamPhoto,
    team_2: teamPhoto,
  },
  {
    name: "Flutter Developer",
    team_1: teamPhoto,
    team_2: teamPhoto,
    team_3: teamPhoto,
    team_4: teamPhoto,
  },
];
</script>

<template>
  <div class="untree_co-section about-page" id="about-section">
    <div class="container-team ">
      <div class="row about-title mb-4">
        <div class="col-lg-2" data-aos="fade-right" data-aos-delay="400">
            <img :src="icon_1" alt="Image" class="img-fluid img-icon" />
        </div>
        <div class="col-lg-8 text-center" data-aos="fade-up" data-aos-delay="0">
            <h3 class="heading">{{ heading }}</h3>
            <p>{{ subHeading }}</p>
        </div>
        <div class="col-lg-2 ml-auto order-lg-2" data-aos="fade-left" data-aos-delay="400">
            <img :src="icon_2" alt="Image" class="img-fluid img-icon" style="width: 50px; height: 50px; position: absolute; bottom: 0; right: 0;" />
        </div>
      </div>
      <div class="row align-items-center justify-content-between team-container">
        <div class="team1" data-aos="fade-up" data-aos-delay="0">
          <div class="about-item">
            <div class="vcard d-flex align-items-center mb-4">
              <div class="post-meta">
                <strong>{{ teamItems[0].name }}</strong>
              </div>
            </div>
            <div class="about-contents">
              <div class="img-wrap">
                <a href="#">
                  <img :src="teamItems[0].team_1" alt="Image" class="img-fluid" />
                </a>
                <a href="#">
                  <img :src="teamItems[0].team_2" alt="Image" class="img-fluid" />
                </a>
                <a href="#">
                  <img :src="teamItems[0].team_3" alt="Image" class="img-fluid" />
                </a>
              </div>
            </div>
          </div>
        </div>
        <div class="team2" data-aos="fade-up" data-aos-delay="0">
          <div class="about-item">
            <div class="vcard d-flex align-items-center mb-4">
              <div class="post-meta">
                <strong>{{ teamItems[1].name }}</strong>
              </div>
            </div>
            <div class="about-contents">
              <div class="img-wrap">
                <a href="#">
                  <img :src="teamItems[1].team_1" alt="Image" class="img-fluid" />
                </a>
                <a href="#">
                  <img :src="teamItems[1].team_2" alt="Image" class="img-fluid" />
                </a>
                <a href="#">
                  <img :src="teamItems[1].team_3" alt="Image" class="img-fluid" />
                </a>
                <a href="#">
                  <img :src="teamItems[1].team_4" alt="Image" class="img-fluid" />
                </a>
              </div>
            </div>
          </div>
        </div>
        <div class="team" data-aos="fade-up" data-aos-delay="0">
          <div class="about-item">
            <div class="vcard d-flex align-items-center mb-4">
              <div class="post-meta">
                <strong>{{ teamItems[2].name }}</strong>
              </div>
            </div>
            <div class="about-contents">
              <div class="img-wrap">
                <a href="#">
                  <img :src="teamItems[2].team_1" alt="Image" class="img-fluid" />
                </a>
                <a href="#">
                  <img :src="teamItems[2].team_2" alt="Image" class="img-fluid" />
                </a>
                <a href="#">
                  <img :src="teamItems[2].team_3" alt="Image" class="img-fluid" />
                </a>
                <a href="#">
                  <img :src="teamItems[2].team_4" alt="Image" class="img-fluid" />
                </a>
              </div>
            </div>
          </div>
        </div>
        <div class="team" data-aos="fade-up" data-aos-delay="0">
          <div class="about-item">
            <div class="vcard d-flex align-items-center mb-4">
              <div class="post-meta">
                <strong>{{ teamItems[3].name }}</strong>
              </div>
            </div>
            <div class="about-contents">
              <div class="img-wrap">
                <a href="#">
                  <img :src="teamItems[3].team_1" alt="Image" class="img-fluid" />
                </a>
                <a href="#">
                  <img :src="teamItems[3].team_2" alt="Image" class="img-fluid" />
                </a>
                <a href="#">
                  <img :src="teamItems[3].team_3" alt="Image" class="img-fluid" />
                </a>
                <a href="#">
                  <img :src="teamItems[3].team_4" alt="Image" class="img-fluid" />
                </a>
              </div>
            </div>
          </div>
        </div>
        <div class="team" data-aos="fade-up" data-aos-delay="0">
          <div class="about-item">
            <div class="vcard d-flex align-items-center mb-4">
              <div class="post-meta">
                <strong>{{ teamItems[4].name }}</strong>
              </div>
            </div>
            <div class="about-contents">
              <div class="img-wrap">
                <a href="#">
                  <img :src="teamItems[4].team_1" alt="Image" class="img-fluid" />
                </a>
                <a href="#">
                  <img :src="teamItems[4].team_2" alt="Image" class="img-fluid" />
                </a>
              </div>
            </div>
          </div>
        </div>
        <div class="team" data-aos="fade-up" data-aos-delay="0">
          <div class="about-item">
            <div class="vcard d-flex align-items-center mb-4">
              <div class="post-meta">
                <strong>{{ teamItems[5].name }}</strong>
              </div>
            </div>
            <div class="about-contents">
              <div class="img-wrap">
                <a href="#">
                  <img :src="teamItems[5].team_1" alt="Image" class="img-fluid" />
                </a>
                <a href="#">
                  <img :src="teamItems[5].team_2" alt="Image" class="img-fluid" />
                </a>
                <a href="#">
                  <img :src="teamItems[5].team_3" alt="Image" class="img-fluid" />
                </a>
                <a href="#">
                  <img :src="teamItems[5].team_4" alt="Image" class="img-fluid" />
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div>
        <img :src="icon_3" alt="Image" class="img-fluid img-icon icon-about">
      </div>
    </div>
  </div>
</template>

<style>
@import "../style.css";

.container-team{
  width: 1280px;
  height: 520px;
  margin: auto;
} 

/* .team1{
  width: 40px;
  height: 161px;
}

.team2{
  width: 450px;
  height: 161px;
} */

.about-page{
  background-color: #CCD591;
}

.about-title h3 {
  color: #436129;
}

.img-icon {
  width: 120px;
  height: 120px;
}

.icon-about {
  margin-left: 1020px;
  margin-top: -90px;
  width: 150px;
  height: 150px;
}

.about-item {
  background: #ffffff;
  border-radius: 15px;
  padding: 20px;
  position: relative;
  margin: 10px;
  align-items: center;
}

.about-item:hover {
  background: #92A760;
}

.about-item .about-contents .img-wrap {
  -webkit-box-flex: 0;
  -ms-flex: 0 0 50px;
  flex: 0 0 50px;
  top: 0;
}

.about-item .about-contents .img-wrap img {
  width: 75px;
  height: 75px;
  margin-left: 10px;
  margin-right: 10px;
  border-radius: 50%;  
  -webkit-transition: transform 0.2s ease-in-out;
  transition: transform 0.2s ease-in-out; 
}

.about-item .about-contents .img-wrap img:hover {
  transform: scale(1.1);
}

.about-item .vcard .post-meta {
  line-height: 1.4; 
}

.about-item .vcard .post-meta strong {
  font-weight: 400;
  display: block;
  font-weight: 700;
  color: #000000;
}
</style>
