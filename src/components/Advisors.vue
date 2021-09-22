<template>
  <div class="advisors">
    <section class="ic-section ic-teams pb-0" id="ICAdvisors">
      <div class="container">
        <div class="ic-section-title right">
          <h1 class="wow fadeInUp animated" style="visibility: visible">
            ADVISORS
          </h1>
          <div
            class="ic-section-sub-title wow fadeIn animated"
            style="letter-spacing: 0px; font-size: 11px; visibility: visible"
          >
            <span>#</span>ADVISORS
          </div>
        </div>
        <p class="mt-4 text-end">
          Our advisors open doors and create new opportunities for clients and
          communities who share our values.
        </p>
        <div class="row mt-5 gx-xl-5 gx-lg-4 gx-md-5 gy-md-3">
          <div class="col-lg-4 col-6">
            <a href="#" class="ic-team">
              <div class="ic-team-inner">
                <div class="ic-team-avatar">
                  <img
                    src="../assets/advisors/MinhDoan.jpg"
                    style="height: 80px"
                    alt="Name"
                  />
                </div>
                <div class="ic-team-name">Minh Doan</div>
                <div class="ic-team-title">Blockchain Advisor</div>
                <div class="ic-team-title2">
                  ex-cofounder of Harmony ONE, <br />
                  ex-Google Tech Lead<br />
                  &amp; Phd Candidate in CS
                </div>
              </div>
            </a>
          </div>
          <div class="col-lg-4 col-6">
            <a href="#" class="ic-team">
              <div class="ic-team-inner">
                <div class="ic-team-avatar">
                  <img
                    src="../assets/advisors/Paulus.jpg"
                    style="height: 80px"
                    alt="Name"
                  />
                </div>
                <div class="ic-team-name">Paulus Pham</div>
                <div class="ic-team-title">Strategy Advisor</div>
                <div class="ic-team-title2">
                  Founder of<br />
                  Clovers Ventures, <br />\ &amp; Founder of Coinbiz.vn
                </div>
              </div>
            </a>
          </div>
          <div class="col-lg-4 col-6">
            <a href="#" class="ic-team">
              <div class="ic-team-inner">
                <div class="ic-team-avatar">
                  <img
                    src="../assets/advisors/garlam.jpg"
                    style="height: 80px"
                    alt="Name"
                  />
                </div>
                <div class="ic-team-name">Garlam Won</div>
                <div class="ic-team-title">Marketing Advisor</div>
                <div class="ic-team-title2">
                  ex-investment banker at JP Morgan &amp; <br />ex-Management
                  consultant at <br />
                  Deloitte
                </div>
              </div>
            </a>
          </div>
          <div class="col-lg-4 col-6">
            <a href="#" class="ic-team">
              <div class="ic-team-inner">
                <div class="ic-team-avatar">
                  <img
                    src="../assets/advisors/chaoma.jpg"
                    style="height: 80px"
                    alt="Name"
                  />
                </div>
                <div class="ic-team-name">CHAO MA</div>
                <div class="ic-team-title">Technical Advisor</div>
                <div class="ic-team-title2">
                  CTO of deeper network, <br />
                  core blockchain engineer<br />
                  &amp; ex-Amazon engineer
                </div>
              </div>
            </a>
          </div>
          <div class="col-lg-4 col-6">
            <a href="#" class="ic-team">
              <div class="ic-team-inner">
                <div class="ic-team-avatar">
                  <img
                    src="../assets/advisors/Kyle.jpg"
                    style="height: 80px"
                    alt="Name"
                  />
                </div>
                <div class="ic-team-name">Kyle Chassé</div>
                <div class="ic-team-title">Blockchain Advisor</div>
                <div class="ic-team-title2">
                  Founder Master Ventures, <br />
                  Founder PAID Network<br />
                  &amp; House of DAO
                </div>
              </div>
            </a>
          </div>
          <div class="col-lg-4 col-6">
            <a href="#" class="ic-team">
              <div class="ic-team-inner">
                <div class="ic-team-avatar">
                  <img
                    src="../assets/advisors/hatu.png"
                    style="height: 80px"
                    alt="Name"
                  />
                </div>
                <div class="ic-team-name">Hatu Skeikh</div>
                <div class="ic-team-title">Marketing Advisor</div>
                <div class="ic-team-title2">
                  Chief Marketing &amp; <br />
                  Product/Token Strategy<br />
                  DAO Maker<br />
                </div>
              </div>
            </a>
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
/* Team */

