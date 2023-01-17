<template>
  <div id="faq-page">
    <!---=== Home Section ===--->
    <section id="home">
      <div class="row rel full-height">
        <div class="container full-height">
          <div class="home-content-wrapper">
            <div class="home-txt-side">
              <h4 class="home-title">
                Your questions <br> answered
              </h4>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of Home Section ===--->

    <!---=== FAQ-Collapsible Section ===--->
    <section id="faq-collapsible">
      <div class="row">
        <div class="container">
          <div class="faq-collapsible-wrapper">
            <ul class="collapsible">
              <li class="active">
                <div class="collapsible-header flex-div justify-content-btw">
                  <span>How is Angala Fintech regulated?</span>
                  <img src="~/assets/images/down-arr.svg" alt="down-arr" class="down-arr">
                </div>
                <div class="collapsible-body">
                  <p class="faq-txt">
                    We are compliant with all relevant regulatory bodies, such as the National Data Protection
                    Regulation (NDPR) and Payment Card Industry Data Security Standards (PCI DSS) in Nigeria,
                    and national equivalents elsewhere.
                  </p>
                </div>
              </li>
              <li>
                <div class="collapsible-header flex-div justify-content-btw">
                  <span>How much do agents earn?</span>
                  <img src="~/assets/images/down-arr.svg" alt="down-arr" class="down-arr">
                </div>
                <div class="collapsible-body">
                  <p class="faq-txt">
                    More transactions means more commissions. As a Payrail Agent, you have the power and control to
                    make as much money as you can by providing financial services in your community easily within the
                    app, and also get your Mastercard debit card almost instantly. An agent by a roadside in a small
                    village might expect to transact 100,000 naira in a day.
                  </p>
                </div>
              </li>
              <li>
                <div class="collapsible-header flex-div justify-content-btw">
                  <span>Which are the most frequently used services?</span>
                  <img src="~/assets/images/down-arr.svg" alt="down-arr" class="down-arr">
                </div>
                <div class="collapsible-body">
                  <p class="faq-txt">
                    Cash withdrawal is the most frequently used service, particularly in regions without a local ATM.
                  </p>
                </div>
              </li>
              <li>
                <div class="collapsible-header flex-div justify-content-btw">
                  <span>What qualifications are needed to become an agent?</span>
                  <img src="~/assets/images/down-arr.svg" alt="down-arr" class="down-arr">
                </div>
                <div class="collapsible-body">
                  <p class="faq-txt">
                    No formal qualifications are necessary. Agents should be able to read and use a mobile phone or tablet.
                  </p>
                </div>
              </li>
              <li>
                <div class="collapsible-header flex-div justify-content-btw">
                  <span>Where are agents located?</span>
                  <img src="~/assets/images/down-arr.svg" alt="down-arr" class="down-arr">
                </div>
                <div class="collapsible-body">
                  <p class="faq-txt">
                    Most agents operate in their own community where they understand the environment and are known.
                    Agents are particularly important in rural or hinterlands where there are no ATMs.
                  </p>
                </div>
              </li>
              <li>
                <div class="collapsible-header flex-div justify-content-btw">
                  <span>What facilities do agents need?</span>
                  <img src="~/assets/images/down-arr.svg" alt="down-arr" class="down-arr">
                </div>
                <div class="collapsible-body">
                  <p class="faq-txt">
                    Agents should have their own working capital to operate and a stall or location to operate from.
                  </p>
                </div>
              </li>
              <li>
                <div class="collapsible-header flex-div justify-content-btw">
                  <span>What training is provided?</span>
                  <img src="~/assets/images/down-arr.svg" alt="down-arr" class="down-arr">
                </div>
                <div class="collapsible-body">
                  <p class="faq-txt">
                    Our business development officers support the agents in their regions, with initial
                    training and regular visits for support.
                  </p>
                </div>
              </li>
              <li>
                <div class="collapsible-header flex-div justify-content-btw">
                  <span>How do I become an agent?</span>
                  <img src="~/assets/images/down-arr.svg" alt="down-arr" class="down-arr">
                </div>
                <div class="collapsible-body">
                  <p class="faq-txt">
                    Click below to go to the Payrail Agency website or ‘Join as an Agent’
                  </p>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of FAQ-Collapsible Section ===--->

    <!---=== Agency-Email-Box Section ===--->
    <section id="agency-email-box">
      <div class="row">
        <div class="container">
          <div class="aeb-wrapper">
            <div>
              <div class="aeb-title center">
                Payrail Agency
              </div>
              <form id="aeb-form" action="#">
                <div class="input-field flex-div">
                  <input id="email" type="email" placeholder="name@example.com">
                  <button type="submit" class="aeb-submiit-btn">
                    JOIN AS AGENT
                  </button>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of Agency-Email-Box Section ===--->
  </div>
</template>

<script>
export default {
  name: 'FaqPage',
  mounted () {
    const M = require('materialize-css')

    const elemsCollapsible = document.querySelectorAll('.collapsible')
    M.Collapsible.init(elemsCollapsible)
  }
}
</script>

<style src="..\assets\css\home.css"></style>
<style src="..\assets\css\faq.css"></style>

<style scoped>
#home {
  background-image: url('../assets/images/hero-image-faq-2.jpg');
}
@media(max-width: 992px) {
  #home {
    background-position: 60%;
  }
}
@media(max-width: 600px) {}
</style>
