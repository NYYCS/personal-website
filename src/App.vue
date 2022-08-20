<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import HelloWorld from "./components/HelloWorld.vue";
</script>

<template>
  <main>
    <section>
      <p style="font-size: 1em; font-weight: bold">Ng Yu Yue</p>
      <p>Hey there friend.</p>
      <p>
        I am currently a 2nd year computer science student studying in Fudan
        University located in Shanghai.
      </p>
      <p>
        Feel free to contact me for freelance opportunities through
        <a class="email" href="mailto:hello@nyydev.me">hello@nyydev.me</a>
      </p>
      <ul class="socials">
        <li>Find me on: </li>
        <li><a href="https://github.com/NYYCS">GitHub</a></li>
        <li><a href="https://linkedin.com/in/nyydev">LinkedIn</a></li>
      </ul>
    </section>
  </main>
</template>

<style scoped>
a {
  position: relative;
  display: inline-block;
  color: white;
  opacity: 0.5;
  font-weight: initial;
  transition: all ease-in-out 0.4s;
}

a.email::after {
  content: "";
  display: inline-block;
  position: absolute;
  width: 100%;
  height: 1px;
  background: white;
  left: 0;
  bottom: -4px;
}

a:hover {
  transform: scale(1.01);
  opacity: 1;
}

.socials {
  display: flex;
  list-style: none;
  padding: 0;
  gap: 0.5em;
  margin-top: 2em;
}

</style>
