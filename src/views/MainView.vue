<script lang="ts" setup></script>

<template>
  <div class="center">
    <p class="text">👉気になるほくろをクリックしてみよう</p>
  </div>
  <div>
    <img alt="face" class="face" src="@/assets/main.png" />
    <p id="hokuro1">・</p>
    <p id="hokuro2">・</p>
    <p id="hokuro3">・</p>
    <p id="hokuro4">・</p>
    <p id="hokuro5">・</p>
    <p id="hokuro6">・</p>
    <p id="hokuro7">・</p>
    <p id="hokuro8">・</p>
    <p id="hokuro9">・</p>
  </div>
</template>

<style>
.face {
  height: 35%;
  width: 35%;
  margin-left: 30%;
  filter: drop-shadow(3px 3px 5px #644125b3);
  margin-top: 6em;
}

.center {
  text-align: center;
}

.center p {
  background-color: rgb(255, 255, 255);
  padding: 0.3em;
  font-weight: bold;
  font-size: 1.5em;
}
.text {
  position: absolute;
  left: 160px;
  top: 30px;
  font-size: 20px;
  border-radius: 2em;
  padding: 1.3em;
  animation: wobbling_x 0.7s ease-in-out infinite alternate,
    wobbling_y 1.2s ease-in-out infinite alternate;
}

@keyframes wobbling_x {
  0% {
    margin-left: 8px;
  }

  100% {
    margin-left: 0px;
  }
}

@keyframes wobbling_y {
  0% {
    margin-top: 0px;
  }

  100% {
    margin-top: 8px;
  }
}
/* 右鼻先横 */
#hokuro1 {
  position: absolute;
  top: 63%;
  left: 51%;
  font-size: 2em;
}
/* 右目尻上 */
#hokuro2 {
  position: absolute;
  top: 48%;
  left: 55%;
  font-size: 2em;
}
/* 眉真ん中 */
#hokuro3 {
  position: absolute;
  top: 44%;
  left: 47%;
  font-size: 2em;
}
/* 唇下 */
#hokuro4 {
  position: absolute;
  top: 76%;
  left: 50%;
  font-size: 2em;
}
/* 目頭近く */
#hokuro5 {
  position: absolute;
  top: 56%;
  left: 44%;
  font-size: 2em;
}
/* 眉尻 */
#hokuro6 {
  position: absolute;
  top: 42%;
  left: 38%;
  font-size: 2em;
}
/* 頬 */
#hokuro7 {
  position: absolute;
  top: 62%;
  left: 38%;
  font-size: 2em;
}
/* 目尻下 */
#hokuro8 {
  position: absolute;
  top: 54%;
  left: 38%;
  font-size: 2em;
}

#hokuro9 {
  position: absolute;
  top: 70%;
  left: 44%;
  font-size: 2em;
}

@keyframes fluffy1 {
  0% {
    transform: translateY(0);
  }
  5% {
    transform: translateY(0);
  }
  10% {
    transform: translateY(0);
  }
  20% {
    transform: translateY(-20px);
  }
  25% {
    transform: translateY(0);
  }
  30% {
    transform: translateY(-10px);
  }
  50% {
    transform: translateY(0);
  }
  100% {
    transform: translateY(0);
  }
}
@media (min-width: 1024px) {
}
</style>
