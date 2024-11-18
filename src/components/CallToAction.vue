<template>
    <div class="container">
        <div class="text">
            <div class="promotion">Promotion</div>
            <div class="contentpromotion">Profitez de -10% sur votre première réservation !</div>
        </div>
        <div class="imgCtn">
            <div class="image">
               <div class="reserver">
                 Réserver
               </div>
            </div>
        </div>

        <div class="text">
            <div class="nouvellesrecettes">
                nouvelles recettes
            </div>
            <div class="contentnouvelles">
                Découvrez nos nouvelles<br></br> recettes délicieuses!
            </div>
        </div>

        <div class="imgCtn">
            <div class="image2">
                <div class="découvrir">
                     découvrir
                </div>
            </div>
        </div>
      
        <div class="search">
            <div class="carteNotreHistoire">
                    <div class="inconerectangle">
                       notre histoire
                    </div>
                <div class="textNotreHistoire">
                    <span class="breakMot"> BrunchBreak</span> vous accueille au coeur de<span class="breakMot"> Paris</span> pour partager notre
                    <span class="breakMot"> passion du brunch.</span><br><br>
                    Dirigée par <span class="breakMot"> Romain Petit</span>, notre équipe s'éfforce de créer des moments mémorables autour de plats délicieux préparés avec<span class="breakMot"> des ingrédients frais et de qualité.</span><br><br>
                    Venez découvrir notre<span class="breakMot"> ambiance conviviale</span>  et <span class="breakMot">nos créations culinaires!</span>
                </div>
            </div>
            <div class="search1">
                <div class="text">
                    <div class="événements">
                        Evénements à venir
                        <div class="contenetévénement">
                            venez profiter de nos concerts!
                        </div>
                    </div>
                </div>

                <div class="imgCtn">
                    <div class="imageconcert">
                    </div>
                </div>
            </div>

            <div class="texte1">
                <div class="content2">
                        Prochain concert le 8 octobre avec Rock fusion.<br></br>
                        Ne manquez pas cette soirée musicale!
                </div>
            </div>

            <div class="actualites">
                Actualités
                <div class="imgCtn">
                    <div class="actualitesImage">   
                    </div>       
                </div>
            </div>

            <div class="texte2">
                <div class="content3">
                    Découvrez notre dernier article de blog!
                    <div class="colored-box">
                        LIRE
                    </div>        
                </div>
            </div>

            <div class="colored-bar">
                <div class="logo">
                    <img class="logoImage" src="../assets/logo.png" alt="" srcset="">
                    <!-- Contenu du logo -->
                </div>
            </div>
        </div>

        <div class="brunch">
            Brunch Break
            <div class="star-rating">
                <span class="star">&#9733;</span>
                <span class="star">&#9733;</span>
                <span class="star">&#9733;</span>
                <span class="star">&#9733;</span>
                <span class="star">&#9733;</span>
            </div>
        </div>

        <div class="avis">
            Avis TripAdvisor
        </div>
        <div class="marinaAvis">
            <div class="carteMarina">
                <div class="logo">
                    <img class="logoImage" src="../assets/" alt="" srcset="">
                    <!-- Contenu du logo -->
                </div>
                <div class="iconeAndTitleCard">
                    <div class="circle">
                        <span class="letter">M</span>
                    </div>
                    <div class="textMarinaD">
                        MARINA D.  
                    </div>
                </div>
                <div class="textMarina">
                    Brunch Break, c'est tout simplement LE spot incontournable à Paris!
                </div>
            </div> 
        </div>
        <div class="newsletter">
            <div class="titleNewsletter">
                NEWSLETTER 
            </div>
            <div class="textNewsletter">
                Pour ne rien manquer,<br></br> inscrivez-vous à la NEWSLETTER
            </div>
        <div class="inputContainer">
            <span class="iconEnvelope">&#9993;
            </span> <!-- Code HTML pour une icône d'enveloppe -->
            <input type="text" class="inputNewsletter" placeholder="Votre adresse email ">
            </div>
        </div> 
        <div class="rejoindre">
            <div class="titleRejoigner-nous">
                Rejoigner-nous !
            </div>
            <div class="lien">
                <img class="brunchImg" src="../assets/Logo_declinaison.png" alt="">
            </div>
        </div>
    </div> 
</template> 
 
<style scoped>
.imgCtn {
    display: flex;
    justify-content: center;
    height : 35vh;
}

.image {
    background-image: url("../assets/table.jpg");
    background-size: cover;
    width: 90%;
    height: 300px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column; 
    margin-top: 19PX;
    border-radius: 10px;
}

