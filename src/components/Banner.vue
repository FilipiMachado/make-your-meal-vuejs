<template>
  <div class="main-banner">
    <h1>Make Your Meal</h1>
    <div class="main-banner__image">
      
    </div>
  </div>
</template>

<script>
export default {
  name: 'BanNer',
  data() {
    return {}
  },
}
</script>

<style scoped>
.main-banner {
  background-position: 0 -250px;
  background-size: cover;
  height: 500px;
  display: flex;
  align-items: center;
  justify-content: flex-start;
  background-color: #3b3b3b;
}
.main-banner h1 {
  color: #FAF304;
  text-align: center;
  font-size: 55px;
  padding: 60px;
}
.main-banner__image {
  background-image: url();
  background-size: cover;

}
</style>
