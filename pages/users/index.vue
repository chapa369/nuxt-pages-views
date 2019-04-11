<template>
  <div>
    <p>/pages/users/test.vueの表示</p>
    <p>Only numbers are accepted</p>
    <div action="post" class="form-inline">
      <input type="text" v-model="userId" placeholder="user id" class="form-control">
      <button @click="onLoadUser" class="btn btn-primary">送信</button>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      userId: ""
    };
  },
  methods: {
    onLoadUser() {
      this.$router.push("/users/" + this.userId);
    }
  }
};
</script>
