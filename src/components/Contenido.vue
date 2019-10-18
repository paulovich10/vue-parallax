<template>

    <section class="container">

        <h2 class="centrar">Servicio a empresas</h2>
        <p class="centrar"><strong>Resolvemos el reto diario del almuerzo, tanto a nivel individual como colectivo,<br>
             satisfaciendo los gustos y restricciones de todas las personas.</strong> Apeteat es tiempo, es salud, es sabor y es compromiso.</p>

        <div class="container-grid">

            <div class="flex flex-row row">
                <div class="imagen">

                    <img src="../assets/servicio-01.svg" alt="ordenador">

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

                    <img src="../assets/servicio-03.svg" alt="chica">

                </div>
            </div>

             <div class="flex flex-row row">
                <div class="imagen">

                    <img src="../assets/servicio-02.svg" alt="ordenador">

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
    width: 80%;
    margin-left: 12%;
    margin-right: 12%;
    padding-bottom: 10%;

}

.container {

 background-color: rgb(250,250,250);

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
    width: 650px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: flex-start;
    padding-left: 10%;
    padding-right: 5%;

}

.imagen  {
  
     box-sizing: inherit;
     width: 650px;
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