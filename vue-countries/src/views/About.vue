<template>
  <div id="about">
    <div class="content-box-md">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="vertical-heading">
              <h5>Countries ?</h5>
              <h2>
                This project is all about <br />
                <strong>Countries </strong>,Enjoy!
              </h2>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="col-md-6">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolorum
              sunt, nostrum impedit ut nihil neque molestiae consequuntur,
              expedita voluptate quisquam velit, quo nisi numquam quasi
              temporibus vero dolorem amet eius. Lorem ipsum dolor sit.
              <strong>
                <i style="letter-spacing: 1px">
                  <a href="#contact" class="smooth-scroll"
                    >cmaxime illo voluptate
                  </a>
                </i> </strong
              >ipsum, maxime illo voluptate consequuntur qui quaerat, quia ab et
              officiis dolorem autem nihil fuga optio quasi ipsa accusamus
              laudantium quod eligendi.
            </p>
          </div>
          <div class="col-md-6 text-center">
            <img
              src="https://www.ticktranslations.com/wp-content/uploads/2019/01/mapa-politico-del-mundo_23-2147511327-1-560x375-1.jpg"
              alt="John Doe"
            />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "About",
  components: {},
};
</script>
<style>
#about {
  background: url(../assets/image/bg/pattern.jpg) center no-repeat fixed;
  background-size: cover;
  overflow: visible;
}
.content-box-md {
  padding: 100px 0;
}

.row.no-gutters [class*="col-"] {
  padding: 0;
}
.col-md-12 {
  display: -webkit-box;
  display: -webkit-flex;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-align: center;
  -webkit-align-items: center;
  -ms-flex-align: center;
  align-items: center;
}
.vertical-heading {
  margin-bottom: 50px;
}
.vertical-heading h2 {
  font-size: 42px;
  margin: 0 0 0 35px;
  line-height: 45px;
  font-weight: 400;
}

.vertical-heading h5 {
  color: #55b9a6;
  font-size: 14px;
  text-transform: uppercase;
  word-spacing: 9px;
  display: inline-block;
  -webkit-transform: translate(-50%) rotate(-90deg);
  -ms-transform: translate(-50%) rotate(-90deg);
  transform: translate(-50%) rotate(-90deg);
  position: relative;
  font-weight: 400;
  top: 56px;
  left: 8px;
}

#about {
  background: url(../../../image/bg/pattern.jpg) center no-repeat fixed;
  background-size: cover;
  overflow: visible;
}
#about p,
#progress-elements {
  margin: 50px 0;
}
</style>
