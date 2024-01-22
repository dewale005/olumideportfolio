<script setup lang="ts">
</script>

<template>
  <!--<< banner >>-->
  <section class="banner__section">
    <!--<< Header v-1 >>-->
    <header class="header-section">
      <div class="container">
        <div class="header-wrapper">
          <div class="main__logo">
            <a href="/" class="logo">
              <img src="/src/assets/img/logo/black name.png" alt="logo" />
            </a>
          </div>
          <ul class="main-menu">
            <li>
              <a href="/"> Home </a>
            </li>
            <li>
              <a href="#about"> About </a>
            </li>
            <li>
              <a href="#prot"> Work </a>
            </li>
            <li>
              <a href="/"> Contact </a>
            </li>
          </ul>
          <div class="menu__components d-flex align-items-center">
            <a href="contact.html" class="d-flex fw-500 cmn--btn align-items-center gap-2">
              <span class="get__text"> Let's Talk </span>
              <span>
                <i class="bi bi-arrow-right fz-20"></i>
              </span>
            </a>
            <div class="header-bar d-lg-none">
              <span></span>
              <span></span>
              <span></span>
            </div>
            <div class="remove__click">
              <i class="bi bi-list"></i>
            </div>
          </div>
        </div>
      </div>
    </header>
    <!--<< Header v-1 >>-->
    <div class="container">
      <div class="row g-4">
        <div class="col-lg-8">
          <div class="banner__content">
            <a href="/resume.pdf" target="_blank" class="bn__currently">
              <!-- <span class="d-block"> Currently available for freelance </span> -->
              <span class="d-flex gap-4 align-items-center">
                Download Resume
                <i class="bi bi-arrow-up-right"></i>
              </span>
            </a>
            <h1>
              <span class="hone"> Abdulazeez Abioye</span>
              <span class="d-block designers" data-text="Portfolio">Portfolio</span>
            </h1>
            <div class="video__area">
              <img src="/src/assets/img/banner/bn-arrow.png" class="vid__arrow" alt="img" />
              <a
                href="https://www.youtube.com/watch?v=zFuJgOiUEso&amp;ab_channel=SujithRajendran"
                class="video__80 video-btn"
              >
                <i class="bi bi-play-fill"></i>
              </a>
              <span class="proces"> Work Process </span>
            </div>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="banner__thumb">
            <img src="/src/assets/img/banner/grey.png" style="width:  100%; height: fit-content; opacity: 0.9;" alt="man-img" />
          </div>
        </div>
      </div>
    </div>
    <div class="banner__leftinfo">
      <div class="left__infomobile">
        <a href="#0">
          <img src="/src/assets/img/banner/dial.png" alt="img" />
        </a>
        <a href="tel:+44738556496"> (+44)-738-556-496 </a>
      </div>
      <div class="right__infoscroll">
        <a href="#prot" class="scroll"> scroll down </a>
        <a href="#prot" class="scroll__bar">
          <img src="/src/assets/img/banner/scroll-down.png" alt="img" />
        </a>
      </div>
    </div>
    <div class="banner__rightinfo">
      <div class="right__infoscroll">
        <a class="scroll"> Follow Me </a>
        <a href="#0" class="scroll__bar">
          <img src="/src/assets/img/banner/scroll-down.png" alt="img" />
        </a>
      </div>
      <div class="banner__xlsocial">
        <ul class="banner__soci d-grid justify-content-center">
          <li>
            <a href=" https://www.behance.net/hayzedcreativesuites" target="_blank">
              <i class="bi bi-behance"></i>
            </a>
          </li>
          <li>
            <a href="https://twitter.com/smmedia126" target="_blank">
              <i class="bi bi-twitter"></i>
            </a>
          </li>
          <li>
            <a href="https://www.instagram.com/hhayzed/" target="_blank">
              <i class="bi bi-instagram"></i>
            </a>
          </li>
          <li>
            <a href=" https://www.linkedin.com/in/abdulazeez-abioye-0b7503160/" target="_blank">
              <i class="bi bi-linkedin"></i>
            </a>
          </li>
        </ul>
      </div>
    </div>
  </section>
  <!--<< banner >>-->
</template>
