<template>
  <div class="main">
    <div class="Main__wrapper ">
      <Header :scrollActive="scrollActive" />
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
      scrollActive: false
    };
  },
  components: {
    Header
  },

  methods: {
    updateScroll() {
      this.scrollPosition = window.scrollY;
      console.log(this.scrollPosition, this.scrollActive);
      if (this.scrollPosition > 50) {
        this.scrollActive = true;
      } else {
        this.scrollActive = false;
        // }
        // const mq = window.matchMedia("[max-width: 500px]");
        // if (mq.matches) {
        //   document.body.style.color = "red";
        //   const Bar = document.getElementsByClassName(".navbar");
        //   const Toggle = document.getElementsByClassName(".toggle");

        //   Toggle.addEventListener("click", function() {
        //     if (Bar.style.display != "block") {
        //       Bar.style.display = "block";
        //       this.innerHTML = "X";
        //     } else {
        //       Bar.style.display = "none";
        //       this.innerHTML = "MENU";
        //     }
        //   });
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
@media only screen and (max-width: 767px) {
  body {
    height: 100%;
  }
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
