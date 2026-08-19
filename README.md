# CANALSAT-ANDROID-TV-RETRO
Une application Android TV moderne bâtie avec Jetpack Compose offrant une interface retro de la box emblématique +Le Cube de Canal+ native, fluide et personnalisable pour Canal+, Netflix et Disney+. Optimisée pour le contrôle à la télécommande, elle transforme l'expérience web en une véritable expérience de décodeur TV."
Une interface TV moderne et fluide développée avec **Jetpack Compose (TV Material 3)**, conçue pour transformer l'expérience de navigation web de Canal+ en une véritable expérience de décodeur natif pour Android TV.

## 🚀 Fonctionnalités

- **Interface Native TV** : Entièrement construite avec les derniers composants Compose pour TV, offrant fluidité et esthétique.
- **Moteur Hybride** : Utilise une `WebView` optimisée en arrière-plan pour diffuser le contenu réel de Canal+, tout en masquant la complexité du site web derrière une UI élégante.
- **Zapliste Rapide** : Accès instantané à une liste de chaînes verticale avec prévisualisation et mémorisation de la dernière chaîne regardée (Démarrage sur TF1 par défaut).
- **Menu Services (Style Canal+)** : Un écran "Mes Services" dédié regroupant Le Guide, Replay, Canal+ à la demande, Foot+, etc.
- **Infos Programme Détaillées** : Interface d'information complète incluant le titre, le synopsis, les horaires, la durée et une barre de progression en temps réel.
- **Multi-Services** : Intégration directe de **Netflix** et **Disney+** au sein de la navigation.
- **Automatisation du Login** : Page de connexion personnalisée en format 16:9 qui injecte automatiquement les identifiants dans le portail web.

## 🎮 Contrôle à la Télécommande (Mapping Nokia)

L'application est optimisée pour les télécommandes Android TV (testée sur Nokia Remote) :

- **INFO (Rose)** : Affiche/Masque les détails du programme en cours.
- **Media (Vert clair)** : Gestion de la Pause / Lecture de la vidéo.
- **P+ / P- (Bleu foncé)** : Zapping rapide entre les chaînes.
- **ROUGE (Jaune)** : Raccourci pour afficher la barre de menu principale au milieu de l'écran.
- **VERT (Orange)** : Ouvre instantanément les **Paramètres Android TV** du système.
- **Pavé Numérique (0-9)** : Zapping direct vers une chaîne via son numéro.
- **BACK** : Navigation intelligente pour fermer les menus un par un.

## 🛠 Installation

1. Téléchargez l'APK depuis le dossier `APK qui est build`.
2. Installez-le sur votre Android TV ou Box TV.
3. Connectez-vous avec vos identifiants Canal+ lors du premier lancement.

## 💻 Tech Stack

- **Langage** : Kotlin
- **UI Framework** : Jetpack Compose (androidx.tv.material3)
- **Backend** : WebView avec injection JavaScript (CanalBridge)
- **Persistence** : SharedPreferences pour les réglages et l'état de connexion.
- **Network** : Navigation Web hybride.

---
*Développé pour une expérience TV ultime.*
