<template>
  <div class="navbar-desktop">
    <a href="#">ABOUT WARENA</a>
    <a href="#">METAVERSE</a>
    <a href="#">FEATURES</a>
    <a href="#">TOKEN</a>
    <img src="../assets/LogoFinal.png" alt="" />
    <a href="#">ROADMAP</a>
    <a href="#">TEAM</a>
    <a href="#">ADVISOR</a>
    <a href="#">CONTACT</a>
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
        href="#"
      >
        <!-- href="https://play.warena.io/" -->
        <i class="fas fa-fire me-2 mb-1"></i>Play
      </a>
    </li>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
.navbar-desktop {
  display: flex;
  justify-content: space-around;
  align-items: center;
  max-height: 150px;
  background: black;
  padding: 20px;
  a {
    color: white;
    font-size: 17px;
    font-weight: 600;
    white-space: nowrap;
    letter-spacing: 0.1em;
    vertical-align: top;
    text-decoration: none;
  }
  img {
    max-width: 160px;
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
</style>
