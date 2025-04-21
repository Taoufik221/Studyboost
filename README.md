
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>StudyBoost</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Barre de navigation -->
    <header class="navbar">
        <div class="logo">StudyBoost</div>
        <nav>
            <a href="#accueil">Accueil</a>
            <a href="#methodes">Méthodes</a>
        </nav>
    </header>

    <!-- Section principale -->
    <main id="hero">
        <h1>Boostez vos <span class="highlight">révisions</span></h1>
        <p>Découvrez les meilleures méthodes pour réussir vos études</p>
        <button onclick="scrollToMethods()">Explorer les méthodes</button>
    </main>

    <script>
        function scrollToMethods() {
            window.location.href = "#methodes";
        }
    </script>
</body>
</html>