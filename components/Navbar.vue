<template>
  <div id="nav-wrapper">
    <!---=== Add .nav-2 to give it a white-background mode ===--->
    <nav class="main-nav">
      <div class="container full-height">
        <div class="nav-wrapper">
          <nuxt-link to="/" class="brand-logo" @click="scrollToTop()">
            <img src="~/assets/images/angala-white.svg" alt="Angala Fintech" class="logo white-img">
            <img src="~/assets/images/angala-black.svg" alt="Angala Fintech" class="logo colored-img">
          </nuxt-link>

          <ul id="nav-mobile-2" class="dn-mobile ul-nav">
            <li>
              <a href="#" data-target="slide-out" class="sidenav-trigger sec-color right">
                <img src="~/assets/images/menu-2.svg" alt="menu" class="">
              </a>
            </li>
          </ul>

          <ul id="nav-mobile" class="right hide-on-med-and-down">
            <li class="dropdown-trigger-">
              <a href="#" class="dropdown-trigger flex-div" data-target="solutions-dropdown">
                <span>Our Solutions</span>
                <span class="nav-caret-down">&#10094;</span>
              </a>
              <!-- Dropdown Structure -->
              <ul id="solutions-dropdown" class="dropdown-content">
                <li>
                  <nuxt-link to="/payrail-agency" @click="scrollToTop()">
                    <span>Payrail Agency</span>
                  </nuxt-link>
                </li>
                <li>
                  <nuxt-link to="/payrail-business" @click="scrollToTop()">
                    <span>Payrail Business</span>
                  </nuxt-link>
                </li>
                <li>
                  <nuxt-link to="/credit-services" @click="scrollToTop()">
                    <span>Credit Services</span>
                  </nuxt-link>
                </li>
              </ul>
            </li>
            <li>
              <nuxt-link to="/approach" @click="scrollToTop()">
                <span>Our Approach</span>
              </nuxt-link>
            </li>
            <li>
              <nuxt-link to="/impact" @click="scrollToTop()">
                <span>Impact</span>
              </nuxt-link>
            </li>
            <li>
              <nuxt-link to="/join-us" class="nav-pry-btn btn" @click="scrollToTop()">
                Join Us
              </nuxt-link>
            </li>
          </ul>
        </div>
      </div>
    </nav>

    <ul id="slide-out" class="sidenav">
      <div class="sidenav-logo">
        <nuxt-link to="/" class="sidenav-close" @click="scrollToTop()">
          <img src="~/assets/images/angala-black.svg" alt="Angala Fintech" class="logo">
        </nuxt-link>
      </div>
      <ul class="sidenav-flex">
        <li>
          <nuxt-link to="/" class="sidenav-close" @click="scrollToTop()">
            <span>Home</span>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/#" class="sidenav-close" @click="scrollToTop()">
            <span>Our Solutions</span>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/approach" class="sidenav-close" @click="scrollToTop()">
            <span>Our Approach</span>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/impact" class="sidenav-close" @click="scrollToTop()">
            <span>Impact</span>
          </nuxt-link>
        </li>
        <li>
          <nuxt-link to="/join-us" class="sidenav-close">
            <button class="nav-pry-btn btn pointer">
              Join Us
            </button>
          </nuxt-link>
        </li>
      </ul>
      <div class="sidenav-footer">
        <div class="footer-social-wrapper">
          <a href="http://twitter.com" target="_blank" rel="noopener noreferrer">
            <img src="~/assets/images/twitter.svg" alt="twitter" class="social-icons">
          </a>
          <a href="http://instagram.com" target="_blank" rel="noopener noreferrer">
            <img src="~/assets/images/instagram.svg" alt="instagram" class="social-icons">
          </a>
          <a href="http://linkedin.com" target="_blank" rel="noopener noreferrer">
            <img src="~/assets/images/linkedin.svg" alt="linkedin" class="social-icons">
          </a>
        </div>
      </div>
    </ul>
  </div>
</template>

<script>
// import M from 'materialize-css'
// import $ from "jquery";
export default {
  name: 'NavbarComp',
  mounted () {
    const M = require('materialize-css')

    const elemsSidenav = document.querySelectorAll('.sidenav')
    M.Sidenav.init(elemsSidenav)
    const elemsScrollspy = document.querySelectorAll('.scrollspy')
    M.ScrollSpy.init(elemsScrollspy)
    const elemsDropdown = document.querySelectorAll('.dropdown-trigger')
    M.Dropdown.init(elemsDropdown, {
      coverTrigger: false,
      hover: true
    })
  },
  methods: {
    scrollToTop () {
      window.scrollTo(0, 0)
    }
  }
}
</script>

<style scoped src="..\assets\css\navbar.css"></style>
<style scoped>
  .scrolled-nav .sidenav-trigger img {
    background-color: var(--pry-color);
    border-radius: 50%;
  }
</style>
