# My Crypto Dex App

Application web de suivi et de swap de cryptomonnaies construite avec Angular 16 et Express.js.

## Technologies Utilisées
- Frontend : Angular 16, Chart.js, tradingView Chart Ethers.js
- Backend : Express.js, Firebase, Ethers.js
- Base de données : Firebase Firestore
- Authentification : Firebase Authentication
- Hébergement : Firebase Hosting

## Installation

### Prérequis
- Node.js et npm
- Angular CLI
- Git

### Cloner le Repository
```bash
git clone https://github.com/Serigne78/my-crypto-app.git
cd my-crypto-app


Voici une trame de 4 diapositives qui intègre tes nouvelles notes (autoformation, méthode Scrum, microservices, « apports », etc.) tout en gardant une approche « high-level ». Les titres sont indicatifs, tu peux les ajuster selon tes besoins.

⸻

Diapo 1 – Qu’est-ce que la “White App” ?
	•	Contexte et finalité :
	•	Outil de facturation/refacturation
	•	Consolidation et historisation du fonctionnement des produits internes (métriques, consommations)
	•	Faciliter la mise à disposition de données pour l’équipe de facturation
	•	Objectifs globaux :
	1.	Recenser et visualiser les consommations de produits « natifs ».
	2.	Permettre l’upload (factures, relevés) pour centraliser les infos.
	3.	Proposer une assistance pour la refacturation.

(Ici, tu présentes rapidement le “pourquoi” de l’appli et en quoi elle est utile.)

⸻

Diapo 2 – Méthodologie & Organisation
	•	Approche de développement :
	•	Autoformation (Udemy, MOOC, etc.) sur Angular, Spring Boot, microservices…
	•	Kanban pour l’instant (Jira), passage futur en Scrum ou “Méthode Sprint” quand les retours utilisateurs finaux (équipe Facturation) seront réguliers.
	•	Collaboration Fatmeh & Moi : répartition des sous-objectifs, code en binôme, relectures, etc.
	•	Architecture globale :
	•	Découpage en microservices (pour la partie back-end).
	•	Séparation Front (Angular / Tailwind / ChartJS) et Back (Java, Spring Boot).

(On aborde comment vous vous êtes organisés, pourquoi ce choix de méthodes, etc.)

⸻

Diapo 3 – Aperçu Technique
	•	Technologies clés :
	•	Front-end : Angular, bibliothèque interne (Muesli), Tailwind pour le style, ChartJS pour les graphs.
	•	Back-end : Java/Spring Boot, APIs REST, microservices.
	•	Stockage & Fichiers : S3 Bucket (upload/download), base NoSQL (MongoDB).
	•	Métriques : Prometheus/Grafana (Kubernetes, Kafka).
	•	Sous-objectifs :
	•	Fatmeh (Sous-objectif 1) : gestion upload/consultation de fichiers (S3, MongoDB).
	•	Moi (Sous-objectif 2) : récupération des métriques (Prometheus, Kafka, Kube) et affichage via Angular + ChartJS.

(Un mini-schéma d’architecture ou des captures d’écran simples peuvent illustrer cette diapo.)

⸻

Diapo 4 – Apports & Perspectives
	•	Apports / Ce que cela nous a apporté :
	•	Montée en compétences en développement web (autoformation sur Udemy/MOOC).
	•	Travail d’équipe, gestion de projet agile (Kanban → future Scrum).
	•	Meilleure compréhension du fonctionnement technique (microservices, CI/CD, NoSQL…).
	•	Perspectives :
	•	Tests et retours de l’équipe Facturation pour valider l’ergonomie et la pertinence des données.
	•	Ajout de nouvelles fonctionnalités : historisation plus avancée, automatisation de la refacturation.
	•	Éventuel passage en production après validation et itérations.

(Conclure en remerciant et en ouvrant la discussion pour d’éventuelles questions.)

⸻

Astuces finales :
	•	Reste synthétique (4 diapos = présentation courte).
	•	Mise en forme visuelle : quelques mots-clés, icônes ou captures d’écran pour illustrer la partie technique.
	•	Insiste bien sur l’intérêt métier (améliorer la refacturation, centraliser les infos) pour un public non technique.

En suivant cette structure, tu intègres tes notes (autoformation, méthodes agile, microservices, etc.) et tu donnes au public une vision générale, sans noyer les gens dans les détails techniques. Bonne présentation !

