<template>
  <div class="front-page">
    <div class="mt-5 pt-5 text-center ic-header-content first">
      <!-- <img
            src="images/banner-image-3.png"
            alt="Warena"
            style="max-height: 260px"
          /> -->
      <h1 style="margin-top: 40vh; filter: drop-shadow(0 1.75rem 1.75rem #000)">
        The first personalized and "play to earn" <br />NFT Metaverse game
      </h1>
    </div>

    <div class="second">
      <a
        href="https://warena.gitbook.io/warena/"
        class="ic-btn ic-btn-v2 ic-btn-primary text-center me-md-4"
        style="filter: drop-shadow(0 0 0.75rem #dc143c)"
        target="_blank"
      >
        <span class="ic-btn-text">Whitepaper</span>
        <div class="ic-btn-hover"></div>
      </a>

      <a href="#ICAbout" class="ic-mouse-scroll">
        <div class="mouse">
          <div class="wheel"></div>
        </div>
        <div class="arrow-down">
          <span class="ic-scroll-arrows unu"></span>
          <span class="ic-scroll-arrows unu"></span>
          <span class="ic-scroll-arrows unu"></span>
        </div>
      </a>

      <a
        href="https://warena.gitbook.io/warena/"
        target="_blank"
        class="ic-btn ic-btn-v2 ic-btn-danger text-center mt-3 mt-md-0"
        style="filter: drop-shadow(0 0 0.75rem #dc143c)"
      >
        <span class="ic-btn-text">Play Now!</span>
        <div class="ic-btn-hover"></div>
      </a>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.front-page {
  width: 100%;
  height: 110vh;
  background-image: url(../assets/banner.jpg);
  background-size: cover;
  background-position: top;
  padding-top: 50px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

.ic-header-content h1 {
  margin-top: 20px;
  margin-bottom: 50px;
  font-size: 48px;
  font-weight: 700;
  text-transform: uppercase;
  color: #ffffff;
  text-shadow: 0px -3px 2px rgb(12 19 55 / 0%), 0 -1px 4px #1b7ae2,
    0 -2px 10px #1b7ae2, 0 -10px 20px #1b7ae2, 0 -18px 40px #1b7ae2;
}

.second {
  a{
    display: inline-block;
    margin: 30px;
  }
  .ic-mouse-scroll{
    display: inline-block;
    margin: 5px;
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

a {
  background: unset;
  text-decoration: none;
  font-size: 17px;
  font-size: 17px;
  line-height: 2em;
  font-weight: 600;
  letter-spacing: 0.1em;
  text-transform: uppercase;
}

span {
  text-decoration: none;
  background: unset;
}

/* Button outline danger */

.ic-btn-outline-danger,
.ic-btn-danger {
  color: #fff !important;
  border-color: #ff3549 !important;
}

.ic-btn-outline-danger:hover,
.ic-btn-danger {
  background-color: #ff3549 !important;
}

.ic-btn-outline-danger::before,
.ic-btn-outline-danger::after,
.ic-btn-danger::before,
.ic-btn-danger::after {
  background-color: #ff3549;
}

.ic-btn-outline-danger .ic-btn-hover {
  background-color: #ff3549;
}

.ic-btn-danger .ic-btn-hover {
  background-color: #af2331;
}

/* Scroll down */

.arrow-down {
  background: unset;
}

.ic-mouse-scroll {
  opacity: 0.8;
  // position: absolute;
  bottom: 20px;
  left: 50%;
  transform: translateX(-50%);
  display: block;
  margin: 0 auto;
  width: 24px;
  height: 100px;
  margin-top: 125px;
}

.ic-scroll-arrows {
  display: block;
  width: 5px;
  height: 5px;
  -ms-transform: rotate(45deg);
  /* IE 9 */
  -webkit-transform: rotate(45deg);
  /* Chrome, Safari, Opera */
  transform: rotate(45deg);
  border-right: 2px solid white;
  border-bottom: 2px solid white;
  margin: 0 0 3px 4px;
  width: 16px;
  height: 16px;
}

.unu {
  margin-top: 1px;
}

.unu,
.doi,
.trei {
  -webkit-animation: mouse-scroll 1s infinite;
  -moz-animation: mouse-scroll 1s infinite;
  animation: mouse-scroll 1s infinite;
}

.unu {
  -webkit-animation-delay: 0.1s;
  -moz-animation-delay: 0.1s;
  -webkit-animation-direction: alternate;
  animation-direction: alternate;
  animation-delay: alternate;
}

.doi {
  -webkit-animation-delay: 0.2s;
  -moz-animation-delay: 0.2s;
  -webkit-animation-direction: alternate;
  animation-delay: 0.2s;
  animation-direction: alternate;
  margin-top: -6px;
}

.trei {
  -webkit-animation-delay: 0.3s;
  -moz-animation-delay: 0.3s;
  -webkit-animation-direction: alternate;
  animation-delay: 0.3s;
  animation-direction: alternate;
  margin-top: -6px;
}

.mouse {
  height: 42px;
  width: 24px;
  border-radius: 14px;
  transform: none;
  border: 2px solid white;
  top: 170px;
  background: unset;
}

.wheel {
  height: 5px;
  width: 2px;
  display: block;
  margin: 5px auto;
  background: white;
  position: relative;
  height: 4px;
  width: 4px;
  border: 2px solid #fff;
  -webkit-border-radius: 8px;
  border-radius: 8px;
}

.wheel {
  -webkit-animation: mouse-wheel 0.6s linear infinite;
  -moz-animation: mouse-wheel 0.6s linear infinite;
  animation: mouse-wheel 0.6s linear infinite;
}

@-webkit-keyframes mouse-wheel {
  0% {
    opacity: 1;
    -webkit-transform: translateY(0);
    -ms-transform: translateY(0);
    transform: translateY(0);
  }
  100% {
    opacity: 0;
    -webkit-transform: translateY(6px);
    -ms-transform: translateY(6px);
    transform: translateY(6px);
  }
}

@-moz-keyframes mouse-wheel {
  0% {
    top: 1px;
  }
  25% {
    top: 2px;
  }
  50% {
    top: 3px;
  }
  75% {
    top: 2px;
  }
  100% {
    top: 1px;
  }
}

@-o-keyframes mouse-wheel {
  0% {
    top: 1px;
  }
  25% {
    top: 2px;
  }
  50% {
    top: 3px;
  }
  75% {
    top: 2px;
  }
  100% {
    top: 1px;
  }
}

@keyframes mouse-wheel {
  0% {
    top: 1px;
  }
  25% {
    top: 2px;
  }
  50% {
    top: 3px;
  }
  75% {
    top: 2px;
  }
  100% {
    top: 1px;
  }
}

@-webkit-keyframes mouse-scroll {
  0% {
    opacity: 0;
  }
  50% {
    opacity: 0.5;
  }
  100% {
    opacity: 1;
  }
}

@-moz-keyframes mouse-scroll {
  0% {
    opacity: 0;
  }
  50% {
    opacity: 0.5;
  }
  100% {
    opacity: 1;
  }
}

@-o-keyframes mouse-scroll {
  0% {
    opacity: 0;
  }
  50% {
    opacity: 0.5;
  }
  100% {
    opacity: 1;
  }
}

@keyframes mouse-scroll {
  0% {
    opacity: 0;
  }
  50% {
    opacity: 0.5;
  }
  100% {
    opacity: 1;
  }
}

@media (max-width: 576px) {
  .ic-mouse-scroll {
    bottom: -10px;
  }
}
</style>
