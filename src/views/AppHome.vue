<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png" /> -->
    <div class="home__copy" style="padding-left: 10px;">
      <h1 class="home__heading">
        Hello I’m Ognjen. <br />I build things for the web.
      </h1>
      <p class="home__description">
        I’m a freelancer specialising in website development, digital design, UX and UI, using <strong>Vue.js</strong>, <strong>Laravel</strong> and <strong>Figma</strong>. I know my name can be hard to pronounce for some people - so, feel free call me Og.
      </p>
    </div>

    <div class="home__right">
      <div class="home__blob">
        <img src="../assets/blob_landing.svg" alt="" />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Home",
});
</script>