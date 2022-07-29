<template>
  <nav class="teal">
    <div class="nav-wrapper">
      <router-link to="/" class="brand-logo">Tasks</router-link>
      <ul class="right hide-on-med-and-down">
        <router-link
          tag="li"
          to="/create"
          exact
          active-class="active"
        >
          <a href="#">Create</a>
        </router-link>
        
      </ul>
    </div>
  </nav>
</template>

<script>

</script>

<style lang="scss" scoped>
  nav {
    padding: 0 2rem;
  }
</style>