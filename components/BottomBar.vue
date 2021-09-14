<template>
  <nav class="nav">
    <Nuxt-Link to="/beranda" class="nav_link">
      <i class="uil uil-estate"></i>
      <p>Home</p>
    </Nuxt-Link>
    <Nuxt-Link to="/berita" class="nav_link">
      <i class="uil uil-plus-circle"></i>
      <p>Profile</p>
    </Nuxt-Link>
    <Nuxt-Link to="/profil" class="nav_link">
      <i class="uil uil-user"></i>
      <p>Profile</p>
    </Nuxt-Link>
  </nav>
</template>

<style scoped>
.nav {
  box-shadow: 0 -8px 16px 5px rgba(20, 33, 61, 0.08);
  position: fixed;
  bottom: 0;
  width: inherit;
  height: 4.5rem;
  background-color: white;
  border-radius: 2rem 2rem 0 0;
  display: flex;
  overflow-x: auto;
}

i.uil {
  font-size: 1.5rem;
}

.nav_link {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  flex-grow: 1;
  min-width: 50px;
  overflow: hidden;
  font-size: 1rem;
  color: #96928e;
  text-decoration: none;
  -webkit-tap-highlight-color: transparent;
}

a.nuxt-link-exact-active {
  color: #fca311;
}
</style>
