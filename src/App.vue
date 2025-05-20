<template>
  <div id="app">
    <ul id="return">
      <li data-menuanchor="page1" class="active">
        <a class="black vanish" href="https://seancyan.github.io/Portfolio/">Return to portfolio</a>
      </li>
    </ul>
    <ul id="menu">
      <li data-menuanchor="page1" class="active">
        <a class="black" href="#page1">Intro</a>
      </li>
      <li data-menuanchor="page2"><a class="black" href="#page2">L'Occitane</a></li>
      <li data-menuanchor="page3"><a class="black" href="#page3">Kenya Airways</a></li>
      <li data-menuanchor="page4"><a class="black" href="#page4">L'erbolario</a></li>
      <li data-menuanchor="page5"><a class="black" href="#page5">Crystal Palace</a></li>
      <li data-menuanchor="page6"><a class="black" href="#page6">EE</a></li>
      <li data-menuanchor="page7"><a class="black" href="#page7">Lyca Mobile</a></li>
      <li data-menuanchor="page8"><a class="black" href="#page8">Asics</a></li>
    </ul>


    <full-page :options="options" id="fullpage" ref="fullpage">
      <div class="section introPage">
        <h3 class="introHeader">Client Design Work</h3>
        <p class="pWhite">Here is a look at some of the email and on-site templates I’ve designed and built for clients. From eye catching emails that boost conversion rates to on-site experiences that feel smooth and on-brand, each project was all about combining clean design with real results.<br><br><span>&#8609;</span></p>
      </div>
      <div class="section">
        <div class="slide">
          <h3 class="clientHeading black">L'Occitane: Cart Abandonment Emails</h3>
          <p class="clientCopy black">Cart abandonment email highlighting the most expensive item in the customers basket.</p>
          <img class="emrImg" src="/src/assets/loccitaneEMRv2.png" alt="Loccitane Email">
        </div>
        <div class="slide">
          <h3 class="clientHeading black">L'Occitane: On-Site Display</h3>
          <p class="clientCopy black">On-site display with a key basket item feature.</p>
          <img class="emrImg" src="/src/assets/loccitaneOSRv2.png" alt="Loccitane OSR">
        </div>
      </div>
      <div class="section">
        <div class="slide">
          <h3 class="clientHeading white">Kenya Airways: On-Site Display with Countdown Timer</h3>
          <p class="clientCopy white">On-site display showing midway through the booking process, highlighting time remaining to take advantage of offers via countdown timer.</p>
          <img class="emrImg" src="/src/assets/kenyaOSR1.png" alt="Kenya Airways OSR">
        </div>
        <div class="slide">
          <h3 class="clientHeading white">Kenya Airways: On-Site Booking Abandonment</h3>
          <p class="clientCopy white">On-site display which will capture the current booking details and email them to the customer to complete at a later time.</p>
          <img class="emrImg" src="/src/assets/kenyaOSR2.png" alt="Kenya Airways OSR">
        </div>
        <div class="slide">
          <h3 class="clientHeading white">Kenya Airways: On-Site Display with Voucher Code</h3>
          <p class="clientCopy white">On-site display with a voucher code feature, aiming to encourage checkout during the customer journey.</p>
          <img class="emrImg" src="/src/assets/kenyaOSR3.png" alt="Kenya Airways OSR">
        </div>
      </div>
      <div class="section">
        <div class="slide">
          <h3 class="clientHeading black">L'erbolario: Cart Abandonment Emails</h3>
          <p class="clientCopy black">Cart abandonment email highlighting the most expensive item in the customers basket with some dynamic imagery relating to the product category.</p>
          <img class="emrImg" src="/src/assets/lerbolarioEMRv2.png" alt="Lerbolario Email">
        </div>
        <div class="slide">
          <h3 class="clientHeading black">L'erbolario: On-Site Display with Free Gift Progress Bar</h3>
          <p class="clientCopy black">On-site display on the checkout page, showing progress toward a free gift with purchase & displaying the remaining amount needed to spend to obtain it.</p>
          <img class="emrImg" src="/src/assets/lerbolarioOSRv2.png" alt="Lerbolario OSR">
        </div>
      </div>
      <div class="section">
        <div class="slide">
          <h3 class="clientHeading white">Crystal Palace: Cart Abandonment Emails</h3>
          <p class="clientCopy white">Cart abandonment email to encourage conversions on the Crystal Palace club shop</p>
          <img class="emrImg" src="/src/assets/palaceEMRv2.png" alt="Crystal Palace Email">
        </div>
        <div class="slide">
          <h3 class="clientHeading white">Crystal Palace: On-Site Display</h3>
          <p class="clientCopy white">On-site display to encourage conversions on the Crystal Palace club shop</p>
          <img class="emrImg" src="/src/assets/palaceOSRv2.png" alt="Crystal Palace OSR">
        </div>
      </div>
      <div class="section">
        <div class="slide">
          <h3 class="clientHeading black">EE: Cart Abandonment Email with Countdown Timer</h3>
          <p class="clientCopy black">An email with a countdown timer feature encouraging customers to complete before Black Friday deals end.</p>
          <img class="emrImg" src="/src/assets/eeEMRv2.png" alt="EE Email">
        </div>
        <div class="slide">
          <h3 class="clientHeading black">EE: On-Site Display with Trends Feature</h3>
          <p class="clientCopy black">An on-site display with a trends feature, displaying the number of other people that have viewed the chosen product in the past 24 hours</p>
          <img class="emrImg" src="/src/assets/eeOSRv2.png" alt="EE OSR">
        </div>
      </div>
      <div class="section">
        <div class="slide">
          <h3 class="clientHeading black">Lyca Mobile: Cart Abandonment Email</h3>
          <p class="clientCopy black">Email visual refresh for SIM customers to differentiate from Contract templates.</p>
          <img class="emrImg" src="/src/assets/lycaEMRv2.png" alt="Lyca Mobile Email">
        </div>
        <div class="slide">
          <h3 class="clientHeading black">Lyca Mobile: On-Site Display</h3>
          <p class="clientCopy black">On-site display aiming to capture the Contract/SIM details in the customers basket and email them to complete the purchase later.</p>
          <img class="emrImg" src="/src/assets/lycaOSRv2.png" alt="Lyca Mobile OSR">
        </div>
      </div>
      <div class="section">
        <div class="slide">
          <h3 class="clientHeading white">Asics: Daily Deals On-Site Carousel</h3>
          <p class="clientCopy white">A scrollable carousel displaying daily offers, allowing the client to drive engagement toward specific products.</p>
          <img class="emrImg" src="/src/assets/asicsOSRv2.png" alt="Asics OSR">
        </div>
        <div class="slide">
          <h3 class="clientHeading white">Asics: Embedded On-Site Cart Abandonment</h3>
          <p class="clientCopy white">A cart abandonment feature using html injected directly into the client site rather than using a modal overlay, allowing for a more seamless user experience.</p>
          <img class="emrImg" src="/src/assets/asics2OSRv2.png" alt="Asics OSR">
        </div>
        <div class="slide">
          <h3 class="clientHeading white">Asics: Embedded Next Day Shipping Countdown Timer</h3>
          <p class="clientCopy white">Countdown Timer feature embedded into product page, displaying how long customers have to complete purchase and recieve next day shipping.</p>
          <img class="emrImg" src="/src/assets/asics3OSRv2.png" alt="Asics OSR">
        </div>
      </div>
    </full-page>
  </div>
