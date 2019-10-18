<template>

<div class="hero flex items-center">

      <img src="../assets/hero-home.jpg" alt="">

      <div class="hero-caption">
          <h1>Disfruta de un almuerzo rico, sano y comprometido en la oficina</h1>
          <p>Comer bien a diario es posible. <span>¿Pedimos?</span></p>

          <div class="flex justify-center">

              <a class="btn blue">A comer</a>
              <a class="btn transparente">Servicio a empresas</a>

          </div>

      </div>

</div>
  
</template>

<script>

</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>



h1 {
  font-family:'Brandon Grotesque Black', sans-serif;
  color: white;
  font-size: 2.3rem;
  text-align: center;
}

.hero {
position: relative;
}

.hero-caption {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  max-width: 980px;
} 

.hero-caption span {

  font-weight: 700;
}

.hero p{

  color:white;
  font-family: 'Robooto', sans-serif;
  font-size: 1.1rem;
  text-align: center;
  padding-top: 3%;
  letter-spacing: 1px;
}

.hero img {
  width: 100%;
  filter:brightness(0.5);
  z-index: 0;
}


</style>
