<template>
  <div v-for="abouts in about" :key="abouts.id" class="about">
    <router-link :to="{name: 'AboutDetails', params: { id: abouts.id }}">
      <h2>{{ abouts.tittle }}</h2>
    </router-link>
  </div>
</template>

<script>
export default {
  data() {
    return {
      about: [
        { tittle: 'Anak Rumahan', id: 1, details: 'lorem' },
        { tittle: 'Visit Me', id: 2, details: 'lorem' },
        
      ]
    }
  }
}
</script>

<style>
.about h2{
  background: #f47200;
  padding: 20px;
  border-radius: 10px;
  margin-top: 100px;
  margin-left: -20px;
  max-width: 600px;
  cursor: pointer;
  color: #ffffff;
}
.about h2:hover {
  background: #4b4b4b;
}
.about a{
  text-decoration: none;
}
</style>