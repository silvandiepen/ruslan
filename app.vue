<template>
  <div class="container">
    <h1><span>Ruslan</span><span>Gazaryan</span></h1>
  </div>
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Paytone+One&display=swap");
body,
html {
  width: 100%;
  min-height: 100vmin;
  margin: 0;
  padding: 0;
  background-color: black;
}
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: #000;
  color: white;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
}
h1 {
  font-weight: bold;
  text-transform: uppercase;
  font-family: "Paytone One", sans-serif;
  font-size: calc(4vw + 1.5em);
  line-height: 0.8;
  animation: whole 0.8s ease-in-out forwards;

  span {
    display: block;
    opacity: 0;
  }
  span:first-child {
    animation: first 0.5s ease-in-out forwards;
  }
  span:last-child {
    animation: last 0.5s 0.4s ease-in-out forwards;
  }
}
@keyframes whole {
  0% {
    transform: rotate(10deg);
  }
  100% {
    opacity: 1;
    transform: translateX(-10deg);
  }
}
@keyframes first {
  0% {
    transform: translateX(-100%);
  }
  100% {
    opacity: 1;
    transform: translateX(0);
  }
}
@keyframes last {
  0% {
    transform: translateX(100%);
  }
  100% {
    opacity: 1;
    transform: translateX(0);
  }
}
</style>
