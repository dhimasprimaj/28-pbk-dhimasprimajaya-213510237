<template>
    <h1>Asal Tembilahan</h1>
    <p>Dhimas Primajaya {{ id }}</p>
</template>

<script>
export default {
    props: ['id'],
    // data() {
    //     return {
    //         id: this.$route.params.id
    //     }
    // }
}
</script>

<style>
.teknik-informatika {
  max-width: 600px;
  margin: 200px auto;
  padding: 20px;
  background-color: #fff;
  border-radius: 4px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  text-align: center;
}

h1 {
  font-family: lauren script;
  text-align: center;
  margin-top: 200px;
  margin-bottom: 40px;
  color: #e5ff00;
  font-size: 50px;
}

p {
  color: #70ff53;
  font-size: 16px;
  line-height: 1.5;
}
</style>