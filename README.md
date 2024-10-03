# quiz_app_repository# Application de quiz

## Aperçu
L'application **Quiz App** est une application basée sur Flutter conçue pour tester les connaissances des utilisateurs à travers une série de questions de quiz. L'application offre une interface intuitive, des visuels attrayants et suit les scores les plus élevés obtenus par les joueurs.

## Caractéristiques
- **Écran de démarrage** : lance l'expérience du quiz avec un message de bienvenue et un bouton « Démarrer le quiz ».
- **Écran de questions** : affiche une question à la fois, permettant aux utilisateurs de sélectionner leurs réponses.
- **Écran de résultats** : Affiche les résultats après avoir terminé le quiz, y compris le nombre de réponses correctes et le meilleur score.
- **Résumé des réponses** : Fournit un résumé des questions auxquelles il a été répondu, en mettant en évidence les réponses correctes et incorrectes.
- **Fonctionnalité de redémarrage** : permet aux utilisateurs de redémarrer le quiz et de tenter de battre leur meilleur score précédent.

## Structure du fichier

/quizz_app
- main.dart # Point d'entrée de l'application
- start_screen.dart # Widget pour l'écran de démarrage
- questions_screen.dart # Widget pour afficher les questions
- results_screen.dart # Widget pour afficher les résultats
- answer_button.dart # Widget pour le bouton de réponse
questions_summary/ # Dossier contenant les widgets liés au résumé
- question_identifier.dart # Widget pour les identifiants de questions
- summary_item.dart # Widget pour les éléments de résumé individuels
- questions_summary.dart # Widget pour le résumé des questions
données/
- questions.dart # Contient les questions et réponses du quiz
- pubspec.yaml # Configuration du package

## Commencer
Prérequis
Flutter SDK installé sur votre machine.
Un IDE tel que Android Studio, VS Code ou IntelliJ IDEA.

## Installation
**Cloner le dépôt :**
git clone <url-du-dépôt>
cd quizz_app

## Installer les dépendances :
Pub Flutter

## Exécutez l'application :
course de flottement

## Utilisation
- Lancez l'application pour voir l'écran de démarrage.
- Appuyez sur le bouton « Démarrer le quiz » pour commencer.
- Sélectionnez les réponses pour chaque question présentée.
- Une fois toutes les questions répondues, examinez les résultats, y compris le meilleur score.
- Utilisez le bouton « Redémarrer le quiz » pour reprendre le quiz.

## Contribuer
Les contributions sont les bienvenues ! N'hésitez pas à soumettre une demande d'extraction ou à ouvrir un ticket pour toute amélioration ou correction de bug.

## Licence
Ce projet est sous licence NTNU. Consultez le fichier [LICENSE](./LICENSE) pour plus de détails.