</template>

<script>

export default {
  name: "App",
  data() {
    return {
      options: {
        licenseKey: "YOUR_KEY_HERE",
        afterLoad: this.afterLoad,
        scrollOverflow: true,
        scrollBar: false,
        menu: "#menu",
        navigation: false,
        anchors: ["page1", "page2", "page3","page4","page5", "page6", "page7","page8"],
        sectionsColor: [
          "#41b883",
          "#fec401",
          "#ff5f45",
          "#95b8a1",
          "#0798ec",
          "#1bcee6",
          "#f5f9ff",
          "#a9a6d1",
          "#ba5be9",
          "#b4b8ab",
        ],
      },
    };
  },
  methods: {
    afterLoad() {
      console.log("After load");
    },

    addSection(e) {
      e.preventDefault();
      var newSectionNumber =
        document.querySelectorAll(".fp-section").length + 1;

      // creating the section div
      var section = document.createElement("div");
      section.className = "section";
      section.innerHTML = `<h3>Section ${newSectionNumber}</h3>`;

      // adding section
      document.querySelector("#fullpage").appendChild(section);

      // creating the section menu element
      var sectionMenuItem = document.createElement("li");
      sectionMenuItem.setAttribute(
        "data-menuanchor",
        "page" + newSectionNumber,
      );
      sectionMenuItem.innerHTML = `<a href="#page${newSectionNumber}">Section${newSectionNumber}</a>`;

      // adding it to the sections menu
      var sectionsMenuItems = document.querySelector("#menu");
      sectionsMenuItems.appendChild(sectionMenuItem);

      // adding anchor for the section
      this.options.anchors.push(`page${newSectionNumber}`);

      // we have to call `update` manually as DOM changes won't fire updates
      // requires the use of the attribute ref="fullpage" on the
      // component element, in this case, <full-page>
      // ideally, use an ID element for that element too
      this.$refs.fullpage.build();
    },

    removeSection() {
      var sections = document
        .querySelector("#fullpage")
        .querySelectorAll(".fp-section");
      var lastSection = sections[sections.length - 1];

      // removing the last section
      lastSection.parentNode.removeChild(lastSection);

      // removing the last anchor
      this.options.anchors.pop();

      // removing the last item on the sections menu
      var sectionsMenuItems = document.querySelectorAll("#menu li");
      var lastItem = sectionsMenuItems[sectionsMenuItems.length - 1];
      lastItem.parentNode.removeChild(lastItem);
    },

    toggleNavigation() {
      this.options.navigation = !this.options.navigation;
    },

    toggleScrollbar() {
      console.log("Changing scrollbar...");
      this.options.scrollBar = !this.options.scrollBar;
    },
  },
};
</script>

