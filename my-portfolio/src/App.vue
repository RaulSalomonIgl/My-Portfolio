<template>

  <!-- Navigation section -->

  <nav class="navbar navbar-expand-lg">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">Navbar</a>

      <div class="navbar-content">
        
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          
          <li class="nav-item">
            <router-link to="/" class="nav-link" aria-current="page">Home</router-link>
          </li>
          
          <li class="nav-item">
            <router-link to="/about" class="nav-link">About me</router-link>
          </li>
          
          <li class="nav-item">
            <router-link to="/work" class="nav-link">Work</router-link>
          </li>

          <li class="nav-item">
            <router-link to="/contact" class="nav-link">Contact</router-link>
          </li>

        </ul>
      </div>

      <button class="btn-navbar-toggler" type="button">
        <span class="bi bi-list"></span>
      </button>

    </div>
  </nav>


  <router-view/>
</template>