.carteNotreHistoire {
    width: 100%;
    height: 400px;
    background-color: rgb(255, 255, 255);
    margin:100px;
    margin-left: 17px;
    margin-right: 10px;
    border-radius: 10px;
}
.inconerectangle {
  width: 400px; 
  height: 40px; 
  background-color: #952bd3; 
  border-radius: 50%; 
  display: flex; 
  justify-content: center;
  align-items: center; 
  color: #fdf4d1; 
  font-size: 20px; 
  font-family: Arial, sans-serif;
}
.notreHistoire {
    border-radius: 10px 10px 0 0;
    background-color: #8CCAE0;
    padding: 20px 12px;
    text-align: center;
    color: #fdf4d1;
    font-size: 20px;
}

.textNotreHistoire {
    text-align: center;
    padding: 40px 40px;
    line-height: 1.5; 
    
}
.breakMot {
    color: rgb(7, 7, 7);
   font-weight: bold;
}

.text {
    text-align: center;
    padding-top: 10px;
    
    
}

.contentpromotion {
    padding: 7px 90px;
    color: #6C9E41;    
    margin: 5px 0 0 0;
    font-family: 'Fredoka', sans-serif;
    font-size: 20px;
}

.image2  {
    background-image: url("../assets/tartine.jpg");
    background-size: cover;
    background-position: center;
    width: 90%;
    height: 300px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column; 
    margin-top: 8PX;
    border-radius: 10px;
}

.search {
    width : 57vh;
    background-position: center;
    background-color: #fdf4d1;
    padding: 0px 20px;
    margin : 50px 0px;
    margin-left: 17px;
    position: relative;
    display: flex;
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
    border-radius: 10px;
    
}
.promotion {
    padding: 10px 50px;
    width: 350px;
    color: #6C9E41;
    margin: 5px 0 0 0;
    font-family: 'Fredoka', sans-serif;
    font-weight: bold;
    font-size: 37px;
}
.découvrir {
    padding: 8px 15px;
    background-color: #6C9E41;
    color: #f9faf9;
    margin: 1px 0 0 0;
    font-weight: bold;
    font-size: 25px;
    border-radius: 10px;
}
.reserver {
    padding: 8px 15px;
    background-color: #6C9E41;
    color: #f9faf9;
    margin: 51px 0 0 0;
    font-weight: bold;
    font-size: 25px;
    border-radius: 10px;
}
.nouvellesrecettes{
    padding: 40px 10px;
    width: 440px;
    height: 90px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column; 
    color: #6C9E41;
    margin: 95px 0 0 0;
    font-family: 'Fredoka', sans-serif;
    font-weight: bold;
    font-size: 37px;
}
.contentnouvelles{
    width: 440px;
    height: 50px;
    padding: -70px 90px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column; 
    color: #6C9E41;  
    margin: -55px 0 0 0;
    font-family: 'Fredoka', sans-serif;
    font-size: 20px;
}
.événements {
    width: 400px;
    padding-top: 90px;
    color: #6C9E41;
    margin-left: 30px;
    margin: 5px 0 0 0;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column; 
    margin-right: 10px;
    margin-left: 10px;
    margin-top: -160px;
    font-family: 'Fredoka', sans-serif;
    font-weight: bold;
    font-size: 30px;
}
.contenetévénement {
    width: 200px;
    padding: 02px 60px;
    color: #6C9E41;
    margin-left: -30px;
    font-family: 'Rag 123', sans-serif;     
    margin: 5px 0 0 0;
    font-size: 15px;
}
.imageconcert  {
    height : 40vh;
    width: 400px;
    margin-left: -30px;
    margin-right: -20px;
    background-image: url("../assets/concert.jpg");
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column; 
    border-radius: 10px;
}
.texte1 {
    width: 400px;
    padding: 50px;
    color: #0a0808;
    font-family: 'Rag 123', sans-serif;     
    margin: 5px 0 0 0;
    margin-left: 10px;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column; 
    font-family: 'Arial', sans-serif;
    font-size: 15px;
}
.actualites {
    padding: 40px 28px;
    width: 300px;
    color: #6C9E41;
    margin: -40px 0 0 0;
    margin-left: -10px;
    font-family: 'Fredoka', sans-serif;
    font-weight: bold;
    font-size: 30px;
}
.actualitesImage {
    width: 190px;
    height: 20px;
    padding: 160px 10px;
    background-image: url("../assets/table2.jpg");
    background-size: cover;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column; 
    margin-top: 40PX;
    margin-left: -190px;
    border-radius: 10px;
    
}
.texte2 {
  
    width: 130px;
    color: #070707;   
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column; 
    margin: -170px 0 0 0;
    margin-left: 250px;
    font-family: 'Arial', sans-serif;
    font-size: 15px;
}
.colored-box {
  width: 100px; /* Largeur du carré */
  height: 30px;
  margin: 40px 0 0 0;
  margin-left: -10px;
  background-color: #8CCAE0; 
  color: #fdf4d1; 
  display: flex;
  justify-content: center; 
  align-items: center;
  font-size: 20px; /* Taille du texte */
  font-family: Arial, sans-serif; 
  border-radius: 10px; 
}
.colored-bar {
  width: 280px; 
  height: 5px; 
  margin: 230px 0 0 0;
  margin-left: 50px;
  background-color: #DE7B14; 
}
.logo {
  
    height : 90px;
    margin: 80px 0 0 0;
    margin-left: -290px;
    position: relative;
    display: flex;
    justify-content: center;
} 

