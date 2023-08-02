<template>
  <section class="join">
    <div class="container">
      <div class="row">
        <div class="col-5">
          <h3>Join our Newsletter</h3>
          <p>Nulla ac convallis lorem, eget euismod nisl. bibendum nec.</p>
        </div>
        <div class="col-2"></div>
        <div class="col-5">
          <input type="text" placeholder="Your E-mail" /> <br />
          <button>Submit</button>
        </div>
      </div>
    </div>
  </section>
</template>
<style scoped>
.join {
  background-color: #dbf0fa;
  height: 188px;
  padding-top: 20px;
}
button {
  background-image: linear-gradient(
    92.88deg,
    #455eb5 9.16%,
    #5643cc 43.89%,
    #673fd7 64.72%
  );
  border-radius: 8px;
  border-style: none;
  box-sizing: border-box;
  color: #ffffff;
  cursor: pointer;
  flex-shrink: 0;
  font-family: "Inter UI", "SF Pro Display", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue",
    sans-serif;
  font-size: 16px;
  font-weight: 500;
  height: 3rem;
  padding: 0 1.4rem;
  text-align: center;
  text-shadow: rgba(0, 0, 0, 0.25) 0 3px 8px;
  transition: all 0.5s;
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
}

button:hover {
  box-shadow: rgba(80, 63, 205, 0.5) 0 1px 30px;
  transition-duration: 0.1s;
}

@media (min-width: 768px) {
  button {
    padding: 0 2.6rem;
  }
}
input {
  margin-top: 10px;
  border-radius: 6px;
  border: 2px solid #673fd7;
  border-top: none;
  width: 100%;
  height: 60%;
}
input:focus {
  box-shadow: 0 0 5px rgba(81, 203, 238, 1);
  padding: 3px 0px 3px 3px;
  margin: 5px 1px 3px 0px;
  border: 1px solid rgba(81, 203, 238, 1);
}
</style>