<style>
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
.introPage {
  background: url('./assets/bgGreen.jpg');
  background-position: center right;
}
.pWhite {
  width: 35%;
  margin: 20px auto 0;
  text-align: center;
  color:#ffffff;
  font-size:20px;
  line-height:34px;
}
.pWhite span {
  font-size:30px;
  line-height:38px;
}
.clientHeading {
  text-align:center;
  margin: 20px auto 20px;
  font-size:32px;
}
.clientCopy {
  text-align:center;
  margin: 0px auto 40px;
  font-size:20px;
  line-height:28px;
  width:40%;
}
.white {
  color:#ffffff !important;
}
.black {
  color:#333333 !important;
}
.emrImg {
  width:800px;
  display:block;
  margin: 0 auto;
}
#return {
  top:20px !important;
  left:20px !important;
  position:fixed;
  z-index:70;
  height:41px;
}
#return li {
  margin: 10px;
}
#return a {
  font-size:1.1em;
  letter-spacing:1px;
  text-decoration: underline;
}
.fp-watermark {
  display:none !important;
}

@media screen and (max-width: 1150px) {
  .vanish {
    display:none;
  }
  .introPage {
    background-size:cover;
  background-position:center bottom;
}
  .introHeader {
    font-size: 36px;
  }
  .pWhite {
  width: 80%;
  font-size:18px;
}
.emrImg {
  width:70vw;
  display:block;
  margin: 0 auto;
}
#menu {
  top:20px !important;
  left:20px !important;
  right:20px !important;
  font-size:10px !important;
  text-align:center !important;
}
.clientHeading {
  text-align:center;
  margin: 20px auto 20px;
  padding: 0 0px;
  font-size:22px;
  width:70%;
}
.clientCopy {
  text-align:center;
  margin: 0px auto 60px;
  font-size:16px;
  line-height:24px;
  width:78%;
}
.fp-arrow.fp-prev {
  border-width: 10px 15px 10px 0 !important;
}
.fp-arrow.fp-next{
  border-width: 10px 0px 10px 15px !important;
}
}
</style>
