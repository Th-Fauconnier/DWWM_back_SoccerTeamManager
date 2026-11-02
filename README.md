# ⚽ Soccer Team Manager — API Backend (Symfony)

[![PHP](https://img.shields.io/badge/PHP-8.x-777BB4?logo=php&logoColor=white)](#)
[![Symfony](https://img.shields.io/badge/Symfony-Framework-000000?logo=symfony&logoColor=white)](#)
[![Status](https://img.shields.io/badge/Status-Refactoring%20en%20cours-orange)](#)

> ⚠️ **Projet en cours de modernisation & refactorisation**  
> Ce dépôt est un projet backend développé initialement dans le cadre de mon titre professionnel **DWWM** (Développeur Web et Web Mobile).  
> Il fait l'objet d'un chantier actif de refactorisation afin d'amener le code historique aux standards actuels de développement (PHP 8+, typage strict, architecture découplée, tests automatisés).  
> L'avancement des chantiers est documenté et suivi dans l'onglet **[Issues](../../issues)** du dépôt.

---

## 📌 Présentation

**Soccer Team Manager** est une API REST sécurisée permettant la gestion complète d'une organisation sportive : équipes de football, joueurs, effectifs et compositions d'équipes.

L'application est conçue selon une architecture découplée (_headless_), destinée à être consommée par un client frontend dédié :

- **Frontend associé (React) :** _En cours d'intégration_ (lien à venir)
- **Authentification :** Sécurisation des endpoints via JWT (JSON Web Tokens)

---

## 🛠️ Stack technique

- **Langage :** PHP 8.x
- **Framework :** Symfony
- **ORM :** Doctrine ORM
- **Base de données :** MySQL / MariaDB
- **Authentification :** JWT (`lexik/jwt-authentication-bundle`)
- **Gestionnaire de dépendances :** Composer

---

## 🏗️ Feuille de route & chantiers de modernisation (Roadmap)

Le travail de refactorisation est découpé en jalons méthodiques traçables via les issues GitHub :

- [ ] **Modernisation du code :** Migration des annotations PHPDoc historiques vers les attributs natifs PHP 8 (`#[ORM\...]`, `#[Route(...)]`) et mise en place du typage strict (`declare(strict_types=1);`).
- [ ] **Architecture & Services :** Allègement des contrôleurs (_thin controllers_) et extraction de la logique métier dans des classes de services dédiées.
- [ ] **Standardisation API :** Normalisation des formats d'erreur (RFC 7807) et sécurisation des sérialisations (groupes de sérialisation pour éviter les références circulaires).
- [ ] **Qualité & Tests :** Mise en place d'une suite de tests automatisés (PHPUnit) couvrant les endpoints critiques et la chaîne d'authentification.
- [ ] **Documentation Swagger / OpenAPI :** Génération d'une documentation interactive via NelmioApiDocBundle.
- [ ] **Infrastructure :** Conteneurisation de l'environnement de développement via Docker (PHP-FPM, Nginx, MariaDB).

---

## 🚀 Installation locale

### 1. Prérequis

- PHP >= 8.1 avec extensions : `pdo_mysql`, `openssl`, `intl`, `mbstring`
- Composer
- Un serveur MySQL ou MariaDB actif

### 2. Cloner le dépôt

```bash
git clone [https://github.com/Th-Fauconnier/DWWM_back_SoccerTeamManager.git](https://github.com/Th-Fauconnier/DWWM_back_SoccerTeamManager.git)
cd DWWM_back_SoccerTeamManager
```
