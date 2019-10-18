<template>

<aside>
  <div class="flex items-center">

    <parallax :fixed="true">

      <img src="../assets/hero-actions.jpg" alt="">

    </parallax>

  <div class="aside-caption">
      
      <p>No esperes más, empieza a disfrutar a diario de una comida sana. <span>¿Pedimos?</span></p>

   <div class="flex justify-center">

     <a class="btn blue">Ver carta</a>
     <a class="btn transparente">Servicio a empresas</a>

   </div>

  </div>
</div>

</aside>

    
</template>

<script>
import Parallax from "vue-parallaxy";

export default {
  components: {
    Parallax
  }
};
</script>


<style scoped>

aside {
  position: relative;
  height: 70vh;
 
}

.aside-caption {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  max-width: 980px;
  z-index: 10;

} 

p {
    font-size: 2.5rem;
    color: white;
    text-align: center;
    font-family: 'Roboto', sans-serif;
}

p span {
    font-weight: 700;
}

aside img {
  width: 100%;
  filter:brightness(0.5);
  display: block;
}

</style>