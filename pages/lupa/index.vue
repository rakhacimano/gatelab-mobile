<template>
  <div class="kontainer text-center">
    <!-- Kontainer Icon Back -->
    <div class="icon-back d-flex justify-content-start mt-3 mb-2">
      <nuxt-link to="masuk">
        <i class="uil desc uil-arrow-left"></i>
      </nuxt-link>
    </div>

    <!-- Kontainer Ilustrasi -->
    <div class="kontainer-ilustrasi">
      <img
        class="ilustrasi"
        src="~/assets/svg/verifikasi-email.svg"
        alt="Ilustrasi Verifikasi Email"
      />
    </div>

    <!-- Kontainer Headline -->
    <div class="headline__sub-headline">
      <h1 class="headline">Validasi Email</h1>
      <p class="sub-headline">Masukkan email untuk akun ini!</p>
    </div>

    <!-- Form Inputan -->
    <form class="form-input" @submit.prevent="">
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
      <button class="btn-filled">Masuk</button>
    </form>

  </div>
</template>

<script>
export default {}
</script>

<style scoped>
i.uil-arrow-left {
  font-size: 2rem;
}

.headline__sub-headline {
  margin-top: 2rem;
}

button.btn-filled {
  margin-top: 1rem;
}
</style>
