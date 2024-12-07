
# Advent of Code 2024

Bienvenue dans mon organisation GitHub dédiée au **Advent of Code 2024** ! 🎄 Chaque jour du mois de décembre, un nouveau challenge de programmation est publié, et ici, je partage mes solutions écrites en **C++**. Ce projet est autant un moyen de relever des défis qu'une opportunité d'améliorer mes compétences en algorithmie et en résolution de problèmes.

## Organisation des repositories

- Chaque jour de l'Advent of Code 2024 possède son propre repository.
- Les repositories sont nommés suivant le format : `X-NAME`, où `X` est le numéro du jour et `NAME` est le titre du challenge.
- Chaque repository contient :
  - **Une solution complète et fonctionnelle** au problème du jour.
  - **Un fichier de test** pour valider les solutions sur différents cas.
  - **Un fichier d'explication** (`EXPLANATION.md`) décrivant ma démarche pour résoudre le problème.

---

## Structure typique d'un repository

Chaque repository suit plus ou moins la structure suivante :

```
.
├── src/
│   ├── Main.cpp                  # Point d'entrée principal du programme
│   ├── ArgumentParser.(hpp/cpp)  # Classe pour parser les arguments de la ligne de commande
│   ├── FileReader.(hpp/cpp)      # Classe pour lire les fichiers d'entrée et extraire les données
│   └── SolutionName.(hpp/cpp)    # Classe principale pour résoudre le problème
├── input.txt                     # Données du problème fournies par AoC
├── build.ps1                     # Script PowerShell pour compiler le projet
└── CMakeLists.txt                # Configuration du projet pour CMake
```

---

## Technologies et outils utilisés

- **Langage principal** : C++
- **Compilateur** : `g++`, compatible avec les versions modernes de C++.
- **Système de build** : [CMake](https://cmake.org/), pour une gestion flexible des dépendances et de la compilation.
- **Gestion des versions** : Chaque repository est versionné pour tracer les évolutions et expérimentations.

---

## Installation et compilation

Pour compiler et exécuter les solutions, suivez ces étapes :

1. Clonez le repository du jour correspondant :
   ```bash
   git clone https://github.com/<organisation>/X-NAME.git
   cd X-NAME
   ```

2. Configurez et compilez avec CMake :
   ```bash
   ./build.ps1
   ```

3. Exécutez le programme :
   ```bash
   ./build/NAME input.txt [1|2]
   Où NAME est le nom du programme et 1 ou 2 est la partie du problème à résoudre.
   ```

---

## Progression

| Jour | Repository | Statut     |
|------|------------|------------|
| 1    | [Historian Hysteria](https://github.com/AdventOfCode2024-clevet/1-Historian-Hysteria) | ✔️ Complété |
| 2    | [Red Nosed Reports](https://github.com/AdventOfCode2024-clevet/2-Red-Nosed-Reports) | ✔️ Complété |
| 3    | [Mull It Over](https://github.com/AdventOfCode2024-clevet/3-Mull-It-Over) | ✔️ Complété |
| 4    | [Ceres Search](https://github.com/AdventOfCode2024-clevet/4-Ceres-Search) | ✔️ Complété |
| 5    | [Print Queue](https://github.com/AdventOfCode2024-clevet/5-Print-Queue) | ✔️ Complété |
| 6    | [Guard Gallivant](https://github.com/AdventOfCode2024-clevet/6-Guard-Gallivant) | ✔️ Complété |
| 7    | [Bridge Repair](https://github.com/AdventOfCode2024-clevet/7-Bridge-Repair) | ✔️ Complété |

---

## Objectifs et apprentissages

En participant à l'Advent of Code 2024, je vise à :
- **Améliorer mes compétences en programmation C++**, en explorant des algorithmes et structures de données avancés.
- **Renforcer mes capacités d’analyse de problèmes**, en résolvant des défis variés.
- **M’entraîner à écrire un code propre et maintenable**, en appliquant les principes de bonne pratique.

---

## Ressources utiles

- [Site officiel de l'Advent of Code](https://adventofcode.com/2024)
- [Documentation C++](https://en.cppreference.com/)
- [Tutoriels sur CMake](https://cmake.org/documentation/)

---

## Contribution

Les solutions sont purement personnelles et reflètent mon approche pour résoudre les problèmes.
Si vous souhaitez échanger des idées ou partager vos solutions, n’hésitez pas à me contacter !

**Bon coding et joyeux Advent of Code !**
