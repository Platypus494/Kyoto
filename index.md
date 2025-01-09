<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://db.onlinewebfonts.com/c/65f0d0406288c83cb989beec8f0f1b1b?family=Dyno+Bold" rel="stylesheet">
    <link href="https://fonts.cdnfonts.com/css/cicle" rel="stylesheet">
    <title>Kyoto - Capitale de la paix et de la tranquillité</title>
    <link rel="stylesheet" href="css.css">
    <style>
        body {
            background-color:#333333;
            color: white;
            margin: 0;
            padding: 0;
        }

        .main-content {
            padding: 20px;  
        }
        .section {
            background-color: #505050;
            border-radius: 10px;
            margin: 20px 0;
            padding: 20px;
            border: 2px solid #F7AF3E;
        }

        .section p {
            font-size: 1rem;
            line-height: 1.5;
        }

        .carrousel-container {
            width: 100%;
            overflow: hidden;
            position: relative;
            margin: 20px auto;
        }
        .carrousel {
            display: flex;
            animation: defilement 50s linear infinite;
        }
        .carrousel img {
            width: 20%;
            flex: 0 0 auto;
            border-radius: 10px;
            margin: 0 5px; 
        }

        @keyframes defilement {
            from {
                transform: translateX(0);
            }
            to {
                transform: translateX(-100%);
            }
        }

        .itinerary-container {
            display: flex;
            flex-direction: row;
            align-items: center;
            gap: 100px;
        }

        .itinerary-container img {
            width: 30%;
            border-radius: 10px;
        }

        .itinerary-container .section {
            width: 45%;
        }

        .bienseance-container {
            display: flex;
            flex-direction: row;
            align-items: center;
            gap: 100px;
        }

        .bienseance-container img {
            width: 40%;
            border-radius: 10px;
        }

        .bienseance-container .section {
            width: 45%;
        }

        .Titre-container {
            position: relative;
            width: 100%;
            height: 50vh;
            overflow: hidden;
        }

        .Titre-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .Titre-container::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(to bottom, rgba(0, 0, 0, 0) 50%, #333333 100%);
        }

        .Image-title {
            position: absolute;
            top: 125px;
            left: 20px;
            color: white;
            font-size: 2.5rem;
            width: 20%;
            background-color: #33333344;
        }

    </style>
</head>
<body>
    <header>
        <nav>
        <a href="acceuil.html" class="ban"> <img src="banniere.jpg" alt="MCN" class="banniere"> </a>
        <ul>
            <li class="eltparcours">Parcours
                <ul class="sous-elt">
                    <li>Les incontournables</li>
                    <li>Tendances</li>
                </ul>
            </li>
            <li class="elt">Monuments</li>
            <li class="elt">Quartiers
                <ul class="sous-elt">
                    <li>Restaurants</li>
                    <li>Hébergements</li>
                    <li>transports</li>
                </ul>
            </li>
            <li class="elt">Traditions
                <ul class="sous-elt">
                    <li>Festivals</li>
                    <li>folklore</li>
                </ul>
            </li>
            <li class="elt">loisirs et cultures
                <ul class="sous-elt">
                    <li>Pop culture</li>
                    <li>Sports</li>
                </ul>
            </li>
            <li class="elt">histoire
                <ul class="sous-elt">
                    <li><a href="frise.html">La fondation de kyoto </a></li>
                    <li>Histoire du Japon</li>
                </ul>
            </li>
        </ul>
    <a href="acceuil.html" ><img src="france-flat-rounded-flag-with-transparent-background-free-png.webp" alt="langue française" class="imglang"></a>
    <a href="acceuil_eng.html" ><img src="circle-flag-of-uk-free-png.webp" alt="langue anglaise" class="imglang"></a>
    </nav>
    <label for="ch" id="lab_petit"><img src="menu.png" class="logo2"></label>
    <input type="checkbox" id="ch"/>
    <ul class="menu_petit">
      <li class="style-hori"><a href="bienseance.html" class="element-menu">Bienséance</a></li>
      <li class="style-hori"><a href="frise.html" class="element-menu" >Frise</a></li> 
      <li><a href="acceuil.html" ><img src="france-flat-rounded-flag-with-transparent-background-free-png.webp" alt="langue française" class="imglangpetit"></a>
    <li><a href="page_acceuil (6).html" ><img src="circle-flag-of-uk-free-png.webp" alt="langue anglaise" class="imglangpetit"></a></li>
    </ul>
