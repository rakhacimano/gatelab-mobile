<template>
  <div class="kontainer">
    <div class="icon-back mt-3 mb-2">
      <nuxt-link to="/beranda">
        <i class="uil uil-arrow-left"></i>
      </nuxt-link>
    </div>

    <div class="kontainer-konten text-center">
      <div class="ilustrasi__tambah-pintu">
        <img src="~/assets/svg/pintu-baru.svg" alt="Ilustrasi Tambah Pintu" />
      </div>

      <div class="headline__sub-headline">
        <h1 class="headline">Tambah Pintu</h1>
        <p class="sub-headline">Mau nambah pintu baru?</p>
      </div>

      <!-- Form Inputan -->
      <form class="form-input" @submit.prevent="">
        <div class="input-group">
          <i class="icon-container uil uil-archway"></i>
          <input
            type="text"
            class="form-control"
            placeholder="Nama Pintu"
            required
          />
        </div>
        <div class="input-group">
          <i class="icon-container uil uil-location-pin-alt"></i>
          <input
            type="email"
            class="form-control"
            placeholder="Lokasi"
            required
          />
        </div>
        <div class="input-group">
          <i class="icon-container uil uil-link"></i>
          <input
            type="url"
            class="form-control"
            placeholder="Tautan Pintu"
            required
          />
        </div>

        <p class="semibold mb-3 mt-4 text-left">Hak Akses</p>

        <div class="input-group">
          <i class="icon-container uil uil-envelope"></i>
          <input
            type="email"
            class="form-control"
            placeholder="Email"
            required
          />
        </div>

        <button class="btn-filled mt-3 mb-5">Tambah Pintu</button>
      </form>
    </div>
  </div>
</template>

<style scoped>
.headline__sub-headline {
  margin-top: 2rem;
}
</style>
