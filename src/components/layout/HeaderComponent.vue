<template>
  <MobileHeaderComponent />
  <!-- Header -->
  <div class="edrea_tm_header">
    <div class="header_inner">
      <div class="logo">
        <a href="#" @click="navFuntions.activeSection('home')"
          ><img src="img/logo/Logo.png" alt=""
        /></a>
      </div>
      <div class="menu">
        <Menu />
      </div>
    </div>
  </div>
</template>

<script>
import { navFuntions } from "@/navFuntions";
import Menu from "./Menu.vue";
import MobileHeaderComponent from "./MobileHeaderComponent.vue";
export default {
  name: `HeaderComponent`,
  components: { MobileHeaderComponent, Menu },
  data() {
    return {
      navFuntions,
    };
  },
};
</script>
