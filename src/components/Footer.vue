<template>

    <footer class="flex flex-column" id="footer">

        <div class="container flex flex-row justify-between">

            <div class="flex flew-row expand">

                    <div class="extra-padding">

                        <ul>
                            <li>Apeteat</li>
                            <li>Servicio a empresas</li>
                            <li>Compromiso</li>
                            <li>Blog</li>
                        </ul>


                    </div>
                    <div class="extra-padding">

                        <ul>
                            <li>Ayuda</li>
                            <li>Contacto</li>
                            <li>FAQs</li>
                            <li>Legal</li>
                        </ul>



                    </div>
                    <div class="extra-padding">

                        <ul class="social">
                            <li>Seamos amigos</li>
                            <li><i class="fab fa-facebook-square"></i>Facebook</li>
                            <li><i class="fab fa-instagram"></i>Instagram</li>
                            <li><i class="fab fa-twitter"></i>Twitter</li>
                            <li><i class="fab fa-linkedin"></i>Linkedin</li>
                        </ul>


                    </div>

            </div>

            <div>

                <img src="../assets/ico-enisa.svg" alt="">

            </div>

        </div>

        <hr>

        <div class="container dos flex flex-row justify-between content-center">
            <div class="modoPago">
                <img src="../assets/ico-visa.svg" alt="">
                <img src="../assets/ico-mastercard.svg" alt="">
                <img src="../assets/ico-sodexo.svg" alt="">
                <img src="../assets/ico-ticket-restaurant.svg" alt="">
                <img src="../assets/ico-cheque-dejeuner-1.svg" alt="">

            </div>
            <div class="flex items-center">

                <small><p>Copyright © 2019 apeteat | Todos los derechos regístrados.</p></small>

            </div>
        </div>
     
    </footer>
        
</template>

<script>
export default {
    
}
</script>

<style scoped>

footer {

    padding-top: 100px;
    background-color: white;
}

ul {

    list-style: none;
    font-family: 'Roboto', sans-serif;
}

ul li{

    padding-bottom: 15px;
    font-size: .9em;
    color: #838286;
   
}

ul>li:first-child {

    padding-bottom: 20px;
    font-weight: 700;
}

.container {
   width: 100%;
   max-width: 1300px;
   margin-left: auto;
   margin-right: auto;
   margin-bottom: 5%;
}

.extra-padding {

    width: 20%;
    
}
 .expand {

     width: 80%;
 }

i {
    padding-right: 3%;
    font-size: 1.2rem;
}


 hr {

   width: 70%;
   display: block;
   margin: auto;
   height: 0;
   border-top: 1px solid #eee;
   border-bottom: none;

}

.modoPago img {

    padding-left: 1%;
    padding-right: 1%;
    width: 120px;
}

.modoPago img:nth-child(2) {

    width: 80px;
}

.container.dos {
    margin-top: 3%;
}

.container.dos p {

    font-family: 'Roboto', sans-serif;
    color:#838286;
}




</style>