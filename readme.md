
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Découvrir le Sénégal</title>
    <style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background-color: #f4f4f4;
}

.header-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  background-color: #004c3f;
  padding: 10px 20px;
}

.logo a {
  color: #ffffff;
  font-size: 24px;
  text-decoration: none;
}

.main-nav ul {
  display: flex;
  list-style: none;
  gap: 15px;
}

.main-nav ul li a {
  color: #ffffff;
  text-decoration: none;
  padding: 8px 12px;
}

.main-nav ul li a:hover {
  background-color: #007c60;
  border-radius: 5px;
}

.cta .btn {
  background-color: #ff8c00;
  color: #ffffff;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
  font-weight: bold;
}
.hero {
  position: relative;
  background-image: url('carrapide.jpg'); 
  background-size: cover;
  background-position: center;
  height: 400px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #ffffff;
  text-align: center;
  border-radius: 15px
}

.section {
  padding: 60px 20px;
  text-align: center;
}

.section h2 {
  margin-bottom: 20px;
  color: #004c3f;
}

.btn {
  display: inline-block;
  background-color: #ff8c00;
  color: #ffffff;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 5px;
}

.destination-list {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.destination-item {
  text-align: center;
  width: 200px;
}

.destination-item img {
  width: 100%;
  border-radius: 10px;
  margin-bottom: 10px;
}

form {
  max-width: 500px;
  margin: 0 auto;
}

form label {
  display: block;
  margin-top: 10px;
}

form input, form textarea {
  width: 100%;
  padding: 10px;
  margin-top: 5px;
  border-radius: 5px;
  border: 1px solid #ccc;
}

form button {
  margin-top: 20px;
}

footer {
  background-color: #004c3f;
  color: #ffffff;
  text-align: center;
  padding: 10px;
}

.image-gallery {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 20px;
  overflow-x: auto; 
}

.image-gallery img {
  max-height: 300px; 
  margin: 10px;
  transition: transform 0.5s ease-in-out; 
}

.image-gallery img:hover {
  transform: scale(1.1); 
  cursor: pointer;
}

.image-gallery::-webkit-scrollbar {
  height: 10px;
}

.image-gallery::-webkit-scrollbar-thumb {
  background-color: #DD0000; 
  border-radius: 5px;
}

.image-gallery::-webkit-scrollbar-track {
  background-color: #f4f4f4;
}

.justified-text {
  text-align: justify; 
  font-family: Arial, sans-serif;
  line-height: 1.6; 
}
    </style>
</head>
<body>

    <header>
        <div class="header-container">
            <div class="logo"><a href="#">Téraanga Sénégal</a></div>
            <nav class="main-nav">
              <div class="logo">
               
            </div>
            
                <ul>
                    <li><a href="#">Accueil</a></li>
                    <li><a href="#decouvrir">Découvrir le Sénégal</a></li>
                    <li><a href="#destinations">Destinations</a></li>
                    <li><a href="#Activités">Activités</a></li>
                    <li><a href="#gastronomie">Gastronomie</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
            <div class="cta"><a href="#" class="btn">Réserver une visite</a></div>
        </div>
        <section class="hero">
          <div class="hero-overlay"></div>
          <div class="hero-text">
          </div>
      </section>
      
    </header>
  
    <section id="home" class="section">
        <h1>Bienvenue au Sénégal</h1>
        <br>
        <p class="justified-text">Plongez dans l'univers captivant du Sénégal et laissez-vous émerveiller par ses trésors culturels, historiques et naturels. Ce pays d'Afrique de l'Ouest regorge de sites exceptionnels, témoins de son passé glorieux et de son patrimoine vivant. Des villes historiques comme Saint-Louis, avec son architecture coloniale et ses ruelles pittoresques, aux plages ensoleillées de la Petite-Côte, le Sénégal offre une diversité de paysages qui séduisent les voyageurs en quête d'authenticité et d'émotions.</p>
        <br>
        <p class="justified-text">Découvrez une culture profondément ancrée dans les traditions, où la musique, la danse, et l'artisanat occupent une place centrale. Chaque région du Sénégal dévoile des facettes uniques de son identité, que ce soit à travers les récits des griots, les cérémonies rituelles ou la cuisine locale savoureuse. Ce pays est également un paradis pour les amoureux de la nature, avec ses parcs nationaux abritant une faune et une flore remarquables, comme le Parc national de Niokolo-Koba ou le sanctuaire ornithologique du Djoudj.</p>
       <br>
        <p class="justified-text">Le Sénégal, c'est aussi un voyage dans l'histoire, avec des lieux emblématiques tels que l'île de Gorée, qui raconte les souffrances et la résilience des peuples africains. Que vous soyez à la recherche d'aventures palpitantes, d'une immersion culturelle ou simplement d'une escapade relaxante, le Sénégal saura vous charmer par sa diversité et l'hospitalité légendaire de ses habitants.</p>
       <br>
        <a href="#decouvrir" class="btn">En savoir plus</a>
    </section>

    <section id="decouvrir" class="section">
        <h2>Découvrir le Sénégal</h2>
        <br>
        <p class="justified-text">Le Sénégal est un pays d'une beauté exceptionnelle, offrant une diversité culturelle et naturelle qui ne cesse de fasciner. Ce pays de l'Afrique de l'Ouest est reconnu pour ses paysages spectaculaires, allant des plages paradisiaques bordées de cocotiers aux vastes savanes dorées, en passant par des forêts luxuriantes et des mangroves mystérieuses. Chaque recoin du Sénégal raconte une histoire unique, imprégnée de traditions ancestrales et de valeurs profondément enracinées dans le respect et la solidarité.</p>
        <br>
        <p class="justified-text">L'île de Gorée, classée au patrimoine mondial de l'UNESCO, est un lieu incontournable pour comprendre l'histoire poignante de l'esclavage. Ce site historique transporte ses visiteurs dans une époque marquée par la douleur, mais aussi par la résilience et la force des peuples africains. Par ailleurs, le Sénégal est un véritable carrefour ethnique où cohabitent harmonieusement les Wolofs, les Sérères, les Diolas et bien d'autres communautés, chacune apportant une richesse inestimable à la culture nationale.</p>
       <br>
        <p class="justified-text">Les traditions sénégalaises se manifestent dans la musique, la danse, les tenues colorées et les cérémonies rituelles qui rythment la vie quotidienne. De la chaleur humaine des habitants à l'art de la "teranga" (hospitalité légendaire sénégalaise), le pays offre une expérience inoubliable, tant pour les amateurs de découvertes culturelles que pour les passionnés d'aventure et de nature.</p>
    </section>

    <section id="destinations" class="section">
        <h2>Destinations populaires</h2>
        <div class="destination-list">
            <div class="destination-item">
                <img src="dkr.jpeg" alt="Dakar">
                <h3>Dakar</h3>
                <p class="justified-text">Découvrez la capitale animée du Sénégal, ses marchés colorés comme Sandaga, la Corniche avec vue sur l’océan et ses musées fascinants comme celui des Civilisations Noires.</p>
            </div>
            <br><br>
            <div class="destination-item">
                <img src="ndar.jpg" alt="Saint-Louis">
                <h3>Saint-Louis</h3>
                <p class="justified-text">Explorez cette ville historique classée au patrimoine mondial de l’UNESCO, avec ses maisons coloniales colorées et son ambiance artistique unique.</p>
            </div>
            <br><br>
            <div class="destination-item">
                <img src="casa.jpeg" alt="Casamance">
                <h3>Casamance</h3>
                <p class="justified-text">Admirez les paysages verdoyants de cette région, découvrez les traditions des Diolas et détendez-vous sur les plages de Cap Skirring.</p>
            </div>
            <br><br>
            <div class="destination-item">
                <img src="lacrose.jpeg" alt="Lac Rose">
                <h3>Lac Rose</h3>
                <p class="justified-text">Un lieu naturel emblématique, connu pour sa couleur rose unique due à sa forte concentration en sel.</p>
            </div>
        </div>
    </section>
    <section id="activites" class="section">
        <h2>Activités</h2>
        <p class="justified-text">Que vous aimiez l’aventure, la détente ou la culture, le Sénégal a des activités pour tout le monde. Voici quelques idées :
            Faire un safari dans le parc national de Niokolo-Koba.
            Explorer le delta du Saloum en pirogue.
            Participer à des festivals comme le festival de Jazz de Saint-Louis.
            Se relaxer sur les plages de Dakar ou de Cap Skirring.</p>
        <div class="image-gallery">
            <img src="IMG-20241230-WA0023.jpg" alt="Sénégal" width="300" height="300">
            <img src="IMG-20241230-WA0024.jpg" alt="Sénégal" width="300" height="300">
            <img src="IMG-20241230-WA0025.jpg" alt="Sénégal" width="300" height="300">
            <img src="IMG-20241230-WA0026.jpg" alt="Sénégal" width="300" height="300">
            <img src="IMG-20241230-WA0027.jpg" alt="Sénégal" width="300" height="300">
            <img src="IMG-20241230-WA0028.jpg" alt="Sénégal" width="300" height="300">
            <img src="IMG-20241230-WA0029.jpg" alt="Sénégal" width="300" height="300">
            <img src="IMG-20241230-WA0030.jpg" alt="Sénégal" width="300" height="300">
            <img src="IMG-20241230-WA0031.jpg" alt="Sénégal" width="300" height="300">
            <img src="IMG-20241230-WA0032.jpg" alt="Sénégal" width="300" height="300">
            <img src="IMG-20241230-WA0033.jpg" alt="Sénégal" width="300" height="300">
            <img src="IMG-20241230-WA0034.jpg" alt="Sénégal" width="300" height="300">
            <img src="IMG-20241230-WA0035.jpg" alt="Sénégal" width="300" height="300">
            <img src="IMG-20241230-WA0036.jpg" alt="Sénégal" width="300" height="300">
            <img src="IMG-20241230-WA0037.jpg" alt="Sénégal" width="300" height="300">
            <img src="IMG-20241230-WA0038.jpg" alt="Sénégal" width="300" height="300">
        </div>
    </section>


    <section id="gastronomie" class="section">
        <h2>Gastronomie</h2>
        <p>La cuisine sénégalaise est riche et savoureuse. Voici quelques plats à ne pas manquer :</p>
        <div class="image-gallery">
            <img src="thieb.png" alt="Sénégal" width="300" height="300">
            <img src="kanjasupu.png" alt="Sénégal" width="300" height="300">
            <img src="maafe.png" alt="Sénégal" width="300" height="300">
            <img src="yassa.png" alt="Sénégal" width="300" height="300">
            <img src="mbaxlusalum.png" alt="Sénégal" width="300" height="300">
            <img src="caldou.png" alt="Sénégal" width="300" height="300">
            <img src="domada.png" alt="Sénégal" width="300" height="300">
        </div>
    </section>

    <section id="contact" class="section">
        <h2>Contactez-nous</h2>
        <form action="#" method="post">
            <label for="name">Nom :</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email :</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message :</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit" class="btn">Envoyer</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Découvrir le Sénégal. Tous droits réservés.</p>
    </footer>

</body>
</html>
