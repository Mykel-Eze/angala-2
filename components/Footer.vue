<template>
  <footer id="contact">
    <div class="row">
      <div class="container">
        <div class="footer-grid-wrapper">
          <div class="footer-block">
            <div class="footer-block-title">
              Headquaters
            </div>
            <ul class="footer-block-list">
              <li>
                20 Layi Yusuf Crescent, <br> Lekki, Lagos, <br> Nigeria
              </li>
            </ul>
          </div>
          <div class="footer-block">
            <div class="footer-block-title">
              Products
            </div>
            <ul class="footer-block-list">
              <li>
                <a href="https://payrail.co/agency" target="_blank" rel="noopener noreferrer" class="footer-link">Payrail Agency</a>
              </li>
              <li>
                <a href="https://payrail.co/business" target="_blank" rel="noopener noreferrer" class="footer-link">Payrail Business</a>
              </li>
            </ul>
          </div>
          <div class="footer-block">
            <div class="footer-block-title">
              General inquiries
            </div>
            <ul class="footer-block-list">
              <li>
                If it's easier, email us?
              </li>
              <li>
                <a href="mailto:info@angalafintech.com" class="footer-link flex-div">
                  <img src="~/assets/images/mail-icon.svg" alt="mail" class="footer-link-icon">
                  <span>info@angalafintech.com</span>
                </a>
              </li>
              <li>
                <a href="tel:+2349042222281" class="footer-link flex-div">
                  <img src="~/assets/images/call-icon.svg" alt="call" class="footer-link-icon">
                  <span>+234 904 2222 281</span>
                </a>
              </li>
            </ul>
          </div>
          <div class="footer-block">
            <div class="footer-block-title">
              Sign up for the newsletter
            </div>
            <form action="#" class="footer-newsletter-form">
              <div class="input-field flex-div">
                <input id="newsletter-inp" type="email" placeholder="name@company.com">
                <button id="subscribe-btn">
                  Subscribe
                </button>
              </div>
            </form>
          </div>
        </div>

        <div class="footer-copyright-social flex-div justify-content-btw">
          <div class="footer-copyright">
            © 2022 Angala Fintech. All Right Reserved
          </div>
          <div class="flex-div footer-social">
            <a href="https://twitter.com/search?q=angala%20fintech&src=recent_search_click" target="_blank" rel="noopener noreferrer" class="footer-link flex-div">
              <img src="~/assets/images/twitter.svg" alt="twitter" class="social-link-icon">
              <span class="pry-color">Twitter</span>
            </a>
            <a href="https://www.instagram.com/angalafintech/" target="_blank" rel="noopener noreferrer" class="footer-link flex-div">
              <img src="~/assets/images/instagram.svg" alt="instagram" class="social-link-icon">
              <span class="pry-color">Instagram</span>
            </a>
            <a href="https://www.linkedin.com/company/angala-financial-technology-limited/" target="_blank" rel="noopener noreferrer" class="footer-link flex-div">
              <img src="~/assets/images/linkedin.svg" alt="linkedin" class="social-link-icon">
              <span class="pry-color">Linkedin</span>
            </a>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterComp'
}
</script>

<style scoped src="..\assets\css\footer.css"></style>
