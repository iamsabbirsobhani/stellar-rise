<template>
  <div class="navbar">
    <div class="ic-navigation">
      <nav
        class="navbar navbar-expand-lg navbar-dark ic-navigation-navbar w-100"
        id="ICHeaderNavbar"
      >
        <div class="container">
          <a class="navbar-brand d-lg-none" href="#home">
            <img src="../assets/mobileLogoFinal.png" alt="Warena" />
          </a>
          <!-- <ul class="social-top">
            <li>
              <span>Follow us:</span>
            </li>
            <li>
              <a
                target="_blank"
                href="https://t.me/warenaofficial"
                class="telegram"
              >
                <i class="fab fa-telegram" title="Telegram"></i>
              </a>
            </li>
            <li>
              <a href="https://discord.gg/kkHQcNmE" class="fab fa-discord"> </a>
            </li>
            <li>
              <a
                target="_blank"
                href="https://twitter.com/warenaofficial"
                class="twitter"
              >
                <i class="fab fa-twitter" title="Twitter"></i>
              </a>
            </li>
            <li>
              <a
                target="_blank"
                href="https://medium.com/warena"
                class="medium"
              >
                <i class="fab fa-medium-m" title="Medium"></i>
              </a>
            </li>
            <li>
              <a
                target="_blank"
                href="https://www.youtube.com/channel/UCQnmYpytaibTz6Uw-K6LcxQ"
                class="youtube"
              >
                <i class="fab fa-youtube" title="Youtube"></i>
              </a>
            </li>
          </ul> -->
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div
            class="
              row
              collapse
              navbar-collapse
              d-lg-flex
              justify-content-lg-between
              w-100
            "
            id="navbarSupportedContent"
          >
            <ul
              class="
                col-lg-5
                pe-lg-0
                ic-navigation-navbar-nav
                navbar-nav
                justify-content-lg-between
                align-items-lg-center
              "
            >
              <li class="nav-item">
                <a class="nav-link" href="#ICAbout">
                  <span>About Stellar RISE</span>
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="#ICMetaverse">
                  <span>Metaverse</span>
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#ICGameFeatures">
                  <span>Features</span>
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#WAREToken">
                  <span>Token</span>
                </a>
              </li>
            </ul>
            <a
              class="navbar-brand navbar-brand-lg me-0 d-lg-block d-none"
              href="#home"
            >
              <img src="../assets/mobileLogoFinal.png" alt="Warena" />
            </a>
            <ul
              class="
                col-lg-5
                ps-lg-0
                ic-navigation-navbar-nav
                navbar-nav
                justify-content-lg-between
                align-items-lg-center align-items-end
              "
            >
              <li class="nav-item">
                <a class="nav-link" href="#ICRoadmap">
                  <span>Roadmap</span>
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#ICTeams">
                  <span>Team</span>
                </a>
              </li>

              <li class="nav-item">
                <a class="nav-link" href="#ICAdvisors">
                  <span>Advisor</span>
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#ICContact">
                  <span>Contact</span>
                </a>
              </li>
              <li class="nav-item">
                <a
                  class="
                    nav-link
                    ic-btn ic-btn-v2 ic-btn-primary
                    px-3 px-xl-4
                    ic-btn-play
                    text-nowrap
                    d-flex
                    align-items-center
                  "
                  target="_blank"
                  href="https://warena.gitbook.io/warena/"
                >
                  <!-- href="https://play.warena.io/" -->
                  <i class="fas fa-fire me-2 mb-1"></i>Play
                </a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.ic-section {
  padding-top: 120px;
  padding-bottom: 60px;
}

.ic-text-primary {
  color: #42bed2 !important;
}

.text-justify {
  text-align: justify;
}

.no-gutters > .col,
.no-gutters > [class*="col-"] {
  padding-right: 0;
  padding-left: 0;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: Rajdhani, sans-serif;
  font-weight: 700;
}

.ic-f-item {
  padding: 20px;
  margin-bottom: 20px;
  text-transform: uppercase;
  position: relative;
  background-color: #3c5a8523;
  transition: all ease-in-out 0.4s;
  font-size: 16px;
}