.logoImage{
  height: 70%;
  width: 70px;
}

.brunch {
    width: 230px;
    color: #070707;   
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column; 
    margin: 80px 0 0 0;
    margin-left: 160px;
    font-family: 'Arial', sans-serif;
    font-size: 25px;
}

.star-rating {
  display: flex;
  justify-content: center; 
}

.star {
  font-size: 20px;
  color: #C38837; 
  margin-left: 5px;
  margin-right: 5px; 
}

.star:hover,
.star:hover ~ .star {
  color: orange; 
}
.avis {
    width: 230px;
    color: #070707;   
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column; 
    margin: 10px 0 0 0;
    margin-left: 160px;
    font-family: 'Arial', sans-serif;
    font-size: 20px;
}
.marinaAvis {
    width : 57vh;
    background-position: center;
    background-color: #fdf4d1;
    margin : 70px 0px;
    margin-left: 35px;
    position: relative;
    display: flex;
    align-items: center;
    justify-content: flex-start;
    justify-content: space-between;
    border-radius: 10px; 
   
}
.carteMarina {
    width: -30px; 
    height: 200px; 
    background-color: rgb(255, 255, 255);
    margin-right: 10px;
    margin-top: 10px;
    margin-bottom: 20px;
    border-radius: 20px;
   
}
.circle {
  width: 40px; 
  height: 40px; 
  background-color: #6C9E41; 
  border-radius: 50%; 
  display: flex; 
  justify-content: center;
  align-items: center; 
  color: #fdf4d1; 
  margin-left: 10px;
  font-size: 20px; 
  font-family: Arial, sans-serif;
}
.logoAndTitleCard {
    display: flex;
    align-items: center;
    padding: 0px 
}
.textMarinaD {
    margin-left: -90px;
    text-align: center; 
   
}
.textMarina {
    padding: 40px
   
}
.newsletter {
    height: 190px;
    width: 450px;
    text-align: center;
    background-color: #DE7B14;
}
.titleNewsletter {
    height: 70px;
    width: 450px;
    margin-top: -70px;
    color: white;
    display: flex; 
    justify-content: center;
    align-items: center; 
    text-align: center;
    font-size: 25px;
}
.textNewsletter {
    height: 60px;
    width: 420px;
    margin-left: 20px;
    color : white;
    text-align: center;
}
.inputNewsletter {
    width: 70%; 
    padding: 10px; 
    margin-left: 20px;
    border-radius: 10px; 
    border: none;
    font-size: 16px; 
    font-family: Arial, sans-serif; 
    text-align: center;
    color: #333;
    cursor: pointer; 
    box-shadow: 0px 2px 4px rgba(0, 0, 0, 0.2); 
}
.iconEnvelope {
    position: relative;
    right: -295px;
    margin-left: -30px;
    transform: translateY(-50%);
    background-color: #DE7B14; 
    padding: 8px;
    border-radius: 0%;
    font-size: 2px;
    font-weight: bold;
}

.rejoindre {
    height: 180px;
    width: 450px;
    text-align: center;
    background-color: #8CCAE0;
}
.titleRejoigner-nous {
    height: 140px;
    width: 220px;
    margin-top: 30px;
    margin-left: 110px;
    color: white;
    display: flex; 
    justify-content: center;
    align-items: center; 
    font-size: 25px;
    
    
}
.lien {
    
    width: 450px;
    background-color: #C38837;;
    margin-top: 70PX; 
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.brunchImg {
    height:45px;
    width: 110px;
    padding: 60px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  
}

</style>






