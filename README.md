# DiceRoller 🎲

**DiceRoller** est une application Android moderne, interactive et simple qui permet de lancer un dé à 6 faces d'un simple clic. Ce projet a été développé en **Kotlin** en utilisant **Jetpack Compose** pour l'interface utilisateur, suivant les principes modernes de développement Android préconisés par Google.

---

## Fonctionnalités

- **Jet de dé interactif** : Cliquez sur le bouton "Lancer" (ou "Roll") pour obtenir un chiffre aléatoire entre 1 et 6.
- **Interface Réactive** : L'affichage change de manière fluide et instantanée avec l'image correspondante au résultat du dé.
- **Design Moderne** : Utilise le thème Material Design 3.
- **Edge-to-Edge** : L'application utilise tout l'écran de l'appareil (barres de système transparentes).

---

## Stack Technique

- **Langage** : [Kotlin]
- **UI Framework** : [Jetpack Compose
- **Minimum SDK** : API 24 (Android 7.0 Nougat)
- **Target SDK** : API 35 (Android 15)
- **Build System** : Gradle (Kotlin DSL - `.kts`)
- **Compatibilité Java** : Java 11

## Structure du Projet

Voici les principaux composants du projet :

- **[`MainActivity.kt`](Diceroller/app/src/main/java/com/example/diceroller/MainActivity.kt)** : Contient l'activité principale ainsi que les fonctions composables de l'application (`DiceRollerApp` et `DiceWithButtonAndImage`).
- **[`Theme.kt`](Diceroller/app/src/main/java/com/example/diceroller/ui/theme/Theme.kt)** : Configuration du thème de l'application (couleurs, typographie, etc.) utilisant Material 3.
- **Ressources (`res/drawable`)** : Contient les images vectorielles et matricielles des 6 faces du dé (`dice_1` à `dice_6`).
