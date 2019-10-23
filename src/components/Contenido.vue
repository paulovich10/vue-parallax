<template>

    <section class="container flex flex-column items-center">

        <h2 class="centrar">Servicio a empresas</h2>
        <p class="centrar"><strong>Resolvemos el reto diario del almuerzo, tanto a nivel individual como colectivo,<br>
             satisfaciendo los gustos y restricciones de todas las personas.</strong> Apeteat es tiempo, es salud, es sabor y es compromiso.</p>

        <div class="container-grid">

            <div class="flex flex-row row">
                <div class="imagen">

                    <img src="../assets/delivery.jpg" alt="ordenador">

                </div>

                <div class="texto">

                    <h3>cantina virtual</h3>
                    <p>Servicios de cantina virtual para satisfacer la demanda individual diaria de almuerzos de toda la empresa.</p>
                    <a class="btn bordeAzul">saber mas</a>
                </div>
            </div>

             <div class="flex flex-row row">
                <div class="texto">
                    <h3>Apeteat corner</h3>
                    <p>Disfruta de toda la experiencia apeteat dentro de tu empresa.</p>

                    <a class="btn bordeAzul" href="#">saber mas</a>

                </div>

                <div class="imagen">

                    <img src="../assets/office.jpg" alt="chica">

                </div>
            </div>

             <div class="flex flex-row row">
                <div class="imagen">

                    <img src="../assets/break.jpg" alt="ordenador">

                </div>

                <div class="texto">

                    <h3>Catering "Finger food"</h3>
                    <p>La mejor solución para disfrutar sin complicaiones de una comida sana y rica mientras estas reunido.</p>
                    <a class="btn bordeAzul">saber mas</a>

                </div>
            </div>
        </div>

        
    </section>
    
</template>

<script>
export default {
    
}
</script>

<style scoped>

h2{

    font-family:'Brandon Grotesque Black', sans-serif;
}

h2 {

    font-size: 1.8rem;
    padding-bottom: 5%;
}

h3 {
    font-family:'Brandon Grotesque Regular', sans-serif;
    font-size: 1.5rem;
    color: #3c475b;
    padding-bottom: 7%;
}

.container-grid {
    padding-top: 10%;
    padding-bottom: 10%;
}

.container-grid > div {

    margin-top: 10%;
}

.container {

 background-color: white;
 

}

section {

    padding-top: 150px;
}

p {

    font-size: 1rem;
    font-family: 'Roboto', sans-serif;
    line-height: 1.4;
    color: #838286;

}

.texto {

    background-color: white;
    width: 50%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    padding: 3%;
}

.imagen  {
  
     box-sizing: inherit;
}

.centrar {

    text-align: center;
}

.btn {

    border: 2px solid #03d0b6;
    color: #03d0b6;
    margin-top: 5%;
    padding: 3% 8%;
    font-size: .8rem;

}

.btn:hover {

    color: white;
    background-color: #03d0b6;
}

</style>