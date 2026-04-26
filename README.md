# 🌌 TP2 : Systèmes Non Linéaires - Plan de Phase & Van der Pol

**Institution :** U.S.T.H.B / F.G.E. - Département d'Automatique  
**Module :** Systèmes Non Linéaires (Année universitaire 2025-2026)  
**Auteur :** DAHANE AHMED LAMINE  

---

## 📋 Description du Projet

Ce projet est une application web interactive "Single-Page" (SPA) développée pour fournir une solution complète, visuelle et dynamique au TP N°2 portant sur l'analyse des systèmes non linéaires. Il offre une exploration approfondie de la modélisation sous Simulink (gestion des boucles algébriques) et de l'intégration numérique de l'oscillateur de Van der Pol dans le plan de phase.

Conçu avec une interface utilisateur moderne de type *Glassmorphism* sur le thème **"Deep Space"**, ce tableau de bord fusionne la théorie mathématique, la simulation en temps réel et les codes sources de référence.

## ✨ Fonctionnalités Principales

* **📘 Théorie Intégrée :** Explications détaillées des transformations d'état et des mathématiques sous-jacentes (systèmes couplés, boucles algébriques).
* **📐 Modélisation Simulink Vectorielle :** Représentation graphique SVG interactive et précise du schéma bloc avec mise en évidence des chemins de retour (feedback) et des intégrateurs.
* **⚙️ Moteur Physique Temps Réel (RK4) :** Solveur mathématique personnalisé écrit en JavaScript natif utilisant la méthode de Runge-Kutta d'ordre 4 pour résoudre l'oscillateur de Van der Pol directement dans le navigateur.
* **📊 Visualisation Interactive :** Rendu dynamique du plan de phase et du champ de vecteurs via **Plotly.js**, répondant instantanément aux modifications des paramètres par l'utilisateur (friction $\mu$ et conditions initiales $x_1$, $x_2$).
* **💻 Code Source MATLAB :** Inclusion du script MATLAB de référence utilisant la fonction `ode45` pour balayer les multiples conditions du cahier des charges et valider les résultats de l'application web.

## 🚀 Instructions d'Utilisation

L'application est totalement autonome et ne nécessite aucune installation de serveur ou de dépendances complexes en local.

1.  **Télécharger** le fichier principal `index.html` (ou le nom que vous lui avez donné).
2.  **Ouvrir** le fichier avec n'importe quel navigateur web moderne (Chrome, Firefox, Edge, Safari).
3.  **Interagir** avec le panneau de contrôle pour modifier le paramètre de non-linéarité ($\mu$) et les conditions initiales afin d'observer la convergence vers le cycle limite dans l'espace des phases.

## 🛠️ Technologies Utilisées

* **Structure & Style :** HTML5, CSS3 (Variables CSS, Flexbox/Grid, Animations, Glassmorphism).
* **Logique Dynamique :** JavaScript (Vanilla ES6+).
* **Rendu Graphique Mathématique :** [Plotly.js](https://plotly.com/javascript/).
* **Dessin Vectoriel :** SVG Intégré.

---
*Ce projet a été réalisé dans le cadre des travaux pratiques d'ingénierie en automatique.*
