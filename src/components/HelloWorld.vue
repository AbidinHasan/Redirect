<script setup>
import { ref } from "vue";
import heroImg from "../assets/hero.png";
import viteLogo from "../assets/vite.svg";
import vueLogo from "../assets/vue.svg";

const count = ref(0);
</script>

<template>
  <section id="center">
    <div class="hero">
      <img :src="heroImg" class="base" width="170" height="179" alt="" />
      <img
        src="https://storage-ipal.bidin.workers.dev/document/LOGO_ABDN_white.png"
        class="framework"
        alt="Vue logo"
      />
      <img :src="vueLogo" class="vite" alt="vue" />
    </div>
    <div>
      <h1>Get started</h1>
    </div>
  </section>
</template>
