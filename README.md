# 🚀 TalentPool API

## 📌 Description
TalentPool API est une API REST développée avec Laravel pour la gestion des recrutements en entreprise. Elle permet aux recruteurs de publier des annonces, de gérer les candidatures et de suivre les recrutements, tandis que les candidats peuvent postuler à des offres et suivre l'évolution de leur candidature.

## 🛠️ Technologies Utilisées
- Laravel (PHP Framework)
- MySQL (Base de données)
- JWT ou Sanctum (Authentification sécurisée)
- Laravel Gates & Policies (Gestion des permissions)
- PHPUnit ou Pest (Tests unitaires)

## 🎯 Fonctionnalités

### 📢 Gestion des Annonces
- Les recruteurs peuvent ajouter, modifier et supprimer des annonces.
- Les candidats peuvent consulter les annonces et leurs détails pour postuler.

### 📝 Gestion des Candidatures
- Les candidats peuvent postuler à une annonce en envoyant leur CV et leur lettre de motivation.
- Ils peuvent également retirer leur candidature.
- Les recruteurs peuvent filtrer et récupérer les candidatures associées à leurs annonces.

### 🔄 Suivi des Candidatures
- Les recruteurs peuvent mettre à jour le statut des candidatures.
- Les candidats sont notifiés par e-mail en cas de changement de statut.

### 🔒 Authentification et Sécurité
- Inscription et connexion des utilisateurs avec JWT ou Sanctum.
- Réinitialisation du mot de passe.
- Choix du rôle (candidat ou recruteur) lors de l'inscription (non modifiable par la suite).

### 📊 Statistiques et Rapports
- Les recruteurs peuvent obtenir des statistiques sur leurs annonces et candidatures.
- Les administrateurs ont accès à des statistiques globales sur l'utilisation de la plateforme.

## 🏗️ Architecture
- **Repository Pattern** et **Service Layer** pour assurer la modularité et la maintenabilité du code.
- **Laravel Gates & Policies** pour la gestion des permissions.
- **Validation des entrées** et gestion des erreurs pour garantir la sécurité et la fiabilité.

## ⚡ Critères de Performance
- Temps de réponse optimisé pour garantir une expérience fluide même sous forte charge.
- Sécurisation des données utilisateur contre les attaques.
- Gestion robuste des erreurs pour faciliter le diagnostic des problèmes.
- Testabilité renforcée avec des tests unitaires et d'intégration couvrant les fonctionnalités clés.
- Documentation complète et claire pour faciliter l'intégration de l'API par d'autres développeurs.

## ⚙️ Installation et Configuration

### ✅ Prérequis
- PHP 8.x
- Composer
- MySQL
- Laravel

### 📥 Installation
```bash
# Cloner le projet
git clone https://github.com/ABDELHAFIDAIT/TalentPool.git
cd talentpool

# Installer les dépendances
composer install

# Configurer l'environnement
cp .env.example .env
php artisan key:generate

# Configurer la base de données (modifier .env avec les bonnes informations)
php artisan migrate

# Lancer le serveur
tphp artisan serve
```

## 🚀 Utilisation
L’API expose des endpoints REST accessibles via un client HTTP (Postman, Curl, etc.).
Une documentation détaillée des endpoints est disponible.

## 🧪 Tests
Pour exécuter les tests unitaires :
```bash
php artisan test
```

## 🤝 Contribution
Les contributions sont les bienvenues ! Merci de soumettre une pull request avec des explications claires.

## 📜 Licence
MIT License. Voir le fichier `LICENSE` pour plus d’informations.

