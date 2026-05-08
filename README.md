# Bienvenue sur mon GitHub !
Voici une description d'une partie de mes différents projets informatiques 👋

## 🚀 Mes Projets Phares

### 🎮 Projet Jeu & Sérialisation XML
*Description courte : Développement d'un moteur de jeu avec un système de sauvegarde complexe via la sérialisation et désérialisation de fichiers XML.*
> **Lien vers le repo :** [Voir le code ici](https://github.com/l3miage-medinap/Jeu_Csharp_Xml)
-> -> -> ->
 <details>
  Pour ce projet nous devions concevoir un jeu en C#, utilisant les différentes méthodes de récupération et écriture XML (Xsd, Xslt, Serialisation, ParserDOM, etc...)

  Nous avons choisi de le développer sur JetBrains à l'aide d'un module de gestion texture Monogame (https://monogame.net/) également utilisé pour de nombreux jeux de pixel art ! Interface final obtenu:
<img width="1916" height="1132" alt="Capture d’écran 2026-05-08 194709" src="https://github.com/user-attachments/assets/80683da6-f2fe-4ebe-8309-cfbd6620dde9" />

  Nous avons donc fait le choix de concevoir un jeu de Donjon le joueur évoluant sur une carte et ayant la possibilité d'entrer dans différents portails, par exemple dans le manoir d'un sorcier (décidement fin connaisseur du XML):
<img width="1907" height="1145" alt="Capture d’écran 2026-05-08 154217" src="https://github.com/user-attachments/assets/697c610b-199c-4857-b6be-dfe1fe19b3f1" />

La première difficulté résidait en la gestion des différentes textures:
<img width="1162" height="537" alt="Capture d’écran 2026-05-08 154514" src="https://github.com/user-attachments/assets/fc90ef4f-b178-4f64-bb54-ccc40800f67e" />

Nous avons ensuite, mis en place un système de sauvegarde des différents caractéristiques du joueur: appelle de la fonction C# visibile ci-dessus après le texte "charger données". 

 Dont voici une petite partie de la class: <img width="1532" height="767" alt="Capture d’écran 2026-05-08 160418" src="https://github.com/user-attachments/assets/fa9f2294-36cb-4085-aeca-038c5e4a6b63" />
 Et le Xml associé: <img width="1425" height="682" alt="Capture d’écran 2026-05-08 160450" src="https://github.com/user-attachments/assets/6989163e-6c41-42b4-9dae-452fb7534ece" />

 Pour réaliser notre souhait d'avoir différent Donjon nous avons crées la class Lieu permettant l'affichage de différentes textures et dialogues/actions en fonctions du "lieu visités": <img width="1670" height="691" alt="Capture d’écran 2026-05-08 155418" src="https://github.com/user-attachments/assets/ab3d55ac-a0bf-4abf-b029-312bedca5086" />

Une de nos grandes difficultés fut de créer des actions dans les donjons et de faire attendre l'execution pour eviter qu'il n'execute tout à la chaine sans s'arreter <img width="1915" height="1132" alt="Capture d’écran 2026-05-08 154113" src="https://github.com/user-attachments/assets/2d294d07-ac32-41ef-8687-abd2e308967b" />


 Il a également fallu créer le joueur comme un objet déplaçable et gérer l'affichage du texture "en plus" de la carte de départ, et différents soucis de complexité que vous pouvez découvrir, si vous le souhaitez, en en lisant le documet explicatif du repository en question !!

 

</details>


---

### 📊 Projet Analyse de Data et Graphes Statistiques
*Description courte : Traitement de jeux de données massifs et génération de visualisations graphiques pour extraire des tendances significatives.*
> **Lien vers le repo :** [Voir le code ici](https://github.com/ton-pseudo/nom-du-repo-data)
<details>
  Pour ce projet, j'ai eu à gerer de gigantesque flux de données (43000 données) en format CSV, à l'aide du logiciel R-Studio et du langage R associé.
  <img width="1912" height="1151" alt="Capture d’écran 2026-05-08 170002" src="https://github.com/user-attachments/assets/7ce76f5f-668a-4461-80da-6d99668de953" />

  Celui-ci consistait à analyser et faire un compte-rendu en fonction d'immense jeux de données sur le baccalauréat, notre problématique était: Le statut du candidat (localité, parcours, statut, sexe) influence-t-il sa réussite au baccalauréat ?

  J'ai par exemple réalisé un audit des résulats au bac général en fonction de l'académie, pour la totalité des trentres académies national: <img width="1885" height="1127" alt="Capture d’écran 2026-05-08 170307" src="https://github.com/user-attachments/assets/4d4b4fc5-7a9c-448d-898a-4044822b3ff1" />
  Un résultat que j'ai pu obtenir à l'aide du code ci dessous utilisant les deux librairies tidyverse et ggplot: <img width="1512" height="747" alt="Capture d’écran 2026-05-08 170128" src="https://github.com/user-attachments/assets/c1268e9c-9063-4355-ba85-dd2206172984" /> Ce qui donne la représentation graphique suivante: <img width="1801" height="1112" alt="Capture d’écran 2026-05-08 170227" src="https://github.com/user-attachments/assets/e77c5671-ab4f-4038-afe1-f0913fb1fe93" />

  J'ai également pu tracer des graphiques se concentrant sur quelques académies: graphe: <img width="1917" height="892" alt="Capture d’écran 2026-05-08 170458" src="https://github.com/user-attachments/assets/ac8a4553-1bb7-477e-8008-06437c3b9d94" /> code associé:
<img width="1917" height="1147" alt="Capture d’écran 2026-05-08 170439" src="https://github.com/user-attachments/assets/62e93222-244f-45bc-aee9-4e042e3e4957" />




</details>

---

### 🗄️ Projet Base de Données SQL
*Description courte : Conception complète d'une architecture de données, incluant la migration, la création de tables optimisées et la mise en place de vues complexes.*
> **Lien vers le repo :** [Voir le code ici](https://github.com/l3miage-medinap/Projet_Base_Donn-es_SQL)

<details>
  Lors de ce projet j'ai eu à récupérer une base de données incomplète et incohérente. J'ai pour cela utiliser DB Browser (SQLite) qui est une application de gestion de base de données et de requetes SQL. 

  Pour commencer, j'ai du refaire la conception initial de ma base en repensant les logiques métiers et les besoins des utilisateurs. Notamment en redéfinissant ce qui est admissible comme format dans la base (domaine) ainsi que les différentes contraintes: <img width="1917" height="925" alt="Capture d’écran 2026-05-08 162224" src="https://github.com/user-attachments/assets/9c748729-e189-4605-a7ed-809774b877a8" />

  Ensuite, une fois les contraintes comprises j'ai creer une nouvelle base, destinée à accueillir ces données de façon cohérentes: <img width="1917" height="1100" alt="Capture d’écran 2026-05-08 163526" src="https://github.com/user-attachments/assets/43b1e6dd-edf7-4465-a542-530054c58bd3" />

  Après avoir récupéré les données à l'aide de différents insert, renommage de tables. J'ai achevé la création de la table et mise en place mes différentes Views (demandé par le client): <img width="1895" height="1011" alt="Capture d’écran 2026-05-08 163504" src="https://github.com/user-attachments/assets/670fdd79-4093-4f5b-b780-373a469accbf" />



</details>
---

### 🧮 Projet "Calculatrice" intelligente par Arbre d'Analyse Syntaxique
![Image du projet](Lien_vers_ton_image.png)
*Description courte : Implémentation d'un parseur capable de résoudre des expressions mathématiques complexes en utilisant des structures d'arbres syntaxiques.*
> **Lien vers le repo :** [Voir le code ici](https://github.com/l3miage-medinap/ProjetC_CalculatriceParAnalyseSyntaxique)

<details>
  Pour ce projet, nous devions concevoir une calculatrice intelligente capable de stocker et lire des variables ! 
  Exemple du rendu final: <img width="1811" height="1107" alt="Capture d’écran 2026-05-08 164958" src="https://github.com/user-attachments/assets/ad6e2635-7aa5-41b7-87d8-7499614a1b7f" />


  Pour cela nous avons mis en place de nombreux états pour effectuer un tri et "comprendre" ce que nous étions en train de traiter (analyse lexical). Ainsi qu'un arbre constituant l'expression reçu dans le but de découper celle-ci pour éviter d'accepter "1+-/2" (analyse syntaxique). 

  analyse lexical: <img width="1877" height="1062" alt="Capture d’écran 2026-05-08 165616" src="https://github.com/user-attachments/assets/9b8c703a-2115-4a27-bfc8-cc51374517a0" />
  analyse syntaxique: <img width="1917" height="1022" alt="Capture d’écran 2026-05-08 165505" src="https://github.com/user-attachments/assets/2ef93917-7c8c-43e4-9043-ff1787fe710c" />

  Exemple d'une equation traitant les opérateurs arithmétiques: 



  

</details>
---

### 🚚 Projet Optimisation de Tournées
*Description courte : Résolution de problèmes logistiques via des algorithmes d'optimisation, couplés à une interface utilisateur et une base de données dédiée ainsi que son backend.*
> **Lien vers le repo :** Pas encore de Repository, pour ce projet (encore en cours)

<details>
  Pour très bientot...
</details>
