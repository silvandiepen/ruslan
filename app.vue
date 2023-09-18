<template>
  <div class="container" @click="showVersions">
    <h1 v-if="isVisible === 0" class="en">
      <span>Ruslan</span><span>Gazaryan</span>
    </h1>
    <h1 v-if="isVisible === 1" class="hy">
      <span>Ռուսլան</span><span>Ղազարյան</span>
    </h1>
    <h1 v-if="isVisible === 2" class="ru">
      <span>Руслан</span><span>Газарыан</span>
    </h1>
    <div class="socials">
      <a href="https://www.facebook.com/ruslan.gazaryan.7">
        <svg
          version="1.1"
          id="Layer_1"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          x="0px"
          y="0px"
          width="96px"
          height="96px"
          viewBox="0 0 96 96"
          enable-background="new 0 0 96 96"
          xml:space="preserve"
        >
          <path
            fill="#010101"
            d="M48,8C25.909,8,8,26.001,8,48.206c0,20.158,14.773,36.801,34.022,39.709V58.862h-9.896V48.293h9.896v-7.032
	c0-11.643,5.644-16.755,15.271-16.755c4.611,0,7.049,0.344,8.204,0.501v9.225h-6.567c-4.087,0-5.515,3.894-5.515,8.284v5.777h11.978
	l-1.625,10.569H53.415V88C72.938,85.337,88,68.559,88,48.206C88,26.001,70.091,8,48,8z"
          />
        </svg>
      </a>
      <a href="https://www.instagram.com/ruslangazaryan/">
        <svg
          version="1.1"
          id="Layer_1"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          x="0px"
          y="0px"
          width="96px"
          height="96px"
          viewBox="0 0 96 96"
          enable-background="new 0 0 96 96"
          xml:space="preserve"
        >
          <path
            fill="#010101"
            d="M31.537,8.5C18.835,8.5,8.5,18.841,8.5,31.546V64.46c0,12.703,10.341,23.04,23.046,23.04H64.46
	c12.703,0,23.04-10.341,23.04-23.046V31.537C87.5,18.835,77.159,8.5,64.454,8.5H31.537z M71.7,21.14c1.744,0,3.16,1.416,3.16,3.16
	c0,1.744-1.416,3.16-3.16,3.16c-1.744,0-3.16-1.416-3.16-3.16C68.54,22.556,69.956,21.14,71.7,21.14z M48,27.46
	c11.329,0,20.54,9.211,20.54,20.54S59.327,68.54,48,68.54c-11.329,0-20.54-9.213-20.54-20.54S36.671,27.46,48,27.46z M48,33.78
	c-7.854,0-14.22,6.366-14.22,14.22S40.146,62.22,48,62.22S62.22,55.854,62.22,48S55.854,33.78,48,33.78z"
          />
        </svg>
      </a>
      <!-- <a href="">
<svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
	 width="96px" height="96px" viewBox="0 0 96 96" enable-background="new 0 0 96 96" xml:space="preserve">
<path fill="#010101" d="M77.853,8.818H18.147c-5.15,0-9.329,4.179-9.329,9.329v59.706c0,5.15,4.179,9.329,9.329,9.329h59.706
	c5.15,0,9.329-4.179,9.329-9.329V18.147C87.182,12.997,83.003,8.818,77.853,8.818z M33.073,38.671v35.451H21.879V38.671H33.073z
	 M21.879,28.353c0-2.612,2.239-4.609,5.597-4.609s5.467,1.996,5.597,4.609c0,2.612-2.09,4.721-5.597,4.721
	C24.118,33.073,21.879,30.965,21.879,28.353z M74.121,74.121H62.927c0,0,0-17.277,0-18.658c0-3.732-1.866-7.463-6.53-7.538h-0.149
	c-4.515,0-6.381,3.844-6.381,7.538c0,1.698,0,18.658,0,18.658H38.671V38.671h11.195v4.776c0,0,3.601-4.776,10.84-4.776
	c7.407,0,13.415,5.094,13.415,15.412V74.121z"/>
</svg>      </a> -->
      <a href="https://twitter.com/RuslanGazaryanA">
        <svg
          version="1.1"
          id="Layer_1"
          xmlns="http://www.w3.org/2000/svg"
          xmlns:xlink="http://www.w3.org/1999/xlink"
          x="0px"
          y="0px"
          width="96px"
          height="96px"
          viewBox="0 0 96 96"
          enable-background="new 0 0 96 96"
          xml:space="preserve"
        >
          <g>
            <g id="layer1" transform="translate(52.390088,-25.058597)">
              <path
                id="path1009"
                d="M-42.667,37.059l29.701,39.712l-29.888,32.288h6.727l26.167-28.269l21.142,28.269h22.891L2.701,67.113
			l27.82-30.055h-6.727L-0.304,63.093l-19.471-26.035H-42.667z M-32.774,42.013h10.516l46.438,62.091H13.664L-32.774,42.013z"
              />
            </g>
          </g>
        </svg>
      </a>
    </div>
  </div>
</template>

<script lang="ts" setup>
useHead({
  title: "Ruslan Gazaryan",
});

const isVisible = ref(0);

const showVersions = ()=>{
  setInterval(() => {
    let newValue = isVisible.value + 1;
    if (newValue > 2) newValue = 0;
    isVisible.value = newValue;
  }, 3000);
}

</script>
<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Paytone+One&display=swap");
@font-face {
  font-family: "Ashot Erkat U";
  src: local("Ashot Erkat U"),
    url(~assets/fonts/AshotErkatU-Bold.ttf) format("truetype");
}
@font-face {
  font-family: "Bonche";
  src: local("Bonche"), url(~assets/fonts/Bonche-Bold.ttf) format("truetype");
}
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
  flex-direction: column;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: #000;
  color: white;
  font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  font-weight: 900;
}
h1 {
  font-weight: bold;
  text-transform: uppercase;
  font-family: "Bonche", "Paytone One", "Ashot Erkat U", sans-serif;
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
@keyframes socials {
  0% {
    transform: scale(0);
  }
  100% {
    transform: scale(1);
    opacity: 0.25;
  }
}
@keyframes socialHover {
  0% {
    transform: scale(1);
    opacity: 0.25;
  }
  100% {
    transform: scale(1.5);
    opacity: 0.5;
  }
}
.socials {
  font-size: 2em;
  display: flex;
  gap: 0.5em;

  a {
    display: flex;
    width: 1em;
    height: 1em;
    opacity: 0;
    @for $i from 1 through 4 {
      &:nth-child(#{$i}) {
        animation: socials 0.5s #{$i * 0.1 + 1}s ease-in-out forwards;
      }
    }
    &:hover {
      animation: socialHover 0.5s ease-in-out forwards;
    }
    svg {
      width: 1em;
      height: 1em;
      path {
        fill: white;
      }
    }
  }
}
</style>
