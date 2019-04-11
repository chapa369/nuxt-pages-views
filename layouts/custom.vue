<template>
  <div>
    <HeaderMenu/>
    <p>Users Selection</p>
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
  font-size: 1.5rem;
}
</style>
