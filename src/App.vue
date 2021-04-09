<template>
  <div class="main">
    <div class="Main__wrapper ">
      <Header :active="active" />
      <router-view></router-view>
    </div>
  </div>
</template>
<script>
import Header from "./components/AppHeader";
export default {
  data() {
    return {
      scrollPosition: null,
      active: false
    };
  },
  components: {
    Header
  },

  methods: {
    updateScroll() {
      this.scrollPosition = window.scrollY;
      console.log(this.scrollPosition, this.active);
      if (this.scrollPosition > 50) {
        this.active = true;
      } else {
        this.active = false;
      }
    }
  },

  mounted() {
    window.addEventListener("scroll", this.updateScroll);
  }
};
</script>

<style>
body {
  margin: 0px;
  font-family: "Josefin Sans", sans-serif !important;
}
.main__wrapper {
  font-family: "Josefin Sans", sans-serif;
  line-height: 25px;
}
h3,
a {
  font-family: "Josefin Sans", sans-serif;
}
a {
  text-decoration: none;
}
.container {
  width: 80%;
  margin: auto;
  padding: 0;
}
</style>
