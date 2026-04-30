# 🎮 Jeu de Devinette en Java

## 📌 Description

Ce projet est une application Java simple qui permet à l'utilisateur de deviner un nombre aléatoire compris entre **1 et 100**.

Le joueur dispose de **10 essais maximum** pour trouver le bon nombre. Après chaque tentative, le programme indique si le nombre proposé est **trop grand** ou **trop petit**.

---

## 🎯 Objectifs pédagogiques

* Manipuler les structures de contrôle (boucle `while`, conditions `if`)
* Utiliser les classes `Scanner` et `Random`
* Comprendre la logique d’un jeu interactif en console
* Gérer les entrées utilisateur

---

## ⚙️ Fonctionnalités

✔ Génération d’un nombre aléatoire
✔ Saisie utilisateur via le clavier
✔ Indication "trop grand" / "trop petit"
✔ Limite de 10 essais
✔ Message de victoire 🎉 ou de défaite ❌

---

## 🛠️ Technologies utilisées

* Java
* `java.util.Scanner`
* `java.util.Random`

---

## ▶️ Exécution du programme

### 1. Compiler le programme

```bash
javac src/JeuDevinette.java
```

### 2. Lancer le programme

```bash
java -cp src JeuDevinette
```

---

## 📁 Structure du projet

```
JeuDevinette/
│── src/
│   └── JeuDevinette.java
│── README.md
│── .gitignore
```

---

## 🖥️ Exemple d'exécution

```
=== Jeu de Devinette ===
Devinez un nombre entre 1 et 100
Vous avez 10 essais.

Entrez votre nombre : 50
Trop grand !

Entrez votre nombre : 25
Trop petit !

🎉 Bravo ! Vous avez trouvé en 3 essais.
```

---

## 🚀 Améliorations possibles

* Ajouter un mode difficulté (facile / moyen / difficile)
* Permettre de rejouer
* Gérer les erreurs (si l’utilisateur entre du texte)
* Ajouter une interface graphique (JavaFX ou Swing)

---

## 👨‍💻 Auteur

**DIEKET ABY IVAN ERWIN TRINITÉ**

---

## ✅ Statut

✔ Projet fonctionnel
✔ Code commenté
✔ Prêt à être exécuté et évalué

---
