<template>
  <router-link class="country-link" :to="{ name: 'CountryDetails' }">
    <div class=".col-xs-6">
      <div class="service-box text-center">
        <i class="fa fa-laptop i-blue" aria-hidden="true"></i>
        <h3>{{ country.name }}</h3>
        <h5>{{ country.capital }}</h5>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      </div>
    </div>
  </router-link>
</template>

<script>
export default {
  name: "Country",
  props: {
    country: {
      type: Object,
      required: true,
    },
  },
};
</script>

<style scoped>
.country-link {
  color: #2c3e50;
  text-decoration: none;
}
</style>
