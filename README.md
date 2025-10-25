# Jeu de réflexion "Solitaire" – Projet C++

Ce projet est une implémentation en **C++** du jeu de réflexion *Solitaire* (ou jeu de billes).
L’objectif est de déplacer les billes sur un plateau de 7x7 cases afin de ne laisser qu’une seule bille à la fin.

---

## 🎯 Objectif du jeu
Le joueur déplace une bille qui saute par-dessus une autre bille adjacente (horizontalement ou verticalement).
La bille sautée est retirée du plateau.
Le joueur gagne lorsqu’il ne reste qu’une seule bille.

---

## ⚙️ Fonctionnalités principales
- Plateau 7x7 (37 cases valides)
- Détection des coups valides
- Affichage du plateau en console
- Possibilité d’annuler un coup (undo)
- Fin de partie automatique (gagné ou perdu)

---

## 🧠 Langage et outils
- **Langage :** C++
- **Compilation :** g++ ou tout autre compilateur compatible C++11 ou supérieur
- **Interface :** Console
/** \brief
 *
 * \param
 * \param
 * \return
 *
 */

---

## ▶️ Compilation et exécution

### Pour compiler :
```bash
g++ -std=c++17 main.cpp -o solitaire
