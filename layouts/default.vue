<template>
  <div class="container">
    <Nuxt/>
  </div>
</template>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  color: #2E495E;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.container {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
  background: url("../assets/bisup.jpg");
  background-repeat: no-repeat;
  background-size: 100%;
  background-blend-mode: blend;
}

.button--green {
  display: inline-block;
  color: white;
  text-decoration: none;
  padding: 10px 30px;
  display: inline-flex;
  align-self: center;
  opacity: 100%;
  background: #33499A;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 30px;
}

.button--green:hover {
  color: #fff;
  opacity: 75%;
}

.button--grey {
  display: inline-block;
  color: white;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
  background: #33499A;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 30px;
  opacity: 100%;
}

.button--grey:hover {
  color: #fff;
  opacity: 75%;
}
</style>
