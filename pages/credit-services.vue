<template>
  <div id="agency-page">
    <!---=== Home Section ===--->
    <section id="home">
      <div class="row full-height">
        <div class="container full-height">
          <div class="home-content-wrapper">
            <div class="home-txt-side">
              <h4 class="home-title">
                <div class="small-title-desc sec-color">
                  Credit services
                </div>
                Lendable
              </h4>
              <div class="home-desc white-txt">
                Even a smallholder farmer with only a hectare of land could be earning above minimum wage
                (more than some in fancy offices) with the right tools, inputs, irrigation and expertise
                to produce more and better harvests. Mostly, it comes down to financial literacy, and the
                ability to get credit to purchase the inputs needed.
              </div>
            </div>
            <div class="home-img-side">
              <img src="~/assets/images/lendable-img.png" alt="farmers and market people" class="home-img">
            </div>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of Home Section ===--->

    <!---=== Connectivity Section ===--->
    <section id="connectivity">
      <div class="row mag-0">
        <div class="cc-block-2">
          <div class="ccbr-grid-div side-1 side-1a">
            <div class="container">
              <div class="ccbr-img-side visible-xs-sm">
                <img src="~/assets/images/l-1.jpg" alt="people with laptop" class="full-width">
              </div>
              <div class="ccbr-txt-side">
                <hr class="top-hr">
                <p>
                  That’s why we consider no business too small for business credit. At Angala Fintech we seek to
                  <span class="sec-color">mass produce financial literacy</span>. We provide workshops for our
                  agents. And through our agents – by training our trainers – we reach more people.
                </p>
              </div>
              <div class="ccbr-img-side hidden-xs-sm">
                <img src="~/assets/images/l-1.jpg" alt="people with laptop" class="full-width">
              </div>
            </div>
          </div>

          <div class="ccbr-grid-div side-2 side-2a">
            <div class="container">
              <div class="ccbr-img-side">
                <img src="~/assets/images/l-2.jpg" alt="savings" class="full-width">
              </div>
              <div class="ccbr-txt-side">
                <hr class="top-hr">
                <p>
                  Based on our network of income-verified and documented small business owners, Angala Fintech
                  is able to provide credit directly at competitive interest rates.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of Connectivity Section ===--->
  </div>
</template>

<script>
export default {
  name: 'CreditServicesPage'
}
</script>

<style src="..\assets\css\home.css"></style>
<style src="..\assets\css\solutions.css"></style>

<style scoped>
#home {
  background-image: url('../assets/images/hero-image-lendable.jpg');
}
.side-1.side-1a {
  background-image: url("../assets/images/l-1.jpg");
}
.side-2.side-2a {
  background-image: url("../assets/images/l-2.jpg");
}
</style>
