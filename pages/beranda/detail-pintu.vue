<template>
  <div class="kontainer">
    <div class="kontainer__deskripsi-pintu sticky-top pt-4 pb-4 bg-white">
      <!-- Kontainer Judul Halaman -->
      <div class="icon-back d-flex align-items-center mb-3">
        <div class="icon-back mr-3">
          <nuxt-link to="/beranda">
            <i class="uil desc uil-arrow-left"></i>
          </nuxt-link>
        </div>
        <div class="judul-halaman">
          <h1 class="headline">Detail Pintu</h1>
        </div>
      </div>

      <!-- Kontainer Detail Pintu -->
      <div class="kontainer__detail-pintu">
        <div class="kontainer__isi-pintu d-flex align-items-center">
          <div class="logo-pintu mr-3">
            <img
              class="logo-pintu__svg"
              src="~/assets/svg/logo.svg"
              alt="Logo Pintu"
            />
          </div>
          <div class="deskripsi-kontainer">
            <div class="title-pintu mb-2">
              <p class="semibold">Pintu Depan</p>
            </div>
            <div class="deskripsi-pintu">
              <table>
                <tbody>
                  <tr>
                    <th><i class="uil uil-lock"></i></th>
                    <td>Status</td>
                    <td>:</td>
                    <td>Terkunci</td>
                  </tr>
                  <tr>
                    <th><i class="uil uil-user"></i></th>
                    <td>Akses</td>
                    <td>:</td>
                    <td>Fulan</td>
                  </tr>
                  <tr>
                    <th><i class="uil uil-location-pin-alt"></i></th>
                    <td>Lokasi</td>
                    <td>:</td>
                    <td>Rumah Fulan</td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!-- Hak Akses -->
    <div
      class="hak-akses d-flex justify-content-between align-items-center mb-4"
    >
      <div class="headline__sub-headline">
        <h1 class="headline">Hak Akses</h1>
        <p class="sub-headline">Daftar hak akses pintu</p>
      </div>
      <div class="button-tambah">
        <nuxt-link to="tambah-akses">
          <button class="btn-outline pl-4 pr-4">Tambah</button>
        </nuxt-link>
      </div>
    </div>

    <!-- Kontainer List Hak Akses -->
    <div class="kontainer__hak-akses mb-5">
      <!-- User 1 -->
      <div class="kontainer-user btn-outline d-flex align-items-center mb-3">
        <div class="foto pl-2 pr-2">
          <img src="~/assets/image/foto-profil.png" alt="Foto Profil" />
        </div>

        <div class="nama">
          <p class="semibold pl-3">Fulan bin Fulan</p>
        </div>

        <div class="button-hapus ml-auto">
          <button class="btn-outline unlock">
            <i class="uil uil-trash"></i>
          </button>
        </div>
      </div>

      <!-- User 2 -->
      <div class="kontainer-user btn-outline d-flex align-items-center mb-3">
        <div class="foto pl-2 pr-2">
          <img src="~/assets/image/foto-profil.png" alt="Foto Profil" />
        </div>

        <div class="nama">
          <p class="semibold pl-3">Fulan bin Fulan</p>
        </div>

        <div class="button-hapus ml-auto">
          <button class="btn-outline unlock">
            <i class="uil uil-trash"></i>
          </button>
        </div>
      </div>

      <!-- User 3 -->
      <div class="kontainer-user btn-outline d-flex align-items-center mb-3">
        <div class="foto pl-2 pr-2">
          <img src="~/assets/image/foto-profil.png" alt="Foto Profil" />
        </div>

        <div class="nama">
          <p class="semibold pl-3">Fulan bin Fulan</p>
        </div>

        <div class="button-hapus ml-auto">
          <button class="btn-outline unlock">
            <i class="uil uil-trash"></i>
          </button>
        </div>
      </div>
    </div>
    <!-- Kontainer Button Bawah -->
    <div class="kontainer__button-bawah pt-4 pb-4">
      <div class="kontainer-button d-flex mb-3">
        <button class="btn-flex btn-outline mr-3">Sambungkan</button>
        <button class="btn-flex btn-filled text-white">
          <i class="uil uil-lock text-white"></i> Kunci
        </button>
      </div>
      <button class="btn-outline hapus">
        <i class="uill uil-trash"></i> Hapus Pintu
      </button>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.logo-pintu__svg {
  width: 6rem;
}

td {
  padding-left: 0.5rem;
}

.uil-lock,
.uil-user,
.uil-location-pin-alt {
  color: #fca311;
}

.kontainer-user {
  border: 0.5px solid rgba(150, 146, 142, 0.32);
}

.btn-flex {
  height: 156px;
}

.btn-filled {
  background-color: #ff4040;
}

.btn-outline.hapus {
  border-color: #ff4040;
  color: #ff4040;
}
</style>
