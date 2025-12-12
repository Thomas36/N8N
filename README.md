# N8N
Dossier_N8N

# MaVeille
Ce projet a pour but de d'automatiser la gestion de tickets sur GLPI avec mails d'assistance reçus.

Les mails non lus reçus sur l'adresse mail sont récupérer.
Ensuite, ces derniers sont traités par IA afin de récupérer uniquement les informations principales.
Puis, un ticket est créé avec les informations renvoyés par l'IA.

## Prérequis
- Docker installé et fonctionnel
- Sinon Installer Docker Desktop sur https://hub.docker.com/

## Installation
- Exécuter "docker Compose"
- Créer un dossier "mkdir nom_dossier"
- Insérer les fichiers .yml et .env dans le dossier

## Accès
- Mailpit --> http://localhost:8025
- n8n --> http://localhost:5678
- GLPI --> http://localhost:8080

## Utilisation
- Lancer les logiciels grâce à docker Compose "docker compose up"
- Accèder à GLPI pour voir les tickets http://127.0.0.1:8080

## Modifications du Workflow
- Lancer docker Compose
- Accèder à http://localhost:5678
- Choisir le workflow "MaVeille"
