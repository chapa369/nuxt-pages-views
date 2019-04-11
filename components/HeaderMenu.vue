<template>
  <header class="header">
    <nav class="navbar navbar-expand-md navbar-dark bg-dark">
      <ul class="navbar-nav">
        <li class="nav-item">
          <nuxt-link to="/" class="nav-link">Home</nuxt-link>
        </li>
        <li class="nav-item">
          <nuxt-link to="/users" class="nav-link">Users</nuxt-link>
        </li>
      </ul>
    </nav>
  </header>
  <!-- <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">Navbar</a>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarNavAltMarkup"
      aria-controls="navbarNavAltMarkup"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
      <div class="navbar-nav">
        <a class="nav-item nav-link active" href="#">
          Home
          <span class="sr-only">(current)</span>
        </a>
        <a class="nav-item nav-link" href="#">Features</a>
        <a class="nav-item nav-link" href="#">Pricing</a>
        <a class="nav-item nav-link disabled" href="#">Disabled</a>
      </div>
    </div>
  </nav>-->
</template>

<script>
export default {};
</script>


<style scoped>
.header {
  width: 100%;
  height: 60px;
  justify-content: center;
  align-items: center;
  margin: 0 0 10px 0;
}
/* .nav-item {
  list-style: None;
  justify-content: space-around;
  align-items: center;
} */
</style>
