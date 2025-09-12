# Bodycount :
# Introduction à Git & GitHub

Ce document résume les bases de **Git** et **GitHub**, leur utilité et les principales commandes à connaître.  

---

## 1. Pourquoi utiliser Git/GitHub ?

- **Git** : permet de sauvegarder et suivre l’historique de son travail en local.  
- **GitHub** : plateforme en ligne qui héberge les dépôts Git. Elle facilite la **collaboration** et le **partage** de projets entre plusieurs personnes.

---

## 2. En entreprise ? En cours ?

- **En entreprise** : travailler à plusieurs sur un même projet sans se gêner, gérer les différentes versions et contributions.  
- **En cours** : mieux s’organiser, partager ses projets et expérimenter des solutions sans risque.

---

## 3. Concepts clés

- **Dépôt (repository ou repo)** : dossier où est stocké le projet avec tout son historique.  
- **Commit** : une "photo" du projet à un instant donné, accompagnée d’un message de description.  
- **Branche** : une copie parallèle du projet utilisée pour tester ou développer de nouvelles fonctionnalités sans modifier la branche principale.

---

## 4. Exemple visuel simplifié

```text
 main (branche principale)
   |
 commit X
   |
   |----- (branche test)
         |
      commit TEST
```

---

## 5. Commandes Git de base

- `git init` → crée un nouveau dépôt Git dans un dossier local.  
- `git clone <url>` → copie un dépôt existant depuis GitHub.  
- `git add <fichier>` → prépare un fichier à être inclus dans le prochain commit.  
- `git commit -m "message"` → enregistre une version du travail (snapshot).  
- `git push` → envoie les commits locaux vers GitHub.  
- `git pull` → récupère les modifications présentes sur GitHub.  
- `git branch` → liste les branches existantes.  
- `git checkout <branche>` → change de branche.  
- `git merge <branche>` → fusionne une branche avec la branche courante.

---

## 6. Différence entre Git et GitHub

- **Git** :  
  - Logiciel local.  
  - Fonctionne sans connexion internet.  
  - Permet de suivre et gérer l’évolution d’un projet.  

- **GitHub** :  
  - Service en ligne basé sur Git.  
  - Nécessite une connexion internet.  
  - Permet le partage, la collaboration et la gestion centralisée des dépôts.
