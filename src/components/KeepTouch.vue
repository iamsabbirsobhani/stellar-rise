<template>
  <div class="keep-touch">
      <section class="ic-section ic-contact pt-5" id="ICContact">
        <div class="container">
          <div class="row">
            <div class="col-lg-7">
              <div class="ic-section-title">
                <h1 class="wow fadeInUp animated" style="visibility: visible;">We'd love to <br>hear from you</h1>
                <div class="ic-section-sub-title wow fadeIn animated" style="visibility: visible;">
                  <span>#</span>Keep in touch
                </div>
              </div>
              <p class="wow fadeInUp mt-4 fs-20 animated" style="visibility: visible;">
                We are always open and we welcome and questions you have for our
                team. <br>If you wish to get in touch, please fill out the
                form below. <br>Someone from our team will get back to you
                shortly. Follow us on:
              </p>
              <div class="ic-contact-socials ic-contact-socials-footer fs-20 mt-4">
                <a href="https://t.me/warenaOfficial">
                  <i class="fab fa-telegram"></i>
                </a>
                <a href="https://twitter.com/warenaofficial">
                  <i class="fab fa-twitter-square"></i>
                </a>
                <a href="https://discord.gg/kkHQcNmE">
                  <i class="fab fa-discord"></i>
                </a>
                <a href="https://medium.com/warena">
                  <i class="fab fa-medium-m"></i>
                </a>
                <a href="https://www.youtube.com/channel/UCQnmYpytaibTz6Uw-K6LcxQ">
                  <i class="fab fa-youtube"></i>
                </a>
              </div>
            </div>
            <div class="col-lg-5 ps-lg-5 mt-3 mt-lg-0">
              <div class="row">
                <div class="col-md-5">
                  <div class="form-group mb-4 wow fadeInUp animated" data-wow-delay=".1s" style="visibility: visible; animation-delay: 0.1s;">
                    <input class="form-control" placeholder="Your name..." type="text" required="">
                    <div class="form-control-border"></div>
                  </div>
                </div>
                <div class="col-md-7">
                  <div class="form-group mb-4 wow fadeInUp animated" data-wow-delay=".2s" style="visibility: visible; animation-delay: 0.2s;">
                    <input class="form-control" placeholder="Your email..." type="email" required="">
                    <div class="form-control-border"></div>
                  </div>
                </div>
              </div>
              <div class="form-group mb-4 wow fadeInUp animated" data-wow-delay=".3s" style="visibility: visible; animation-delay: 0.3s;">
                <textarea class="form-control" rows="5" placeholder="Your message..." required=""></textarea>
                <div class="form-control-border"></div>
              </div>
              <div class="form-group wow fadeInUp animated" data-wow-delay=".3s" style="visibility: visible; animation-delay: 0.3s;">
                <button type="submit" class="ic-btn ic-btn-v2 ic-btn-outline-primary text-center">
                  <span class="ic-btn-text">Send message</span>
                  <div class="ic-btn-hover"></div>
                </button>
              </div>
            </div>
          </div>
        </div>
      </section>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

/* 3. FORM CONTROL */

.form-control {
    position: relative;
    width: 100%;
    margin: 0 0 10px;
    padding: 24px 33px;
    font-family: inherit;
    font-size: 17px;
    font-weight: 600;
    font-weight: inherit;
    line-height: calc(63px - (48px - 2px));
    color: #fff !important;
    background-color: #2a394a52 !important;
    border: none;
    border-radius: 0 !important;
    outline: 0;
    cursor: text;
    box-sizing: border-box;
    transition: border-color 0.2s ease-in-out;
    filter: drop-shadow(0 3px 7px rgba(14, 8, 18, 0.44));
    outline: none !important;
    box-shadow: none !important;
    position: relative;
}

.form-control::placeholder {
    color: rgba(255, 255, 255, 0.6);
}

.form-group {
    position: relative;
}

.form-control-border {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 0;
    height: 3px;
    background-color: #42bed2;
    transition: all ease-in-out 0.2s;
}