</header>
    <div class="Titre-container "> 
        <img src="https://media.discordapp.net/attachments/1285235591428177920/1318561707001516053/shutterstock_1017748132-1536x1025.jpg?ex=677e7548&is=677d23c8&hm=1d61b0e30cc1e731ccf49cb2d853c5d2291773517bb3ee3f2ec80ee6a1cbd4c0&=&format=webp&width=984&height=657" alt="Kyoto" class="Image-image"> 
        <div class="Image-title">Kyoto - La capitale de la paix et de la tranquillité</div> 
    </div>
    <div class="main-content">
        <h1>Les monuments</h1>

        <div class="carrousel-container">
            <div class="carrousel">
                <img src="https://images-ext-1.discordapp.net/external/5qLt7v-C41GU_3TFQQwoYIVLIXBpptydBajLNJaPdb0/https/destinationjapon.fr/wp-content/uploads/2019/09/kyoto_higashiyama_blog-800x359.jpg?format=webp" alt="">
                <img src="https://destinationjapon.fr/wp-content/uploads/2018/11/kyoto_kinkakuji.jpg" alt="Le pavillon d'or">
                <img src="https://destinationjapon.fr/wp-content/uploads/2019/09/kyoto_ginkakuji.jpg" alt="Le temple de Ryoan-ji">
                <img src="https://destinationjapon.fr/wp-content/uploads/2018/11/kyoto_tenryuji.jpg" alt="Le temple d'argent">
                <img src="https://images-ext-1.discordapp.net/external/EJMMXixykJttYLIxRmQNV0R9ntnnkHnz69_cXSMo14w/https/www.rivagesdumonde.fr/media/contentmanager/content/repeater_block_media_layout/images/550x400_Japon-Kyoto-cheminPhilosophie_oben901-AdobeStock_592621855-1.jpg?format=webp" alt="Le chemin de la philosophie">
                
                <img src="https://images-ext-1.discordapp.net/external/5qLt7v-C41GU_3TFQQwoYIVLIXBpptydBajLNJaPdb0/https/destinationjapon.fr/wp-content/uploads/2019/09/kyoto_higashiyama_blog-800x359.jpg?format=webp" alt="Coeur culturel de Kyoto">
                <img src="https://destinationjapon.fr/wp-content/uploads/2018/11/kyoto_kinkakuji.jpg" alt="Le pavillon d'or">
                <img src="https://destinationjapon.fr/wp-content/uploads/2019/09/kyoto_ginkakuji.jpg" alt="Le temple de Ryoan-ji">
                <img src="https://destinationjapon.fr/wp-content/uploads/2018/11/kyoto_tenryuji.jpg" alt="Le temple d'argent">
                <img src="https://images-ext-1.discordapp.net/external/EJMMXixykJttYLIxRmQNV0R9ntnnkHnz69_cXSMo14w/https/www.rivagesdumonde.fr/media/contentmanager/content/repeater_block_media_layout/images/550x400_Japon-Kyoto-cheminPhilosophie_oben901-AdobeStock_592621855-1.jpg?format=webp" alt="Le chemin de la philosophie">
            </div>
        <h1>Préparer son itinéraire</h1>
        <div class="itinerary-container">
            <img src="https://images-ext-1.discordapp.net/external/XYk4OSiL5kBXqeof0rb-k0RP31_v8fTQPrUftIgZQrM/https/upload.wikimedia.org/wikipedia/commons/thumb/2/2b/Kyotomap-fr.svg/735px-Kyotomap-fr.svg.png?format=webp&quality=lossless" alt="Carte Kyoto">
            <div class="section">
                <p>
                    La préparation d'un itinéraire est essentielle pour profiter au mieux de Kyoto. Avec ses nombreux monuments et lieux incontournables, une bonne planification permettra de gagner du temps et de ne rien rater !
                </p>
            </div>
        </div>
        <h1>Les règles de bienséance à Kyoto</h1>
        <div class="bienseance-container">
            <div class="section">
                <p>
                    Une fois que vous êtes arrivé à Kyoto, il se peut qu’on vous regarde de travers à cause de tatouages ou de 
                    comportements que vous faites qui peuvent perturber les habitants. Il faut donc, avant d’aller à Kyoto, 
                    connaître les règles de bienséance.
                    <br>
                    <a href="bienseance.html">savoir plus</a> 
                </p>
            </div>
            <img src="https://media.discordapp.net/attachments/1285235591428177920/1326258717389361296/pexels-photo-2918492.png?ex=677ec62e&is=677d74ae&hm=5768cb3268a0df247902b97627c42392794330682f6682b5c7ae6a9952c07eef&=&format=webp&quality=lossless&width=984&height=657" alt="Image des règles de bienséance">  
        </div>
    </div>
    <footer>
        <div class="footer-container">
            <div style="width:40%">
                <h3>Qui sommes-nous ?</h3>
                <p>
                    Nous sommes des étudiants en BUT 1 informatique qui ont créé ce site dans le cadre d'un projet qui implique la création d'un site internet qui propose la visite de monuments et de lieux à Kyoto, dans un objectif de médiation culturelle et numérique en partenariat avec l'UNESCO.
                </p>
            </div>
            <div >
                <h3>Contact</h3>
                <p><u>Thinojan Pulendran :</u> thinojan.pulendran@edu.univ-eiffel.fr</p>
                <p><u>Clara DRIEUX :</u> clara.drieux@edu.univ-eiffel.fr</p>
                <p><u>DUMUR Sébastien :</u> sebastien.dumur@edu.univ-eiffel.fr</p>
                <p><u>Valentin CARCHON :</u> valentin.carchon@edu.univ-eiffel.fr</p>
                <p><u>Matéo VENDEMAN--LARBI BEN HAMMOU :</u> vendemanlarbib@edu.univ-eiffel.fr</p>
            </div>
            <div>
                <h3>Informations légales</h3>
          <p>Université Gustave Eiffel, 5 boulevard Descartes
            Champs-sur-Marne <br>
            77454 Marne-la-Vallée cedex 2</p>
            </div>
        </div>
    </footer>
    
</body>
</html>
