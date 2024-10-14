<template>
    <nav id="nav">
        <router-link id="logo-url"  to="/">
            <img :src="logo" :alt="alt" id="logo">
        </router-link>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/pedidos">Pedidos</RouterLink>
    </nav>
</template>

<script>
export default {
    name: "NavBar",
    props: ["logo", "alt"]
}
</script>

<style scoped>
#nav {
  background-color: #222;
  border-bottom: 4px solid #111;
  padding: 15px 50px;
  display: flex;
  justify-content: flex-end;
  align-items: center;
}

#nav #logo-url {
  margin: auto;
  margin-left: 0;
}

#logo {
  width: 40px;
  height: 40px;
}

#nav a {
  color: #fcba03;
  text-decoration: none;
  margin: 12px;
  transition: .5s;
  padding: 6px 12px;
  border-radius: 8px;
}

#nav a:hover {
  background: #fcba0331;
}
</style>