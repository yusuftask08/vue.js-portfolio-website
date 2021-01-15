<template>
  <div>
    <houder />
    <portfolio />
    <homeAbout />
    <contact />
    <homeFooter />
    <copyright />
  </div>
</template>
<script>
import houder from "@/components/houder";
import portfolio from "@/components/portfolio";
import homeAbout from "@/components/homeAbout";
import contact from "@/components/contact";
import homeFooter from "@/components/homeFooter";
import copyright from "@/components/copyright";

export default {
  components: {
    portfolio,
    houder,
    homeAbout,
    contact,
    homeFooter,
    copyright,
  },
};
</script>
