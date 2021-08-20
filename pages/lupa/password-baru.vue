<template>
  <div class="kontainer text-center">
    <!-- Kontainer Icon Back -->
    <div class="icon-back d-flex justify-content-start mt-3 mb-2">
      <nuxt-link to="cek-email">
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
      <h1 class="headline">Password Baru</h1>
      <p class="sub-headline">Ganti passwordmu, jangan lupa lagi ya!</p>
    </div>

    <!-- Form Inputan -->
    <form class="form-input" @submit.prevent="">
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
          v-model="password_validation"
          type="password"
          class="form-control"
          placeholder="Konfirmasi Password"
          required
        />
      </div>
      <button class="btn-filled">Buat Password</button>
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
  margin-top: 2rem;
}
</style>
