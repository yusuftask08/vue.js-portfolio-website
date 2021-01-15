<template>
  <div>
    <body>
      <navBar />

      <router-view></router-view>
    </body>
  </div>
</template>
<script>
import navBar from "@/components/navBar";
export default {
  components: {
    navBar,
  },
};
</script>
