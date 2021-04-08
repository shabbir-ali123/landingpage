<template>
  <div class="form__wrapper">
    <div class="main__content container">
      <div class="form__content">
        <h2>book appointment</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem
          doloremque quam consectetur commodi
        </p>
      </div>
      <div class="main__form">
        <form action="">
          <div class="labels">
            <label for="">
              <input type="text" placeholder="Full Name" />
            </label>
            <label for=""> <input type="number" placeholder="Phone" /> </label
            ><br />
          </div>
          <div class="labels">
            <label for="">
              <input type="email" placeholder="Email" />
            </label>
            <label for="">
              <input type="text" placeholder="Select Service" /> </label
            ><br />
          </div>
          <div class="labels">
            <label for="">
              <input type="number" placeholder="Select Date " />
            </label>
            <label for="">
              <input type="number" placeholder="Select Time" /> </label
            ><br />
            <textarea placeholder="Your Message"></textarea>
          </div>
          <button>make an appointments</button>
        </form>
      </div>
    </div>
  </div>
</template>
<style scoped>
.form__wrapper {
  /* font-family: "Josefin Sans", sans-serif; */
  text-align: center;
  height: 100vh;
  background-color: #9e005d;
}
.form__content p {
  color: aliceblue;
  /* font-family: "Josefin Sans", sans-serif; */
  display: inline-block;
  width: 400px;
  margin-top: -9px;
  margin-bottom: 5px;
  padding: 0px;
  line-height: 25px;
}
.form__content h2 {
  font-size: 45px;
  text-transform: uppercase;
  font-weight: 600;
  padding-top: 35px;
  color: white;
  /* font-family: "Josefin Sans", sans-serif; */
}
.form__content {
  padding: 20px;
}
input {
  outline: none;
  border: transparent;
  /* padding: 30px; */
  padding-left: 20px;
  height: 55px;
  width: 360px;
  /* margin-top: 10px; */
  margin: 7px;
}
textarea {
  outline: none;
  width: 760px;
  height: 83px;
  margin-top: 18px;
  padding-left: 15px;
}
.main__form {
  margin-top: 10px;
}
form button {
  border-radius: 38px;
  color: white;
  text-transform: capitalize;
  background-color: #0e0c0c;
  width: 180px;
  height: 44px;
  /* font-family: "Josefin Sans", sans-serif; */
  /* outline: none; */
  border: none;
  margin-top: 30px;
  font-size: 15px;
  cursor: pointer;
  outline: none;
}
button:hover {
  box-shadow: 0px 0px 7px currentcolor;
  background-color: palevioletred;
}
</style>
