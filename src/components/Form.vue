<template>
  <div class="form__wrapper">
    <div class="main__content container">
      <div class="form__content">
        <h2>book appointment</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem
          doloremque quam consectetur commodi magnam aperiam aut, quas ex nobis
          atque.
        </p>
      </div>
      <div class="main__form">
        <form action="">
          <div class="labels">
            <label for="">
              <input type="text" placeholder="Full Name" />
            </label>
            <label for=""> <input type="text" placeholder="Phone" /> </label
            ><br />
          </div>
          <div class="labels">
            <label for="">
              <input type="text" placeholder="Email" />
            </label>
            <label for="">
              <input type="text" placeholder="Select service" /> </label
            ><br />
          </div>
          <div class="labels">
            <label for="">
              <input type="text" placeholder="Select Date " />
            </label>
            <label for="">
              <input type="text" placeholder="Select Time" /> </label
            ><br />
            <textarea placeholder="Write something..">your message</textarea>
          </div>
          <button>make an appointments</button>
        </form>
      </div>
    </div>
  </div>
</template>
<style scoped>
.form__wrapper {
  font-family: "Josefin Sans", sans-serif;
  text-align: center;
  height: 100vh;
  background-color: #9e005d;
}
p {
  color: aliceblue;
  font-family: "Josefin Sans", sans-serif;
  display: inline-block;
  width: 400px;
  margin-top: 5px;
  margin: 0px;
  padding: 0px;
}
h2 {
  padding-top: 35px;
  text-transform: uppercase;
  color: white;
  font-family: "Josefin Sans", sans-serif;
  font-size: 40px;
}
.form__content {
  padding: 20px;
}
input {
  height: 55px;
  width: 360px;
  /* margin-top: 10px; */
  margin: 7px;
}
::-webkit-input-placeholder {
  padding-left: 10px;
}
textarea {
  /* width: 520px; */
  width: 741px;
  height: 83px;
  margin-top: 18px;
}
.main__form {
  margin-top: 10px;
}
button {
  border-radius: 38px;
  color: white;
  text-transform: capitalize;
  background-color: black;
  width: 180px;
  height: 44px;
  /* outline: none; */
  border: none;
  box-shadow: 0px 0px 15px currentcolor;
  margin-top: 30px;
  font-size: 15px;
  cursor: pointer;
}
button:hover {
  background-color: palevioletred;
}
</style>
