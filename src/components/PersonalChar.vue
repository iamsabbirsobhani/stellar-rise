<template>
  <div class="per-char">
    <div class="container mt-5 pt-5">
      <div class="ic-section-title text-center">
        <h1 class="wow fadeInUp animated" style="visibility: visible">
          Personalized Character
        </h1>
      </div>
      <div class="row gx-xl-4 gx-md-5 gy-md-3 mt-5">
        <div class="col-xl-4 col-md-6 mt-5 mt-md-0">
          <div
            class="ic-f-item-flow wow fadeInUp animated"
            data-wow-delay=".1s"
            style="visibility: visible; animation-delay: 0.1s"
          >
            <div class="ic-f-item">
              <img
                src="../assets/0.png"
                alt="Avatar created by Voila AI Artist"
              />
            </div>
            <div class="ic-f-item-flow-title">
              Avatar created by Voila AI Artist
            </div>
            <div class="ic-f-item-flow-desc">
              The end-users<b class="ic-text-primary">
                uploads their personalized</b
              >
              Voila AI Artist avatars
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-md-6 mt-5 mt-md-0">
          <div
            class="ic-f-item-flow wow fadeInUp animated"
            data-wow-delay=".1s"
            style="visibility: visible; animation-delay: 0.1s"
          >
            <div class="ic-f-item">
              <img src="../assets/b1.png" alt="Character template" />
            </div>
            <div class="ic-f-item-flow-title">Character template</div>
            <div class="ic-f-item-flow-desc">
              <b class="text-danger">Configure</b> their preference body parts
            </div>
          </div>
        </div>
        <div class="col-xl-4 col-md-6 mt-5 mt-xl-0">
          <div
            class="ic-f-item-flow wow fadeInUp animated"
            data-wow-delay=".1s"
            style="visibility: visible; animation-delay: 0.1s"
          >
            <div class="ic-f-item">
              <img
                src="../assets/b5.png"
                alt=" Personalized character NFT Warrior"
              />
            </div>
            <div class="ic-f-item-flow-title">
              Personalized character NFT Warrior
            </div>
            <div class="ic-f-item-flow-desc">
              <b class="ic-text-primary">Summon WARRIOR</b> by triggering the
              NFT ticket
            </div>
          </div>
        </div>
      </div>
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
</style>
