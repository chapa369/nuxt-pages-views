<template>
  <div>
    <HeaderMenu/>
    <p>Written in /layouts/custom.vue</p>
    <nuxt/>
  </div>
</template>

<script>
import HeaderMenu from "@/components/HeaderMenu";

export default {
  components: {
    HeaderMenu
  }
};
</script>

<style>
* {
  font-size: 1.2rem;
}
</style>
