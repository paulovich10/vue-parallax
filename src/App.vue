<template>
  <div id="app">

    <Navegacion/>
    <Cabecera/>
    <Contenido/>
    <Aside/>
    <Footer/>
   
  </div>
</template>

<script>
import Cabecera from './components/Cabecera.vue';
import Navegacion from './components/Navegacion.vue';
import Contenido from './components/Contenido.vue';
import Aside from './components/Aside.vue';
import Footer from './components/Footer.vue';



export default {
  name: 'app',
  components: {
    Cabecera,
    Navegacion,
    Contenido,
    Aside,
    Footer
  },

  
}
</script>

<style>

@font-face {
font-family: 'Brandon Grotesque Black';
font-style: normal;
font-weight: normal;
src: local('Brandon Grotesque Black'), url('./fonts/Brandon_blk.woff') format('woff');
}

@font-face {
font-family: 'Brandon Grotesque Black';
font-style: normal;
font-weight: normal;
src: local('Brandon Grotesque Regular'), url('./fonts/Brandon_reg.woff') format('woff');
}

.flex { display: flex; }
.flex-column  { flex-direction: column; }
.flex-row     { flex-direction: row; }
.flex-wrap    { flex-wrap: wrap; }
.flex-nowrap  { flex-wrap: nowrap; }

.content-center  { align-content: center; }

.items-center   { align-items: center; }

.justify-start   { justify-content: flex-start; }
.justify-end     { justify-content: flex-end; }
.justify-center  { justify-content: center; }
.justify-between { justify-content: space-between; }

 * {
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}

a {
  text-decoration: none;
  font-family: 'Roboto', sans-serif;
}

.btn {

  cursor: pointer;
  color: white;
  display: inline-block;
  border-radius: 5px;
  transition: .4s;
  text-transform: uppercase;
  width: 200px;
  text-align: center;
  padding-top: 2%;
  padding-bottom: 2%;
  margin: 3%;
  font-size: .9rem;
}

.btn.blue:hover {

  background-color: transparent;
  color: #03d0b6;
}

.btn.blue {

  background-color:  #03d0b6;
  border: 2px solid #03d0b6;
  

}

.btn.transparente {
  background-color: transparent;
  border: 2px solid white;
  
}

.btn.transparente:hover {
  background-color: white;
  color: rgba(0,0,0,.8);
}

h1, h2, h3 {

  text-transform: uppercase;
}

p {

  font-family: 'Roboto', sans-serif;
}


</style>
