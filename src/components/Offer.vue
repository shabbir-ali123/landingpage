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
              Praesentium, neque! Lorem ipsum dolor sit amet consectetur.
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
              Praesentium, neque! Lorem ipsum dolor sit amet consectetur.
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
              Praesentium, neque! Lorem ipsum dolor sit amet consectetur.
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
              Praesentium, neque! Lorem ipsum dolor sit amet consectetur.
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
  /* font-family: cursive; */
  /* font-family: "Josefin Sans", sans-serif; */
  color: #6b6161;
  font-size: 15px;
  padding-bottom: 40px;
  margin-top: 25px;
  margin-left: 3px;
}
.heading h2 {
  /* font-family: "Josefin Sans", sans-serif; */
  color: #3e2828;
  font-size: 45px;
  text-transform: uppercase;
  font-weight: 600;
  margin-bottom: 53px;
  margin-top: -27px;
}
.icon {
  padding-right: 45px;
}
h5 {
  color: #9e005d;
}

.icon h3 {
  line-height: 32px;
  padding-right: 15px;
  color: #6b6161;
}
.heading {
  margin-top: 11px;
  font-size: 30px;
}
.content__wrapper p {
  margin-top: 85px;
  line-height: 32px;
  width: 550px;
  margin-right: 111px;
  color: #6b6161;
  font-size: 23px;
}
.offer__heading {
  display: flex;
  justify-content: space-between;
}
.cards__wrapper {
  display: flex;
  padding: 10px;
  margin-top: 34px;
  /* margin: 10px; */
}
.cards__wrapper .icon p {
  width: 250px;
  word-spacing: 2px;
  line-height: 25px;
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
