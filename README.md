# Soccer Team Manager — Backend (API Symfony)

> **Statut du projet :** 📦 _Archive / Work in progress_  
> Projet backend développé initialement dans le cadre de ma formation **DWWM** (Développeur Web et Web Mobile). Retrouvé et versionné pour conservation d'historique, remise en route et exploration de potentielles évolutions (refactorisation, mise à jour des dépendances, ajout de features).

---

## 📌 Présentation

Ce dépôt contient l'API backend du projet **Soccer Team Manager**.  
Il a pour objectif la gestion d'équipes de football, de joueurs, de compositions ou de statistiques, exposé via des endpoints REST sécurisés par authentification JWT.

---

## 🛠️ Stack technique

- **Langage :** PHP (8.x)
- **Framework :** Symfony
- **ORM :** Doctrine
- **Base de données :** MySQL / MariaDB
- **Authentification :** JWT (`lexik/jwt-authentication-bundle`)
- **Gestionnaire de dépendances :** Composer

---

## 🚀 Installation locale

### 1. Prérequis

- PHP installé (avec les extensions requises : `pdo_mysql`, `openssl`, `intl`, `mbstring`)
- Composer
- Un serveur de base de données MySQL / MariaDB (via XAMPP, Laragon, WampServer ou Docker)

### 2. Cloner le projet

```bash
git clone [https://github.com/Th-Fauconnier/DWWM_back_SoccerTeamManager.git](https://github.com/Th-Fauconnier/DWWM_back_SoccerTeamManager.git)
cd DWWM_back_SoccerTeamManager
```