.form-control:focus+.form-control-border {
    width: 100%;
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
    transition: color 0.2s ease-in-out, background-color 0.2s ease-in-out, border-color 0.2s ease-in-out;
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
    clip-path: polygon( 0 0, calc(100% - 20px) 0, 100% 20px, 100% 100%, 20px 100%, 0 calc(100% - 20px));
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



// social
/* Contact */

.ic-contact-socials {
    display: flex;
    align-items: center;
    gap: 15px;
}

.ic-contact-socials a {
    color: rgb(224, 224, 224);
    transition: all ease-in-out 0.3s;
}

.ic-contact-socials a:hover {
    color: #fff;
}


/* 7. FOOTER */

footer {
    width: 100%;
    background-color: #131723;
    position: relative;
    padding: 40px 0 20px 0;
    font-size: 15px;
    font-weight: 500;
    color: #a4b7d1;
}

footer a {
    color: rgba(255, 255, 255, 0.7);
}

/*---------------------------------
## Socialbar
---------------------------------*/

.social-top {
    display: none;
    list-style: none;
    padding: 0 !important;
    align-items: center;
    column-gap: 12px;
    margin-bottom: 0;
    margin-right: 8px;
    position: absolute;
    top: 5px;
    right: 4px;
    width: 100%;
    justify-content: flex-end;
    border-bottom: 1px #1d2135 solid;
}

@media screen and (max-width: 992px) {
    .elements-bar.right {
        right: 0px;
    }
}

@media screen and (max-width: 767px) {
    .elements-bar.right {
        display: none;
    }
    .social-top {
        display: flex;
    }
    .social-top li a {
        font-size: 13px;
    }
    .social-top li span {
        font-size: 12px;
        display: block;
    }
    .navbar-brand img {
        height: 60px;
    }
    .navbar-brand {
        position: relative;
        z-index: 2;
    }
    .navbar-dark .navbar-toggler {
        margin-top: 30px;
    }
}

.clb-social {
    -webkit-transition: all cubic-bezier(0.4, 0, 0.2, 1) 0.4s;
    -o-transition: all cubic-bezier(0.4, 0, 0.2, 1) 0.4s;
    transition: all cubic-bezier(0.4, 0, 0.2, 1) 0.4s;
}

.clb-social-holder {
    white-space: nowrap;
    display: flex;
    align-items: center;
    list-style: none;
    padding: 0 !important;
}

.clb-social-holder li {
    margin: 0px 10px;
}

.clb-social-holder li:last-child a:after {
    display: none;
}

.clb-social-holder.icons li {
    padding: 0px 5px;
}

.clb-social-holder li a {
    transition: all ease-in-out 0.3s;
    line-height: 1;
}

.clb-social-holder li a:hover {
    color: #42bed2;
}

.clb-social-holder.icons li i {
    -webkit-transform: rotate(90deg);
    -ms-transform: rotate(90deg);
    transform: rotate(90deg);
}

.clb-social-holder.icons li a:after {
    display: none;
}

.ic-contact-socials-footer {
    column-gap: 24px;
}

.ic-contact-socials-footer a {
    display: flex;
    width: 50px;
    height: 50px;
    clip-path: polygon( 0 0, calc(100% - 15px) 0, 100% 15px, 100% 100%, 15px 100%, 0 calc(100% - 15px));
    align-items: center;
    justify-content: center;
    background-color: #3c5a8523;
    position: relative;
    border: 1px #42bed240 solid;
}

.ic-contact-socials-footer a::before,
.ic-contact-socials-footer a::after {
    content: "";
    position: absolute;
    background-color: #42bed240;
    width: 60px;
    height: 2px;
    transform: rotate(45deg);
}

.ic-contact-socials-footer a::before {
    top: 0;
    right: -18px;
}

.ic-contact-socials-footer a::after {
    bottom: 0;
    left: -18px;
}

@media (max-width: 576px) {
    .ic-team {
        height: 100%;
    }
    .ic-team-inner {
        padding-left: 5px;
        padding-right: 5px;
    }
    .ic-team-inner .ic-team-title {
        font-size: 13px;
    }
    .ic-team-name {
        font-size: 22px;
    }
    .ic-contact-socials-footer {
        column-gap: 20px;
        margin-bottom: 20px;
    }
    .social-top li a {
        font-size: 18px;
    }
    .social-top li span {
        font-size: 14px;
        margin-bottom: 3px;
    }
}



// social









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