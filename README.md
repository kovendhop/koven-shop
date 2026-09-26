<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Koven Shop</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenue sur Koven Shop</h1>
        <p>Votre boutique en ligne lancée ce matin !</p>
    </header>
    
    <main>
        <section class="produits">
            <!-- Exemple de produit -->
            <div class="produit-carte">
                <h2>Produit Exemple</h2>
                <p>Prix : 10,00 €</p>
                <button>Ajouter au panier</button>
            </div>
        </section>
    </main>

    <script src="script.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Koven Shop | Boutique en Ligne</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <!-- Barre de navigation -->
    <header class="navbar">
        <div class="logo">Koven Shop</div>
        <nav>
            <a href="#">Accueil</a>
            <a href="#">Produits</a>
            <a href="#">À propos</a>
            <a href="#">Contact</a>
        </nav>
        <div class="panier">🛒 Panier (0)</div>
    </header>

    <!-- Bannière d'accueil -->
    <section class="hero">
        <h1>Découvrez la Collection Koven</h1>
        <p>Des articles uniques sélectionnés avec soin pour vous.</p>
        <button class="btn-principal">Acheter Maintenant</button>
    </section>

    <!-- Section des Produits -->
    <main class="boutique-container">
        <h2>Nos Produits Vedettes</h2>
        
        <div class="grille-produits">
            
            <!-- Produit 1 -->
            <div class="carte-produit">
                <img src="https://unsplash.com" alt="Montre élégante">
                <h3>Montre Design Classic</h3>
                <p class="description">Un style minimaliste et intemporel au poignet.</p>
                <div class="prix">129,00 €</div>
                <button class="btn-ajouter">Ajouter au panier</button>
            </div>

            <!-- Produit 2 -->
            <div class="carte-produit">
                <img src="https://unsplash.com" alt="Chaussures de sport">
                <h3>Sneakers Koven Sport</h3>
                <p class="description">Le confort absolu allié à un design urbain moderne.</p>
                <div class="prix">89,99 €</div>
                <button class="btn-ajouter">Ajouter au panier</button>
            </div>

            <!-- Produit 3 -->
            <div class="carte-produit">
                <img src="https://unsplash.com" alt="Casque audio">
                <h3>Casque Audio Sans Fil</h3>
                <p class="description">Réduction de bruit active et son haute fidélité.</p>
                <div class="prix">199,00 €</div>
                <button class="btn-ajouter">Ajouter au panier</button>
            </div>

            <!-- Produit 4 -->
            <div class="carte-produit">
                <img src="https://unsplash.com" alt="Manette de jeu">
                <h3>Manette Pro Gaming</h3>
                <p class="description">Une réactivité maximale pour toutes vos sessions de jeu.</p>
                <div class="prix">59,50 €</div>
                <button class="btn-ajouter">Ajouter au panier</button>
            </div>

        </div>
    </main>

    <!-- Pied de page -->
    <footer>
        <p>&copy; 2026 Koven Shop. Tous droits réservés.</p>
    </footer>

</body>
</html>
