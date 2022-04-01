<template>
  <div id = "App">
      <header>
        <navbar />
      </header>    
     <agenda />

  </div>  
</template>

<script>
import Agenda from './components/EventCalendar.vue';
import Navbar from './components/NavBar.vue'; 

export default {
  name: 'App',
  components: {
    Agenda,
    Navbar
  }
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box; 
}
body{
  font-family: 'montserrat', sans-serif;

}
header{
  width: 100vw;
  background-color: #222;
  padding: 25px;
}
</style>