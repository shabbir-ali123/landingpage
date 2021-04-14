<template>
  <div class="home" id="Home">
    <section id="heroSection">
      <div class="container">
        <div class="wrapper">
          <h2 class="home__heading">get your stylish</h2>
          <h2 class="look">look today</h2>
          <p>
            Lorem ipsum dolor sit amet consectetur<br />
            adipisicing elit Lorem ipsum dolor sit amet.
          </p>
          <button class="btn1">make an appointments</button>
        </div>
      </div>
    </section>
    <Supplies />
    <Offer />
    <Sale />
    <Form />
    <Footer />
  </div>
</template>

<script>
import Supplies from "../components/Supplies";
import Offer from "../components/Offer";
import Sale from "../components/Sale";
import Form from "../components/Form";
import Footer from "../components/Footer";
export default {
  name: "Home",
  components: {
    Supplies,
    Offer,
    Sale,
    Form,
    Footer
  }
};
</script>
<style>
#heroSection {
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url(../assets/img/2.jpg);
  height: 100vh;
  display: flex;
  align-items: center;
  text-transform: uppercase;
  color: #fff;
}
@media (min-width: 200px) and (max-width: 1123px) {
  #heroSection {
    height: 100vh;
    /* width: 100vh; */
    margin: 0px;
    padding: 0px;
  }
}

.wrapper p {
  line-height: 25px;
  text-transform: capitalize;
  margin-left: 7px;
  padding-bottom: 10px;
  margin-top: -31px;
}
.btn1 {
  /* font-family: "Josefin Sans", sans-serif; */
  border-radius: 38px;
  color: white;
  text-transform: capitalize;
  background-color: #9e005d;
  width: 180px;
  height: 44px;
  /* outline: none; */
  border: none;

  font-size: 15px;
  margin-left: 3px;
  outline: none;
}
.btn1:hover {
  box-shadow: 0px 0px 15px currentcolor;
  background-color: hotpink;
  cursor: pointer;
}
.wrapper {
  margin-top: 133px;
}
.home__heading {
  padding-bottom: 16px;
  margin-bottom: -44px;
  text-transform: uppercase;
  font-size: 35px;
}
.look {
  font-weight: revert;
  font-size: 65px;
}
</style>
