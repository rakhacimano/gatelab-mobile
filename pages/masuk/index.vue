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
        src="~/assets/svg/masuk.svg"
        alt="Ilustrasi Login"
      />
    </div>

    <!-- Kontainer Headline -->
    <div class="headline__sub-headline">
      <h1 class="headline">Masuk Akun</h1>
      <p class="sub-headline">Hai, kembali lagi. Yuk masuk!</p>
    </div>

    <!-- Form Inputan -->
    <form class="form-input" @submit.prevent="masukUser()">
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
      <nuxt-link class="link-lupa" to="/lupa">Lupa password?</nuxt-link>
      <button class="btn-filled">Masuk</button>
    </form>

    <!-- Link Daftar -->
    <div class="kontainer-daftar">
      <p class="sub-headline">
        Belum punya akun?
        <nuxt-link class="link-daftar" to="/daftar"> Daftar</nuxt-link>
      </p>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    masukUser() {
      const formLogin = {
        email: this.email,
        password: this.password,
      }
      this.$axios
      .post('https://gatelab.thunderlab.id/login', formLogin)
      .then((res) => {
        console.log(res)
        this.$router.push('/beranda')
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

.link-lupa {
  float: right;
  margin-bottom: 2rem;
}

.kontainer-daftar {
  margin-top: 2rem;
}

a {
  color: #14213d;
  font-weight: 500;
  text-decoration: none;
}
</style>
