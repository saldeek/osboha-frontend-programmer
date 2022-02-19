<template>
  <div class="content-box-md">
    <div id="services-tabs">
      <div id="service-tab-1" class="service-tab">
        <div class="container">
          <div class="row">
            <div class="col-md-6 image-tab image-tab-01"></div>
            <div class="col-md-6">
              <div class="tab-bg">
                <h2>Country</h2>
                <h3>Lorem ipsum dolor sit amet.</h3>
                <p>
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Reprehenderit delectus dignissimos ex aut, nihil iure beatae
                  consequuntur fuga distinctio aspernatur odio magni maiores
                  aperiam ut quisquam nesciunt numquam repellendus amet!
                </p>
                <div id="services-02-btn-01">
                  <a
                    class="btn btn-general btn-blue smooth-scroll"
                    href="#contact"
                    title="get in touch"
                    >Convert Currency to USD</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CountryDetails",
};
</script>

<style scoped>
.service-tab .col-md-6 {
  padding: 0;
}
.service-tab .image-tab-01,
.service-tab .image-tab-02,
.service-tab .image-tab-03,
.service-tab .image-tab-04 {
  height: 520px;
}
.service-tab .image-tab-01 {
  background: url(../../../image/services/img_tab_01.webp) center no-repeat;
  background-size: cover;
  -webkit-filter: saturate(1.5) hue-rotate(345deg);
  filter: saturate(1.5) hue-rotate(345deg);
}
.service-tab .image-tab-02 {
  /*background: url(../image/services/img_tab_02.webp) center no-repeat;*/
  background-size: cover;
  -webkit-filter: saturate(1.5) hue-rotate(360deg);
  filter: saturate(1.5) hue-rotate(360deg);
}
.service-tab .image-tab-03 {
  /*background: url(../image/services/img_tab_03.webp) center no-repeat;*/
  background-size: cover;
  -webkit-filter: saturate(1.5) hue-rotate(345deg);
  filter: saturate(1.5) hue-rotate(345deg);
}
.service-tab .image-tab-04 {
  /*background: url(../image/services/img_tab_04.webp) center no-repeat;*/
  background-size: cover;
  -webkit-filter: saturate(1.5) hue-rotate(360deg);
  filter: saturate(1.5) hue-rotate(360deg);
}
.service-tab .tab-bg {
  padding: 50px 30px;
  height: 520px;
}
.service-tab h2 {
  font-size: 48px;
  color: #bbb;
  margin-bottom: 20px;
  font-weight: 400;
}
.service-tab h3,
.service-tab p {
  margin-bottom: 30px;
}
.service-tab h3 {
  font-size: 32px;
}
</style>
