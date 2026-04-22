🧬 Jeu de la Vie — Simulation & POO en C++

Simulation complète de l'automate cellulaire de John Conway, développée en C++ avec une double interface : console et graphique.


👥 Équipe
Projet réalisé en équipe de 3 dans le cadre de la formation ingénieur au CESI :

Matis Lavignac
Arthur Duret
Baptiste Ceccaldi


🎯 Description
Le Jeu de la Vie est un automate cellulaire imaginé par le mathématicien John Conway en 1970. Une grille de cellules évolue génération après génération selon des règles simples, produisant des comportements émergents complexes.
Ce projet implémente une simulation complète avec :

Un mode console optimisé
Un mode graphique interactif via SFML
Des cellules obstacles (règles spéciales)
Un système de fichiers de configuration pour charger/sauvegarder des états


🛠️ Stack technique
TechnologieUsageC++17Langage principalSFMLRendu graphiqueSTLStructures de donnéesUMLModélisation (classes, séquences, cas d'utilisation)Git / GitHubVersionnement

🏗️ Architecture
Le projet suit les principes SOLID et une architecture orientée objet modulaire :
├── src/
│   ├── Grille.cpp / Grille.h       ← Logique de la simulation
│   ├── Cellule.cpp / Cellule.h     ← États et règles des cellules
│   ├── ModeConsole.cpp             ← Affichage terminal
│   └── ModeGraphique.cpp           ← Rendu SFML
├── config/
│   └── *.txt                       ← Fichiers de configuration (états initiaux)
└── tests/
    └── ...                         ← Tests unitaires

🚀 Lancer le projet
Prérequis

Compilateur C++17 (g++)
SFML 2.5+
make

Compilation & exécution
bashmake        # Compile le projet
make run    # Compile et lance directement
make clean  # Supprime les fichiers compilés

Au lancement, choisissez le mode console ou graphique, puis chargez un fichier de configuration ou générez une grille aléatoire.


🧠 Compétences mobilisées

Programmation Orientée Objet (C++, principes SOLID)
Modélisation logicielle (UML)
Bibliothèque graphique SFML
Tests unitaires
Travail collaboratif (Git/GitHub)


📸 Screenshots

À venir


Projet réalisé dans le cadre de la formation Diplôme d'Ingénieur — CESI (nov. 2025 – jan. 2026)
