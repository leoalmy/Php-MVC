Une architecture **MVC (Modèle - Vue - Contrôleur)** en PHP réalisée dans le cadre d’un **projet scolaire** avec XAMPP. Ce projet montre comment structurer une application PHP en MVC, avec gestion des utilisateurs, employés et services, et interface simple.

---

## ✨ Fonctionnalités

* Gestion des employés : ajouter, modifier, lister, supprimer
* Gestion des services : lier des services aux employés
* Gestion des utilisateurs : inscription, connexion, profil
* Interface simple : header, menu, messages et footer
* MVC clair pour faciliter la maintenance

---

## 📂 Structure du projet

```
php-mvc/
├── BDD/            # Schéma et données exemples
├── config/         # Configuration de l’application
├── controleurs/    # Contrôleurs
├── metiers/        # Classes métiers
├── modeles/        # Modèles / accès aux données
├── vues/           # Templates et formulaires
├── public/         # Ressources statiques (CSS, JS, images)
├── vendor/         # Dépendances Composer
├── index.php       # Point d’entrée
├── .env.example    # Exemple de configuration
├── composer.json   # Composer
└── README.md       # Documentation
```

---

## ⚙️ Prérequis

* XAMPP (Apache, PHP, MySQL)
* PHP ≥ 7.4
* Composer

---

## 🚀 Installation

### Cloner le dépôt

```bash
git clone https://github.com/leoalmy/Site-Gestion-Personnel-Bootstrap.git
```

Déplacer le projet dans `C:/xampp/htdocs/php-mvc`

### OU Télécharger le .zip

Télécharger depuis [Releases GitHub](https://github.com/leoalmy/Site-Gestion-Personnel-Bootstrap/releases) et extraire dans `C:/xampp/htdocs/php-mvc`

### Configuration

```bash
composer install
cp .env.example .env
```

Modifier `.env` avec vos identifiants de base de données.

### Base de données

* Démarrer Apache et MySQL depuis XAMPP
* Créer les bases dans phpMyAdmin
* Importer les fichiers SQL du dossier **BDD/**

### Lancer le projet

Ouvrir [http://localhost/php-mvc](http://localhost/php-mvc)

---

## 🖥️ Utilisation

* Inscription ou connexion
* Gestion des employés et services via l’interface

---

## 🛠️ Technologies

* Backend : PHP (MVC)
* Frontend : HTML, CSS, JavaScript basique
* Base de données : MySQL
* Dépendances : Composer

---

## 🙌 Remarques

* Projet réalisé pour **apprentissage scolaire** du MVC
* **Non destiné à la production**
