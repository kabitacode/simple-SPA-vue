<template>
  <div id="app">
    <header id="header">
      <div class="container-fluid navbar-fluid">
        <nav class="navbar navbar-expand-lg" role="navigation">
        <div class="container">
            <div class="logo">
              <a href="#" class="navbar-brand">
                <img src="./assets/logo.png" alt>
              </a>
            </div>
            <button
              class="navbar-toggler"
              data-target="#navigation"
              data-toggle="collapse"
              aria-controls="navigation"
              aria-expanded="false"
              aria-label="Toggle navigation"
            >
              <span class="fa fa-bars"></span>
            </button>
            <div id="navigation" class="collapse navbar-collapse">
              <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                  <a class="nav-link">
                    <router-link to="/">Home</router-link>
                  </a>
                </li>
                <li class="nav-item">
                  <a class="nav-link">
                    <router-link to="/About">About us</router-link>
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </nav>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-sm-12">
            <div class="hero_content">
               <h1 class="hero_title">Spend Quality Holidays With Us</h1>
              <p class="hero_desc">
                Each room at our hotel is decorated with great taste. Designers’ solutions
                will impress you greatly. Each and every trifle is here for your comfort.
                Room service personnel is perfectly trained.
              </p>
            <div class="hero_btn">
              <a href="#" class="btn btn-more">Learn more</a>
            </div>
            </div>
          </div>
        </div>
      </div>
    </header>
    <router-view></router-view>
      <section class="footer">
            <div class="container">
                <p>Corinthia hotel &copy; 2019 Privacy Policy</p>
            </div>
      </section>
  </div>
</template>

<style lang="scss">
@import "assets/scss/_app.scss";  
</style>

