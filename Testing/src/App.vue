<script setup>
// import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="landing-body">
    <header>
      <h1>
        LuLemon's Testing Ground
      </h1>
    </header>

    <RouterView />
  </div>
</template>

<style scoped>
html, body {
  margin: 0; /* Removes default margin */
  padding: 0; /* Removes default padding */
  border: 0; /* Removes any default border */
  height: 100%; /* Ensures the body takes the full height of the viewport */
  overflow: hidden; /* Prevents scrolling */
  box-sizing: border-box; /* Ensures padding and borders are included in dimensions */
}

.landing-body {
  background-color: rgb(0, 0, 0);
  background-image: url('https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExbzQxY3BnYzhocmUybzAzYjhubHRtcTNpYno3OG12YzlkcnMwOXE4aSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/ndP9IIQYeF2OnR6AmF/giphy.gif');
  background-size: cover; /* Ensures the image covers the entire background */
  background-repeat: no-repeat; /* Prevents the image from repeating */
  background-position: center; /* Centers the image */
  height: 100vh; /* Makes the div take the full viewport height */
  width: 100vw; /* Makes the div take the full viewport width */
  display: flex; /* Makes the div a flex container */
  flex-direction: column; /* Aligns children vertically */
  justify-content: center; /* Centers children vertically */
  align-items: center; /* Centers children horizontally */
  margin: 0; /* Removes any margin around the div */
  padding: 0; /* Removes any padding inside the div */
  border: 0; /* Removes any border around the div */
}
</style>