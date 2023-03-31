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
                            src="../../assets/estimate.png"
                            class="img-fluid"
                        />
                        <div class="card-body">
                            <h5 class="card-title">Virtual Moving Estimation</h5>
                            <p class="card-text">
                            Have a virtual call with one of our respresentatives and get an instant moving quote.
                            </p>
                            <h5 class="card-title">Price: FREE</h5>
                            <a
                            class="btn btn-primary"
                            href="#"
                            target="_blank"
                            >
                            Know More</a
                            >
                        </div>
                        </div>
                    </div>
            </b-col>
            <b-col sm="6">
                <div class="container">
                        <div class="card">
                        <img
                            src="../../assets/bulk_moving.jpeg"
                            class="img-fluid"
                        />
                        <div class="card-body">
                            <h5 class="card-title">Bulk Product Moving</h5>
                            <p class="card-text">
                            Need more that one truck to move commodities and goods to any part of Kenya?
                            </p>
                            <h5 class="card-title">Price: starting from $850</h5>
                            <a
                            class="btn btn-primary"
                            href="#"
                            target="_blank"
                            >
                            Know More</a
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
          © 2023 Copyright: easymove
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
