<template>
  <div>
    <Navs />
    <div class="container-fluid bg-soft">
      <div class="row">
        <div class="col-12">

          <!-- Sidebar -->
          <Sidebar />
          <!-- End Sidebar -->

          <main class="content">

            <!-- Navbar -->
            <Navbar />
            <!-- End Navbar -->

            <!-- Content -->
            <div class="d-flex justify-content-between flex-wrap flex-md-nowrap align-items-center py-4">
              <div class="card border-light shadow-sm">
                <div class="card-body">
                  <div class="table-responsive">
                    <table class="table table-centered table-nowrap mb-0 rounded">
                      <thead class="thead-light">
                        <tr>
                          <th class="border-0">Country</th>
                          <th class="border-0">All</th>
                          <th class="border-0">All Change</th>
                          <th class="border-0">Travel & Local</th>
                          <th class="border-0">Travel & Local Change</th>
                          <th class="border-0">Widgets</th>
                          <th class="border-0">Widgets Change</th>
                        </tr>
                      </thead>
                      <tbody>
                        <!-- Item -->
                        <tr>
                          <td class="border-0">
                            <a
                              href="#"
                              class="d-flex align-items-center"
                            >
                              <img
                                class="mr-2 image image-small rounded-circle"
                                alt="Image placeholder"
                                src="../assets/img/flags/united-states-of-america.svg"
                              >
                              <div><span class="h6">United States</span></div>
                            </a>
                          </td>
                          <td class="border-0 font-weight-bold">106</td>
                          <td class="border-0 text-danger">
                            <span class="fas fa-angle-down"></span>
                            <span class="font-weight-bold">5</span>
                          </td>
                          <td class="border-0 font-weight-bold">
                            3
                          </td>
                          <td class="border-0">
                            =
                          </td>
                          <td class="border-0 font-weight-bold">
                            32
                          </td>
                          <td class="border-0 text-success">
                            <span class="fas fa-angle-up"></span>
                            <span class="font-weight-bold">3</span>
                          </td>
                        </tr>
                        <!-- End of Item -->

                        <!-- Item -->
                        <tr>
                          <td class="border-0">
                            <a
                              href="#"
                              class="d-flex align-items-center"
                            >
                              <img
                                class="mr-2 image image-small rounded-circle"
                                alt="Image placeholder"
                                src="../assets/img/flags/canada.svg"
                              >
                              <div><span class="h6">Canada</span></div>
                            </a>
                          </td>
                          <td class="border-0 font-weight-bold">76</td>
                          <td class="border-0 text-success">
                            <span class="fas fa-angle-up"></span>
                            <span class="font-weight-bold">17</span>
                          </td>
                          <td class="border-0 font-weight-bold">
                            4
                          </td>
                          <td class="border-0">
                            =
                          </td>
                          <td class="border-0 font-weight-bold">
                            30
                          </td>
                          <td class="border-0 text-success">
                            <span class="fas fa-angle-up"></span>
                            <span class="font-weight-bold">3</span>
                          </td>
                        </tr>
                        <!-- End of Item -->

                        <!-- Item -->
                        <tr>
                          <td class="border-0">
                            <a
                              href="#"
                              class="d-flex align-items-center"
                            >
                              <img
                                class="mr-2 image image-small rounded-circle"
                                alt="Image placeholder"
                                src="../assets/img/flags/united-kingdom.svg"
                              >
                              <div><span class="h6">United Kingdom</span></div>
                            </a>
                          </td>
                          <td class="border-0 font-weight-bold">147</td>
                          <td class="border-0 text-success">
                            <span class="fas fa-angle-up"></span>
                            <span class="font-weight-bold">10</span>
                          </td>
                          <td class="border-0 font-weight-bold">
                            5
                          </td>
                          <td class="border-0">
                            =
                          </td>
                          <td class="border-0 font-weight-bold">
                            34
                          </td>
                          <td class="border-0 text-success">
                            <span class="fas fa-angle-up"></span>
                            <span class="font-weight-bold">7</span>
                          </td>
                        </tr>
                        <!-- End of Item -->

                        <!-- Item -->
                        <tr>
                          <td class="border-0">
                            <a
                              href="#"
                              class="d-flex align-items-center"
                            >
                              <img
                                class="mr-2 image image-small rounded-circle"
                                alt="Image placeholder"
                                src="../assets/img/flags/france.svg"
                              >
                              <div><span class="h6">France</span></div>
                            </a>
                          </td>
                          <td class="border-0 font-weight-bold">112</td>
                          <td class="border-0 text-success">
                            <span class="fas fa-angle-up"></span>
                            <span class="font-weight-bold">3</span>
                          </td>
                          <td class="border-0 font-weight-bold">
                            5
                          </td>
                          <td class="border-0 text-success">
                            <span class="fas fa-angle-up"></span>
                            <span class="font-weight-bold">1</span>
                          </td>
                          <td class="border-0 font-weight-bold">
                            34
                          </td>
                          <td class="border-0 text-danger">
                            <span class="fas fa-angle-down"></span>
                            <span class="font-weight-bold">2</span>
                          </td>
                        </tr>
                        <!-- End of Item -->

                        <!-- Item -->
                        <tr>
                          <td class="border-0">
                            <a
                              href="#"
                              class="d-flex align-items-center"
                            >
                              <img
                                class="mr-2 image image-small rounded-circle"
                                alt="Image placeholder"
                                src="../assets/img/flags/japan.svg"
                              >
                              <div><span class="h6">Japan</span></div>
                            </a>
                          </td>
                          <td class="border-0 font-weight-bold">115</td>
                          <td class="border-0 text-danger">
                            <span class="fas fa-angle-down"></span>
                            <span class="font-weight-bold">12</span>
                          </td>
                          <td class="border-0 font-weight-bold">
                            6
                          </td>
                          <td class="border-0 text-danger">
                            <span class="fas fa-angle-down"></span>
                            <span class="font-weight-bold">1</span>
                          </td>
                          <td class="border-0 font-weight-bold">
                            37
                          </td>
                          <td class="border-0 text-danger">
                            <span class="fas fa-angle-down"></span>
                            <span class="font-weight-bold">5</span>
                          </td>
                        </tr>
                        <!-- End of Item -->

                        <!-- Item -->
                        <tr>
                          <td class="border-0">
                            <a
                              href="#"
                              class="d-flex align-items-center"
                            >
                              <img
                                class="mr-2 image image-small rounded-circle"
                                alt="Image placeholder"
                                src="../assets/img/flags/germany.svg"
                              >
                              <div><span class="h6">Germany</span></div>
                            </a>
                          </td>
                          <td class="border-0 font-weight-bold">220</td>
                          <td class="border-0 text-danger">
                            <span class="fas fa-angle-down"></span>
                            <span class="font-weight-bold">56</span>
                          </td>
                          <td class="border-0 font-weight-bold">
                            7
                          </td>
                          <td class="border-0 text-danger">
                            <span class="fas fa-angle-down"></span>
                            <span class="font-weight-bold">3</span>
                          </td>
                          <td class="border-0 font-weight-bold">
                            30
                          </td>
                          <td class="border-0 text-success">
                            <span class="fas fa-angle-up"></span>
                            <span class="font-weight-bold">2</span>
                          </td>
                        </tr>
                        <!-- End of Item -->
                      </tbody>
                    </table>
                  </div>
                </div>
              </div>
            </div>
            <!-- End Content -->

            <!-- Footer -->
            <Footer />
            <!-- End Footer -->

          </main>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Navs from '@/components/Navs.vue'
import Navbar from '@/components/Navbar.vue'
import Sidebar from '@/components/Sidebar.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Dashboard',
  components: {
    Navs,
    Navbar,
    Sidebar,
    Footer
  }
}
</script>

<style>

</style>