.ic-f-item span {
  font-size: 18px;
}

.ic-f-item::before,
.ic-f-item::after {
  position: absolute;
  content: "";
  top: 0;
  height: 100%;
  width: 45px;
  border: 1px solid #3c5a85;
  transition: all ease-in-out 0.4s;
}

.ic-f-item::before {
  left: 0;
  border-radius: 6px 0 0 6px;
  border-right: none;
}

.ic-f-item::after {
  right: 0;
  border-radius: 0 6px 6px 0;
  border-left: none;
}

.ic-f-item:hover {
  background-color: #3c5a8562;
  box-shadow: 1px 2px 20px rgba(0, 0, 0, 0.3);
}

.ic-f-item:hover::before,
.ic-f-item:hover::after {
  border-color: #42bed2;
}

.ic-f-item h4 {
  font-weight: bold;
  margin-bottom: 15px;
  transition: all ease-in-out 0.3s;
  color: #fff;
}

.ic-f-item:hover h4 {
  color: #42bed2;
}

.ic-f-item p {
  text-transform: none;
}

.ic-f-item-full-height {
  height: calc(100% - 30px);
}

@media (min-width: 1024px) {
  h3 {
    font-size: 35px;
  }
}

@media (max-width: 767px) {
  .ic-section {
    padding-top: 50px;
    padding-bottom: 50px;
  }
}

@media (max-width: 1023px) {
  .ic-f-item {
    font-size: 16px;
    padding: 20px !important;
  }
}

.ic-section-title {
  padding: 0 0 0 45px;
  overflow: hidden;
  position: relative;
}

.ic-section-title h1 {
  font-size: 80px;
  font-weight: bold;
  margin: 0;
  text-transform: uppercase;
  line-height: 1;
  color: #fff;
}

.ic-section-sub-title {
  position: absolute;
  bottom: 2px;
  left: 6px;
  font-size: 15px;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.15em;
  color: #fff;
  transform: rotate(-90deg) translateX(0) !important;
  transform-origin: left center;
}

.ls-06em {
  letter-spacing: 0.06em;
}

.ls-0em {
  letter-spacing: 0em;
}

.ic-section-sub-title span {
  color: #42bed2;
}

.ic-section-title.center {
  padding-left: 0 !important;
  padding-right: 0 !important;
  text-align: center;
}

.ic-section-title.right {
  padding-left: 0;
  padding-right: 45px;
}

.ic-section-title.right h1 {
  text-align: right;
}

.ic-section-title.right .ic-section-sub-title {
  right: 6px;
  left: auto;
  transform: rotate(-90deg) translateX(100%) !important;
  transform-origin: right center;
}

@media (max-width: 1024px) {
  .ic-section-title h1 {
    font-size: 58px;
  }
  .ic-section-sub-title {
    letter-spacing: 0.1em;
    font-size: 12px;
    bottom: -8px;
  }
}

@media (max-width: 767px) {
  .ic-section-title {
    padding-left: 30px;
  }
  .ic-section-title h1 {
    font-size: 42px;
  }
  .ic-section-sub-title {
    left: 12px;
    letter-spacing: 0.1em;
    font-size: 9px;
    bottom: -8px;
  }
  .ic-section-title.right {
    padding-right: 30px;
    padding-left: 0;
  }
  .ic-section-title.right .ic-section-sub-title {
    right: 12px;
    left: auto;
  }
}

/* 2. BUTTON */

.ic-btn {
  position: relative;
  width: auto;
  margin: 0;
  font-family: Rajdhani, sans-serif;
  font-size: 17px;
  line-height: 2em;
  font-weight: 600;
  letter-spacing: 0.1em;
  text-transform: uppercase;
  outline: 0;
  box-sizing: border-box;
  transition: color 0.2s ease-in-out, background-color 0.2s ease-in-out,
    border-color 0.2s ease-in-out;
  padding: 10px 65px;
  border: 2px solid #42bed2;
  display: inline-block;
  vertical-align: middle;
  overflow: hidden;
}

