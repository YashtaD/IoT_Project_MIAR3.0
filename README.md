# MyFarmTracker 

MyFarmTracker est une application web innovante conçue pour aider les agriculteurs à surveiller et gérer les conditions environnementales de leurs serres en temps réel. Grâce à des données simulées ou réelles, elle permet de suivre des paramètres clés comme la température, l'humidité, l'intensité lumineuse, et les niveaux de CO₂, tout en offrant des alertes et des recommandations pour optimiser la santé des cultures.

---

## Liens
Application en ligne : http://myfarmtracker.lovable.app/
Code source : https://github.com/YashtaD/IoT_Project_MIAR3.0

---

## Fonctionnalités Principales

✅ Tableau de bord interactif : Visualisation des données en temps réel.
✅ Alertes intelligentes : Notifications pour les conditions anormales.
✅ Analyse des tendances : Graphiques pour suivre l'évolution des paramètres.
✅ Gestion des récoltes et des ravageurs : Outils pour diagnostiquer et traiter les problèmes des plantes.
✅ Prévisions météorologiques : Intégration des données OpenWeatherMap pour anticiper les changements climatiques.

---

##  Technologies Utilisées

| Catégorie        | Technologies                                                                                  |
|-------- ---------|-----------------------------------------------------------------------------------------------|
|   Frontend       | React, Tailwind CSS, Recharts, React-Toastify, React-Dropzone                                 |
|   Backend        | Deno, Supabase                                                                                |
|   APIs           | OpenWeatherMap, Lovable AI                                                                    |
|  Outils          | Lovable (pour la génération de code)                                                          |

---

## Installation et Exécution

Prérequis

- Node.js (version 18 ou supérieure)
- Un compte [Supabase](https://supabase.com/) (pour la base de données)
- Une clé API [OpenWeatherMap](https://openweathermap.org/) (pour les prévisions météorologiques)

Étapes d'Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/YashtaD/IoT_Project_MIAR3.0.git
   cd IoT_Project_MIAR3.0

2. Installez les dépendances :
  ```bash
  npm install

3. Créez un fichier .env à la racine du projet et ajoutez vos clés API :
  '''env
  VITE_SUPABASE_PROJECT_ID=votre_supabase_project_id
  VITE_SUPABASE_PUBLISHABLE_KEY=votre_supabase_publishable_key
  VITE_SUPABASE_URL=votre_supabase_url
  VITE_OPENWEATHERMAP_API_KEY=votre_openweathermap_api_key


4. Lancez l'application en mode développement :
   '''bash
   npm run dev

