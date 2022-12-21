<template>
  <header class="site-header sticky-top py-1 bg-light">
    <nav class="mx-3 d-flex flex-column flex-md-row navbar navbar-expand-sm ">
      <h4>Rajiv Dikshit Gurukul</h4>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="/">
            Home
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/about">
            About
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">
            Team
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">
            Testimonials
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">
            Trainings
          </a>
        </li>
        <!-- <li class="nav-item">
          <a class="nav-link" href="#">
            Donations
          </a>
        </li> -->
        <li class="nav-donate">
          <a class="btn btn-danger " href="/donation">
            Donate
          </a>
        </li>
      </ul>
    </nav>
  </header>

</template>
<script>
export default {
  name: 'rdgHeader',
}
</script>
<style>
.navbar-nav {
  margin-left: auto;
}
</style>