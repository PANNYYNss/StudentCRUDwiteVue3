<template>
  <div>
    <nav class="navbar navbar-dark bg-primary justify-content-between flex-nowrap flex-row">
      <div class="container">
        <router-link to="/" class="navbar-brand float-left">MEVN Stack CRUD</router-link>
        <ul class="nav navbar-nav flex-row float-right">
          <li class="nav-item">
            <router-link to="/" class="nav-link pe-3">Create Student</router-link>
          </li>
          <li class="nav-item">
            <router-link to="/view" class="nav-link ">View Student</router-link>
          </li>
        </ul>
      </div>
    </nav>

    <!-- Router View -->
    <div class="container mt-5">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
  export default {
    
  }
</script>

<style>

</style>