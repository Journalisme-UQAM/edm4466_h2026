---
metaLinks:
  alternates:
    - https://app.gitbook.com/s/BxN1F1nhGZEAcZR0HuGO/travaux/travaux
---

# 🛠️ Travaux

Les travaux à remettre ont été mentionnés brièvement dans les pages précédentes. Je vous donne, ci-dessous, un peu plus de détails sur chacun de ces éléments d'évaluation.

Liens directs vers les devoirs:

* [Devoir 1](travaux.md#md) (markdown; en classe)
* [Devoir 2](travaux.md#devoir-2) (python 1 - rudiments)
* [Devoir 3](travaux.md#devoir-2)
* [Devoir 4](travaux.md#site)
* [Exercice en classe](travaux.md#moisson)
* [Votre proposition](travaux.md#devoir-3)
* [Tutorat](travaux.md#tutorat-10-points)
* [Travail final](travaux.md#projet-final-25-points) et [_making-of_](travaux.md#making-of-10-points)

### Devoir 1 - Markdown (5 points) <a href="#md" id="md"></a>

Il suffit d'exporter votre carnet dans lequel vous avez rédigé du markdown en classe et de le déposer dans Moodle.

Voici des instructions plus détaillées. Rédigez un carnet ne contenant que deux cellules (ou blocs) de texte.

Dans la première cellule:

* Commencez avec une entête de niveau 1 (h1) pour donner un titre à votre carnet, titre de votre choix (« Mon premier carnet », si vous manquez d'inspiration)
* Suivez avec un texte dans lequel vous vous présentez brièvement. Votre nom doit être en **gras**.
* Faites une liste non ordonnée (avec des puces) avec au moins trois sujets que vous préférez couvrir dans votre travail comme journaliste, ou qui vous interpellent plus particulièrement.

Dans la seconde cellule:

* Commencez avec une entête de niveau 2 avec l'un des trois sujets que vous avez inclus dans votre liste de la première cellule.
* Suivez avec un texte dans lequel vous racontez brièvement un reportage que vous avez fait ou que vous avez lu sur le sujet en question. Donnez la date où ce reportage a été diffusé ou publié. Donnez le nom du média en _italique_ (même s'il ne s'agit pas d'un périodique). Ajoutez quelque part dans votre texte un lien vers le reportage en question. Ne faites pas juste coller l'URL. Faites un lien.
* Terminez ce bloc avec une image qui illustre le reportage ou le sujet. Ne téléversez pas une image dans votre carnet. Faites un lien vers le fichier de l'image en question.

Tombée : 12h30 à la fin de la séance 02. Téléchargez votre carnet en **format .ipynb** sur votre ordinateur. Remettez-le dans Moodle en rebaptisant **mardown.ipynb**, par exemple. [<mark style="color:$info;">**🚨 PAS DE FICHIER HTML !!! 🚨**</mark>](#user-content-fn-1)[^1]

### Devoir 2 - Fraudeurs fictifs de faible wattage (10 points) <a href="#devoir-1" id="devoir-1"></a>

#### Cas fictif.

Une source vous a parlé d'un groupe de fraudeurs qui utilise le réseau social [_Kick_](https://kick.com/). Cette source vous a dit que les membres du groupe utilisent tous (c'est leur manière de se reconnaître) des noms d'utilisateur de **cinq lettres** qui ont la **même structure** :

* `consonne, voyelle, consonne, voyelle, consonne`. En lettres minuscules.

Ça donne « `babab` », par exemple. Ou, à l'autre extrémité de l'alphabet : « `zyzyz` ». Avec ces cinq malheureuses lettre, il y a quand même 288 000 combinaisons possibles, ce qui contribue à leur sentiment d'invulnérabilité aussi futile qu'il leur est fatal.

Écrivez un script qui génère tous les noms d'utilisateurs possibles et qui, pour chaque mot de passe possible, génère l'URL de la page de cet utilisateur sur Kick. Voici la mienne, à titre d'exemple : [https://kick.com/jhroy](https://kick.com/jhroy).

Quelques consignes, qui sont à un devoir ce que la sauce Sriracha est à une patate frite:

* Commencez avec une variable de type **texte** comprenant toutes les lettres de l'alphabet. Voici son contenu : "abcdefghijklmnopqrstuvwxyz". À vous de lui créer un contenant.
* Les voyelles sont dans une variable de type **liste** dont voici le contenu: \["a", "e", "i", "o", "u", "y"].
* Créez une autre liste avec les consonnes.
* N'utilisez que des boucles. Des tutoriels ou, dieu nous en préserve, des outils d'IA générative vont vous suggérer différents modules en python. _Vade retro_ :hand\_splayed:.
* Utilisez des «f-strings» pour générer vos noms d'utilisateurs et les url.
* À chaque itération de la boucle, indiquez à quelle combinaison on est rendu à l'aide d'un compteur, de telle sorte qu'à la fin, c'est le nombre 288 000 qui s'affiche avant l'URL.

:star::star::star: La notion de **compteur** n'a pas été vue en classe, mais elle utilise un opérateur que nous avons vu à la semaine 1, (`+=`). Et je vous donne un exemple dans le carnet que j'ai mis en ligne pour la semaine 2 dans la [section tutoriels](../contenu/00.tutoriels.md#python).

➡️➡️➡️ Idem pour les **opérateurs** utiles dans des conditions. J'ai eu le temps de vous montrer le égal (`==`). Mais il y en a d'autres. Voyez le carnet que j'ai mis en ligne dans les tutos!

Quand vous avez terminé, téléchargez votre carnet en **format .ipynb** sur votre ordinateur.

Remettez votre carnet (**devoir2.ipynb**) dans Moodle

Tombée : 23h59, le lundi 2 février 2026.

### Devoir 3 - À venir (10 points) <a href="#devoir-2" id="devoir-2"></a>

Description à venir

Vous me remettez votre carnet par Moodle, comme d'habitude (**devoir3.ipynb**)

Si vous avez des difficultés, n'hésitez pas à me demander de l'aide. :rotating\_light:

Tombée : 23h59, le lundi 16 février 2026.

### Devoir 4 - À venir (10 points) <a href="#site" id="site"></a>

Description à venir

Tombée : 23h59, le lundi 9 mars 2026.

### Exercice en classe (10 points) <a href="#moisson" id="moisson"></a>

Remettez dans Moodle votre carnet réalisé en classe.

Tombée : 12h30 à la fin de la séance 10.

### Proposition (5 points) <a href="#devoir-3" id="devoir-3"></a>

J'attends de votre part une proposition de travail final qui doit décrire votre projet en un paragraphe.

À remettre en format PDF dans Moodle.

Tombée : 23h59, le lundi 30 mars 2026.

### Tutorat (10 points)

Vous devez être en classe lors de toutes les séances consacrées à du tutorat visant à faire en sorte que je puisse vous aider à réaliser votre travail final.

### Projet final (25 points)

Pour votre projet final, qui est un travail **individuel**, vous avez deux options. Vous pouvez faire :

* un <mark style="background-color:blue;">**reportage**</mark> ou
* un <mark style="background-color:green;">**outil**</mark>

Si vous choisissez l'option <mark style="background-color:blue;">**reportage**</mark>, vous pouvez le faire sur un **sujet** de votre choix (conditionnel à mon approbation). Vous avez aussi le choix de la **forme** de ce reportage : il peut s'agir d'un article (de 3 000 à 10 000 caractères), d'un reportage radio (entre 3 et 10 minutes), d'un reportage télé (entre 3 et 10 minutes) ou d'un reportage web (jusqu'à 10 000 caractères également).

La production de ce reportage ou de cet outil devra impliquer de la programmation en Python pour moissonner et/ou traiter et/ou visualiser des données.

Votre reportage devra également comprendre **au moins une entrevue** avec une personne experte ou témoin, ou toute autre personne intervenante en mesure de valider ou d'incarner ce que racontent les données dans votre reportage. Un plus grand nombre d'entrevues est signe d'un plus grand effort.

L'option <mark style="background-color:green;">**outil**</mark> peut prendre diverses formes. Il peut s'agir d'un robot Instagram, d'un outil qui automatise des tâches fastidieuses dans une salle de presse, etc. Si vous vous êtes déjà dit : « Hé! Ce serait cool si on pouvait faire telle chose! » Eh bien, allez-y! Faites-la! _W kapab_!

### _Making-of_ (10 points)

Quelle que soit la forme que prendra votre travail final, il devra être accompagné d'un texte **(en format PDF)** qui :

* compte entre 3 000 et 5 000 caractères;
* comprend des liens vers **toutes** les sources de documentation qui vous ont aidées en cours de route;
* comprend des hyperliens vers **toutes** les sources de vos données et/ou carnets que vous avez utilisés (s'il y a lieu);
* décrit votre démarche :
  * Pourquoi ce sujet?
  * Quels outils ou quelles technologies avez-vous utilisés?
  * Pourquoi les avoir choisi(e)s?
  * Comment vous ont-ils(elles) servi?
  * Quels problèmes avez-vous éprouvés (s'il y a lieu).

Votre document PDF doit être accompagné, s'il y a lieu, de tous les carnets que vous avez écrits, et/ou de tous les autres fichiers pertinents **(.py, .csv, .ods, .xls, .sql ou autres)** que vous avez récoltés ou dont vous vous êtes servis.

Vous mettez tout cela dans Moudeul avant le début du dernier cours (9h30, le 23 avril 2026) _por favor_.

[^1]: 
