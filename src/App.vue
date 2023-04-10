<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <!-- <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" /> -->
  <div class="max-w-sm">
    <div class="shadow-lg rounded overflow-hidden">
        <img class="" src="syahmi2.jpg">
        <div class="bg-white p-12">
          <h1 class="mb-6 text-5xl font-bold">Syahmi Hazim</h1>
          <p class="mt-4 font-light text-sm text-gray-500">Web Development Student</p>
            <p class="font-light text-xl italic font-gray-800">
               I am currently on my Level 5 Diploma in Web Development in Politeknik Brunei. I have strong coding skill. I am team leader, player and very effective doing work independently. I am enthusiatic person and enjoy working with people both young and old.
            </p>
            <p class="mt-4 font-light text-sm text-gray-500">21ftt1282@student.pb.edu.bn</p>
        </div>
    </div>
</div>
</template>


<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}

.text-5xl{
  font-size: 2rem;
}

.mb-6 {
  margin-bottom: -0.5rem;
}
</style>
