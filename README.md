
# Sujet : Conception d'une Démo d'Interaction Homme-Robot dans le cadre du Mondiale des Métiers

## Contexte et Objectifs
Vous devez concevoir une démonstration d'interaction homme-robot (HRI) pour un stand "Concepteur d'Avenir" du Mondiale des  Métiers. Ce projet s'inspire de la participation de CPE LYON à un stand précédent, avec une démo utilisant le robot Baxter (intégrant son, position et émotions) et une démo IA (affichage YOLO pour détection d'objets + détection d'émotions sur les passants).

[![Version 2024 SETUP](https://img.youtube.com/vi/dU6WokFrbxE/0.jpg)](https://www.youtube.com/watch?v=dU6WokFrbxE?autoplay=1&mute=1)

[![Version 2024 SETUP](https://img.youtube.com/vi/4Uqp6coTVtw/0.jpg)](https://www.youtube.com/watch?v=4Uqp6coTVtw?autoplay=1&mute=1)

**Objectif principal** : Proposer une démo plus interactive avec le public, en exploitant le matériel disponible à l'école. L'interaction doit être engageante, éducative sur l'IA et la robotique, et adaptée à un contexte de salon (public varié, temps court par visiteur).

## Durée 
**Durée du projet** : 
- 3 jours pour la conception (storyboard, choix logiciels, architecture, interface).
- Tests optionnels sur le matériel disponible à l'école ou en votre possesion pendant ces 3 jours.
- La démo finale (non à implémenter ici) doit être réalisable en **1 semaine maximum pour 2 personnes**.
- Pas d'accès internet sur place : Tout doit être offline (modèles IA pré-téléchargés, développement local).

**Équipe** : Travail en Monome.

## Contraintes


- Rendu via votre dépôt GitLab , unn push doit être a minima effectué à chaque demi journée de travail.
- Focus sur l'explication des problèmes potentiels et solutions.
- Mettez l'accent sur un **Plan A** (idéal, innovant) et un **Plan B** (garanti en temps court, simple à développer).
- Utilisez GitLab Flavored Markdown (GLFM) pour le README.md, compatible avec tables, diagrammes (via Excalidraw PNG en incluant le code générateur)


## Matériel Disponible

Utilisez ce qui est listé ; vous pouvez proposer d'ajouter des écrans ou autres équipements disponibles à l'école.

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
Proposez et justifiez les outils logiciels (open-source, offline). Justifiez la compatibilité Ubuntu/CUDA/ROS. Expliquer les besoins en ressources et dépendances logicielles

- **Composants clés** :
  - IA : Détection objets/émotions. Generation
  - Robots : Contrôle Baxter/Pepper.
  - Interface : Web offline + StreamDeck ou autre à proposer + Son
  - Impression

### 3. Proposition d'Interface
Proposez une interface utilisateur (ex. : web + StreamDeck Mini pour opérateur+ son par exemple ). Faites une proposition pour l'ensemble des briques d'interactions.



### 4. Définition de l'Architecture
Définissez le système global (hardware/software). **Utilisez Excalidraw pour les schémas d'architecture** et inclure les sources des diagrammes



## Plans A et B

- **Plan A (Idéal)** : Interaction riche . Temps : 1 semaine (40h/2 pers.).
- **Plan B (Garantie)** : Version basique . Temps : 3-4 jours, fallback si matos indisponible.

Expliquez pourquoi Plan B est robuste. Utilisez Excalidraw pour comparer les deux plans (diagramme side-by-side).

##Début de tests préliminares des solutions 
Montrer les retartds et logs 

## Rendu Final (GitLab)

Créez un dépôt GitLab dédié. Structure :
- README.md : Ce sujet rempli avec vos propositions (storyboard, tableaux, schémas Excalidraw en PNG).
- Fichiers : Images PNG (storyboard, architecture via Excalidraw), code testés, 
- Commit final pour le mardi 2 décembre 23H00

**Critères d'évaluation** :
- Innovation/engagement public.
- Faisabilité (1 semaine/2 pers., offline).
- Qualité explications (problèmes/solutions).
- Clarté visuelle (storyboard, diagrammes Excalidraw).
- Tests
-  **Anticipation** : Expliquez les problèmes potententiels et solutions.

**Attention** :
- ROS Baxter : attention ROS 1 / veille version de ubuntu <10. Impossible de faire des mises à jour du linux . eviter l'usage d'un apt install ou equivalent 
- Pepper : NAOqi / python 2.7.9

**Banque de son de la demo 2024** :

😊 Émotions positives
- happy

👏 Réactions enthousiastes
- applause

😢 Émotions négatives
- sad
- worry

🤔 Gestes ou sons de réflexion
- scratch-head
- wait

😲 Surprise
- surprised

**Banque de mouvementde la demo 2024**

🖐 Mouvements des mains
- hands_down.bag, hands_down_m.bag
- hands_up.bag, hands_up_m.bag
- hands_head2.bag, hands_head2_m.bag
- give_hand2.bag, give_hand2_m.bag
- grip2.bag, grip2_m.bag

👋 Salutations et gestes
- hi.bag, hi_m.bag
- wave_hello.bag, wave_hello2.bag, wave_hello_m.bag
- wave_big.bag, wave_big2.bag, wave_big_m.bag, wave_big2_m.bag
- applause2.bag, applause2_m.bag

🤗 Interactions sociales
- hug.bag, hug_m.bag
- jose.bag, jose2.bag, jose3.bag, jose_m.bag, jose2_m.bag, jose3_m.bag
- nico.bag, nico_m.bag

🤷 Expressions d'incertitude
- dont_know.bag, dont_know2.bag, dont_know3.bag
- dont_know_m.bag, dont_know2_m.bag, dont_know3_m.bag

🤔 Gestes de réflexion ou de démonstration
- look_hand.bag, look_hand2.bag, look_hand_m.bag, look_hand2_m.bag
- scratch_head.bag, scratch_head_m.bag, scratch_test_m.bag
- nescratch.bag, nescratch_m.bag
- open2.bag, open2_m.bag
- open_wide2.bag, open_wide2_m.bag
- explain_left.bag, explain_left_m.bag

😐 Postures neutres
- neutral.bag, neutral_m.bag
- neutral3.bag, neutral3_m.bag
- neutral_open2.bag, neutral_open2_m.bag
- neutral_hand2.bag, neutral_hand2_m.bag
- neutral_point2.bag, neutral_point2_m.bag
- neutral_down2.bag

💪 Mouvements des bras
- arms.bag, arms_m.bag
- arms2.bag, arms2_m.bag

😊 Émotions positives
- happy.bag, happy-sav-test.bag, happy-sav-test_migrated.bag, happy_m.bag

⏳ Attente ou pause
- wait2.bag, wait2_m.bag
- test.bag



