<script setup>

</script>

<template>
      <router-view />
</template>

<style>

html {
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  inset: 0;
  padding: 50px;
  height: 100%;
  width: 100%;
  background-image: linear-gradient(
    to bottom right,
    rgb(173, 2, 252) 0%,
    rgb(89, 2, 252) 20%,
    rgb(196, 86, 247) 40%,
    rgb(91, 29, 190) 60%,
    rgb(173, 2, 252) 100%
  );
  background-size: 800% 800%;
  animation: movingGradient 20s linear infinite alternate;
}
@keyframes movingGradient {
  from {
    background-position: 0 0;
  }
  to {
    background-position: 100% 100%;
  }
}
</style>
