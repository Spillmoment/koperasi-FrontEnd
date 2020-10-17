<template>

  <body class="bg-soft">
    <main>
      <!-- Section -->
      <section class="vh-lg-100 d-flex align-items-center">
        <div class="container">
          <div
            class="row justify-content-center form-bg-image"
            data-background-lg="../assets/illustrations/signin.svg"
          >

            <div class="col-12 d-flex align-items-center justify-content-center">
              <div class="signin-inner my-3 my-lg-0 bg-white shadow-soft border rounded border-light p-4 p-lg-5 w-100 fmxw-500">
                <div class="text-center text-md-center mb-4 mt-md-0">
                  <h1 class="mb-0 h3">{{ login }}</h1>
                </div>
                <form
                  action="#"
                  class="mt-4"
                >
                  <!-- Form -->
                  <div class="form-group mb-4">
                    <label
                      for="email"
                      class="email-mr"
                    >Email Anda</label>
                    <div class="input-group">
                      <span
                        class="input-group-text"
                        id="basic-addon1"
                      ><span class="fas fa-envelope"></span></span>
                      <input
                        type="email"
                        class="form-control"
                        placeholder="example@koperasi.com"
                        id="email"
                        autofocus
                        required
                      >
                    </div>
                  </div>
                  <!-- End of Form -->
                  <div class="form-group">
                    <!-- Form -->
                    <div class="form-group mb-4">
                      <label
                        for="password"
                        class="pass-mr"
                      >Password Anda</label>
                      <div class="input-group">
                        <span
                          class="input-group-text"
                          id="basic-addon2"
                        ><span class="fas fa-unlock-alt"></span></span>
                        <input
                          type="password"
                          placeholder="Password"
                          class="form-control"
                          id="password"
                          required
                        >
                      </div>
                    </div>
                    <!-- End of Form -->
                    <div class="d-flex justify-content-between align-items-center mb-4">
                      <div class="form-check">
                        <input
                          class="form-check-input"
                          type="checkbox"
                          value=""
                          id="defaultCheck5"
                        >
                        <label
                          class="form-check-label"
                          for="defaultCheck5"
                        >
                          Remember me
                        </label>
                      </div>
                      <div><a
                          href="#"
                          class="small text-right"
                        >Lupa password?</a></div>
                    </div>
                  </div>
                  <button
                    type="submit"
                    class="btn btn-block btn-primary"
                  >Masuk</button>
                </form>
                <div class="d-flex justify-content-center align-items-center mt-4">
                  <span class="font-weight-normal">
                    Not registered?
                    <a
                      href="./sign-up.html"
                      class="font-weight-bold"
                    >Create account</a>
                  </span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
  </body>

</template>

<script>
export default {
  name: 'Login',
  data () {
    return {
      login: 'Koperasi Sinjam Kemenag'
    }
  }
}
</script>

<style>
 .email-mr {
    margin-right: 310px
}
 .pass-mr {
    margin-right: 280px
}
</style>