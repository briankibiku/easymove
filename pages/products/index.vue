<template>
    <div>
      <Navbar />
      <br />

        <b-container>
            <b-row align-v="center" fluid="md" style="margin: 1em;">
            <b-col sm="6">
                    <div class="container">
                        <div class="card">
                        <img
                            src="../../assets/tb.jpeg"
                            class="img-fluid"
                        />
                        <div class="card-body">
                            <h5 class="card-title">Rubicon X Trading Bot</h5>
                            <p class="card-text">
                            Make $1 every day trading forex and binary options.
                            </p>
                            <h5 class="card-title">Price: $600</h5>
                            <a
                            class="btn btn-primary"
                            href="http://fikisha-app.herokuapp.com"
                            target="_blank"
                            >
                            Buy Rubicon</a
                            >
                        </div>
                        </div>
                    </div>
            </b-col>
            <b-col sm="6">
                <div class="container">
                        <div class="card">
                        <img
                            src="../../assets/tb.jpeg"
                            class="img-fluid"
                        />
                        <div class="card-body">
                            <h5 class="card-title">Rubicon ProFX Trading Bot</h5>
                            <p class="card-text">
                            Make $1.6 every day trading forex and binary options.
                            </p>
                            <h5 class="card-title">Price: $850</h5>
                            <a
                            class="btn btn-primary"
                            href="http://fikisha-app.herokuapp.com"
                            target="_blank"
                            >
                            Buy Rubicon ProFX</a
                            >
                        </div>
                        </div>
                    </div>
            </b-col>
        </b-row>
        </b-container>

      <br />
      <div class="d-flex justify-content-center">
        <div class="row align-items-start" style="width: 1400"></div>
      </div>
      <!-- <Footer /> -->
      <footer class="page-footer font-small blue pt-4">
        <div class="footer-copyright text-center py-3" style="color: grey">
          © 2023 Copyright: ProFX
        </div>
      </footer>
      <Footer />
    </div>
  </template>
  <script>
  export default {
    name: 'IndexPage'
  }
  </script>
