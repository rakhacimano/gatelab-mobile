<template>
  <div class="kontainer text-center">
    <!-- kontainer ilustrasi -->
    <div class="kontainer-ilustrasi">
      <img
        class="ilustrasi"
        src="~/assets/svg/get-started.svg"
        alt="Ilustrasi Get Started"
      />
    </div>

    <div class="kontainer__button-headline">
      <!-- Headline -->
      <div class="headline__sub-headline">
        <h1 class="headline">Gatelab Mobile</h1>
        <p class="sub-headline">Aplikasi pembuka pintu dari HP-mu!</p>
      </div>

      <!-- Button -->
      <div class="kontainer-button">
        <nuxt-link to="/daftar">
          <button class="btn-filled">Daftar</button>
        </nuxt-link>
        <nuxt-link to="/masuk">
          <button class="btn-outline">Masuk</button>
        </nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.kontainer-ilustrasi {
  margin: 8rem 0 10rem;
}

.kontainer-button {
  margin-bottom: 3rem;
}

.btn-filled {
  margin: 2rem 0 1rem;
}
</style>
