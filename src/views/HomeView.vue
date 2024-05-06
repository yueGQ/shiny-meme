<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <!-- <router-link to=""> -->
    <router-link to="/setup">点击前往setup页</router-link>
    <router-view />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({});
</script>
