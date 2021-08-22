<template>
  <div class="kontainer text-center">
    <!-- Kontainer Icon Back -->
    <div class="icon-back d-flex justify-content-start mt-3 mb-2">
      <nuxt-link to="/">
        <i class="uil desc uil-arrow-left"></i>
      </nuxt-link>
    </div>

    <!-- Kontainer Ilustrasi -->
    <div class="kontainer-ilustrasi">
      <img
        class="ilustrasi"
        src="~/assets/svg/daftar.svg"
        alt="Ilustrasi Register"
      />
    </div>

    <!-- Kontainer Headline -->
    <div class="headline__sub-headline">
      <h1 class="headline">Daftar Akun</h1>
      <p class="sub-headline">Yuk daftar jadi bagian gatelab!</p>
    </div>

    <!-- Form Inputan -->
    <form class="form-input" @submit.prevent="daftarUser()">
      <div class="input-group">
        <i class="icon-container uil uil-envelope"></i>
        <input
          v-model="email"
          type="email"
          class="form-control"
          placeholder="Email"
          required
        />
      </div>
      <div class="input-group">
        <i class="icon-container uil uil-lock-alt"></i>
        <input
          v-model="password"
          type="password"
          class="form-control"
          placeholder="Password"
          required
        />
      </div>
      <div class="input-group">
        <i class="icon-container uil uil-lock-alt"></i>
        <input
          v-model="password_confirmation"
          type="password"
          class="form-control"
          placeholder="Konfirmasi Password"
          required
        />
      </div>
      <button class="btn-filled mt-3">Daftar</button>
    </form>

    <!-- Link Daftar -->
    <div class="kontainer-masuk">
      <p class="sub-headline">
        Sudah punya akun?
        <nuxt-link class="link-masuk" to="/masuk"> Masuk</nuxt-link>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    daftarUser() {
      const formRegister = {
        email: this.email,
        password: this.password,
        password_confirmation: this.password_confirmation,
      }
      this.$axios
      .post('https://gatelab.thunderlab.id/register', formRegister)
      .then((res) => {
        console.log(res)
        this.$router.push('/masuk')
      })

      .catch((err) => {
        this.errors = err.response.data.errors
      })
    },
  },
}
</script>

<style scoped>
i.uil-arrow-left {
  font-size: 2rem;
}

.headline__sub-headline {
  margin-top: 2rem;
}

.kontainer-masuk {
  margin-top: 2rem;
}

a {
  color: #14213d;
  font-weight: 500;
  text-decoration: none;
}
</style>
