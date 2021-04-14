<template>
  <div class="form__wrapper">
    <div class="main__content container">
      <div class="form__content">
        <h2>book appointment</h2>
        <p>
          Lorem ipsum dolor sit amet consectetur adipisicing elit. <br> Autem
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
            <label for="">
              <input type="email" placeholder="Email" />
            </label>
            <select name="" id="select" >
            <option value="">Select Service</option>
              /></option>
              </select>
            <br />
          <select name="" id="select" >
            <option value="">Select Date</option>
              /></option>
              </select>
               <select name="" id="select" >
            <option value="">Select Time</option>
              /></option>
              </select>
            <br />
          </div>
          <button>make an appointments</button>
        </form>
      </div>
    </div>
  </div>
</template>
<style scoped>
.form__wrapper {
  margin: 0px;
  /* width: auto; */
  /* font-family: "Josefin Sans", sans-serif; */
  text-align: center;
  height: auto;
  background-color: #9e005d;
}
.form__content p {
  color: aliceblue;
  /* font-family: "Josefin Sans", sans-serif; */
  display: inline-block;
  /* width: 100%; */
  margin-top: -9px;
  margin-bottom: 5px;
  padding: 10px 10px;
  line-height: 25px;
}
#select{
    padding-left: 15px;
  width: 383px;
  height: 55px;
  outline: none;
   margin: 7px;
    color:  #696868;
    border: transparent;
}
.form__content h2 {
  font-size: 45px;
  text-transform: uppercase;
  font-weight: 600;
  padding-top: 52px;
  color: white;
  /* font-family: "Josefin Sans", sans-serif; */
}
.form__content {
  padding-top: 5px;
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
@media (max-width:462px) {
  input{
    /* margin-right: 10px; */
  }
}
@media (min-width: 548px) and (max-width: 900px) {
.message{
      width: 500px;
    padding-left: 0px;
  }
}

.message {
  outline: none;
  width: 765px;
  height: 83px;
  margin-top: 18px;
  padding-left: 15px;
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
  margin-top: 40px;
  font-size: 15px;
  cursor: pointer;
  outline: none;
  margin-bottom: 50px;
}
button:hover {
  box-shadow: 0px 0px 7px currentcolor;
  background-color: palevioletred;
}
</style>
