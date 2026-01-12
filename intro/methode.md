---
metaLinks:
  alternates:
    - https://app.gitbook.com/s/BxN1F1nhGZEAcZR0HuGO/intro/methode
---

# ✨ Méthode

Le contenu de ce cours colle davantage à ce qu'on appelle, dans le monde anglo-saxon, du [_Computational journalism_](https://www.datajconf.com). Il s'agit de l'application de l'informatique au journalisme.

Même le plan de cours que vous consultez en ce moment est un exemple de ce qu'on peut faire avec ces technologies. Il repose sur un système appelé [_git_](https://fr.wikipedia.org/wiki/Git), qui permet de collaborer à plusieurs sur un même projet et de voir les différentes versions d'un même fichier (pour voir comment ce plan de cours a évolué, consultez [ce répertoire sur le compte Github du programme](https://github.com/Journalisme-UQAM/edm4466_h2026)).

Mais ce qu'on fera, surtout, c'est d'apprendre la **programmation** et ses applications journalistiques.

<figure><img src="../.gitbook/assets/logoPython.png" alt=""><figcaption></figcaption></figure>

Le langage qu'on utilisera s'appelle [**Python**](https://www.python.org/). C'est un langage d'usage général qui est l'un des plus utilisés dans le monde. C'est celui qui, en 2023 et pour la prochaine décennie au moins, me paraît le plus utile pour vous comme journalistes et comme citoyennes. **JavaScript** est plus couramment utilisé par des informaticiennes, mais il est difficile à appréhender pour des gens qui n'ont jamais programmé. Le langage **R** est très utilisé par mes collègues en sciences humaines et sociales, mais en dehors des cercles académiques, il demeure plutôt inusité.

<figure><img src="https://github.blog/wp-content/uploads/2023/11/top-programming-languages-2023.png" alt=""><figcaption><p>Les langages les plus populaires utilisés dans <strong>Github</strong>, site de travail collaboratif, de contrôle de versions et de partage de code informatique, au cours des dix dernières années (source: <a href="https://github.blog/2023-11-08-the-state-of-open-source-and-ai/">The State of the Octoverse 2023</a>).</p></figcaption></figure>

Python a ses avantages et ses inconvénients, comme tous les langages informatiques. C'est celui que j'ai choisi, car il est devenu la _lingua franca_ dans l'univers de l'« intelligence artificielle » et de la science des données. C'est aussi un langage que comprendront les informaticiennes que vous croiserez peut-être dans les rédactions où vous travaillerez. Enfin, son grand nombre d'utilisatrices fait en sorte que vous pourrez compter sur une grande communauté pour répondre aux questions que vous poserez certainement en ligne au cours de la session.

Plus concrètement, on s'en servira pour :

* **moissonner** des données, ou faire du _data scraping_, comme le font les artisans de [Common Crawl](https://commoncrawl.org), une archive colossale de 250 milliards de pages web archivées depuis 2008 (elle contient 10 petaoctets, c'est-à-dire 10 000 000 000 000 000 octets ou 10 milliards de gigaoctets; je sais, j'ai le tournis moi aussi)
* **extraire du sens** de grands volumes de texte à l'aide du **traitement du langage naturel** (ou _Natural Language Processing \[NLP]_),
* **se familiariser** avec différentes techniques d'« intelligence artificielle » appliquée, ou d'**apprentissage automatique** (Machine Learning \[ML]),
* **explorer** l'utilisation programmatique d'outils d'intelligence artificielle générative comme OpenAI.
* **analyser** des données lorsqu'elles sont trop volumineuses pour un tableur comme _Excel_ ou _Calc_ de LibreOffice.

<figure><img src="../.gitbook/assets/Google_Colaboratory.png" alt=""><figcaption></figcaption></figure>

On va le faire au moyen de [Google Colaboratory](https://colab.research.google.com), ou [**Colab**](https://colab.research.google.com). Pour ce faire, il faut que vous disposiez d'un compte Google (si vous vous servez déjà de Gmail et/ou de Google Drive, tout va bien).

Je ne suis pas un _cheerleader_ des GAFA. Mais si j'ai opté pour Colab, c'est après avoir jonglé avec plusieurs autres options au cours des sessions précédentes :

* en 2016 et 2017, je demandais aux étudiantes d'utiliser [Cloud9](https://aws.amazon.com/fr/cloud9/); ce service en ligne a cependant été acheté par Amazon qui l'a intégré à ses AWS (Amazon Web Services) et l'a rendu payant :skull::exclamation:
* à partir de 2018, j'ai demandé à tout le monde d'installer sur son ordi [Anaconda](https://www.anaconda.com/), une plateforme d'analyse de données. On réutilisait [Sublime Text](https://www.sublimetext.com/), comme dans le EDM4455 (_nostalgie_) pour écrire du code. Mais cela se traduisait par une expérience différente selon que vous possédiez un ordinateur avec Windows ou avec Mac. En outre, les personnes munies d'un Chromebook étaient larguées (elles pouvaient utiliser [CodeAnywhere](https://codeanywhere.com/) ou [PythonAnywhere](https://www.pythonanywhere.com/), des services cependant payants). En 2020, j'ai même introduit un éditeur de code professionnel : [Visual Studio Code](https://code.visualstudio.com/).
* à l'été 2020, j'ai donné avec deux collègues de la Faculté des sciences le cours [Initiation à la science des données et à l'intelligence artificielle](https://etudier.uqam.ca/cours?sigle=INF7100). C'était entre les deux premières vagues de la pandémie et le cours a exclusivement été donné en ligne. Je me suis alors servi des [Azure Notebooks](https://portal.azure.com), un service auquel toute personne qui travaille ou étudie à l'UQAM avait accès gratuitement dans le cadre de l'abonnement de l'université à Office365... j'utilise l'imparfait parce que ce service n'existe plus...
* En 2022, j'ai exploré des solutions de rechange comme [PyCharm](https://www.jetbrains.com/fr-fr/pycharm/), [Gitpod](https://www.gitpod.io/), [Glitch](https://glitch.com) ou les [Codespaces de Github](https://github.com/features/codespaces). Pour toutes sortes de raisons, je ne les trouvais pas appropriés pour cette session au cours de laquelle les risques de reconfinement sont grands et où j'ai besoin d'une solution en ligne. Je me suis donc tourné vers [Colab](https://colab.research.google.com). Ça s'est bien passé en 2023. On poursuit en 2024.

Ce service devrait donc fonctionner, quel que soit l'ordi que vous possédez : Mac, Windows, Linux, ChromeBook... Je l'ai même testé sur un téléphone dans l'application Chrome. Et ça marche :scream: !! Pas très pratique cependant...

![Colab dans l'application Chrome sous iOS 15.1 sur un iPhone XR](../.gitbook/assets/colab-ios.png)

Il permet de programmer à l'intérieur de ce qu'on appelle des **carnets**, ou _**notebooks**_, en anglais. Vous me rendrez d'ailleurs vos devoirs sous la forme de carnets.

Lorsque ce sera nécessaire, je partagerai au préalable avec vous des fichiers qui seront utiles dans le cadre des exercices en classe dans ce répertoire partagé sur Google Drive, répertoire auquel vous pouvez aussi accéder directement à partir de Colab.

### Ce cours est un échange

Je reste ouvert à vos [**demandes spéciales**](https://vimeo.com/jhroy/dj). Vous avez entendu parler d'un projet, d'un reportage retentissant, d'une technologie, d'une application particulière en journalisme? Si je puis vous aider à l'appréhender, voire la réaliser, je vais tâcher de le faire. La meilleure façon d'apprendre est avec un projet concret.

Inversement, si vous connaissez une technique, un outil, un truc, n'hésitez jamais à le **partager** avec l'ensemble du groupe. Parlez-m'en au préalable et on pourra prévoir une période dans le prochain cours pour que vous puissiez nous le ou la présenter. Si vous pouvez vous aussi m'apprendre quelque chose, je serai le prof le plus heureux du monde.

> #### _Il n'y a aucune honte à admettre qu'on ignore quelque chose. La seule honte est de prétendre avoir réponse à tout._
>
> – Neil deGrasse Tyson

![L'un de mes héros <3](../.gitbook/assets/NeilDTyson.jpg)
