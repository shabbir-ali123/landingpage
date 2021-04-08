<template>
  <div class="Footer__wrapper  ">
    <div class="hello container">
      <div class="wrapp  ">
        <div class="footer__content ">
          <div class="footer__heading">
            <h2>Book your appointment now!</h2>
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
            <p>Link 01</p>
            <p>Link 02</p>
            <p>Link 03</p>
            <p>Link 04</p>
          </div>
          <div class="right">
            <p>@2021 Creative Hair & Supplies</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>
.Footer__wrapper {
  height: 40vh;
  background-color: black;
  color: white;
  /* font-family: "Josefin Sans", sans-serif; */
}
.footer__content {
  display: flex;
  justify-content: space-around;
  align-items: center;
  /* text-transform: capitalize; */
}
.footer__heading {
  padding-top: 35px;
  margin-right: 350px;
}
.footer__heading h2 {
  font-size: 40px;
  font-weight: 600;
}
.right {
  margin-top: 20px;
}
.footer__icon img {
  height: 30px;
  padding: 10px;
  background-color: #9e005d;
  border-radius: 100%;
  width: 30px;
  margin: 10px;
}
.copy__wrapper {
  color: #f4ecde;
  display: flex;
  justify-content: space-around;
}
.link p {
  /* word-spacing: 50px; */
  padding-left: 20px;
}
.copy__wrapper .link {
  margin-right: 620px;
  display: flex;
  justify-content: space-around;
  margin-top: 20px;
  /* padding-top: 100px; */
}
.icons img:hover {
  background-color: palevioletred;
}
</style>
