<template>
  <div class="Main__wrapper   ">
    <div class="offer__wrapper container ">
      <div class="offer__heading">
        <div class="heading">
          <h5>services</h5>
          <h2>we offer</h2>
        </div>
        <div class="content__wrapper">
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quam
            eveniet unde incidunt error praesentium in sapiente placeat esse
            beatae omnis.
          </p>
        </div>
      </div>
      <div class="cards__wrapper">
        <div class="first__card">
          <div class="icon">
            <i><img src="../assets/img/4.png" alt="" srcset=""/></i>
            <h3>
              Lorem ipsum dolor sit amet <br />Lorem ipsum dolor sit amet.
            </h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Praesentium, neque!
            </p>
          </div>
        </div>
        <div class="2nd__card">
          <div class="icon">
            <i><img src="../assets/img/5.png" alt=""/></i>
            <h3>
              Lorem ipsum dolor sit amet <br />Lorem ipsum dolor sit amet.
            </h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Praesentium, neque!
            </p>
          </div>
        </div>
        <div class="third__card">
          <div class="icon">
            <i><img src="../assets/img/6.png" alt=""/></i>
            <h3>
              Lorem ipsum dolor sit amet <br />Lorem ipsum dolor sit amet.
            </h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Praesentium, neque!
            </p>
          </div>
        </div>
        <div class="four__card">
          <div class="icon">
            <i><img src="../assets/img/7.png" alt=""/></i>
            <h3>
              Lorem ipsum dolor sit amet <br />Lorem ipsum dolor sit amet.
            </h3>
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit.
              Praesentium, neque!
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.main__wrapper {
  height: 100vh;
}

.icon p {
  color: #6b6161;
  font-size: 20px;
  padding-bottom: 40px;
  margin-top: 25px;
  margin-left: 3px;
}
h2 {
  text-transform: uppercase;
  color: #6b6161;
  font-family: "Josefin Sans", sans-serif;
  font-size: 64px;
  font-weight: 600;
  margin-bottom: 53px;
  margin-top: -27px;
}
h5 {
  color: #9e005d;
}

h3 {
  padding-right: 15px;
  color: #4a4545;
}
.heading {
  margin-top: 11px;
  font-size: 30px;
}
.content__wrapper {
  width: 550px;
  margin-right: 111px;
  color: #6b6161;
  margin-top: 122px;
  font-size: 20px;
}
.offer__heading {
  display: flex;
  justify-content: space-between;
}
.cards__wrapper {
  display: flex;
  padding: 10px;
  /* margin: 10px; */
}

.cards__wrapper i img {
  color: aliceblue;
  background-color: #9e2e54;
  height: 100px;
  border: 100%;
  width: 100px;
  border-radius: 100%;
}
</style>
