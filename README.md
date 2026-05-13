# Bienvenue sur mon GitHub !

Voici une description d'une partie de mes différents projets informatiques 🎇

## 🚀 Mes Projets Phares

### 🎮 Projet Jeu C# & Sérialisation XML
*Description courte : Développement d'un moteur de jeu avec un système de sauvegarde complexe via la sérialisation et la désérialisation de fichiers XML.*
> **Lien vers le repo :** [Voir le code ici](https://github.com/l3miage-medinap/Jeu_Csharp_Xml)
> 
-> -> -> Cliquez ci-dessous pour quelques détails et images du projet <- <- <-
<details>
  Pour ce projet, nous devions concevoir un jeu en C#, utilisant les différentes méthodes de récupération et d'écriture XML (XSD, XSLT, sérialisation, Parser DOM, etc.).

  Nous avons choisi de le développer sur JetBrains à l'aide du module de gestion de textures MonoGame (https://monogame.net/), également utilisé pour de nombreux jeux en pixel art ! Interface finale obtenue :
<img width="1916" height="1132" alt="Capture d’écran 2026-05-08 194709" src="https://github.com/user-attachments/assets/80683da6-f2fe-4ebe-8309-cfbd6620dde9" />

  Nous avons donc fait le choix de concevoir un jeu de donjon où le joueur évolue sur une carte et a la possibilité d'entrer dans différents portails, par exemple dans le manoir d'un sorcier (décidément fin connaisseur du XML) :
<img width="1907" height="1145" alt="Capture d’écran 2026-05-08 154217" src="https://github.com/user-attachments/assets/697c610b-199c-4857-b6be-dfe1fe19b3f1" />

La première difficulté résidait dans la gestion des différentes textures :
<img width="1162" height="537" alt="Capture d’écran 2026-05-08 154514" src="https://github.com/user-attachments/assets/fc90ef4f-b178-4f64-bb54-ccc40800f67e" />

Nous avons ensuite mis en place un système de sauvegarde des différentes caractéristiques du joueur : appel de la fonction C# visible ci-dessus après le texte "charger données". 

Dont voici une petite partie de la classe : <img width="1532" height="767" alt="Capture d’écran 2026-05-08 160418" src="https://github.com/user-attachments/assets/fa9f2294-36cb-4085-aeca-038c5e4a6b63" />
Et le XML associé : <img width="1425" height="682" alt="Capture d’écran 2026-05-08 160450" src="https://github.com/user-attachments/assets/6989163e-6c41-42b4-9dae-452fb7534ece" />

Pour réaliser notre souhait d'avoir différents donjons, nous avons créé la classe Lieu permettant l'affichage de différentes textures et dialogues/actions en fonction du "lieu visité" : <img width="1670" height="691" alt="Capture d’écran 2026-05-08 155418" src="https://github.com/user-attachments/assets/ab3d55ac-a0bf-4abf-b029-312bedca5086" />

Une de nos grandes difficultés fut de créer des actions dans les donjons et de faire attendre l'exécution pour éviter qu'il n'exécute tout à la chaîne sans s'arrêter. <img width="1915" height="1132" alt="Capture d’écran 2026-05-08 154113" src="https://github.com/user-attachments/assets/2d294d07-ac32-41ef-8687-abd2e308967b" />

Il a également fallu créer le joueur comme un objet déplaçable et gérer l'affichage d'une texture "en plus" de la carte de départ, ainsi que différents soucis de complexité que vous pouvez découvrir, si vous le souhaitez, en lisant le document explicatif du repository en question !

</details>

---

### 📊 Projet Analyse de Data et Graphes Statistiques
*Description courte : Traitement de jeux de données massifs et génération de visualisations graphiques pour extraire des tendances significatives.*
> **Lien vers le repo :** Pour Très bientot...
>
-> -> -> Cliquez ci-dessous pour quelques détails et images du projet <- <- <-

<details>
  Pour ce projet, j'ai eu à gérer de gigantesques flux de données (43 000 données) au format CSV, à l'aide du logiciel RStudio et du langage R associé.
  <img width="1912" height="1151" alt="Capture d’écran 2026-05-08 170002" src="https://github.com/user-attachments/assets/7ce76f5f-668a-4461-80da-6d99668de953" />

  Celui-ci consistait à analyser et faire un compte-rendu en fonction d'immenses jeux de données sur le baccalauréat. Notre problématique était : Le statut du candidat (localité, parcours, statut, sexe) influence-t-il sa réussite au baccalauréat ?

  J'ai par exemple réalisé un audit des résultats au bac général en fonction de l'académie, pour la totalité des trente académies nationales : <img width="1885" height="1127" alt="Capture d’écran 2026-05-08 170307" src="https://github.com/user-attachments/assets/4d4b4fc5-7a9c-448d-898a-4044822b3ff1" />
  Un résultat que j'ai pu obtenir à l'aide du code ci-dessous utilisant les deux librairies tidyverse et ggplot2 : <img width="1512" height="747" alt="Capture d’écran 2026-05-08 170128" src="https://github.com/user-attachments/assets/c1268e9c-9063-4355-ba85-dd2206172984" /> Ce qui donne la représentation graphique suivante : <img width="1801" height="1112" alt="Capture d’écran 2026-05-08 170227" src="https://github.com/user-attachments/assets/e77c5671-ab4f-4038-afe1-f0913fb1fe93" />

  J'ai également pu tracer des graphiques se concentrant sur quelques académies : graphe : <img width="1917" height="892" alt="Capture d’écran 2026-05-08 170458" src="https://github.com/user-attachments/assets/ac8a4553-1bb7-477e-8008-06437c3b9d94" /> code associé :
<img width="1917" height="1147" alt="Capture d’écran 2026-05-08 170439" src="https://github.com/user-attachments/assets/62e93222-244f-45bc-aee9-4e042e3e4957" />

</details>

---

### 🗄️ Projet Base de Données SQL
*Description courte : Conception complète d'une architecture de données, incluant la migration, la création de tables optimisées et la mise en place de vues complexes.*
> **Lien vers le repo :** [Voir le code ici](https://github.com/l3miage-medinap/Projet_Base_Donn-es_SQL)
>
-> -> -> Cliquez ci-dessous pour quelques détails et images du projet <- <- <-
<details>
  Lors de ce projet, j'ai eu à récupérer une base de données incomplète et incohérente. J'ai pour cela utilisé DB Browser (SQLite) qui est une application de gestion de base de données et de requêtes SQL. 

  Pour commencer, j'ai dû refaire la conception initiale de ma base en repensant les logiques métiers et les besoins des utilisateurs, notamment en redéfinissant ce qui est admissible comme format dans la base (domaine) ainsi que les différentes contraintes : <img width="1917" height="925" alt="Capture d’écran 2026-05-08 162224" src="https://github.com/user-attachments/assets/9c748729-e189-4605-a7ed-809774b877a8" />

  Ensuite, une fois les contraintes comprises, j'ai créé une nouvelle base destinée à accueillir ces données de façon cohérente : <img width="1917" height="1100" alt="Capture d’écran 2026-05-08 163526" src="https://github.com/user-attachments/assets/43b1e6dd-edf7-4465-a542-530054c58bd3" />

  Après avoir récupéré les données à l'aide de différents inserts et renommages de tables, j'ai achevé la création de la table et mis en place mes différentes vues (demandées par le client) : <img width="1895" height="1011" alt="Capture d’écran 2026-05-08 163504" src="https://github.com/user-attachments/assets/670fdd79-4093-4f5b-b780-373a469accbf" />

</details>

---

### 🧮 Projet "Calculatrice" intelligente par Arbre d'Analyse Syntaxique en C
*Description courte : Implémentation d'un parseur capable de résoudre des expressions mathématiques complexes en utilisant des structures d'arbres syntaxiques.*
> **Lien vers le repo :** [Voir le code ici](https://github.com/l3miage-medinap/ProjetC_CalculatriceParAnalyseSyntaxique)
>
-> -> -> Cliquez ci-dessous pour quelques détails et images du projet <- <- <-

<details>
  Pour ce projet, nous devions concevoir une calculatrice intelligente capable de stocker et lire des variables ! 
  Exemple du rendu final : <img width="1811" height="1107" alt="Capture d’écran 2026-05-08 164958" src="https://github.com/user-attachments/assets/ad6e2635-7aa5-41b7-87d8-7499614a1b7f" />

  Pour cela, nous avons mis en place de nombreux états pour effectuer un tri et "comprendre" ce que nous étions en train de traiter (analyse lexicale). Nous avons également utilisé un arbre constituant l'expression reçue dans le but de découper celle-ci pour éviter d'accepter "1+-/2" (analyse syntaxique). 

  Fichier pour l'analyse lexicale : <img width="1877" height="1062" alt="Capture d’écran 2026-05-08 165616" src="https://github.com/user-attachments/assets/9b8c703a-2115-4a27-bfc8-cc51374517a0" />
  Fichier pour l'analyse syntaxique : <img width="1917" height="1022" alt="Capture d’écran 2026-05-08 165505" src="https://github.com/user-attachments/assets/2ef93917-7c8c-43e4-9043-ff1787fe710c" />

  Exemple d'une équation traitant les opérateurs arithmétiques basiques : <img width="1906" height="1122" alt="Capture d’écran 2026-05-08 165044" src="https://github.com/user-attachments/assets/f697e968-6429-416c-a777-9c24f97c11fa" />

 Exemple avec écriture et lecture de variables ainsi que if/else : <img width="1712" height="1110" alt="Capture d’écran 2026-05-08 164901" src="https://github.com/user-attachments/assets/037d021a-adf0-4e6c-8726-2e031d41f2f0" />

  N'hésitez pas à consulter, si vous le souhaitez, le repository associé !

</details>

---
 ### 🐍 Solveur et Créateur de Labyrinthe Python 
 *Description courte : Création d'une interface graphique Turtle dédiée à la génération et à la résolution de labyrinthes via des algorithmes d'exploration autonome.*
> **Lien vers le repo :** [Voir le code ici](https://github.com/l3miage-medinap/Solveur_Createur_Labyrinthe_Python)
> 
-> -> -> Cliquez ci-dessous pour quelques détails et images du projet <- <- <-

<details>
Pour ce projet, nous devions tout d'abord concevoir une petite interface graphique Turtle capable de reconnaître puis de dessiner un labyrinthe à l'aide de la librairie Turtle.

  Si vous souhaitez le lancer, je vous invite à installer un petit IDE (ici, nous avions utilisé IDLE), puis à ouvrir le fichier étiqueté "[Fichier Principal]". <img width="1905" height="1112" alt="1" src="https://github.com/user-attachments/assets/c48654ce-0dc4-4271-b8af-e048f27825c9" />

  Une fois le labyrinthe choisi (exemple : laby2.laby), vous avez différents choix d'exploration de celui-ci, que nous avons établis par différentes stratégies.

  On a par exemple : l'exploration à l'aveugle (qui fonctionne en longeant le mur à gauche de la flèche, en créant de faux murs une fois qu'on considère une zone explorée pour éviter d'y revenir). <img width="1911" height="1097" alt="2" src="https://github.com/user-attachments/assets/49b04daa-d449-4047-9860-21eb334c3222" />

  On peut également effectuer une course de tortues, toutes deux effectuant une stratégie à l'aveugle, mais l'une démarrant du départ et l'autre de l'arrivée : <img width="1916" height="1102" alt="4" src="https://github.com/user-attachments/assets/debef522-b188-496b-89b2-eff53335ac97" />

  Notre projet contient également un mode "manuel" pour pouvoir diriger soi-même la flèche, ainsi qu'un mode "plus court chemin" qui offre une résolution de n'importe quel dédale.

  Il est également possible de créer son propre labyrinthe ! À l'aide du fichier CreationDeLabyrinthe.py, dont voici l'affichage du résultat : <img width="1917" height="1125" alt="8-1" src="https://github.com/user-attachments/assets/4cdb577f-01ba-4c7f-92c5-b731f83f8e4a" />

  <img width="1917" height="1112" alt="6" src="https://github.com/user-attachments/assets/818b41e9-0ab7-46b8-a950-5421449b70f5" />

  





</details>
