<template>
  <div class="kontainer">
    <div class="icon-back mt-3 mb-2">
      <nuxt-link to="detail-pintu">
        <i class="uil uil-arrow-left"></i>
      </nuxt-link>
    </div>

    <div class="kontainer-konten text-center">
      <div class="ilustrasi__tambah-akses">
        <img src="~/assets/svg/akses-baru.svg" alt="Ilustrasi Tambah Akses" />
      </div>

      <div class="headline__sub-headline">
        <h1 class="headline">Tambah Hak Akses</h1>
        <p class="sub-headline">Mau nambah pintu hak akses pintu?</p>
      </div>

      <form class="form-input" @submit.prevent="">
        <div class="input-group">
          <i class="icon-container uil uil-user-plus"></i>
          <input
            type="email"
            class="form-control"
            placeholder="Email"
            required
          />
        </div>
        <button class="btn-filled mt-3 mb-5">Tambah Hak Akses</button>
      </form>
    </div>
  </div>
</template>

<style scoped>
  .headline__sub-headline {
    margin-top: 2rem;
  }
</style>