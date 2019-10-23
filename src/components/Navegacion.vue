<template>

    <div class="flex flex-row blanco">
        <div class="item-uno">
            <nav class="flex flex-row items-center">

                <a href="#">Quienes somos</a>
                <a href="#">Cómo funciona</a>
                <a href="#">Servicios a empresas</a>
                <a href="#">Compromiso</a>

            </nav>

        </div>

        <div class="item-dos flex justify-center">

            <img id="logo" src="../assets/logo.svg" alt="logo apeteat">

        </div>

        <div class="item-uno flex justify-center items-center">

            <a class="btn blue">Nuevo pedido</a>
            <div class="flex flex-row items-center">
               <i class="fas fa-shopping-bag"></i>
               <p>0,00 €</p>
            </div>
        </div>

    </div>
    
</template>

<script>
export default {
    
}
</script>

<style scoped>

.blanco {
   background-color: white;
   position: fixed;
   width: 100%;
   z-index: 999;

}

nav {
  width: 100%;
  height: 75px;
 
}

nav a {
    padding: 1.5%;
    font-family: 'Roboto', sans-serif;
    color: rgb(137,137,137);
    transition: all .5s;

}

nav a:hover {

    color: #03d0b6;
}
.btn {
    width: 120px;
    font-size: .8rem;
    text-transform: capitalize;
}

i {
    font-size: 2rem;
    padding-left: 20px;
    padding-right: 20px;
}

.item-uno {
    flex-grow: 1;
}

.item-dos {
    flex-grow: 2;
    visibility: hidden;
}

#logo {
    width: 100px;
}

.item-uno a{
    padding: 3%;
}

</style>