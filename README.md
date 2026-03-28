# 🎵 Lowify - Spotify Remake (PHP/SQL)

> ### [Consulter le projet en ligne](https://lowify.alwaysdata.net/)

**Lowify** est une application web de streaming musical (sans son) simplifiée, développée comme projet d'initiation au développement **PHP** et à la gestion de bases de données **SQL**. Ce projet permet d'explorer des artistes, des albums et des titres via une interface moderne inspirée de Spotify.

---

## Fonctionnalités
* **Navigation Artistes & Albums** : Consultation dynamique des fiches artistes et des listes de lecture d'albums.
* **Recherche Globale** : Système de recherche performant filtrant simultanément les artistes, les albums et les chansons.
* **Lecteur de Contenu** : Affichage des détails des pistes (durée, notes, pochettes).

---

## 🛠️ Stack Technique
* **Backend** : PHP 8 (PDO MySQL).
* **Frontend** : HTML5, CSS3, Bootstrap 5.
* **Base de données** : MySQL.
* **Environnement** : Développé sous XAMPP et déployé sur Alwaysdata.

---

## 📦 Installation & Utilisation Locale

### 1. Prérequis
* Un serveur local (XAMPP, WAMP, ou Docker).
* PHP 8.0 ou supérieur.

### 2. Installation de la base de données
* Créez une base de données nommée `lowify`.
* Importez le fichier `db.sql` pour générer la structure et les données de test.

### 3. Configuration
* Rendez-vous dans le dossier `app/inc/`.
* Renommez le fichier `config.php.example` en `config.php`.
