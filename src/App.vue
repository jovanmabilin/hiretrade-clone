<template>
  <div id="app">
    <Home />
  </div>
</template>

<script>
import Home from './components/Home.vue'

export default {
  name: 'App',
  components: {
    Home
  }
}
</script>

<style>
html {
    overflow: scroll;
    overflow-x: hidden;
}
body {
  height: 100%;
  background-color: #f2f4f4;
  font-size: 14px;
  font-family: Helvetica, Arial, sans-serif;
  margin: 0;
  padding: 0;
  color: #475f7b;
  overflow: hidden;
}
.cursor-pointer {
  cursor: pointer;
}
ul, li {
  list-style-type: none;
  margin: 0;
  padding: 0;
}
a {
  text-decoration: none;
  color: #727e8c;
}
a:hover {
  text-decoration: underline;
  color: #7367f0;
}

h1,h2,h3,h4,h5,h6 {
  margin: 0;
  padding: 0;
  font-family: Rubik,Helvetica,Arial,serif;
  font-weight: 400;
  color: #475f7b;
}

h6 {
  font-size: 1.8rem;
}

.btn {
  cursor: pointer;
  display: inline-block;
  font-weight: 400;
  color: #727e8c;
  text-align: center;
  vertical-align: middle;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  background-color: transparent;
  border: 0 solid transparent;
  padding: 10px 20px;
  font-size: 14px;
  border-radius: .267rem;
  transition: color .15s ease-in-out,background-color .15s ease-in-out,border-color .15s ease-in-out,box-shadow .15s ease-in-out;
}


.btn-purple {
  color: #7367f0!important;
  border-color: #7367f0;
  border: 1px solid #5a8dee;
  background-color: transparent;
}

.btn-purple:hover {
  background-color: #7367f0!important;
  color: #fff!important;
}


.btn-danger {
  width: 50%;
  padding: .6rem 1.8rem;
  font-size: 1.2rem;
  line-height: 1.7;
  border-radius: .267rem;
  border-color: #ff2829!important;
  background-color: #ff5b5c!important;
  color: #fff;
}

.btn-danger:hover {
  box-shadow: 0 4px 12px 0 rgba(255,91,92,.6)!important;
}


::-webkit-scrollbar {
    width: 0;  /* Remove scrollbar space */
    background: transparent;  /* Optional: just make scrollbar invisible */
}
/* Optional: show position indicator in red */
::-webkit-scrollbar-thumb {
    background: #FF0000;
}
</style>
