<template>
  <div id="infrastructure-page">
    <!---=== Home Section ===--->
    <section id="home">
      <div class="row full-height">
        <div class="container full-height">
          <div class="home-content-wrapper">
            <div class="home-txt-side">
              <h4 class="home-title">
                Financial <br> Infrastructure
              </h4>
              <div class="home-desc white-txt">
                <p>
                  Angala Fintech works with business owners, agents, banks, investors, nonprofits, governments
                  and other organisations to put in place financial infrastructure where it is missing.
                </p>
              </div>
            </div>
            <div class="home-img-side">
              <img src="~/assets/images/integrated-network-img.png" alt="integrated-network" class="home-img">
            </div>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of Home Section ===--->

    <!---=== African-Operation Section ===--->
    <section id="african-operation">
      <div class="row">
        <div class="container">
          <div class="african-operation-wrapper">
            <div class="aow-title">
              Operational across east and west Africa, we are now expanding to the south.
            </div>
            <div class="aow-img">
              <img src="~/assets/images/africa.png" alt="africa">
            </div>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of African-Operation Section ===--->

    <!---=== Stakeholders Section ===--->
    <section id="stakeholders">
      <div class="row">
        <div class="container">
          <div class="stakeholders-wrapper">
            <div class="stakeholders-block pry-bg">
              <div class="stakeholders-title">
                Business owners
              </div>
              <div class="stakeholders-desc">
                Increase transaction frequency and volumes. Our Payrail app helps companies to collect
                money efficiently while our automated and synchronised data tools provide a clear view on
                how well the business is doing and identifies the channels where money is being made.
              </div>
            </div>
            <div class="stakeholders-block sec-bg">
              <div class="stakeholders-title">
                Agents
              </div>
              <div class="stakeholders-desc">
                Agents looking to earn extra income by using their mobile phone and our POS terminals to
                bring financial services to their communities. Our user-friendly interface, incorporating
                local language voice guidance for customers unable to read, assists agents to provide
                services including cash withdrawals, deposit taking, bill payments, health insurance,
                and buy now pay later plans. Agents charge commission directly on each transaction.
              </div>
            </div>
            <div class="stakeholders-block sec-bg pry-bg-xs-sm">
              <div class="stakeholders-title">
                Banks & financial institutions
              </div>
              <div class="stakeholders-desc">
                Banks and financial institutions seeking to increase lending to financially excluded
                communities and small businesses, or provide equipment such as POS machines. We work to
                fulfil each institution’s financial inclusion mandate by reaching far farther into under-served
                communities and using our extensive database and technology to bring down the barriers
                to financial literacy. We provide deep and detailed networks of income-verified business
                owners for those organisations looking to lend to this demographic.
              </div>
            </div>
            <div class="stakeholders-block pry-bg sec-bg-xs-sm">
              <div class="stakeholders-title">
                Investors
              </div>
              <div class="stakeholders-desc">
                Investors as equity or debt partners in Angala Fintech. Our business achieves extraordinary
                impact and has significant profit potential. Even though profit per transaction is minimal,
                the overall earnings potential is very significant given the high velocity of transactions
                and number of people reached.
              </div>
            </div>
            <div class="stakeholders-block pry-bg">
              <div class="stakeholders-title">
                Job opportunities
              </div>
              <div class="stakeholders-desc">
                We are expanding!
                <p>
                  Find out about available opportunities across a wide span of roles and regions.
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!---=== end of Stakeholders Section ===--->
  </div>
</template>

<script>
export default {
  name: 'InfrastructurePage'
}
</script>

<style src="..\assets\css\home.css"></style>
<style src="..\assets\css\infrastructure.css"></style>

<style scoped>
#home {
  background-image: url('../assets/images/hero-image-infrastructure.jpg');
}
</style>
