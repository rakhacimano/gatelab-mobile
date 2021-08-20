<template>
  <div class="kontainer">
    <!-- Kontainer Top Bar Position Sticky -->
    <div class="kontainer__top-bar sticky-top pt-4 pb-2 bg-white">
      <!-- Top Bar -->
      <div
        class="
          top-bar
          d-flex
          justify-content-between
          align-items-center
          mb-4
        "
      >
        <div class="lokasi">
          <p class="sub-headline">
            Rumah Fulan
            <i class="uil desc uil-angle-down ml-2"></i>
          </p>
        </div>
        <div class="foto-profil bg-warning rounded">
          <img src="~/assets/image/foto-profil.png" alt="Foto Profil" />
        </div>
      </div>

      <!-- Kontainer Headline & Button Tambah -->
      <div
        class="
          headline-tambah
          d-flex
          justify-content-between
          align-items-center
          mb-3
        "
      >
        <div class="headline__sub-headline">
          <h1 class="headline">Daftar Pintu</h1>
          <p class="sub-headline">Yuk, lihat pintumu!</p>
        </div>
        <div class="button-tambah">
          <nuxt-link to="tambah-pintu">
            <button class="btn-outline pl-4 pr-4">Tambah</button>
          </nuxt-link>
        </div>
      </div>
    </div>

    <!-- Kontainer List Pintu -->
    <div class="kontainer__daftar-pintu mb-4">
      <!-- Kontainer Pintu1 -->
      <div class="kontainer-pintu p-3 mb-4">
        <div class="kontainer__isi-pintu d-flex align-items-center">
          <div class="logo-pintu mr-3">
            <img src="~/assets/svg/logo.svg" alt="Logo Pintu" />
          </div>
          <div class="deskripsi-kontainer">
            <div class="title-pintu mb-1">
              <p class="semibold">Pintu Depan</p>
            </div>
            <div class="deskripsi-pintu d-flex align-items-center">
              <i class="uil desc uil-lock mr-2"></i>
              <p class="sub-headline">Terkunci</p>
            </div>
            <div class="deskripsi-pintu d-flex align-items-center">
              <i class="uil desc uil-user mr-2"></i>
              <p class="sub-headline">Gajahmada</p>
            </div>
          </div>
        </div>

        <!-- Kontainer Button -->
        <div class="button-container d-flex mt-3">
          <nuxt-link
            class="btn-outline d-flex justify-content-center align-items-center"
            to="/beranda/detail-pintu"
          >
            Detail
          </nuxt-link>
          <button class="btn-outline lock ml-3">
            <i class="uil uil-power"></i>
          </button>
        </div>
      </div>

      <!-- Kontainer Pintu2-->
      <div class="kontainer-pintu p-3 mb-4">
        <div class="kontainer__isi-pintu d-flex align-items-center">
          <div class="logo-pintu mr-3">
            <img src="~/assets/svg/logo.svg" alt="Logo Pintu" />
          </div>
          <div class="deskripsi-kontainer">
            <div class="title-pintu mb-1">
              <p class="semibold">Pintu Depan</p>
            </div>
            <div class="deskripsi-pintu d-flex align-items-center">
              <i class="uil desc uil-lock mr-2"></i>
              <p class="sub-headline">Terkunci</p>
            </div>
            <div class="deskripsi-pintu d-flex align-items-center">
              <i class="uil desc uil-user mr-2"></i>
              <p class="sub-headline">Fulan</p>
            </div>
          </div>
        </div>

        <!-- Kontainer Button -->
        <div class="button-container d-flex mt-3">
          <nuxt-link
            class="btn-outline d-flex justify-content-center align-items-center"
            to="/beranda/detail-pintu"
          >
            Detail
          </nuxt-link>
          <button class="btn-outline lock ml-3">
            <i class="uil uil-power"></i>
          </button>
        </div>
      </div>

      <!-- Kontainer Pintu4 -->
      <div class="kontainer-pintu p-3 mb-4">
        <div class="kontainer__isi-pintu d-flex align-items-center">
          <div class="logo-pintu mr-3">
            <img src="~/assets/svg/logo.svg" alt="Logo Pintu" />
          </div>
          <div class="deskripsi-kontainer">
            <div class="title-pintu mb-1">
              <p class="semibold">Pintu Depan</p>
            </div>
            <div class="deskripsi-pintu d-flex align-items-center">
              <i class="uil desc uil-lock mr-2"></i>
              <p class="sub-headline">Tidak Dikunci</p>
            </div>
            <div class="deskripsi-pintu d-flex align-items-center">
              <i class="uil desc uil-user mr-2"></i>
              <p class="sub-headline">Brawijaya</p>
            </div>
          </div>
        </div>

        <!-- Kontainer Button -->
        <div class="button-container d-flex mt-3">
          <nuxt-link
            class="btn-outline d-flex justify-content-center align-items-center"
            to="/beranda/detail-pintu"
          >
            Detail
          </nuxt-link>
          <button class="btn-outline unlock ml-3">
            <i class="uil uil-power"></i>
          </button>
        </div>
      </div>

      <!-- Kontainer Pintu3 -->
      <div class="kontainer-pintu p-3 mb-4">
        <div class="kontainer__isi-pintu d-flex align-items-center">
          <div class="logo-pintu mr-3">
            <img src="~/assets/svg/logo.svg" alt="Logo Pintu" />
          </div>
          <div class="deskripsi-kontainer">
            <div class="title-pintu mb-1">
              <p class="semibold">Pintu Depan</p>
            </div>
            <div class="deskripsi-pintu d-flex align-items-center">
              <i class="uil desc uil-lock mr-2"></i>
              <p class="sub-headline">Tidak Dikunci</p>
            </div>
            <div class="deskripsi-pintu d-flex align-items-center">
              <i class="uil desc uil-user mr-2"></i>
              <p class="sub-headline">Brawijaya</p>
            </div>
          </div>
        </div>

        <!-- Kontainer Button -->
        <div class="button-container d-flex mt-3">
          <nuxt-link
            class="btn-outline d-flex justify-content-center align-items-center"
            to="/beranda/detail-pintu"
          >
            Detail
          </nuxt-link>
          <button class="btn-outline unlock ml-3">
            <i class="uil uil-power"></i>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'bottom-bar',
}
</script>

<style scoped>
.kontainer-pintu {
  border: .5px solid rgba(150, 146, 142, .32);
  border-radius: 1rem;
}

a {
  text-decoration: none;
  color: #14213d;
}


i.uil-lock,
i.uil-user {
  color: #fca311;
}

.kontainer {
  margin-bottom: 10rem;
}

</style>
