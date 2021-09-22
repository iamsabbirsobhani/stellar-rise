<template>
  <div class="game-features">
    <section class="ic-section ic-game-features pb-5" id="ICGameFeatures">
      <div class="container">
        <div class="ic-section-title right">
          <h1 class="wow fadeInUp animated" style="visibility: visible">
            GAME FEATURES
          </h1>
          <div
            class="ic-section-sub-title wow fadeIn ls-06em animated"
            style="visibility: visible"
          >
            <span>#</span>GAME
          </div>
        </div>
        <p class="mt-4 fs-20 text-end">
          CHARACTER CUSTOMIZATION across elements, roles, rarity, skills.
          <br />PvE (player vs environment)-PvP (player vs player)-PvP Area
          (player vs players)
        </p>
        <div class="row mt-3">
          <div class="col-xl-9">
            <div
              class="
                swiper-container
                featuresSwiper
                pt-4
                pb-5
                wow
                slideInLeft
                animated
              "
              style="visibility: visible"
            >
              <img src="../assets/features/f3.png" class="w-100" alt="1" />
            </div>
          </div>
          <div class="col-xl-3">
            <div
              class="ic-features-more wow slideInRight animated"
              style="visibility: visible"
            >
              <div
                class="ic-features-more-item active wow fadeInUp animated"
                data-wow-delay=".1s"
                data-bs-toggle="tooltip"
                title=""
                data-bs-original-title="Fire"
                style="visibility: visible; animation-delay: 0.1s"
              >
                <span class="ic-f-elements">Elements</span>
                <img src="../assets/features/e-1.png" />
              </div>
              <div
                class="ic-features-more-item wow fadeInUp animated"
                data-wow-delay=".1s"
                data-bs-toggle="tooltip"
                title=""
                data-bs-original-title="Water"
                style="visibility: visible; animation-delay: 0.1s"
              >
                <span class="ic-f-elements">Elements</span>
                <img src="../assets/features/e-2.png" />
              </div>
              <div
                class="ic-features-more-item wow fadeInUp animated"
                data-wow-delay=".1s"
                data-bs-toggle="tooltip"
                title=""
                data-bs-original-title="Grass"
                style="visibility: visible; animation-delay: 0.1s"
              >
                <span class="ic-f-elements">Elements</span>
                <img src="../assets/features/e-3.png" />
              </div>
              <div
                class="ic-features-more-item wow fadeInUp animated"
                data-wow-delay=".1s"
                data-bs-toggle="tooltip"
                title=""
                data-bs-original-title="Thunder"
                style="visibility: visible; animation-delay: 0.1s"
              >
                <span class="ic-f-elements">Elements</span>
                <img src="../assets/features/e-4.png" />
              </div>
              <div
                class="ic-features-more-item wow fadeInUp animated"
                data-wow-delay=".1s"
                data-bs-toggle="tooltip"
                title=""
                data-bs-original-title="Rock"
                style="visibility: visible; animation-delay: 0.1s"
              >
                <span class="ic-f-elements">Elements</span>
                <img src="../assets/features/e-5.png" />
              </div>
              <div
                class="ic-features-more-item wow fadeInUp animated"
                data-wow-delay=".1s"
                data-bs-toggle="tooltip"
                title=""
                data-bs-original-title="Ice"
                style="visibility: visible; animation-delay: 0.1s"
              >
                <span class="ic-f-elements">Elements</span>
                <img src="../assets/features/e-6.png" />
              </div>
              <div
                class="ic-features-more-item wow fadeInUp animated"
                data-wow-delay=".1s"
                data-bs-toggle="tooltip"
                title=""
                data-bs-original-title="Common"
                style="visibility: visible; animation-delay: 0.1s"
              >
                <span class="ic-f-rarities">Rarities</span>
                <img src="../assets/features/rar-1.png" />
              </div>
              <div
                class="ic-features-more-item wow fadeInUp animated"
                data-wow-delay=".1s"
                data-bs-toggle="tooltip"
                title=""
                data-bs-original-title="Rare"
                style="visibility: visible; animation-delay: 0.1s"
              >
                <span class="ic-f-rarities">Rarities</span>
                <img src="../assets/features/rar-2.png" />
              </div>
              <div
                class="ic-features-more-item wow fadeInUp animated"
                data-wow-delay=".1s"
                data-bs-toggle="tooltip"
                title=""
                data-bs-original-title="Epic"
                style="visibility: visible; animation-delay: 0.1s"
              >
                <span class="ic-f-rarities">Rarities</span>
                <img src="../assets/features/rar-3.png" />
              </div>
              <div
                class="ic-features-more-item wow fadeInUp animated"
                data-wow-delay=".1s"
                data-bs-toggle="tooltip"
                title=""
                data-bs-original-title="Legend"
                style="visibility: visible; animation-delay: 0.1s"
              >
                <span class="ic-f-rarities">Rarities</span>
                <img src="../assets/features/rar-4.png" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
/* Features */

.ic-features-more {
  padding: 15px 15px 30px 20px;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 45px;
  text-align: center;
  background-image: url(../assets/features/features-more-bg.png);
  background-size: 100% 100%;
}

.ic-features-more-item {
  background-color: #3c5a8523;
  width: calc(50% - 5px);
  padding: 10px 8px;
  border-radius: 10px;
  position: relative;
}

.ic-features-more-item::before,
.ic-features-more-item::after {
  position: absolute;
  content: "";
  top: 0;
  height: 100%;
  width: 20px;
  border: 1px solid #3c5a85;
  transition: all ease-in-out 0.4s;
}

.ic-features-more-item::before {
  left: 0;
  border-radius: 6px 0 0 6px;
  border-right: none;
}

.ic-features-more-item::after {
  right: 0;
  border-radius: 0 6px 6px 0;
  border-left: none;
}

.ic-features-more-item.active,
.ic-features-more-item:hover {
  background-color: #3c5a8562;
  box-shadow: 1px 2px 20px rgba(0, 0, 0, 0.3);
}

.ic-features-more-item.active::before,
.ic-features-more-item.active::after,
.ic-features-more-item:hover::before,
.ic-features-more-item:hover::after {
  border-color: #42bed2;
}

.ic-features-more-item img {
  max-height: 68px;
}

.ic-features-more-item span {
  position: absolute;
  top: 5px;
  left: 4px;
  background-color: red;
  color: #fff;
  padding: 2px 4px;
  font-size: 12px;
  line-height: 1;
  border-radius: 3px;
}

.ic-features-more-item span.ic-f-elements {
  background-color: #42bed2;
  color: #000;
}

.ic-features-more-item span.ic-f-rarities {
  background-color: #ff9533;
  color: #000;
}

.ic-features-more img {
  max-width: 100%;
}

.swiper-container {
  width: 100%;
  padding-top: 50px;
  padding-bottom: 50px;
  overflow: hidden;
}

.swiper-slide {
  background-position: center;
  background-size: cover;
  width: 280px;
  height: 374px;
}

.swiper-slide img {
  display: block;
  width: 100%;
  border-radius: 10px;
  box-shadow: 1px 2px 20px #12091f8a;
}

@media (max-width: 1024px) {
  .ic-features-more {
    display: none !important;
  }
}

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
</style>
