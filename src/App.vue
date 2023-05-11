<template>
  <nav class="navbar">
    <router-link to="/" class="navbar-link">Home</router-link> |
    <router-link :to="{ name: 'About' }" class="navbar-link">About</router-link> |
    <router-link :to="{ name: 'Kegiatan' }" class="navbar-link">Kegiatan</router-link>
  </nav>
  <router-view/>
</template>

<style>
body {
	background-image: url('https://github.com/dhimasprimaj/28-pbk-uts-213510237/blob/master/src/assets/Ramadhan.png?raw=true'); 
	background-size: cover;
	background-repeat: no-repeat;
	background-position: center center;
	min-height: 150vh;
}

.navbar {
	display: flex;
	justify-content: center;
	margin-left: 20px;
	padding: 20px;
  background-color: #4b4b4b;
}

.navbar-link {
	margin: 0 10px;
	padding: 10px;
	color: #fff;
	text-decoration: none;
	font-size: 16px;
	font-weight: bold;
  background-color: #f47200;
  border-radius: 4px;
}

.navbar-link:hover {
	background-color: #555;
	border-radius: 4px;
}

.app {
	max-width: 600px;
	margin: 40px auto;
	padding: 20px;
}

h1 {
	font-family: lauren script;
	text-align: center;
	margin-bottom: 40px;
	color: #e5ff00;
	font-size: 50px;
}

input {
	margin-bottom: 10px;
	padding: 10px;
	width: 100%;
	border: none;
	background-color: #f7fafc;
	border-radius: 4px;
	color: #333;
	font-size: 16px;
}

ul {
    list-style-type: none;
    padding: 0;
}

li {
	list-style-type: none;;
	font-size: 125%;
	margin-bottom: 1em;
	position: relative;
	display: flex; /* tambahkan kode ini */
	align-items: center; /* tambahkan kode ini */
}

input[type="checkbox"] {
	
    margin-right: 10px; /* ubah margin menjadi 10px */
	background-color: #00ffc3;
}

.mt-4 {
	margin-top: 16px;
}

.p-6 {
	padding: 24px;
}

span {
	margin-right: 200px;
	color: #e5ff00;
	font-size: 30px;
	border: solid #636363;
 	border-radius: 90px;
	width: 6000px;
	text-align: center;
}

button {
	margin-right: 10px;
	padding: 10px 16px;
	background-color: #f47200;
	color: #fff;
	font-size: 16px;
	border: none;
	border-radius: 4px;
	cursor: pointer;
}

button:hover {
	background-color: #e460ff;
}

.home {
  max-width: 600px;
  margin: 200px auto;
  padding: 20px;
  background-color: #4b4b4b;
  border-radius: 4px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  text-align: center;
}

h1 {
  font-family: lauren script;
  text-align: center;
  margin-bottom: 40px;
  color: #e5ff00;
  font-size: 50px;
}

p {
  color: #87da2f;
  font-size: 16px;
  line-height: 1.5;
}

hr {
  border: none;
  border-top: 1px solid #ccc;
  margin-bottom: 20px;
}
.about {
  display: flex;
  justify-content: center;
  margin: 10px auto;
  max-width: 600px;
}

.about h2 {
  background: rgba(0, 0, 0, 0.35);
  padding: 20px;
  border-radius: 10px;
  cursor: pointer;
  color: #070707;
  font-size: 18px;
  line-height: 1.5;
  text-align: center;
  width: 100%;
  margin: 0;
}

.about h2:hover {
  background: rgba(0, 0, 0, 0.15);
}

.about a {
  text-decoration: none;
}

.about-details {
  max-width: 600px;
  padding: 20px;
  margin-top: 50px;
  margin-bottom: 70px;
  background-color: #fff;
  border-radius: 4px;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
  text-align: center;
}

h1 {
  font-family: lauren script;
  text-align: center;
  margin-top: 20px;
  margin-bottom: 40px;
  color: #e5ff00;
  font-size: 50px;
}

p {
  color: #87da2f;
  font-size: 16px;
  line-height: 1.5;
  text-align: center;
}
</style>
