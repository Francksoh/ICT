<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Document</title>
</head>

<body>
    <style>
        /* Style par défaut (ordinateur) */
        
        body {
            font-size: 16px;
        }
        /* Tablettes */
        
        @media (max-width: 768px) {
            body {
                font-size: 14px;
            }
        }
        /* Téléphones */
        
        @media (max-width: 480px) {
            body {
                font-size: 12px;
            }
        }
    </style>


    <style>
        body {
            background-color: white;
            text-align: center;
        }
        
        img {
            width: 300px;
            height: 200px;
            border-radius: 0px;
        }
        
        nav {
            display: flex;
            justify-content: space-evenly;
            background-color: blue;
            border-radius: 6px;
        }
        
        nav p {
            background-color: bisque;
            padding: 6px;
            border-radius: 5px;
            font-weight: bold;
            color: cadetblue;
        }
        
        footer {
            position: fixed;
            bottom: 0;
            font-size: 40px;
            font-weight: 500;
            font-style: italic;
            width: 100%;
            background-color: aqua;
        }
        
        .section0 {
            display: flex;
        }
        
        .section1 {
            width: 20%;
            background-color: rgb(35, 179, 179);
            border: 2px solid black;
            margin: 4px;
        }
        
        .section2 {
            display: flex;
            justify-content: space-evenly;
            width: 80%;
        }
        
        .section2 div {
            color: red;
            background-color: beige;
            width: 70%;
            border: 2px solid black;
        }
        
        .section3 {
            background-color: rgb(52, 163, 163);
            width: 100%;
            min-height: 200px;
        }
    </style>
    <nav>
        <p>chap 1</p>
        <p>chap 2</p>
        <p> chap 3</p>
        <p> chap 4</p>
    </nav>
    <section class="section0">
        <section class="section1">
            <div>

            </div>



        </section>
        <section>
            <section class="section2">
                <div>
                    <p>Nom: NJONTU SOH</p>
                    <p>Prenom: TEDDY FRANCK</p>
                    <p>Matricule:24H2102</p>

                </div>
                <div>
                    <img src="IMG_9071.JPG" alt=/*<img style="max-width: 100%; height: auto">
                </div>

            </section>
            <section class="section3">
                <p>description:Je suis etudiant a ICT-4D et J'aimerais etre un ingenieur en cybersecurite</p>

            </section>

        </section>
    </section>


    <footer>
        copyright 2025 ICT-108
    </footer>

</body>

</html>