.ic-team {
  display: block;
  filter: drop-shadow(0 3px 7px rgba(14, 8, 18, 0.44));
  margin-bottom: 24px;
}

.ic-team-inner {
  padding: 28px;
  box-sizing: border-box;
  background-color: #3c5a8523;
  text-align: center;
  transition: 0.3s cubic-bezier(0.21, 0.04, 0, 1.07);
  position: relative;
  /* clip-path: polygon(20px 0, 100% 0, 100% calc(100% - 20px), calc(100% - 20px) 100%, 0 100%, 0 20px); */
}

.ic-team-inner::before,
.ic-team-inner::after {
  position: absolute;
  content: "";
  top: 0;
  height: 100%;
  width: 45px;
  border: 2px solid #42bed240;
  transition: all 0.4s;
}

.ic-team-inner::before {
  left: 0;
  border-radius: 6px 0 0 6px;
  border-right: none;
}

.ic-team-inner::after {
  right: 0;
  border-radius: 0 6px 6px 0;
  border-left: none;
}

.ic-team:hover .ic-team-inner::after {
  border-top: 0;
}

.ic-team:hover .ic-team-inner::before {
  border-bottom: 0;
}

.ic-team:hover .ic-team-inner {
  clip-path: polygon(
    0 0,
    calc(100% - 24px) 0,
    100% 24px,
    100% 100%,
    24px 100%,
    0 calc(100% - 24px)
  );
  transform: translateY(-10px);
}

.ic-team-avatar {
  display: flex;
  align-items: center;
  justify-content: center;
  /* height: 245px; */
  margin: 0;
  margin-bottom: 24px;
  overflow: hidden;
  clip-path: polygon(
    0 0,
    calc(100% - 18px) 0,
    100% 18px,
    100% 100%,
    18px 100%,
    0 calc(100% - 18px)
  );
}

.ic-team-avatar img {
  height: auto;
  max-width: 100%;
}

.ic-team-name {
  font-size: 25px;
  color: #fff;
  text-transform: uppercase;
  font-weight: bold;
  margin-bottom: 6px;
}

.ic-team-title {
  color: #8bf0ff77;
  font-size: 14px;
  font-weight: 600;
  line-height: 1.43em;
  letter-spacing: 0.1em;
  font-family: Rajdhani, sans-serif;
  text-transform: uppercase;
  transition: color ease-in-out 0.3s;
}

.ic-team:hover .ic-team-title {
  color: #42bed2;
}

.ic-team-socials {
  justify-content: center;
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  display: none;
}

.ic-team-socials a {
  color: #fff;
  font-size: 24px;
  opacity: 0.7;
  transform-origin: center center;
  transition: all ease-in-out 0.3s;
}

.ic-team:hover .ic-team-socials a {
  transform: scale(1.1);
}

.ic-team-socials a:hover {
  opacity: 1;
}

.team-popup-photo {
  display: block;
  position: relative;
  margin-left: auto;
  margin-right: auto;
  transition: all 0.4s;
  z-index: 2;
}

.team-popup-photo img {
  max-width: 100%;
}

.team-popup-info {
  font-size: 16px;
}

.team-popup-name {
  margin-bottom: 0;
  font-weight: bold;
  text-transform: uppercase;
  font-size: 30px;
  color: #fff;
}

.team-popup-position {
  color: #fff;
  font-size: 20px;
  border-bottom: 1px rgba(255, 255, 255, 0.1) solid;
  margin-bottom: 15px;
  padding-bottom: 8px;
}

.team-popup-social {
  list-style: none;
  padding-left: 0;
  text-align: center;
  margin-bottom: -20px;
}

.team-popup-social li {
  display: inline-block;
  padding-right: 8px;
}

.team-popup-social li a {
  text-align: center;
  display: inline-block;
  font-size: 16px;
  line-height: 32px;
  height: 32px;
  width: 32px;
  border-radius: 50%;
  color: #fff !important;
  background: #6b54b6;
  transition: all 0.5s;
}

@media (max-width: 992px) {
  .team-popup-social {
    margin-bottom: 0px;
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
