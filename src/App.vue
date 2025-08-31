<template>
  <div>
    <!-- Mobile view -->
    <div class="block md:hidden">
      <MobilePortfolio />
    </div>

    <!-- Desktop / Web view -->
    <div class="hidden md:block">
      <WebPortfolio />
    </div>
  </div>
</template>

<script>
import MobilePortfolio from "./mobile.vue";
import WebPortfolio from "./web.vue";

export default {
  name: "ResponsivePortfolio",
  components: { MobilePortfolio, WebPortfolio },
};
</script>
