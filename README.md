<div align="center">

# Maneyge
**Un outil tout-en-un pour centraliser ta vie numérique, sans dépendre des géants du web.**

![Status](https://img.shields.io/badge/status-en%20développement%20actif-brightgreen)
![PHP](https://img.shields.io/badge/PHP-8.2-777BB4?logo=php&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind%20CSS-v4-06B6D4?logo=tailwindcss&logoColor=white)
![DaisyUI](https://img.shields.io/badge/DaisyUI-latest-5A0EF8)
![MariaDB](https://img.shields.io/badge/MariaDB-10.4-003545?logo=mariadb&logoColor=white)
![License](https://img.shields.io/badge/licence-privé-red)

</div>

## Objectif initial
Maneyge a démarré comme un simple **outil de gestion financière personnelle** : suivre ses comptes bancaires, enregistrer ses transactions (gains et dépenses), visualiser ses budgets et recevoir des alertes intelligentes en cas d'anomalie.

L'idée de base était de remplacer les tableaux Excel ou les apps bancaires limitées par quelque chose de **personnalisable, hébergeable soi-même, et sans abonnement**.

## Évolution du projet
Au fil du développement, Maneyge a grandi pour devenir bien plus qu'un simple gestionnaire de finances.

L'ambition est désormais d'en faire une **plateforme personnelle tout-en-un**, capable de remplacer les outils Google et autres services tiers qui collectent bien plus de données que nécessaire.

> **Centraliser. Contrôler. Simplifier.**

Les modules prévus ou en cours de développement couvrent les grandes catégories du quotidien numérique :

| Module | Description |
|---|---|
| 💰 **Finances** | Comptes, transactions, budgets, alertes, paiements récurrents, export PDF |
| 📅 **Agenda** | Calendrier collaboratif multi-vues (Jour, Semaine, Mois, Année), partage par rôle |
| ✅ **Todo list** | Gestion de tâches personnelles et partagées |
| 📝 **Notes** | Prise de notes centralisée |

## Stack technique
- **Backend** : PHP 8.2 — architecture MVC avec séparation Model / DAO / View / Controller
- **Frontend** : Tailwind CSS v4 + DaisyUI — 100% responsive (desktop & mobile)
- **Base de données** : MariaDB 10.4
- **Génération PDF** : FPDF
- **Icônes** : FontAwesome
- **Internationalisation** : système maison  - anglais par défaut, français disponible

## État d'avancement

### 💰 Module Finances — terminé
- Gestion multi-comptes (création, modification, suppression)
- Enregistrement des transactions par catégorie
- Système de budget avec suggestions automatiques basées sur l'historique
- 5 types d'alertes : solde bas, budget dépassé, aucun revenu, anomalie de dépense, dépense inhabituelle
- Envoi d'alertes par email + messagerie interne
- Paiements récurrents (quotidien, hebdomadaire, mensuel, trimestriel, annuel) avec exécution automatique via tâche planifiée
- Export PDF (à but personnel) avec logo, numérotation des pages et mentions légales

### 📅 Module Agenda — en cours
- [x] Vue **Jour** — affichage horaire 00h–23h, chevauchement d'événements, responsive
- [x] Vue **Semaine** — grille 7 colonnes desktop, affichage empilé mobile
- [x] Vue **Mois** — grille responsive, jours hors-mois affichés
- [x] Vue **Année** — 12 mini-calendriers, colonnes fixes Lun→Dim
- [x] Jours fériés `français` intégrés dans toutes les vues + légende
- [x] Création et modification d'événements, chargement BDD dynamique
- [x] Agenda collaboratif avec système de rôles
- [x] Page de gestion des calendriers
- [ ] Création d'un nouveau calendrier
- [ ] Gestion des membres et rôles

### 🌍 Internationalisation — en cours
- [x] Système i18n en place (session + BDD)
- [ ] Sélecteur de langue
- [x] Module Finances traduit
- [ ] Traduction des autres modules en cours

### 🔲 À venir
- Todo list
- Notes
- Import de transactions (CSV/XLSX banque)

## Licence & accès au code
> **Ce projet n'a pas vocation à être open-source pour le moment.**

## Aperçu
> *Captures d'écran à venir.*
