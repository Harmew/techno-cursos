<template>
  <header>
    <nav>
      <div class="logo">
        <router-link to="/">Techno</router-link>
      </div>
      <ul>
        <li>
          <router-link to="/cursos">Cursos</router-link>
        </li>
        <li>
          <router-link to="/contato">Contato</router-link>
        </li>
      </ul>
    </nav>
  </header>
</template>

<script>
export default {
  nem: "TheHeader",
};
</script>

<style scoped>
header {
  background: #234;
}

header a {
  color: #fff;
}

nav {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  align-items: center;
  align-content: space-between;
  padding: 20px;
}

.logo {
  flex: 1;
}

.logo a {
  font-size: 2rem;
  color: #fff;
}

a.router-link-exact-active {
  color: #4b8;
}

ul li {
  display: inline-block;
}

li a {
  padding: 0 10px;
  margin-left: 10px;
}
</style>
