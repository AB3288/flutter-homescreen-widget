#  Flutter Home Screen Widget

Un projet Flutter démontrant comment créer des **widgets d'écran d'accueil** pour Android, basé sur le codelab officiel Google.

[![Google Developer Badge](https://img.shields.io/badge/Google%20Developer-Apprentissage%20Badge-blue?logo=google)](https://developers.google.com/profile)
[![Flutter](https://img.shields.io/badge/Flutter-3.x-02569B?logo=flutter)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.x-0175C2?logo=dart)](https://dart.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

##  Aperçu

L'application affiche une liste d'articles d'actualité. Un widget d'écran d'accueil affiche le titre, la description et un graphique de l'article sélectionné.

---

##  Fonctionnalités

-  Liste d'articles d'actualité
-  Widget d'écran d'accueil Android
-  Mise à jour du widget depuis l'application Flutter
-  Affichage d'un graphique Flutter comme image dans le widget
-  Partage de données via `SharedPreferences` (package `home_widget`)

---

##  Technologies utilisées

| Technologie | Usage |
|-------------|-------|
| Flutter | Framework principal |
| Dart | Langage de programmation |
| Kotlin | Code natif Android |
| `home_widget ^0.9.0` | Communication Flutter ↔ Widget |
| `shared_preferences ^2.5.4` | Stockage local |
| Genymotion | Émulateur Android |

---

##  Structure du projet

```
step_03/
├── lib/
│   ├── main.dart               # Point d'entrée
│   ├── home_screen.dart        # Écran principal + updateHeadline()
│   ├── article_screen.dart     # Écran article + renderFlutterWidget()
│   └── news_data.dart          # Données fictives
├── android/
│   └── app/src/main/
│       ├── AndroidManifest.xml           # Déclaration du receiver
│       ├── kotlin/.../NewsWidget.kt      # Widget Android natif
│       └── res/
│           ├── layout/news_widget.xml    # Layout du widget
│           └── xml/news_widget_info.xml  # Config du widget
└── pubspec.yaml
```

---

##  Installation

### Prérequis

- Flutter SDK installé
- Genymotion ou un appareil Android
- VSCode ou Android Studio

### Étapes

```bash
# Cloner le repo
git clone https://github.com/VOTRE_USERNAME/flutter-homescreen-widget.git
cd flutter-homescreen-widget

# Installer les dépendances
flutter pub get

# Lancer l'application
flutter run
```

---

##  Étapes du codelab réalisées

| Étape | Description | Statut |
|-------|-------------|--------|
| 3 | Créer un widget d'écran d'accueil de base | ✅ |
| 4 | Envoyer des données Flutter au widget | ✅ |
| 6 | Afficher un widget Flutter comme image | ✅ |

---

##  Comment tester le widget

1. Lancer l'app avec `flutter run`
2. Sur Genymotion ou Android studio, faire un **appui long** sur l'écran d'accueil
3. Sélectionner **Widgets** → chercher **homescreen_widgets**
4. Ajouter le widget à l'écran d'accueil
5. Ouvrir un article dans l'app → appuyer sur **"Update Homescreen"**
6. Le widget affiche le titre, la description et le graphique ! 

---

##  Badge Google Developer

Ce projet a été réalisé dans le cadre du codelab officiel Google :

> **[Adding a Home Screen widget to your Flutter App](https://codelabs.developers.google.com/flutter-home-screen-widgets)**
>
> Badge **Apprentissage** obtenu le 3 avril 2026 🎖️

---

##  Ressources

- [Documentation Flutter](https://docs.flutter.dev)
- [Package home_widget](https://pub.dev/packages/home_widget)
- [Codelab officiel Google](https://codelabs.developers.google.com/flutter-home-screen-widgets)
- [Documentation Android App Widgets](https://developer.android.com/develop/ui/views/appwidgets)

---

##  Auteur

**Abdallahi**
- GitHub: [@AB3288](https://github.com/AB3288)
- Google Developer Profile: [Mon profil]([https://developers.google.com/profile](https://developers.google.com/profile/u/115985114902930184863?hl=fr))

---

*Projet réalisé avec ❤️ et Flutter*
