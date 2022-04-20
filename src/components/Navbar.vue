<template>
  <div id="nav">
    <router-link to="/" id="logo-url">
      <img :src="logo" :alt="alt" id="logo">
    </router-link>
    <router-link to="/">Home</router-link>
    <router-link to="/orders">My Orders</router-link>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
  props: [
    'logo',
    'alt'
  ],
  data() {
    return {}
  },
};
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
  color: #fff;
  text-decoration: none;
  font-weight: bold;
  margin: 12px;
  transition: .5s;
  border-bottom: 2px solid #FAF304;
}
#nav a:first-child {
  border-bottom: none;
}
#nav a:hover {
  color: #fff;
  border-bottom: 2px solid #ED1B24;
}
</style>
