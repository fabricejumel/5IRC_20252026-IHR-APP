
# Sujet : Conception d'une Démo d'Interaction Homme-Robot dans le cadre du Mondiale des Métiers

## Contexte et Objectifs

Vus devez concevoir une démonstration d'interaction homme-robot (HRI) pour un stand "Concepteur d'Avenir" ldu Mondiale des  Métiers. Ce projet s'inspire de la participation de CPE LYON à un stand précédent, avec une démo utilisant le robot Baxter (intégrant son, position et émotions) et une démo IA (affichage YOLO pour détection d'objets + détection d'émotions sur les passants).

[![Version 2024 SETUP](https://img.youtube.com/vi/dU6WokFrbxE/0.jpg)](https://www.youtube.com/watch?v=dU6WokFrbxE?autoplay=1&mute=1)

Vidéo intégrée via YouTube (15s) : Interface tactile IHR.

[![Version 2024 SETUP](https://img.youtube.com/vi/4Uqp6coTVtw/0.jpg)](https://www.youtube.com/watch?v=4Uqp6coTVtw?autoplay=1&mute=1)

**Objectif principal** : Proposer une démo plus interactive avec le public, en exploitant le matériel disponible à l'école. L'interaction doit être engageante, éducative sur l'IA et la robotique, et adaptée à un contexte de salon (public varié, temps court par visiteur).

## Durée et Équipe

**Durée du projet** : 
- 3 jours pour la conception (storyboard, choix logiciels, architecture, interface).
- Tests optionnels sur le matériel disponible à l'école ou en votre possesion pendant ces 3 jours.
- La démo finale (non à implémenter ici) doit être réalisable en **1 semaine maximum pour 2 personnes**.
- Pas d'accès internet sur place : Tout doit être offline (modèles IA pré-téléchargés, développement local).

**Équipe** : Travail en Monome.

## Contraintes


- Rendu via votre dépôt GitLab 
- Focus sur l'explication des problèmes potentiels et solutions.
- Mettez l'accent sur un **Plan A** (idéal, innovant) et un **Plan B** (garanti en temps court, simple à développer).
- Utilisez GitLab Flavored Markdown (GLFM) pour le README.md, compatible avec tables, diagrammes (via Excalidraw PNG en incluant le code générateur)


## Matériel Disponible

Utilisez ce qui est listé ; vous pouvez proposer d'ajouter des écrans ou autres équipements disponibles à l'école (ex. : capteurs supplémentaires, batteries pour robots).

- **Robots** : Baxter (mode recherche), Pepper (optionnel).
- **Lampes interactives** : Logitech Beam LX (pour éclairage réactif).
- **PCs** : PC gamer (2x RTX 3090 24 Go), PC Deep (2x RTX 1070 Ti) – sous Ubuntu 22.04 avec drivers CUDA installés.
- **Périphériques** : Webcams, micros Logitech Orbi, StreamDeck Mini, imprimante A6 couleur (USB ou Ethernet), routeur WiFi local, 2 TVs/écrans (ajout possible d'autres écrans)....

**Réseau** : Utilisez le routeur WiFi pour un réseau local (comms entre PCs/robots/StreamDeck), sans internet. Utiliser le wifi que si vraiement utile

## Tâches à Réaliser (3 Jours)

### 1. Storyboard des Interactions
Créez un storyboard séquentiel (6-12 panneaux) décrivant l'interaction complète entre le public et la démo. Utilisez un format simple 

- **Plans A/B** : Plan A  ; Plan B simplifié.


### 2. Choix des Logiciels
Proposez et justifiez les outils logiciels (open-source, offline). Justifiez la compatibilité Ubuntu/CUDA/ROS.

- **Composants clés** :
  - IA : Détection objets/émotions.
  - Robots : Contrôle Baxter/Pepper.
  - Interface : Web offline + StreamDeck ou autre à proposer
  - Impression


### 3. Définition de l'Architecture
Définissez le système global (hardware/software). **Utilisez Excalidraw pour les schémas d'architecture** et inclure les sources des diagrammes
- **Contenu** : Diagramme flux (IA input → processing → output robots/UI). Expliquez communications (WiFi local, ROS topics).
- **Plans A/B** 



### 4. Proposition d'Interface
Proposez une interface utilisateur (ex. : web + StreamDeck Mini pour opérateur).



## Plans A et B

- **Plan A (Idéal)** : Interaction riche (Baxter + Pepper + IA + impression). Temps : 1 semaine (40h/2 pers.).
- **Plan B (Garantit)** : Version basique (Pepper + webcam + affichage TV). Temps : 3-4 jours, fallback si matos indispo.

Expliquez pourquoi Plan B est robuste. Utilisez Excalidraw pour comparer les deux plans (diagramme side-by-side).



## Rendu Final (GitLab)

Créez un dépôt GitLab dédié. Structure :
- README.md : Ce sujet rempli avec vos propositions (storyboard, tableaux, schémas Excalidraw en PNG).
- Fichiers : Images PNG (storyboard, architecture via Excalidraw), snippets code tests, liste dépendances offline.
- Commit final pour le XXX

**Critères d'évaluation** :
- Innovation/engagement public.
- Faisabilité (1 semaine/2 pers., offline).
- Qualité explications (problèmes/solutions).
- Clarté visuelle (storyboard, diagrammes Excalidraw).
-  **Anticipation** : Expliquez problèmes potententiels et solutions.

**Attention** :
- ROS Baxter : attention ROS 1 / veille version de ubuntu <10. Impossible de faire des mises à jour du linux . eviter l'usage d'un apt install ou equivalent 
- Pepper : NAOqi



