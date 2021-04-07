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
  padding-top: 264px;
}
.discount {
  color: palevioletred;
}
.heading {
  padding: 0px;
  margin: 0px;
  font-size: xxx-large;
  font-family: "Josefin Sans", sans-serif;
  text-transform: uppercase;
}
p {
  margin-left: 549px;
  width: 400px;
  font-family: sans-serif;
  margin-top: 24px;
}
button {
  border-radius: 38px;
  color: white;
  text-transform: capitalize;
  background-color: #9e005d;
  width: 180px;
  height: 44px;
  /* outline: none; */
  border: none;
  font-size: 15px;
  cursor: pointer;
  margin-top: 43px;
  box-shadow: 0px 0px 15px currentcolor;
}
button:hover {
  background-color: palevioletred;
}
</style>
