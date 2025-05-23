# 📚 Author-Symfony

Un exercice Symfony réalisé pour apprendre à utiliser une base de données avec Symfony et Twig.

## 🎯 Objectif

Ce projet permet de se familiariser avec le framework Symfony, la gestion des bases de données via Doctrine, et le rendu de vues avec Twig.

## 🚀 Technologies utilisées

- **Symfony**
- **PHP**
- **Twig**
- **Doctrine ORM**
- **Base de données (MySQL)**

## 🖥️ Fonctionnalités

- Connexion à une base de données
- CRUD (Create, Read, Update, Delete) basique via Symfony
- Rendu des pages avec Twig
- Gestion des entités et des migrations

## 🛠️ Installation

1. Clone ce dépôt :
   ```bash
   git clone https://github.com/SirAdaz/Author-Symfony.git
   ```
2. Installe les dépendances avec Composer :
   ```bash
   composer install
   ```
3. Configure ta base de données dans le fichier `.env`
4. Lance les migrations :
   ```bash
   php bin/console doctrine:migrations:migrate
   ```
5. Lance le serveur local :
   ```bash
   symfony serve
   ```
6. Ouvre `http://localhost:8000` dans ton navigateur.

## Auteur

- **SirAdaz** – [GitHub](https://github.com/SirAdaz)
