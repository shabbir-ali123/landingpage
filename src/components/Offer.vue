<template>
  <div class="Main__wrapper container">
    <div class="offer__wrapper  ">
      <div class="heading">
        <h5>services</h5>
        <h2>we offer</h2>
      </div>
      <div class="content__wrapper">
        <p>
          Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quam eveniet
          unde incidunt error praesentium in sapiente placeat esse beatae omnis.
        </p>
      </div>
    </div>
    <div class="cards__wrapper">
      <div class="first__card">
        <div class="icon">
          <i><img src="../assets/img/4.png" alt="" srcset=""/></i>
          <h3>Lorem ipsum dolor sit amet.</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Praesentium, neque!
          </p>
        </div>
      </div>
      <div class="2nd__card">
        <div class="icon">
          <i><img src="../assets/img/5.png" alt=""/></i>
          <h3>Lorem ipsum dolor sit amet.</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Praesentium, neque!
          </p>
        </div>
      </div>
      <div class="third__card">
        <div class="icon">
          <i><img src="../assets/img/6.png" alt=""/></i>
          <h3>Lorem ipsum dolor sit amet.</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Praesentium, neque!
          </p>
        </div>
      </div>
      <div class="four__card">
        <div class="icon">
          <i><img src="../assets/img/7.png" alt=""/></i>
          <h3>Lorem ipsum dolor sit amet.</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit.
            Praesentium, neque!
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
p {
  padding-right: 15px;
}
h2 {
  margin-bottom: 85px;
  margin-top: -39px;
}
h5 {
  color: #9e005d;
}

h3 {
  padding-right: 15px;
  color: #4a4545;
}
.heading {
  margin-top: 75px;
  font-size: 30px;
}
.content__wrapper {
  width: 450px;
  color: #6b6161;
  margin-top: 153px;
  font-size: 20px;
}
.cards__wrapper {
  display: flex;
  /* margin: 10px; */
}
.offer__wrapper {
  display: flex;
  justify-content: space-between;
  /* align-items: center; */
}
.cards__wrapper i img {
  color: aliceblue;
  background-color: #9e2e54;
  height: 124px;
  border: 100%;
  width: 127px;
  border-radius: 100%;
}
</style>
