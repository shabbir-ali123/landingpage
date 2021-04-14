<template>
  <div class="Supply__wrapper container">
    <div class="Supply__content ">
      <div class="img__wrapper">
        <img src="../assets/img/1.jpg" alt="" srcset="" />
      </div>
      <div class="detail__wrapper">
        <h2 class="upp">
          welcom to
        </h2>
        <h2>
          <span class="change">
            creative hair <br />
            & supplies
          </span>
        </h2>
        <p>
          Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur
          explicabo natus asperiores quisquam doloremque ab blanditiis molestias
          itaque placeat nihil! Lorem ipsum dolor sit, amet consectetur
          adipisicing elit. Numquam, ipsa!
        </p>
      </div>
    </div>
  </div>
</template>
<style scoped>
.Supply__content {
  display: flex;
  /* justify-content: space-evenly; */
  align-items: center;
  margin-top: 42px;
  padding-bottom: 46px;
  border-bottom: 2px solid #d1c9c9;
}
@media (min-width: 200px) and (max-width: 1123px) {
  .Supply__content {
    /* width: 100%; */
    flex-direction: column;
    /* text-align: center; */
  }
  .detail__wrapper {
    width: 100%;
    padding-left: 0px;
  }
  .img__wrapper img {
    width: 100%;
  }
}

.img__wrapper img {
  margin-top: 35px;
  height: auto;
  /* padding-left: 200px; */
  box-shadow: 0px 0px 20px lightgray;
}
.detail__wrapper {
  padding-left: 50px;
}
.detail__wrapper p {
  line-height: 25px;
  /* width: 500px; */
  margin-top: 50px;
  color: #6b6161;
}
.change {
  color: #3e2828;
  font-size: 45px;
  text-transform: uppercase;
  font-weight: 600;
}
.upp {
  font-weight: 400;
  margin-top: 30px;
  text-transform: uppercase;
  color: #9e005d;
}
</style>
