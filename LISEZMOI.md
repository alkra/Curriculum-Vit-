To view this file in English, go on [README.md](README.md).  
Um diese Datei auf Deutsch zu lesen, bitte gehen Sie auf
[LIESMICH.md](LIESMICH.md).


Voici mon CV
============

Je m'appelle Alban Kraus, et je suis étudiant en dernière année de
l'[École nationale des sciences géographiques](http://www.ensg.eu) de
Marne-la-Vallée (77).  Je suis spécialisé en systèmes d'information :
à l'école, j'ai pu explorer pendant un an diverses nouvelles
technologies.

Vous êtes ici sur mon [GitHub](https://github.com/alkra), où vous
pouvez voir certains de mes projets d'étude ; n'oubliez pas de jeter
aussi un œil aux dépôts auxquels j'ai contribué.

Ce dépôt est mon *curriculum vitæ*. Il est écrit en LaTeX, mais je
prévois de proposer également une version en Markdown et une version
HTML+CSS.



Les derniers PDF
================

- [en anglais]() ;
- [en français]() ;
- [en allemand]()



Compilation depuis les sources
==============================

Téléchargement
--------------

### Prérequis

Un client *git*.  Vous pouvez le télécharger de puis la section
*Download* de [git-scm.com](https://git-scm.com/).

### Procédure

À l'invite de commande, lancez les commandes suivantes :

    git clone https://github.com/alkra/Curriculum-Vitae.git
    cd Curriculum-Vitae

Vous pouvez également appuyer sur le bouton *Download ZIP*, extraire
le résultat, puis ouvrir une invite de commande dans le dossier
d'extraction.

Ensuite, téléchargez toutes les têtes de branche :

    git fetch

Selon le langage que vous souhaitez, vous devez récupérer la branche
correspondante. Par exemple, si vous voulez compiler un PDF en
français, lancez la commande ci-dessous :

    git checkout origin/master-fr



Compiler un PDF
---------------

### Prérequis

- Une distribution LaTeX. Pour la liste des paquets requis,
  référez-vous aux fichiers sources [`cv.tex`](cv.tex) et
  [`cv.sty`](cv.sty).

### Procédure

À l'invte de commande, lancez la commande :

    pdflatex cv.tex

### Résultat

Le PDF résultat aura pour nom `cv.pdf` .




Licence
=======

Vous pouvez librement télécharger et redistribuer les PDF
ci-dessus. Ils vous sont concédés sous la licence
[Creative Commons – Attribution – Pas d'utilisation commerciale – Pas de modification](http://creativecommons.org/licenses/by-nc-nd/3.0/).

La feuille de style est `cv.sty`. Vous pouvez librement télécharger,
modifier, compiler, et redistribuer ce fichier selon les conditions de
la [Licence Publique Générale GNU amoindrie](lgpl-3.0.txt) version 3.0
ou supérieure.

Le contenu de cette œuvre (le Contenu) est composé de tous les
fichiers `.tex` de ce dépôt, ainsi que les images du sous-dossier
`imgs`. Il est protégé par le droit d'auteur. Je vous donne néanmoins
la permission de :

- lire et télécharger le Contenu ; vous pouvez même faire des
  modifications mineures qui vous permettront de lire les fichiers ;

- générer un document compilé à partir du Contenu non modifié ;

- modifier tout ou partie du Contenu, créant ainsi une œuvre dérivée ;
  dans ce cas, vous devez supprimer tout ce qui se rapporte à moi, et
  notamment mon nom, les photographies, et les données
  personnelles. Cette permission ne s'applique pas aux photographies
  du dossier `imgs` ; vous devez donc les enlever de votre œuvre
  dérivée.

Vous pouvez distribuer des copies du Contenu non modifié. Vous pouvez
distribuer un document compilé s'il respecte la sémantique et la
disposition du résultat de `pdflatex` lancé sur le Contenu non
modifié. Dans tous les cas, vous n'avez pas la permission de réaliser
des bénéfices commerciaux en distribuant. Si vous distribuez l'un ou
l'autre de ce qui précède, vous ne pouvez pas imposer des conditions
qui restreignent ou étendent celles qui vous sont applicables.

Vous pouvez aussi réutiliser ce Contenu sous les conditions de la
licence
[Creative Commons – Attribution – Pas d'utilisation commerciale – Pas de modification](http://creativecommons.org/licenses/by-nc-nd/3.0/).
