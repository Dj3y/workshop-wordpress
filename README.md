# 𝖶𝗈𝗋𝗄𝗌𝗁𝗈𝗉: 𝖢𝗋é𝖺𝗍𝗂𝗈𝗇 𝖽'𝗎𝗇 𝗌𝗂𝗍𝖾 𝖾𝖢𝗈𝗆𝗆𝖾𝗋𝖼𝖾 𝖺𝗏𝖾𝖼 𝖶𝗈𝗋𝖽𝖯𝗋𝖾𝗌𝗌

Ce guide vous accompagnera dans la création d'un site eCommerce avec WordPress et WooCommerce. 
Nous couvrirons l'installation avec XAMPP ou Docker, la configuration de WooCommerce et la personnalisation de votre boutique.

## Étape 1 : Installation de WordPress en local (Deux méthodes)

### 1.1 Méthode 1 : Installation de WordPress avec XAMPP

1. *Télécharger et installer XAMPP* :
   - Allez sur le [site officiel de XAMPP](https://www.apachefriends.org/index.html) et téléchargez la version adaptée à votre système d'exploitation (Windows, macOS ou Linux).
   - Suivez les instructions à l'écran pour l'installer.

2. *Démarrer Apache et MySQL* :
   - Ouvrez le panneau de contrôle XAMPP et démarrez les services *Apache* et *MySQL*.

3. *Télécharger WordPress* :
   - Visitez le [site de WordPress.org](https://wordpress.org/download/) et téléchargez la dernière version de WordPress.

4. *Extraire WordPress dans htdocs* :
   - Décompressez le fichier WordPress.
   - Déplacez le dossier extrait dans le répertoire htdocs de XAMPP (généralement C:\xampp\htdocs sous Windows).

5. *Créer une base de données* :
   - Ouvrez votre navigateur et allez sur http://localhost/phpmyadmin/.
   - Cliquez sur *Bases de données* et créez une nouvelle base de données (par exemple, wordpress_db).

6. *Installer WordPress* :
   - Dans votre navigateur, accédez à http://localhost/wordpress.
   - Suivez l'assistant d'installation. Entrez les détails de la base de données (nom de la base de données : wordpress_db, nom d'utilisateur : root, laissez le champ mot de passe vide si vous utilisez la configuration par défaut de XAMPP).
   - Terminez l'installation et connectez-vous.

### 1.2 Méthode 2 : Installation de WordPress avec Docker

1. *Installer Docker* :
   - Téléchargez et installez Docker depuis le [site officiel](https://www.docker.com/products/docker-desktop).

2. *Créer un fichier Docker Compose* :
   - Ouvrez votre terminal ou invite de commandes et créez un nouveau répertoire pour votre projet WordPress.
   - À l'intérieur de ce répertoire, créez un fichier nommé docker-compose.yml, le fichier il est mis à votre disposition. 


3. *Exécuter Docker Compose* :
   - Exécutez la commande suivante dans le terminal pour démarrer les conteneurs :

     bash
     docker-compose up -d
     

4. *Accéder à WordPress* :
   - Ouvrez votre navigateur et allez sur http://localhost:8000 pour compléter l'installation de WordPress.

---

## Étape 2 : Configuration de votre site eCommerce

### 2.1 Installer le plugin WooCommerce :
1. Connectez-vous à votre tableau de bord WordPress.
2. Allez dans *Extensions > Ajouter*.
3. Recherchez "WooCommerce".
4. Cliquez sur *Installer maintenant, puis **Activer*.

### 2.2 Configurer WooCommerce :
1. Après activation, WooCommerce lancera un assistant de configuration.
2. Remplissez les détails de base comme l'emplacement de la boutique, la devise et le type de produit.
3. WooCommerce vous demandera également d'installer des pages essentielles (comme Boutique, Panier, Commande et Mon Compte).

---

## Étape 3 : Ajouter des produits à votre boutique

1. Depuis le tableau de bord, allez dans *Produits > Ajouter un nouveau*.
2. Entrez le titre du produit, la description, le prix et définissez l'image du produit.
3. Configurez les catégories et les balises des produits pour une meilleure organisation.
4. Une fois terminé, cliquez sur *Publier*.

---

## Étape 4 : Personnaliser votre site eCommerce WordPress

1. *Choisir un thème* :
   - Allez dans *Apparence > Thèmes*.
   - Sélectionnez un thème gratuit ou premium adapté à vos besoins eCommerce (par exemple, Storefront).

2. *Personnaliser le thème* :
   - Allez dans *Apparence > Personnaliser*.
   - Ajustez la mise en page, les couleurs et la typographie selon vos préférences.

---

## Étape 5 : Configurer les options de paiement et d'expédition

### 5.1 Paramètres de paiement :
1. Allez dans *WooCommerce > Réglages > Paiements*.
2. Choisissez vos méthodes de paiement souhaitées (par exemple, PayPal, Stripe).
3. Suivez les instructions pour les configurer.

### 5.2 Paramètres d'expédition :
1. Allez dans *WooCommerce > Réglages > Expédition*.
2. Définissez les zones et les tarifs d'expédition.

---

## Étape 6 : Lancer votre boutique

1. Après avoir configuré vos produits, thème, options de paiement et d'expédition, vous pouvez réviser votre boutique.
2. Visitez la page d'accueil de votre site, naviguez à travers les pages produits et assurez-vous que tout fonctionne correctement.
3. Si vous êtes satisfait, votre boutique est prête à être mise en ligne (si hébergée) ou présentée en local.

# Tres important n'oubliez pas de partager le benef!
