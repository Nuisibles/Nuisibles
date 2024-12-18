<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>France Nettoyage Pro</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 1rem;
        }
        nav a:hover {
            background-color: #575757;
        }
        .hero {
            background: url('https://images.unsplash.com/photo-1617450368703-3c4d114ecf3b?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=1200') no-repeat center center/cover;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .hero h1 {
            font-size: 3rem;
        }
        .services {
            padding: 2rem;
            text-align: center;
        }
        .services h2 {
            margin-bottom: 1rem;
        }
        .service-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1rem;
            margin-top: 1rem;
        }
        .service {
            padding: 1rem;
            border: 1px solid #ddd;
            border-radius: 5px;
            background-color: #f9f9f9;
        }
        .service img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .contact {
            background-color: #f4f4f4;
            padding: 2rem;
            text-align: center;
        }
        .planning {
            padding: 2rem;
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>France Nettoyage Pro</h1>
        <p>Votre partenaire pour une maison et un environnement sans nuisibles</p>
    </header>

    <nav>
        <a href="#services">Nos Services</a>
        <a href="#about">À Propos</a>
        <a href="#contact">Contact</a>
        <a href="#planning">Planning</a>
    </nav>

    <section class="hero">
        <h1>Éradiquez les nuisibles, protégez votre maison</h1>
    </section>

    <section id="services" class="services">
        <h2>Nos Services</h2>
        <div class="service-list">
            <div class="service">
                <img src="https://cdn.pixabay.com/photo/2022/09/17/09/10/rat-7383028_1280.jpg" alt="Élimination des rats">
                <h3>Élimination des rats</h3>
                <p>Des solutions rapides et efficaces pour éradiquer les rats de votre maison ou bureau.</p>
            </div>
            <div class="service">
                <img src="https://images.unsplash.com/photo-1609140256331-3bcdf5e29a6a?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=400" alt="Traitement contre les insectes">
                <h3>Traitement contre les insectes</h3>
                <p>Nous éliminons cafards, fourmis, puces et autres insectes nuisibles.</p>
            </div>
            <div class="service">
                <img src="https://www.istockphoto.com/fr/photo/lenc%C3%A9phalite-de-tique-rampe-sur-le-tissu-gm1220906854-357676705">
                <h3>Traitement des punaises de lit</h3>
                <p>Solutions garanties pour éradiquer les punaises de lit de façon durable.</p>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <div class="contact">
            <h2>À Propos de Nous</h2>
            <img src="https://cdn.pixabay.com/photo/2021/01/15/14/30/exterminator-5827398_1280.jpg" alt="Technicien contre nuisibles" style="width: 50%; border-radius: 10px; margin-bottom: 1rem;">
            <p>Avec plus de 10 ans d'expérience, notre équipe intervient partout en France pour assurer un environnement sain et sécurisé. Nous utilisons des produits respectueux de l'environnement et des techniques modernes pour garantir votre satisfaction.</p>
        </div>
    </section>

    <section id="planning" class="planning">
        <h2>Réservez un créneau</h2>
        <p>Sélectionnez une date et un créneau horaire pour une intervention :</p>
        <iframe src="https://calendar.google.com/calendar/embed?src=your_calendar_id&ctz=Europe/Paris" style="border: 0" width="800" height="600" frameborder="0" scrolling="no"></iframe>
    </section>

    <section id="contact" class="contact">
        <h2>Contactez-Nous</h2>
        <p>Pour toute question ou prise de rendez-vous, contactez-nous au :</p>
        <p><strong>Téléphone :</strong> +33 6 68 62 97 15</p>
        <p><strong>Email :</strong> france.nettoyagepro@gmail.com</p>
        <p><strong>Adresse :</strong> 39 Square de la Tarentaise, 78310 Maurepas, France</p>
    </section>

    <footer>
        <p>&copy; 2024 France Nettoyage Pro. Tous droits réservés.</p>
    </footer>
</body>
</html>
