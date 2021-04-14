<template>
  <div class="sale__wrapper">
    <div class="sale__content ">
      <div class="sale__heading">
        <h2 class="heading">
          save upto <span class="discount">30% off </span><br />
          on first visit
        </h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. <br />
          Sint commodi autem tempora architecto sunt ad!
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
  width: 100%;
  background-image: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)),
    url(../assets/img/3.jpg);
  /* height: auto; */
  text-align: center;
  color: white;
}
.sale__heading {
  line-height: 60px;
}
.discount {
  color: palevioletred;
}
.heading {
  padding-top: 159px;
  margin: 0px;
  font-size: xxx-large;
  /* font-family: "Josefin Sans", sans-serif; */
  text-transform: uppercase;
}
.sale__heading p {
  /* margin-left: 549px; */
  /* font-family: "Josefin Sans", sans-serif; */
  line-height: 25px;
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
  margin-top: 40px;
  outline: none;
  margin-bottom: 130px;
}
button:hover {
  box-shadow: 0px 0px 15px currentcolor;
  background-color: palevioletred;
}
</style>
