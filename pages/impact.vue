<template>
  <div id="impact-page">
    <!---=== Home Section ===--->
    <section id="home">
      <div class="row full-height">
        <div class="container full-height">
          <div class="home-content-wrapper">
            <div class="home-txt-side">
              <h4 class="home-title">
                Our Impact
              </h4>
            </div>
            <div class="home-img-side">
              <img src="~/assets/images/impact-img.png" alt="impact" class="home-img">
            </div>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of Home Section ===--->

    <!---=== Financial-Inclusion Section ===--->
    <section id="financial-inclusion">
      <div class="row">
        <div class="container">
          <div class="financial-inclusion-wrapper">
            <div class="fiw-title">
              Bridging the gap in <span class="sec-color">financial inclusion</span>
            </div>
            <div class="fiw-desc">
              <p>
                Angala Fintech is able to provide credit to under-banked and financially excluded communities by
                verifying income and business activity through our sister company activities.
              </p>
              <p>
                Our innovative financial technology, such as voice automation in local languages, is helping to
                bring down the barriers to financial literacy.
              </p>
              <p>
                We work additionally with organisations including Mercy Corps. and USAID to offer financial education
                and literacy to our communities.
              </p>
              <p>
                Our biggest focus is encouraging more women and youths to become financially independent through job
                creation and access to finance for merchants and micro small and medium enterprises (MSMEs).
              </p>
            </div>
          </div>

          <div class="sme-financing hidden-xs">
            <img src="~/assets/images/sme-financing-1.png" alt="sme financing" class="sme-financing">
          </div>
          <div class="sme-financing visible-xs">
            <img src="~/assets/images/sme-financing-2.png" alt="sme financing" class="sme-financing">
          </div>
        </div>
      </div>
    </section>
    <!---=== end of Financial-Inclusion Section ===--->

    <!---=== SDG Section ===--->
    <section id="sdg">
      <div class="row">
        <div class="container rel">
          <div class="sdg-header flex-div justify-content-btw">
            <div class="sdg-header-title bold-txt">
              Within <span class="pry-color">5 years</span> <br class="hidden-xs"> we will …
            </div>
            <div class="sdg-imp">
              <img src="~/assets/images/sdg.svg" alt="sdg" class="sdg-txt-image"> <br>
              <i>How our impact targets align with UN sustainable development goals (SDGs)</i>
            </div>
          </div>

          <div class="sdg-block-wrapper">
            <div class="sdg-block">
              <div class="sdg-img-wrapper flex-div">
                <img src="~/assets/images/sdg/sdg-3.png" alt="sdg-img" class="sdg-img">
                <img src="~/assets/images/sdg/sdg-4.png" alt="sdg-img" class="sdg-img">
                <img src="~/assets/images/sdg/sdg-9.png" alt="sdg-img" class="sdg-img">
              </div>
              <div class="sdg-block-header">
                <div class="sdg-figure">
                  500,000
                </div>
                <div class="sdg-title">
                  People
                </div>
              </div>
              <div class="sdg-desc">
                Bring the benefits of financial literacy to 500,000 people
              </div>
            </div>
            <div class="sdg-block">
              <div class="sdg-img-wrapper flex-div">
                <img src="~/assets/images/sdg/sdg-1.png" alt="sdg-img" class="sdg-img">
                <img src="~/assets/images/sdg/sdg-2.png" alt="sdg-img" class="sdg-img">
                <img src="~/assets/images/sdg/sdg-5.png" alt="sdg-img" class="sdg-img">
                <img src="~/assets/images/sdg/sdg-10.png" alt="sdg-img" class="sdg-img">
              </div>
              <div class="sdg-block-header">
                <div class="sdg-figure">
                  72,000
                </div>
                <div class="sdg-title">
                  Agents
                </div>
              </div>
              <div class="sdg-desc">
                Recruit 72,000 financial inclusion agents, <span class="pry-color">70% women & youths</span>
              </div>
            </div>
            <div class="sdg-block">
              <div class="sdg-img-wrapper flex-div">
                <img src="~/assets/images/sdg/sdg-8.png" alt="sdg-img" class="sdg-img">
                <img src="~/assets/images/sdg/sdg-12.png" alt="sdg-img" class="sdg-img">
                <img src="~/assets/images/sdg/sdg-14.png" alt="sdg-img" class="sdg-img">
                <img src="~/assets/images/sdg/sdg-15.png" alt="sdg-img" class="sdg-img">
                <img src="~/assets/images/sdg/sdg-17.png" alt="sdg-img" class="sdg-img">
              </div>
              <div class="sdg-block-header">
                <div class="sdg-figure">
                  40,000
                </div>
                <div class="sdg-title">
                  Businesses
                </div>
              </div>
              <div class="sdg-desc">
                Support 40,000 active businesses with POS terminals and financial services
              </div>
            </div>
            <div class="sdg-block">
              <div class="sdg-img-wrapper flex-div">
                <img src="~/assets/images/sdg/sdg-6.png" alt="sdg-img" class="sdg-img">
                <img src="~/assets/images/sdg/sdg-7.png" alt="sdg-img" class="sdg-img">
                <img src="~/assets/images/sdg/sdg-11.png" alt="sdg-img" class="sdg-img">
                <img src="~/assets/images/sdg/sdg-13.png" alt="sdg-img" class="sdg-img">
                <img src="~/assets/images/sdg/sdg-16.png" alt="sdg-img" class="sdg-img">
              </div>
              <div class="sdg-block-header">
                <div class="sdg-figure">
                  $37 billion+
                </div>
                <div class="sdg-title">
                  Transaction volume
                </div>
              </div>
              <div class="sdg-desc">
                Carry out 3 billion transactions totaling $37 billion+
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of SDG Section ===--->
  </div>
</template>

<script>
export default {
  name: 'ImpactPage'
}
</script>

<style src="..\assets\css\home.css"></style>
<style src="..\assets\css\impact.css"></style>

<style scoped>
#home {
  background-image: url('../assets/images/hero-image-impact.jpg');
}
@media (max-width: 600px) {
  #home {
    height: 80vh;
    min-height: 650px;
  }
}
</style>
