<template>
  <navbar></navbar>
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </nav>
  <router-view />
</template>

<style lang="scss">
@import "bulma/css/bulma.css";

</style>
<script>
import Navbar from "@/components/utils/navbar";
export default {
  components: { Navbar }
}
</script>