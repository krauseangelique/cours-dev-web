# Création d'un nouveau projet

Un projet Git est composé de trois partie :

- Le répertoire de travail

    Le répertoire de travail est le dossier où se situe vos fichiers de HTML, CSS, Javascript, etc...
    C'est le dossier du projet, du site, de l'application sur lequel vous travaillez actuellement.
    
    Exemple de structure ci-dessous :
    
    ````
    |-- css
    |   `-- main.css
    |
    `-- js
    |   `-- main.js
    |
    |-- index.html    
    ````


- l'index

   L'index est une zone transitoire entre le répertoire de travail et le dépot.
   
   Pour passer du répertoire de travail à l'index, il faut effectuer un ``git add``
   
   Tant que vous n'effectuez pas un ``git add``, Git n'a pas conscience qu'il y un nouveau fichier ou qu'un fichier a été modifier.

- le dépôt

  Le dépôt 