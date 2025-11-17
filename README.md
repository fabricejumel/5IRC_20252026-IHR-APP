## Démo IHR App

[![Version 2024 SETUP](https://img.youtube.com/vi/dU6WokFrbxE/0.jpg)](https://www.youtube.com/watch?v=dU6WokFrbxE?autoplay=1&mute=1)

Vidéo intégrée via YouTube (15s) : Interface tactile IHR.

[![Version 2024 SETUP](https://img.youtube.com/vi/4Uqp6coTVtw/0.jpg)](https://www.youtube.com/watch?v=4Uqp6coTVtw?autoplay=1&mute=1)


# Sujet : Conception d'une Démo d'Interaction Homme-Robot pour les WorldSkills des Métiers

## Contexte et Objectifs

Dans le cadre du programme 5ETI (Ingénierie des Systèmes et Technologies de l'Information), vous devez concevoir une démonstration d'interaction homme-robot (HRI) pour un stand "Concepteur d'Avenir" lors des WorldSkills des Métiers. Ce projet s'inspire de la participation de Fabrice Jumel à un stand précédent, avec une démo utilisant le robot Baxter (intégrant son, position et émotions) et une démo IA (affichage YOLO pour détection d'objets + détection d'émotions sur les passants).

**Objectif principal** : Proposer une démo plus interactive avec le public, en exploitant le matériel disponible à l'école. L'interaction doit être engageante, éducative sur l'IA et la robotique, et adaptée à un contexte de salon (public varié, temps court par visiteur).

## Durée et Équipe

**Durée du projet** : 
- 3 jours pour la conception (storyboard, choix logiciels, architecture, interface).
- Tests optionnels sur le matériel disponible à l'école pendant ces 3 jours.
- La démo finale (non à implémenter ici) doit être réalisable en **1 semaine maximum pour 2 personnes**.

**Équipe** : Travail en groupes de 2-4 étudiants. Chaque membre contribue à des sections spécifiques (marquez vos initiales dans le rendu).

## Contraintes

- Pas d'accès internet : Tout doit être offline (modèles IA pré-téléchargés, développement local).
- Rendu via un nouveau dépôt GitLab (créez-le vous-même ; nommez-le ex. "HRI-Demo-WorldSkills-[Groupe]").
- Focus sur l'explication des problèmes potentiels et solutions.
- Mettez l'accent sur un **Plan A** (idéal, innovant) et un **Plan B** (garanti en temps court, simple à développer).
- Utilisez GitLab Flavored Markdown (GLFM) pour le README.md, compatible avec tables, diagrammes (via Excalidraw PNG), et previews offline.
- Pour téléchargement : Sauvegardez ce sujet en fichier .md (copiez-collez dans un éditeur comme VS Code ou Typora), exportez en PDF via Pandoc (si installé localement) ou imprimer depuis GitLab preview. Structure optimisée pour export : Headers clairs, tables simples, sans liens externes.

## Matériel Disponible

Utilisez ce qui est listé ; vous pouvez proposer d'ajouter des écrans ou autres équipements disponibles à l'école (ex. : capteurs supplémentaires, batteries pour robots).

- **Robots** : Baxter (mode recherche), Pepper (optionnel).
- **Lampes interactives** : Logitech Beam LX (pour éclairage réactif).
- **PCs** : PC gamer (2x RTX 3090 24 Go), PC Deep (2x RTX 1070 Ti) – sous Ubuntu 22.04 avec drivers CUDA installés.
- **Périphériques** : Webcams, micros Logitech Orbi, StreamDeck Mini, imprimante A6 couleur (USB ou Ethernet), routeur WiFi local, 2 TVs/écrans (ajout possible d'autres écrans).
- **Autres** : Imprimante pour badges ou sorties papier.

**Réseau** : Utilisez le routeur WiFi pour un réseau local (comms entre PCs/robots/StreamDeck), sans internet.

## Tâches à Réaliser (3 Jours)

### 1. Storyboard des Interactions
Créez un storyboard séquentiel (6-12 panneaux) décrivant l'interaction complète entre le public et la démo. Utilisez un format simple (tableau ou images rough dessinées/numérisées via imprimante A6).

- **Contenu** : Flux étape par étape (accueil → interaction → feedback → fin). Incluez rôles (robot, public, opérateur via StreamDeck).
- **Plans A/B** : Plan A avec Baxter + Pepper + IA avancée ; Plan B simplifié.
- **Outils** : Papier + scan imprimante, ou Draw.io offline (export PNG).
- **Anticipation** : Expliquez problèmes potentiels et solutions.

### 2. Choix des Logiciels
Proposez et justifiez les outils logiciels (open-source, offline). Justifiez la compatibilité Ubuntu/CUDA/ROS.

- **Composants clés** :
  - IA : Détection objets/émotions.
  - Robots : Contrôle Baxter/Pepper.
  - Interface : Web offline + StreamDeck.
  - Autres : Audio/vidéo, impression.
- **Format** : Tableau avec logiciel, justification, alternatives (Plan B), temps estimé.
- **Problèmes** : Expliquez risques et solutions.

### 3. Définition de l'Architecture
Définissez le système global (hardware/software). **Utilisez Excalidraw pour les schémas d'architecture** (outil offline recommandé : téléchargez la version desktop ou utilisez la version exportable sans internet).

- **Contenu** : Diagramme flux (IA input → processing → output robots/UI). Expliquez comms (WiFi local, ROS topics).
- **Plans A/B** : Plan A multi-PC/multi-robot ; Plan B un PC + un robot.
- **Outils pour schémas** : 
  - **Excalidraw principal** : Créez des diagrammes clairs (blocs, flèches, labels) pour l'architecture. Exportez en PNG/SVG et intégrez dans le README (via chemin relatif ou drag-and-drop GitLab).
  - Alternatives si Excalidraw indisponible : ASCII art dans Markdown ou Draw.io offline.
- **Anticipation** : Expliquez problèmes et solutions.

### 4. Proposition d'Interface
Proposez une interface utilisateur (ex. : web + StreamDeck Mini pour opérateur).

- **Web** : Serveur local accessible sur TVs (realtime, instructions public).
- **StreamDeck** : Boutons pour opérateur.
- **Plans A/B** : Plan A web + StreamDeck ; Plan B console simple.
- **Exemples code** : Snippets Python basiques à tester.
- **Schéma interface** : Utilisez Excalidraw pour un wireframe simple.
- **Problèmes** : Expliquez risques et solutions.

## Plans A et B

- **Plan A (Idéal)** : Interaction riche (Baxter + Pepper + IA + impression). Temps : 1 semaine (40h/2 pers.).
- **Plan B (Garantit)** : Version basique (Pepper + webcam + affichage TV). Temps : 3-4 jours, fallback si matos indispo.

Expliquez pourquoi Plan B est robuste. Utilisez Excalidraw pour comparer les deux plans (diagramme side-by-side).

## Tests et Anticipation des Problèmes

Pendant les 3 jours :
- Jour 1 : Test IA sur PC Deep.
- Jour 2 : Setup ROS/robots ; Test StreamDeck.
- Jour 3 : Mock interactions ; Schémas Excalidraw.

**Problèmes globaux à aborder** :
- Techniques : CUDA bugs, latence, calibration (solutions : tests, fallbacks).
- Temps : Overrun → priorisez core.
- Matos : Indispo école → Plan B sans Baxter.
- Offline : Modèles pré-installés (préparez liste).
- Outils : Si Excalidraw lent, fallback Draw.io ; Exportez en PNG.

## Rendu Final (GitLab)

Créez un dépôt GitLab dédié. Structure :
- README.md : Ce sujet rempli avec vos propositions (storyboard, tableaux, schémas Excalidraw en PNG).
- Fichiers : Images PNG (storyboard, architecture via Excalidraw), snippets code tests, liste dépendances offline.
- Commit final avant fin des 3 jours.

**Critères d'évaluation** :
- Innovation/engagement public.
- Faisabilité (1 semaine/2 pers., offline).
- Qualité explications (problèmes/solutions).
- Clarté visuelle (storyboard, diagrammes Excalidraw).

**Ressources** :
- Excalidraw : Téléchargez version offline pour diagrammes architecture.
- ROS Baxter : Intera SDK (docs offline).
- Pepper : NAOqi SDK (clone repo offline).
- YOLO/Émotions : Modèles pré-téléchargés.
- Interface : Flask tutorial offline.

Contactez Fabrice Jumel via GitLab issues pour questions. Bonne chance pour cette démo WorldSkills des Métiers !

[1](https://docs.gitlab.com/user/markdown/)
[2](https://gitlab.com/gitlab-org/gitlab-ee/-/issues/10785)
[3](https://gitlab.univ-lille.fr/ls1-odi/portail/-/tree/master/3-markdown)
[4](https://gitlab.com/gitlab-com/www-gitlab-com/-/blob/release-13-8/doc/formatting_markdown.md)
[5](https://www-apps.univ-lehavre.fr/forge/help/user/markdown)
[6](https://faq.gutenberg-asso.fr/8_contribuer/methodes/webide.html)
[7](http://www.mathieupassenaud.fr/markdown-pdf/)
[8](https://docs.framasoft.org/fr/grav/markdown.html)
[9](https://gitlab.huma-num.fr/ecrinum/manuels/tutoriel-markdown-pandoc/-/blob/master/parcours/02_stylo.md)
