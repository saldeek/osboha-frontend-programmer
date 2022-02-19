<template>
  <!--  This component will contain the list of countries-->
  <div id="services">
    <div class="content-box-md">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <div class="vertical-heading">
              <h5>Interested?</h5>
              <h2>
                Discover <br />
                <strong>Countries</strong> here
              </h2>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="service-boxes">
            <!--list of countries-->
            <Country v-for="country in countries" :key="country.id" :country="country"/>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Country from "@/components/Country";

export default {
  name: "CountriesList",
  components: {
    Country,
  },
  data() {
    return {
      countries: [
        {
          id: 1,
          name: "Syria",
          capital: "Damascus",
        },
        { id: 2, name: "Palastine", capital: "Quds" },
        { id: 3, name: "UK", capital: "London" },
        { id: 4, name: "Jordan", capital: "Amman" },
      ],
    };
  },
};
</script>
<style scoped>
#services{
  position: relative;
}

.vertical-heading {
  margin-bottom: 60px;
}
</style>