.ic-btn-text {
  position: relative;
  z-index: 2;
}

.ic-btn-hover {
  background-color: #42bed2;
  position: absolute;
  display: block;
  top: 104%;
  left: -114%;
  width: 150%;
  height: 600%;
  z-index: 1;
  transform: rotate(45deg) translate3d(0, 0, 0);
  transition: 0.5s cubic-bezier(0.24, 0.69, 0.12, 0.9);
  pointer-events: none;
}

.ic-btn:hover .ic-btn-hover {
  transition: 0.5s cubic-bezier(0.1, 0.48, 0.25, 0.86);
  transform: rotate(45deg) translate3d(0, -85%, 0);
}

.ic-btn-v2 {
  background-color: transparent !important;
  border: 2px solid #42bed2;
  clip-path: polygon(
    0 0,
    calc(100% - 20px) 0,
    100% 20px,
    100% 100%,
    20px 100%,
    0 calc(100% - 20px)
  );
}

.ic-btn-v2::before,
.ic-btn-v2::after {
  content: "";
  position: absolute;
  background-color: #42bed2;
  width: 60px;
  height: 2px;
  transform: rotate(45deg);
}

.ic-btn-v2::before {
  top: 0;
  right: -14px;
}

.ic-btn-v2::after {
  bottom: 0;
  left: -14px;
}

/* Button outline primary */

.ic-btn-outline-primary,
.ic-btn-primary {
  color: #fff !important;
  border-color: #42bed2 !important;
}

.ic-btn-outline-primary:hover,
.ic-btn-primary {
  background-color: #42bed2 !important;
}

.ic-btn-primary .ic-btn-hover {
  background-color: #4cdbf1;
}

/* Brand Logo */

.navbar-brand img {
  height: 70px;
  // width: 100px;
}

.navbar-brand-lg {
  position: absolute;
  top: 0;
  left: 50%;
  transform: translateX(-50%);
  width: auto;
  padding-top: 0 !important;
  padding-bottom: 0 !important;
}

.navbar-brand-lg img {
  height: 90px;
  // width: 120px;
  margin: 5px;
}

/* Navigation */

.ic-navigation {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  transition: all 0.3s ease-out;
  z-index: 999;
  background-color: #060c17c7;
  box-shadow: 3.5px 6.1px 30px rgb(0 0 0 / 57%);
  //   background-image: url(../images/bg.png);
  background-size: cover;
  background-position: center center;
}

.ic-navigation-navbar {
  padding-top: 14px !important;
  padding-bottom: 14px !important;
}

.ic-navigation-navbar-nav {
  min-height: 70px;
}

.ic-navigation-navbar-nav a {
  padding: 0;
  display: flex;
  height: 100%;
}

.ic-navigation-navbar-nav a span {
  position: relative;
  display: inline-block;
  width: 100%;
  vertical-align: top;
  font-size: 17px;
  letter-spacing: 0.1em;
  box-sizing: border-box;
  font-weight: 600;
  line-height: 20px;
  text-transform: uppercase;
  color: #fff !important;
  opacity: 1;
  white-space: nowrap;
}

.ic-navigation-navbar-nav a span::after {
  content: "";
  position: absolute;
  bottom: -9px;
  left: 0;
  display: inline-block;
  width: 100%;
  height: 4px;
  background-color: #42bed2;
  transform-origin: left;
  transform: scaleX(0);
  transition: 0.3s cubic-bezier(0.47, 0.11, 0, 0.96);
}

.ic-navigation-navbar-nav a.active span::after,
.ic-navigation-navbar-nav a:hover span::after {
  transform: scaleX(1);
}

.navbar {
  padding: 0;
}

@media (min-width: 1400px) {
  .ic-mx-1400 {
    margin-left: 30px !important;
    margin-right: 30px !important;
  }
}

@media (max-width: 1024px) {
  .ic-navigation-navbar-nav a {
    padding: 10px 12px !important;
    text-align: right;
  }
  .ic-navigation-navbar-nav a span {
    display: inline !important;
  }
}
</style>
