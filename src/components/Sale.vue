<template>
  <div class="sale__wrapper">
    <div class="sale__content ">
      <div class="sale__heading">
        <h2 class="heading">
          save upto <span class="discount">30% off </span><br />
          on first visit
        </h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Sint commodi
          autem tempora architecto sunt ad!
        </p>
        <button>make an applications</button>
      </div>
    </div>
  </div>
</template>
<style scoped>
.sale__wrapper {
  background-repeat: no-repeat;
  background-size: cover;
  background-image: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
    url(../assets/img/3.jpg);
  height: 100vh;
  text-align: center;
  color: white;
}
.sale__heading {
  line-height: 60px;
  padding-top: 230px;
}
.discount {
  color: palevioletred;
}
.heading {
  padding: 0px;
  margin: 0px;
  font-size: xxx-large;
  /* font-family: "Josefin Sans", sans-serif; */
  text-transform: uppercase;
}
.sale__heading p {
  margin-left: 549px;
  width: 400px;
  /* font-family: "Josefin Sans", sans-serif; */
  line-height: 25px;
  margin-top: 10px;
}
button {
  border-radius: 38px;
  /* font-family: "Josefin Sans", sans-serif; */
  color: white;
  text-transform: capitalize;
  background-color: #9e005d;
  width: 180px;
  height: 44px;
  border: none;
  font-size: 15px;
  cursor: pointer;
  margin-top: 30px;
  outline: none;
}
button:hover {
  box-shadow: 0px 0px 15px currentcolor;
  background-color: palevioletred;
}
</style>
