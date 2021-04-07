<template>
  <div class="Supply__wrapper">
    <div class="Supply__content container">
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
          itaque placeat nihil!
        </p>
      </div>
    </div>
  </div>
</template>
<style scoped>
.Supply__content {
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  margin-top: 42px;
}
.img__wrapper img {
  height: 438px;
  width: 517px;
}

.detail__wrapper {
  margin: 30px;
}
p {
  font-family: cursive;
  color: #6b6161;
}
.change {
  color: #3e2828;
  font-size: 45px;
  text-transform: uppercase;
  font-weight: 600;
}
.upp {
  margin-top: 30px;
  text-transform: uppercase;
  color: #9e005d;
}
</style>
