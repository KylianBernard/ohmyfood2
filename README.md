<!DOCTYPE html>
<html lang="fr">
   <head>
      <meta charset="utf-8" />
      <meta name="viewport" content="initial-scale=1, maximum-scale=1, minimum-scale=1, width=320, height=device-height, target-densitydpi=medium-dpi" />
      <link rel="stylesheet" href="style.css" />

      <script src="https://kit.fontawesome.com/0cb7c5b8f4.js" crossorigin="anonymous"></script>
      <link rel="preconnect" href="https://fonts.googleapis.com">
      <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
      <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Shrikhand&display=swap" rel="stylesheet">
      <title> Ohmyfood </title>
   </head>

                  <!--  Header -->
   <body>
      <div class="spinner_chargement fin">
         <span class="spinner"></span>
       </div>
         <header>
               <h1>Ohmyfood</h1>
         </header>
            <!-- div localisation -->

            <div class="localisation">
               <i class="fas fa-map-marker-alt"></i>
               <p>Paris, Belleville</p>
       </div>

         <div class="a_propos">
            <h2> Réservez le menu qui vous convient </h2>
               <p> Découvrez des restaurants d'exception, sélectionnés par nos soins </p>
               <a href="restaurant" class="btn">Explorer nos restaurants</a>
            </div>
                  <!-- Section fonction -->
   <main>
      <section class="fonction">
         <h2>Fonctionnement</h2>
         <ul class="liste_fonctionnement">
            <li class="choix">
               <div class="choisir">1</div>
               <div><i class="fas fa-mobile-alt "></i></div>
               <span class="choix-menu choix-menu2">Choissisez un restaurant</span>
            </li>
            <li class="choix">
               <div class="composer">2</div>
               <div><i class="fas fa-list-ul "></i></div>
               <span class="choix-menu">Composez votre menu</span>
            </li>
            <li class="choix">
               <div class="deguster">3</div>
               <div><i class="fas fa-store "></i></div>
               <span class="choix-menu">Dégustez au restaurant</span>
            </li>
         </ul>
      </section>
      
                     <!-- Section Restaurants -->
                     <section class="restaurant" id="restaurant"> 
                        <div class="titre_restaurant">
                              <h3>Restaurants</h3>
                           </div>
                        <div class="all_restaurant">
                          

                           <div class="Nouveau_palette">
                              <div class="boutton_nouveau">
                                 <span class="New"> Nouveau </span>
                           </div>
                        </div>
                           
                     <article>
                        <a class="lien_page" href="./la_palette_dugout.html">
                           <img src="./images/restaurants/jay-wennington-N_Y88TWmGwA-unsplash.jpg" alt="Restaurant la palette du gout">
                        </a>
                        <div class="description">
                        <div class="caption">
                                 <h4>La palette du goût</h4>
                                    <p>Ménilmontant</p>
                        </div>
                        <div class="aime">
                           <span><i class="fas fa-heart coeur"></i></span>
                       </div>
                     </div>
                     </article>
                        
                     <div class="Nouveau_note">
                        <div class="boutton_nouveau">
                           <span class="New"> Nouveau </span>
                     </div>
                  </div>
                     <article>
                        <a class="lien_page" href="./la_note_enchentee.html">
                        <img src="./images/restaurants/stil-u2Lp8tXIcjw-unsplash.jpg" alt="Restaurant la note enchantee">
                      </a>
                      <div class="description">
                        <div class="caption">
                                 <h4>La note enchantée</h4>
                              
                                    <p>Charonne</p>  
                        </div>
                                   <div class="aime">
                                       <span><i class="fas fa-heart coeur"></i></span>
                                   </div>
                     </div>
                     </article>
                  </div>
                     <article>
                        <a class="lien_page" href="./a_la_francaise.html">
                        <img src="./images/restaurants/toa-heftiba-DQKerTsQwi0-unsplash.jpg" alt="Restaurant a la francaise">
                     </a>
                     <div class="description">
                        <div class="caption">
                                 <h4>A la française</h4>
                               
                                       <p>Cité Rouge</p>
                        </div>  
                        <div class="aime">
                           <span><i class="fas fa-heart coeur"></i></span>
                       </div>
                     </div>
                     </article>
                  </div>
                     <article>
                        <a class="lien_page" href="./le_delice_des_sens.html">
                        <img src="./images/restaurants/louis-hansel-shotsoflouis-qNBGVyOCY8Q-unsplash.jpg" alt="Restaurant Le délice des sens">
                     </a>
                     <div class="description">
                        <div class="caption">
                                 <h4>Le délice des sens</h4>
                                     <p>Folie-Méricourt</p>
                        </div>
                        <div class="aime">
                           <span><i class="fas fa-heart coeur"></i></span>
                       </div>
                      </div>
                     </article>
               </div>
         </section>
      </main>



                  <!--Footer-->
      <footer>
         <h3>ohmyfood</h3>
         <ul>
            <li>
               <div class="icone"> 
                  <i class="fas fa-utensils"></i>
            </div>
               <a href="#">Proposer un restaurant</a>
            </li>
            <li>
               <div class="icone">
                  <i class="fas fa-hands-helping"></i> 
               </div>
                     <a href="#">Devenir partenaire</a>
            </li>
            <li><a href="#">Mentions légales</a></li>
            <li><a href="">Contact</a></li>
         </ul>
      </footer>
      </body>
</html>