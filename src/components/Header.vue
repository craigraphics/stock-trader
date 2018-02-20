<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <router-link class="navbar-brand" :to="{ name: 'home' }">Stock Trader</router-link>

  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#nv" aria-controls="nv" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="nv">
    <ul class="navbar-nav mr-auto">
      <router-link tag="li" class="nav-item" :to="{ name: 'portfolio' }">
        <a class="nav-link" href="#">Portfolio</a>
      </router-link>
      <router-link tag="li" class="nav-item" :to="{ name: 'stocks' }">
        <a class="nav-link" href="#">Stocks</a>
      </router-link>



    </ul>
    <ul class="navbar-nav ml-auto">
      <li class="nav-item">
        <a class="nav-link" href="#">End Day</a>
      </li>
      <li class="nav-item dropdown ml-auto">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Save & Load
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>
      </li>
      <li class="nav-item">
       <a class="nav-link" href="#">Funds $</a>
     </li>
    </ul>

  </div>
</nav>
</template>

<script>
export default {
}
</script>

<style lang="css">
</style>
