<template>
  <div class="Footer__wrapper ">
    <div class="wrapp ">
      <div class="footer__content ">
        <div class="footer__heading">
          <h2>book your appointment now!</h2>
          <h1>(000) 123 4567</h1>
        </div>
        <div class="footer__icon">
          <div class="icons">
            <img src="../assets/img/sss.png" alt="" srcset="" />
            <img src="../assets/img/snap.png" alt="" srcset="" />
            <img src="../assets/img/app.png" alt="" srcset="" />
          </div>
        </div>
      </div>
      <div class="copy__wrapper">
        <div class="link">
          <p>Link01</p>
          <p>Link02</p>
          <p>Link03</p>
          <p>Link4</p>
        </div>
        <div class="right">
          <p>@2021 Creative Hair & Supplies</p>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.Footer__wrapper {
  height: 35vh;
  background-color: black;
  color: white;
  font-family: "Josefin Sans", sans-serif;
}
.footer__content {
  display: flex;
  justify-content: space-around;
  align-items: center;
  text-transform: capitalize;
  padding: 25px;
}
.footer__heading {
  margin-right: 271px;
}
.right {
  margin-top: 37px;
}
.footer__icon img {
  height: 40px;
  padding: 7px;
  background-color: #9e005d;
  border-radius: 100%;
  width: 40px;
  margin: 10px;
}
.copy__wrapper {
  color: #a69981;
  display: flex;
  justify-content: space-around;
}
.link {
  margin-left: 14px;
  margin-right: 364px;
  display: flex;
  justify-content: space-around;
  margin-top: 40px;
  padding-bottom: 0px;
}
.icons img:hover {
  background-color: palevioletred;
}
</style>
