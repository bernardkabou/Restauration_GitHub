------------------------------------------------------------------------------------------------------
PROCESSUS DE RESTAURATION GITHUB
------------------------------------------------------------------------------------------------------
Suite à une modification de code dans GitHub, votre solution ne fonctionne plus. Vous devez donc restaurer votre code mais comment faire.  

**Exercice :** Ecrire dans ce Readme une procédure pour expliquer étape par étape le processus de restauration d'un code issue de votre historique (vos commits). C'est dire, décivrez comment faire un Checkout depuis l'interfaçe GitHub. Vous trouverez ci-dessous le début de la séquence de restauration.  

-------------------------------------------------------------------------------------------------------
Début de procédure : Historique des commits
-------------------------------------------------------------------------------------------------------
L'historique de vos commits vous donne accès à vos différentes versions de votre code.  
A chaque commit, un point de sauvegarde est créé dans GitHub.  

Cliquez sur Commits pour accèder à votre historique de commits  
  
![Screenshot Historique](Historique.jpg)   

Sélectionnez le sauvegarde que vous souhaitez restaurer.  

![Screenshot Browse](Browse.jpg)   

A présent vous n'êtes plus dans votre branche main (branche principale) mais vous naviguez dans un point de restauration (votre code du passé).  

![Screenshot Browse](Browse1.jpg)   

Votre objectif à présent est de faire de ce point de sauvegarde une nouvelle branche pour que vous puissiez ensuite la fusionner avec votre branche principale. C'est à dire faire de cette branche de restauration votre branche main.

**C'est vous de créer la suite de cette procedure de restauration**  

Il faut d'abord créer une nouvelle branche et le nommer

![Screenshot Historique](1.png)

Ensuite, une fois la branche créer, aller dans l'historique des commits

![Screenshot Historique](2.png)

Choisir le commit qu'on veut restaurer

![Screenshot Historique](3.png)

Faire view page et copier le contenu du fichier de l'ancien commit

![Screenshot Historique](4.png)

Le coller dans le fichier de la nouvelle branche 

![Screenshot Historique](6.png)

Faire un commit change pour valider les modifications 


Créer une pull request 

![Screenshot Historique](7.png)

Séléctionner la branche de restauration comme branche de comparaison et la branche main comme branche de base


Ajouter un titre, une description à la pull request


Enfin de fusionner la Pull request 


