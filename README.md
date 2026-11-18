 L'Encyclopédie des Jeux de Cartes Classiques

Application web statique (fichier unique autonome) répertoriant 75 jeux de cartes traditionnels, réussites et adaptations modernes, tous jouables exclusivement avec 1 ou 2 jeux de cartes standards de 52/54 cartes (sans cartes spéciales, atouts dédiés ni plateau).

✨ Fonctionnalités principales

75 jeux classés par ordre alphabétique strict (A–Z & 0–9) répartis en 6 grandes familles :

Levées & Plis (Belote, Coinche, Bridge, Barbu, Briscola, Écarté, Euchre, Jass, Manille, Piquet, Spades, Whist, etc.)

Défausse & Combinaisons (Rami, Gin Rami, Canasta, Président, Dourak, 8 Américain, Scopa, Yaniv, Tamalou, Mao, etc.)

Casino & Bluff (Poker, Blackjack, Cribbage, Menteur, Truco)

Duel & Réflexes (Bataille, Bataille Corse, Crapette, Double solitaire, Kem's, Nerts, Snap !, Speed / Spit)

Adaptations 52 cartes (Régicide, Trio, Lucky Numbers, Fox in the Forest, Fugitive, Brawl, Gobblet, Hanamikoji)

Solitaires & Réussites (Klondike, FreeCell, Spider, Pyramide, Golf, TriPeaks, Scorpion, Yukon, Calcul, Horloge, etc.)

Guide de préparation pour jeu de 52/54 cartes : chaque fiche détaille exactement quelles cartes conserver ou écarter (24, 32, 36, 40, 43, 48, 51, 52 ou 54 cartes).

Recherche & Filtres multi-critères : filtrage instantané par mot-clé, catégorie, nombre de joueurs (1, 2, 3–4, 5+), matériel (1 jeu ou 2 jeux) et index alphabétique rapide.

Double affichage : bascule instantanée entre Vue Cartes et Vue Tableau comparatif.

Modale de règles accessible & Tirage au sort : règles complètes (but, mise en place, déroulement, hiérarchie, décompte), navigation clavier (←, →, Échap) et bouton « Piocher un jeu au hasard ».

Interface épurée : conçue avec le micro-framework CSS Primitive UI de Tania Rascia, sans dépendance JavaScript externe.

🚀 Déploiement sur GitHub Pages

Renommez le fichier HTML principal en index.html à la racine de votre dépôt GitHub.

Placez ce fichier README.md à la racine du dépôt.

Dans votre dépôt GitHub, ouvrez Settings → Pages.

Sous Build and deployment, sélectionnez la branche main et le dossier / (root), puis cliquez sur Save.

Votre site sera accessible à l'adresse : https://<votre-identifiant>.github.io/<nom-du-depot>/.

📁 Structure du projet

.
├── index.html   # Application complète (HTML5, CSS Primitive UI, base de données JS des 75 jeux)
└── README.md    # Documentation du projet et historique des versions


🏷️ Versioning (SemVer)

Ce projet suit la convention de gestion de versions sémantiques Semantic Versioning 2.0.0 (MAJEUR.MINEUR.CORRECTIF).

[v1.3.0] — 2026-11-18

Ajout : Intégration de 24 jeux supplémentaires jouables avec 1 ou 2 paquets standards (500, 99, Asec, Bésigue, Brawl, Briscola, Cassino, Double solitaire, Écarté, Euchre, Fox in the Forest, Fugitive, Gin Rami, Gobblet, Hanamikoji, Lucky Numbers, Mao, Nerts, Piquet, Rami-500, Spades, Speed / Spit, Trio, Truco), portant le total à 75 jeux.

Ajout : Tri alphabétique strict (localeCompare('fr')) de l'ensemble du catalogue et barre d'indexation rapide 0–9 / A–Z.

Ajout : Navigation Jeu précédent / Jeu suivant (boutons et flèches clavier) directement dans la modale de règles.

[v1.2.0] — 2026-11-18

Modification : Filtrage strict du répertoire pour retirer les jeux nécessitant des cartes spéciales, des atouts dédiés ou un plateau (Tarot, Ganjifa, Aluette, Nain Jaune, 7 Familles, Koi-Koi).

Modification : Mise en page migrée vers le framework Primitive UI avec ajout de la Vue Tableau (.striped-table).

[v1.1.0] — 2026-11-18

Ajout : Mention explicite sous le titre principal indiquant la compatibilité universelle avec un jeu traditionnel de 52 cartes et bloc « Préparation 52 cartes » sur chaque fiche.

Suppression : Retrait du carnet de scores latéral pour recentrer l'interface sur la consultation des règles.

[v1.0.0] — 2026-11-18

Initialisation : Première version de l'encyclopédie interactive en fichier HTML autonome avec recherche, filtres par catégorie/joueurs/paquet, tirage au sort et modales de règles détaillées.
