# WithYou

**WithYou** est une plateforme web collaborative qui permet à plusieurs personnes de regarder des vidéos ensemble de manière synchronisée et d’interagir en temps réel.

## Fonctionnalités

- Création et partage de salons de visionnage
- Lecture vidéo synchronisée, notamment avec YouTube
- Chat en temps réel
- Gestion des membres, des rôles et des permissions
- Playlists, sondages et salons publics
- Outils de régie : annonces, verrouillage de session, historique des actions et marque-pages vidéo

## Technologies

- **Front-end :** React, TypeScript, Vite et Tailwind CSS
- **Back-end :** Laravel et PHP
- **Temps réel :** Laravel Reverb, Laravel Echo et Socket.IO
- **Données et authentification :** Supabase et base relationnelle selon l’environnement

## Structure du projet

Le code et la documentation de l’application se trouvent dans le dossier [`WithYou/`](WithYou/).

- [`WithYou/README.md`](WithYou/README.md) : présentation détaillée et instructions d’installation
- `WithYou/client/` : application front-end
- `WithYou/server/` : API Laravel
- `WithYou/realtime/` : service temps réel
- `WithYou/doc/` : documentation du projet

## Démarrage rapide

Consultez le [README détaillé](WithYou/README.md) pour les prérequis et les étapes d’installation du front-end, du back-end et du service temps réel.
