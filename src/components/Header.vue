<template>
  <div>
      <nav id="myNav" class="navbar navbar-expand-lg navbar-light bg-light">
  <router-link class="navbar-brand" to="/">Tactbook</router-link>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarColor03" aria-controls="navbarColor03" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarColor03">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item">
        <router-link class="nav-link" to="/profile">Your Profile</router-link>
      </li>
      <!-- <li class="nav-item">
        <router-link class="nav-link" to="/add-friends">Add Friends</router-link>
      </li> -->
      <li class="nav-item">
        <router-link class="nav-link" to="/network">Your Network</router-link>
      </li>
      <li class="nav-item">
        <router-link class="nav-link" to="/about">About</router-link>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" placeholder="Search" type="text">
      <button class="btn btn-secondary my-2 my-sm-0" type="submit">Search Coming Soon</button>
    </form>
  </div>
</nav>
  </div>
</template>

<script>
export default {
  name: "Header"
};
</script>

<style scoped>

</style>


