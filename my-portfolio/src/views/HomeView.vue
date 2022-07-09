<template>
  <section class="container">

    <div class="row" id="main">
      <div class="col-8" id="panelLeft">
        <h2>Hello Wellcome, I´m</h2>
        <h1>Raúl Arturo Salomon Iglesias</h1>
        <p>우리가 아는 것은 한 방울의 물입니다. 우리가 무시하는 것은 바다입니다</p>

        <div class="btn-more">
          <router-link to="/about" class="btn-more-action">More &rarr;</router-link>
        </div>
      </div>

      <div class="col-4" id="panelRight">
        <img src="./../assets/profile-picture.png" alt="UserZ">
      </div>
    </div>
    
    <div class="row" id="footer">
      <div class="col-8"></div>

      <div class="col-4">

        <div class="container">
          <div class="row">

            <div class="col">
              <a href="http://" target="_blank" rel="noopener noreferrer">
                <span class="bi bi-github"></span>
              </a>
            </div>

            <div class="col">
              <a href="http://" target="_blank" rel="noopener noreferrer">
                <span class="bi bi-twitter"></span>
              </a>
            </div>

            <div class="col">
              <a href="http://" target="_blank" rel="noopener noreferrer">
                <span class="bi bi-linkedin"></span>
              </a>
            </div>

          </div>
        </div>

      </div>

    </div>

  </section>
</template>

<script>
// @ is an alias to /src

export default {
  name: 'HomeView'
}
</script>
