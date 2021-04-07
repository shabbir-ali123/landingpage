<template>
  <div class="home" id="Home">
    <section id="heroSection">
      <div class="container">
        <div class="wrapper">
          <h2 class="heading">get your stylish</h2>
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
  background-image: url(../assets/img/2.jpg);
  height: 100vh;
  display: flex;
  align-items: center;
  text-transform: capitalize;
  color: #fff;
}
p {
  margin-left: 7px;
}
.btn1 {
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
}
.wrapper {
  margin-top: 133px;
}
.heading {
  margin-bottom: -51px;
  text-transform: uppercase;
  font-size: 35px;
}
.look {
  font-weight: revert;
  font-size: 65px;
}
</style>
