# Bienvenue sur mon GitHub !
Voici une description d'une partie de mes différents projets informatiques 👋

## 🚀 Mes Projets Phares

### 🎮 Projet Jeu & Sérialisation XML
*Description courte : Développement d'un moteur de jeu avec un système de sauvegarde complexe via la sérialisation et désérialisation de fichiers XML.*
> **Lien vers le repo :** [Voir le code ici](https://github.com/l3miage-medinap/Jeu_Csharp_Xml)
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
</details>

---

### 🗄️ Projet Base de Données SQL
*Description courte : Conception complète d'une architecture de données, incluant la migration, la création de tables optimisées et la mise en place de vues complexes.*
> **Lien vers le repo :** [Voir le code ici](https://github.com/l3miage-medinap/Projet_Base_Donn-es_SQL)

<details>
</details>
---

### 🧮 Projet "Calculatrice" intelligente par Arbre d'Analyse Syntaxique
![Image du projet](Lien_vers_ton_image.png)
*Description courte : Implémentation d'un parseur capable de résoudre des expressions mathématiques complexes en utilisant des structures d'arbres syntaxiques.*
> **Lien vers le repo :** [Voir le code ici](https://github.com/l3miage-medinap/ProjetC_CalculatriceParAnalyseSyntaxique)

<details>
</details>
---

### 🚚 Projet Optimisation de Tournées
*Description courte : Résolution de problèmes logistiques via des algorithmes d'optimisation, couplés à une interface utilisateur et une base de données dédiée ainsi que son backend.*
> **Lien vers le repo :** Pas encore de Repository, pour ce projet 

<details>
</details>
