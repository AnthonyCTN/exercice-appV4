# exercice-appV4


    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
</head>
<body>
    <nav>
        <ul>
            <li><a href="application.html"><span class="material-icons">home</span>Accueil</a></li>
        </ul>
    </nav>
    
    <h1>Tous les Exercices</h1>

    <div class="container">
        <a class="box" href="#">
            <span class="material-icons">group</span>
            <h3>Personnes Agées</h3>
        </a>

        <a class="box" href="exercice2.html">
            <span class="material-icons">group</span>
            <h3>Personne Agées v2</h3>
        </a>

        <a class="box" href="exercice-3.html">
            <span class="material-icons">calculate</span>
            <h3>Exercice 3: Calculatrice + - / *</h3>
        </a>

        <a class="box" href="loto.html">
            <span class="material-icons">casino</span>
            <h3>Exercice 4: Loto</h3>
        </a>

        <a class="box" href="shifoumie.html">
            <span class="material-icons">gesture</span>
            <h3>Pierre - Feuille - Ciseau</h3>
        </a>

        <a class="box" href="dessin.html">
            <span class="material-icons">brush</span>
            <h3>Dessin</h3>
        </a>

        <a class="box" href="jeu-trouve.html">
            <span class="material-icons">games</span>
            <h3>Jeu avec l'Ordinateur</h3>
        </a>

        <a class="box" href="fonctionmath.html">
            <span class="material-icons">functions</span>
            <h3>Fonction Math</h3>
        </a>

        <a class="box" href="nombrepremier.html">
            <span class="material-icons">grade</span>
            <h3>Nombre Premier</h3>
        </a>

        <a class="box" href="verbe.html">
            <span class="material-icons">menu_book</span>
            <h3>Verbe</h3>
        </a>
    </div>
</body>
</html>

<style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #292f3f;
            color: #fff;
            margin: 0;
            padding: 0;
        }

        nav {
            background: linear-gradient(to right, #292f3f, #007bff);
            padding: 20px 0;
            position: sticky;
            top: 0;
            z-index: 10;
        }

        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: space-around;
            max-width: 960px;
            margin: 0 auto;
        }

        nav li a {
            color: #fff;
            text-decoration: none;
            font-size: 18px;
            transition: color 0.3s ease;
        }

        nav li a:hover {
            color: #292f3f;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;  /* change this from space-between to space-around */
            align-items: center;
            max-width: 960px;
            margin: 50px auto;
            padding: 0 20px;
            gap: 20px;  /* add this line to create gaps between boxes */
        }

        h1 {
            text-align: center;
            font-size: 36px;
            margin-top: 40px;
            text-decoration: underline;
        }

        .box {
            flex-basis: calc(30% - 40px);
            background-color: #fff;
            border-radius: 10px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 200px;
            margin-bottom: 30px;
            transition: box-shadow 0.3s ease, transform 0.3s ease;
            cursor: pointer;
            box-shadow: 0px 5px 15px rgba(0,0,0,0.1);
            text-align: center;
            color: #333;
            text-decoration: none;
            padding: 20px;
        }

        .box:hover {
            box-shadow: 0px 10px 20px rgba(0,0,0,0.2);
            transform: translateY(-10px);
        }

        @media (max-width: 768px) {
            .box {
                flex-basis: 100%;
                margin-bottom: 20px;
            }
        }

        .material-icons {
            font-size: 48px;
            margin-bottom: 10px;
        }

        h3 {
            font-size: 18px;
            color: #333;
            margin-top: 20px;
        }
    </style>
