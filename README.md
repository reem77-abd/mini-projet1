# mini-projet1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Mini Project</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background:black;
            color: beige;
        }
 .header-container {
    display: flex;
    align-items: center;
    justify-content: space-between; /* espace entre logo, texte et photo */
    gap: 1rem;
}

.header-container img {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    border: 3px solid white;
}

       
.section{
        max-width: 800px;
        margin: 2rem  auto;
        padding: 1.5rem;
        background: black;
        border-radius: 8px;
        box-shadow: 0px 2px 10px black;
       }
       h2{
        color: red;
       }
     .footer{
          text-align: center;
          padding: 1rem;
          background: black;
          color: antiquewhite;
          margin-top: 3rem;
         }

 select {
    padding: 10px;
    border-radius: 8px;
    border: 2px solid red;
    background: #121212;
    color: beige;
    font-size: 1rem;
   }
option {
    padding: 5px;
}

</style>
</head>
<body>
    <header>
  <div class="header-container">
     <img src="https://www.w3schools.com/howto/img_avatar2.png" alt="Mon logo">
      <h1>Bent AL MOUDIR</h1>
       <p>Développeur Web Débutant</p>

 </div>
    </header>
    <h3>Contact</h3>
    <p>Email : : <a href="mailto:rfghjk@exemple.com" style="color:white;">rfghjk@exemple.com</a>rmourafi@gmail.com</p>
    <p>Adresse : Casablanca, Maroc</p>
    <p>LinkedIn : <a href="https://www.linkedin.com/in/rachid-mourafi-1b0a4b1b2/" target="_blank" style="color:white;">Rim Mourafi</a></p>
   <p>Téléphone : <a href="tel:+212600000000">0600000000</a></p>
    <section>
        <h2>a propos de moi </h2>
        <p> je suis passionné par le développement web etc et c'est mon premier projet <p>
        <p>J'ai commencé à apprendre le développement web il y a quelques mois et j'adore créer des sites web interactifs.</p>
    </section>
    <section>
        <h2>Mes compétences</h2>
        <ul>
            <li>HTML & css </li>
            <li>>Design simple et responsive</li>
            <li>Esprit d’équipe</li>
        </ul>
    </section>
    <section>
      
  </section>
<section>
  <h2>Langages de programmation</h2>
  <label for="langages">Choisissez votre langage préféré :</label>
  <select id="langages" name="langages">
      <option value="html">HTML</option>
      <option value="css">CSS</option>
      <option value="js">JavaScript</option>
      <option value="python">Python</option>
      <option value="java">Java</option>
  </select>
  <p id="choix"></p>
</section>

<script>
  const select = document.getElementById("langages");
  const choix = document.getElementById("choix");

  select.addEventListener("change", () => {
    choix.textContent = "Vous avez choisi : " + select.value;
  });
</script>
  


  <footer>
    © 2025 - Mon Portfolio
  </footer>
    
</body>
</html>
