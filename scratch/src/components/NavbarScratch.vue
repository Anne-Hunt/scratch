<script setup>

</script>


<template>
<nav class="navbar navbar-expand-lg bg-body-tertiary">
  <div class="container-fluid">
    <a class="navbar-brand" href="#">Scratch</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText" aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <routerlink :to="{name: 'about'}">
            <span class="nav-link">About</span>
          </routerlink>
        </li>
        <!-- <li class="nav-item">
          <routerlink :to="{name: 'about'}">
            <span class="nav-link">About</span>
          </routerlink>
        </li> -->
      </ul>
      <span class="navbar-text">
        Scratch it.
      </span>
    </div>
  </div>
</nav>
</template>


<style lang="scss" scoped>

</style>