<template>
  <div id="contact-us-page" class="other-pages">
    <!---=== Home Section ===--->
    <section id="home">
      <div class="row full-height">
        <div class="container full-height">
          <div class="home-content-wrapper">
            <div class="home-txt-side">
              <h4 class="home-title">
                Contact Us
              </h4>
            </div>
            <div class="home-img-side">
              <img src="~/assets/images/contact-img.png" alt="farmer and market people" class="home-img">
            </div>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of Home Section ===--->

    <!---=== Contact-Content Section ===--->
    <section id="contact-content">
      <div class="row">
        <div class="container">
          <div class="contact-content-wrapper">
            <div class="contact-form-side">
              <div class="cfs-tab-wrapper">
                <ul class="tabs">
                  <li class="tab">
                    <a href="#contact-form">Contact Form</a>
                  </li>
                  <li class="tab">
                    <a class="active" href="#job-opportunities-form">Job Opportunities</a>
                  </li>
                </ul>
              </div>

              <div class="cfs-content-wrapper">
                <ContactForm />
                <JobOpportunitiesForm />
              </div>
            </div>
            <div class="contact-details-side">
              <div>
                <div class="cds-header">
                  <div class="cds-title">
                    Talk to us.
                  </div>
                  <div class="cds-desc">
                    Join us in bridging the last mile gap in financial inclusion & Business
                  </div>
                </div>

                <div class="cds-info">
                  <div class="cds-info-title">
                    Contact Info
                  </div>
                  <div class="cds-info-row flex-div">
                    <img src="~/assets/images/call-icon.svg" alt="call" class="cds-info-img">
                    <a href="tel:+2349042222281" class="cds-info-link">+234 904 2222 281</a>
                  </div>
                  <div class="cds-info-row flex-div">
                    <img src="~/assets/images/mail-icon.svg" alt="call" class="cds-info-img">
                    <a href="mailto:info@angalafintech.com" class="cds-info-link">info@angalafintech.com</a>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of Contact-Content Section ===--->
  </div>
</template>

<script>
import ContactForm from '~/components/ContactForm.vue'
import JobOpportunitiesForm from '~/components/JobOpportunitiesForm.vue'

export default {
  name: 'ContactUsPage',
  components: {
    ContactForm,
    JobOpportunitiesForm
  },
  mounted () {
    const M = require('materialize-css')

    const elemsSelect = document.querySelectorAll('select')
    M.FormSelect.init(elemsSelect)
    const elemsTabs = document.querySelectorAll('.tabs')
    M.Tabs.init(elemsTabs)
  }
}
</script>

<style src="../assets/css/home.css"></style>
<style src="../assets/css/contact.css"></style>

<style scoped>
#home {
  background-image: url('../assets/images/hero-image-approach.jpg');
  height: 100vh;
}

@media(min-width: 993px) {
  #home {
    height: 70vh;
    min-height: 500px;
    margin-bottom: 130px;
  }
  img.home-img {
    position: relative;
    top: 50px;
  }
}

@media(max-width: 992px) {}

@media(max-width: 600px) {
  #home {
    height: 90vh;
  }
}

</style>
