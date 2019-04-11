<template>
  <h1>User ID : {{$route.params.id}}</h1>
</template>
<script>
export default {
  validate(data) {
    //idが数字の時のみを許容する
    return /^\d+$/.test(data.params.id);
  }
};
</script>
