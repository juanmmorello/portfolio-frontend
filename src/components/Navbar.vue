<template>
  <div>
    <ul class="nav justify-content-center">
      <li class="nav-item">
        <router-link to="/" class="nav-link" exact>Home</router-link>
      </li>
      <li class="nav-item">
        <router-link to="/blog" class="nav-link" exact>Blog</router-link>
      </li>
      <li class="nav-item">
        <router-link to="/about" class="nav-link" exact>About</router-link>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Navbar"
};
</script>

<style scoped>
a {
  color: rgb(202, 202, 202);
}
a.router-link-active {
  color: rgb(230, 225, 225);
  border-bottom: 1px solid rgb(230, 225, 225);
}

a:hover {
  color: #fff;
  border-bottom: 1px solid #fff;
}
</style>
