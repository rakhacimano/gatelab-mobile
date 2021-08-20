<template>
  <div class="kontainer text-center">
    <!-- Kontainer Icon Back -->
    <div class="icon-back d-flex justify-content-start mt-3 mb-2">
      <nuxt-link to="/lupa">
        <i class="uil desc uil-arrow-left"></i>
      </nuxt-link>
    </div>

    <!-- Kontainer Ilustrasi -->
    <div class="kontainer-ilustrasi">
      <img
        class="ilustrasi"
        src="~/assets/svg/cek-email.svg"
        alt="Ilustrasi Cek Email"
      />
    </div>

    <!-- Kontainer Headline -->
    <div class="headline__sub-headline">
      <h1 class="headline">Cek Pesan Email</h1>
      <p class="sub-headline">Kami sudah mengirim email untuk validasi</p>
    </div>

    <button class="btn-filled">Buka Aplikasi Email</button>
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
